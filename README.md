# Anleitung BAPP

## TLN-Daten extrahieren

1. **Download:** Eureka-TRS-Daten [Link]

2. **TRS -> TLN-Liste:** 
   - 1. TLN anklicken
   - links oben auf Drucken
   - mit dem nächsten TLN wiederholen

3. **PDFs in txt-Dateien umwandeln:** 
   - PDF24 -> In der Toolbox öffnen -> PDF umwandeln in … -> Format: Text (.txt)

4. **Erstellung: Ordnerstruktur:** 
   - Die erstellten Text-Dateien in `Downloads/Erstellung_BAPP/Teilnehmer` abspeichern
   - Im Ordner `Erstellung_BAPP` eine Excel-Datei mit dem Namen „Prüfvermerk“ erstellen
   - Excel-Datei sollte wie folgt aufgebaut sein: A1: Projektnummer, B1: TLN-Nummer, C1: Monate, D1: SOLL, E1: IST, F1: Jahr, G1: Monate, H1: Kriterien

5. **Visual Studio Code: Ausführung des Codes:** 
   - Download des Programmes Visual Studio Code und führe den Code mit diesem aus
   - Code hier: [GitHub Repository](https://github.com/TheDevAlan/BAPP_Datenbasis) (siehe Datei TLN_extrahieren.py)

6. **Excel: Daten in den Prüfvermerk einfügen:** 
   - In der Excel-Datei „Prüfvermerk“, die in Punkt 4 erstellt wurde, sollten nun alle Daten der Teilnehmer eingefügt worden sein
   - Die dort eingefügten Daten in den `Pruefvermerk_Festbetragsfinanzierung_BAPP` in das Arbeitsblatt `TLN_Phasen_Data` (ist eventuell im Excel-Dokument ausgeblendet) einfügen und abspeichern.

**Done and Enjoy 😊** 