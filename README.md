# IPT1 · Lernsession 03 · GitHub-Flow & Markdown

> **Name:** Ruslan  
> **Datum:** 14.09.2026

## Ziel

Ich kann die wichtigsten Begriffe rund um **Git**, **GitHub**, den **GitHub-Flow** und **Markdown** kurz erklären und meinen Lernfortschritt mit einem eigenen README dokumentieren.

> **Hinweis:** Ersetze die Platzhalter `DEINE ANTWORT` durch deine eigenen kurzen Antworten. Committe die ausgefüllte Datei anschliessend mit einer aussagekräftigen Commit-Nachricht.

---

## 1 · Git und GitHub verstehen

### 1. Was ist Git?

**Meine Antwort:** Git ist ein Versionskontrollsystem, das lokal auf meinem Computer läuft. Es speichert Änderungen an Dateien als nachvollziehbare Versionen, sodass ich den Verlauf sehen und frühere Stände wiederherstellen kann.

### 2. Was ist GitHub?

**Meine Antwort:** GitHub ist eine Online-Plattform, auf der Git-Repositories gespeichert werden. Sie bietet zusätzlich Funktionen für die Zusammenarbeit, zum Beispiel Issues und Pull Requests.

### 3. Was ist der wichtigste Unterschied zwischen Git und GitHub?

**Meine Antwort:** Git ist das Werkzeug zur Versionskontrolle auf meinem Computer, GitHub ist der Online-Dienst, der Repositories im Internet speichert und die Zusammenarbeit ermöglicht.

### 4. Funktioniert Git auch ohne GitHub?

**Meine Antwort:** Ja. Git funktioniert komplett lokal (z.B. `git init`, `git add`, `git commit`, `git log`). GitHub brauche ich nur, wenn ich mein Repository online speichern oder mit anderen zusammenarbeiten will.

### 5. Was ist ein Repository (Repo)?

**Meine Antwort:** Ein Repository ist ein Projektordner zusammen mit dem gesamten Versionsverlauf. Es kann lokal auf dem Computer oder online auf GitHub liegen.

### 6. Was ist der `main`-Branch?

**Meine Antwort:** Der `main`-Branch ist der Hauptzweig eines Repositories. Er enthält die stabile, gültige Version des Projekts und ist normalerweise der Standard-Branch.

### 7. Was ist Markdown?

**Meine Antwort:** Markdown ist eine einfache Auszeichnungssprache, mit der man Text mit wenigen Zeichen formatiert (z.B. `#` für Überschriften, `-` für Listen, `**` für fett). Markdown-Dateien enden auf `.md`.

### 8. Was bedeutet GitHub-Flavoured Markdown (GFM)?

**Meine Antwort:** GFM ist die Markdown-Variante von GitHub. Sie erweitert Markdown um zusätzliche Funktionen wie Tabellen, Aufgabenlisten mit Checkboxen, durchgestrichenen Text und Codeblöcke mit Sprachangabe.

---

## 2 · GitHub-Flow

### 9. Bringe die Schritte in die richtige Reihenfolge

`Commit · Issue · Pull Request · Branch`

**Meine Antwort:** Issue → Branch → Commit → Pull Request (danach Review und Merge)

### 10. Was ist ein Issue?

**Meine Antwort:** Ein Issue ist ein Eintrag auf GitHub, in dem eine Aufgabe, ein Problem oder eine Idee festgehalten und besprochen wird.

### 11. Was ist ein Branch?

**Meine Antwort:** Ein Branch ist ein eigener Entwicklungszweig, in dem ich Änderungen machen kann, ohne den Hauptzweig (`main`) zu verändern.

### 12. Warum arbeitet man für eine Änderung häufig auf einem eigenen Branch?

**Meine Antwort:** Damit `main` stabil bleibt. Die Änderung ist getrennt, kann geprüft werden, mehrere Personen können parallel arbeiten, und wenn etwas schiefgeht, lässt sich der Branch einfach verwerfen.

### 13. Was ist ein Commit?

**Meine Antwort:** Ein Commit ist ein gespeicherter Stand (Speicherpunkt) der vorgemerkten Änderungen im Repository, mit Nachricht, Autor und Zeitpunkt.

### 14. Wozu dient eine Commit-Nachricht?

**Meine Antwort:** Sie beschreibt kurz und konkret, was geändert wurde und warum. So bleibt der Verlauf später verständlich und nachvollziehbar.

### 15. Was ist ein Pull Request?

**Meine Antwort:** Ein Pull Request ist ein Antrag, die Änderungen aus meinem Branch in einen anderen Branch (meist `main`) zu übernehmen. Er ist der Ort, an dem die Änderungen geprüft und besprochen werden.

### 16. Was bedeutet Review?

**Meine Antwort:** Ein Review ist die Prüfung meiner Änderungen durch eine andere Person. Sie gibt Feedback, stellt Fragen und gibt die Änderung frei oder verlangt Anpassungen.

### 17. Was bedeutet Merge?

**Meine Antwort:** Merge bedeutet, die Änderungen eines Branches in einen anderen Branch zusammenzuführen, z.B. von meinem Arbeits-Branch in `main`.

