# ipt1_portfollio1

## Inhalt
 
- **Modul 319:** Applikationen entwerfen und implementieren (C#, VS Code, Git)
- **Modul 162:** Daten analysieren und modellieren
- **Modul 117:** Informatik- und Netzwerkinfrastruktur
- **Lernjournal:** Notizen und Reflexionen zu den Lernsessions
## Verwendete Werkzeuge
 
- [Visual Studio Code](https://code.visualstudio.com/) als Entwicklungsumgebung
- [.NET SDK](https://dotnet.microsoft.com/download) zum Ausführen von C#-Programmen
- [Git und GitHub](https://github.com/Ruslan929266/IMS_Lernmaterial) für Versionsverwaltung
## IPT1 – Erster Lernnachweis: Vom Problem zum C#-Programm
 
### Ausgangslage
 
In der Mensa berechnet eine Person den Gesamtpreis von Einkäufen von Hand. Besonders bei mehreren gleichen Artikeln entstehen Rechenfehler.
 
### Was ich gelernt habe
 
- Ein **Problem** (Fehler beim Rechnen), ein **Ziel** (Gesamtpreis zuverlässig bestimmen) und eine **Lösung** (Programm) sind drei verschiedene Dinge.
- Mit dem **EVA-Prinzip** zerlege ich ein Programm in **E**ingabe, **V**erarbeitung und **A**usgabe.
- Vor dem Programmieren prüfe ich meinen Ablauf mit einem **Trockenlauf** von Hand.
- Jede Anforderung braucht ein **Akzeptanzkriterium**, das eindeutig mit «erfüllt» oder «nicht erfüllt» beantwortet werden kann.
### EVA-Modell
 
| Eingabe | Verarbeitung | Ausgabe |
|---|---|---|
| Artikelname, Einzelpreis, Menge | Gesamtpreis = Einzelpreis × Menge | Zusammenfassung mit Gesamtpreis |
 
### Code
 
```csharp
using System.Globalization;
 
// EINGABE
Console.Write("Artikelname: ");
string artikel = Console.ReadLine()!;
 
Console.Write("Einzelpreis (CHF): ");
decimal einzelpreis = decimal.Parse(Console.ReadLine()!, CultureInfo.InvariantCulture);
 
Console.Write("Menge: ");
int menge = int.Parse(Console.ReadLine()!);
 
// VERARBEITUNG
decimal gesamtpreis = einzelpreis * menge;
 
// AUSGABE
Console.WriteLine($"{menge} × {artikel} à CHF {einzelpreis:F2} = CHF {gesamtpreis:F2}");
```
 
### Tests (SOLL / IST)
 
| Artikel | Preis | Menge | SOLL | IST |
|---|---|---|---|---|
| Apfelschorle | 2.50 | 3 | CHF 7.50 | CHF 7.50 |
| Sandwich | 5.80 | 2 | CHF 11.60 | CHF 11.60 |
 
### Warum diese Datentypen?
 
- `string` für den Artikelnamen, weil es Text ist.
- `int` für die Menge, weil nur ganze Stück gekauft werden.
- `decimal` für Geldbeträge, weil es Dezimalstellen exakt speichert (ohne Rundungsfehler wie bei `double`).
## Nächste Schritte
 
1. Mehrere Artikel pro Einkauf erfassen (Wiederholungen)
2. Eingaben prüfen, z.B. keine negative Menge (Entscheidungen)
3. Weitere Lernnachweise in diesem Repository ergänzen