### 18. Wann sollte ein Pull Request gemergt werden?

**Meine Antwort:** Wenn die Änderungen geprüft und freigegeben sind (Review), keine Konflikte mehr bestehen, allfällige Tests bestanden sind und die Aufgabe aus dem Issue erfüllt ist.

---

## 3 · Wichtige Git-Begriffe und Befehle

### 19. Was bedeutet Push?

**Meine Antwort:** Push bedeutet, meine lokalen Commits ins Remote-Repository (z.B. auf GitHub) hochzuladen.

### 20. Was bedeutet Pull?

**Meine Antwort:** Pull bedeutet, Änderungen aus dem Remote-Repository (z.B. von GitHub) zu holen und in mein lokales Repository zu übernehmen.

### 21. Was ist der Unterschied zwischen Commit und Push?

**Meine Antwort:** Ein Commit speichert Änderungen nur lokal in meinem Repository. Ein Push lädt die bereits gemachten Commits anschliessend auf GitHub hoch.

### 22. Was ist der Unterschied zwischen Pull und Pull Request?

**Meine Antwort:** Pull ist ein Git-Befehl, der Änderungen vom Remote auf meinen Computer holt. Ein Pull Request ist ein Antrag auf GitHub, einen Branch in einen anderen zu übernehmen.

### 23. Was bedeutet Clone?

**Meine Antwort:** Clone erstellt eine vollständige lokale Kopie eines Remote-Repositories, inklusive Versionsverlauf.

### 24. Was macht `git status`?

**Meine Antwort:** Es zeigt den aktuellen Zustand: auf welchem Branch ich bin und welche Dateien geändert, vorgemerkt (staged) oder neu sind.

### 25. Was macht `git add`?

**Meine Antwort:** Es merkt Änderungen für den nächsten Commit vor, indem es sie in die Staging Area legt.

### 26. Was ist die Staging Area?

**Meine Antwort:** Die Staging Area ist ein Zwischenbereich, in dem ich festlege, welche Änderungen in den nächsten Commit kommen.

### 27. Was macht `git log`?

**Meine Antwort:** Es zeigt den Verlauf der bisherigen Commits mit Autor, Datum und Commit-Nachricht.

### 28. Was bedeutet Branch wechseln?

**Meine Antwort:** Ich schalte auf einen anderen Branch um (z.B. mit `git switch`). Mein Arbeitsverzeichnis zeigt dann den Stand dieses Branches.

### 29. Speichert `git add` bereits eine neue Version?

**Meine Antwort:** Nein. `git add` merkt Änderungen nur vor. Erst `git commit` speichert eine neue Version.

### 30. Speichert `git push` deine noch nicht committeten Dateiänderungen?

**Meine Antwort:** Nein. `git push` lädt nur Änderungen hoch, die bereits committet wurden. Nicht committete Änderungen bleiben lokal.

---

## 4 · GitHub-Flow praktisch erklären

### 31. Erkläre den GitHub-Flow in einem kurzen Satz.

**Meine Antwort:** Eine Aufgabe wird als Issue festgehalten, auf einem eigenen Branch mit Commits umgesetzt, per Pull Request prüfen lassen und danach in `main` gemergt.

### 32. Ordne die Begriffe zu

| Bedeutung | Git-/GitHub-Begriff |
|---|---|
| Aufgabe | Issue |
| Arbeitszweig | Branch |
| Speicherpunkt | Commit |
| Änderungsantrag | Pull Request |
| Zusammenführen | Merge |

### 33. Welche Richtung beschreibt Push?

**Meine Antwort:** Von meinem lokalen Repository zum Remote-Repository (zu GitHub).

### 34. Welche Richtung beschreibt Pull?

**Meine Antwort:** Vom Remote-Repository (von GitHub) zu meinem lokalen Repository.

### 35. Warum sind mehrere sinnvolle Commits oft besser als ein einziger riesiger Commit?

**Meine Antwort:** Jeder Commit ist eine kleine, logische Einheit. Dadurch ist der Verlauf übersichtlich, ein Fehler lässt sich leichter finden, einzelne Änderungen können einfacher rückgängig gemacht werden und ein Review ist einfacher.

### 36. Nenne ein Beispiel für eine gute Commit-Nachricht.

```text
README: Gliederung, Link und Codeblock ergänzt
```

### 37. Warum ist die Commit-Nachricht `update` wenig hilfreich?

**Meine Antwort:** Sie sagt nicht, was oder warum etwas geändert wurde. Später kann man den Verlauf nicht mehr verstehen und muss jede Änderung einzeln nachschauen.

---

## 5 · Markdown und README

### 38. Überschrift Ebene 1

Ergänze darunter eine Markdown-Überschrift der Ebene 1:

# Mein Git- und GitHub-Lernnachweis

### 39. Ungeordnete Liste

Erstelle eine Liste mit mindestens drei Begriffen aus dieser Lernsession:

- Repository
- Branch
- Commit
- Pull Request

### 40. Link

Erstelle einen funktionierenden Markdown-Link zu GitHub oder Microsoft Learn:

[GitHub](https://github.com) und [Microsoft Learn](https://learn.microsoft.com/training/)

### 41. Bild

Schreibe die Markdown-Syntax für ein Bild mit Alternativtext:

```text
![Ablauf des GitHub-Flows](bilder/github-flow.png)
```

### 42. Inline-Code

Schreibe `git status` als Inline-Code in einem sinnvollen Satz:

Mit `git status` sehe ich, welche Dateien geändert oder für den nächsten Commit vorgemerkt sind.

### 43. Codeblock

Ergänze mindestens drei Git-Befehle in diesem Codeblock:

```bash
git status
git add README.md
git commit -m "README: Gliederung, Link und Codeblock ergänzt"
git push
```

### 44. Was sollte ein gutes Portfolio-README mindestens leisten?

**Meine Antwort:** Es sollte klar gegliedert sein (Überschriften), kurz erklären, worum es im Repository geht, eine Liste oder Übersicht enthalten, funktionierende Links, lesbare Codeblöcke und einen ersten fachlichen Lernnachweis. Auf GitHub muss es korrekt dargestellt werden und für Aussenstehende verständlich sein.

---

## 6 · Mein fachlicher Lernnachweis

### Was habe ich heute über Git und GitHub gelernt?

Ich habe gelernt, wie der GitHub-Flow funktioniert: Eine Aufgabe wird als Issue festgehalten, auf einem eigenen Branch mit Commits umgesetzt, mit einem Pull Request geprüft und dann in `main` gemergt. Ich kann Git (lokales Werkzeug) und GitHub (Online-Plattform) unterscheiden. Ausserdem kenne ich jetzt den Unterschied zwischen Commit und Push sowie zwischen Pull und Pull Request. Mit Markdown kann ich ein README mit Überschriften, Listen, Links, Bildern und Codeblöcken übersichtlich aufbauen.

### Was habe ich heute praktisch umgesetzt?

Ich habe die geführte GitHub-Übung und das Markdown-Modul auf Microsoft Learn abgeschlossen. Danach habe ich ein Portfolio-README mit Überschriften, Liste, Link, Codeblock und einem ersten fachlichen Lernnachweis erstellt und die Änderung mit einer aussagekräftigen Commit-Nachricht dokumentiert.

### Meine konkrete Verbesserung aus dem Selbst- oder Peer-Check

Ich habe mein README klarer gegliedert, indem ich die Überschriften sinnvoll aufgebaut, einen funktionierenden Link und einen lesbaren Codeblock ergänzt habe. Die Commit-Nachricht beschreibt jetzt konkret, was geändert wurde, statt nur «update» zu heissen.

### Mein nächster Portfolio-Schritt

Ich ergänze im Portfolio den IPT1-Lernnachweis zum Mensa-Fall (Problem, Ziel, Anforderungen, EVA-Modell und C#-Programm) und zeige dort meinen eigenen Beitrag mit nachvollziehbaren Commits.

---

## 7 · Microsoft Learn · Abschlusskontrolle

- [x] **Einführung in GitHub**: Übung, Modulbewertung und Zusammenfassung abgeschlossen
- [x] **Effektive Kommunikation auf GitHub mithilfe von Markdown** abgeschlossen
- [x] Ich habe meinen Lernfortschritt / meine Modulbewertung kontrolliert.

## 8 · Begriffe · deutsche Merkhilfe

Fülle die zweite Spalte mit einer kurzen deutschen Merkhilfe aus.

| Begriff | Deutsche Merkhilfe |
|---|---|
| Issue | Aufgabenzettel: hier steht, was zu tun ist |
| Branch | Arbeitszweig: eigener Seitenweg neben `main` |
| Commit | Speicherpunkt: ein festgehaltener Stand mit Beschreibung |
| Push | Hochladen: lokale Commits zu GitHub schicken |
| Pull | Herunterholen: neue Änderungen von GitHub auf meinen Computer holen |
| Pull Request | Änderungsantrag: «Bitte übernehmt meine Änderung» |
| Review | Gegenlesen: eine andere Person prüft meine Änderung |
| Merge | Zusammenführen: Änderungen in `main` übernehmen |
| Clone | Kopie holen: ein ganzes Repository auf meinen Computer kopieren |
| Repository | Projektordner mit Versionsverlauf |

---

## 9 · Selbstcheck

- [x] Ich kann **Git** und **GitHub** unterscheiden.
- [x] Ich kann **Issue → Branch → Commit → Pull Request → Merge** erklären.
- [x] Ich kenne den Unterschied zwischen **Commit** und **Push**.
- [x] Ich kenne den Unterschied zwischen **Pull** und **Pull Request**.
- [x] Ich kann Überschriften, Listen, Links, Bilder und Codeblöcke in Markdown verwenden.
- [ ] Mein README wird auf GitHub korrekt gerendert.
- [x] Ich habe mindestens eine konkrete Verbesserung umgesetzt.
- [ ] Ich habe meine Änderung mit einer aussagekräftigen Commit-Nachricht dokumentiert.

## Meine Commit-Nachricht für diese Abgabe

```text
IPT1 LS03: README mit Antworten zu Git, GitHub-Flow und Markdown ausgefüllt
```
