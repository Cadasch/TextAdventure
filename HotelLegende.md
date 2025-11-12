# Hotel Grundriss & Konzept

## Untergeschosse
### -2 Technick & service
    **Links:** Hausmeisterbereich, nur Personal
    **Rechts:** Servicebereich: Küche & Waschküche

### -1 Wellness& Sport
    **Links:** Wellnesbereich mit Sauna, Ruheort, Massagesalon
    **Rechts:** Sportbereich, Gym, Yoga/Kurse

## Erdgeschoss (EG)
    **Lobby (Zentrum):** Haupt-Eingang, Rezeption
    **Links:** Flur L-Form
    **Rechts:** Flur L-Form
    **Innenhoff:** Zwischen Fluren
    **Hinten:** Fahrstuhl & Treppenhaus

## Stockwerke 1-10
    **Links und Rechts:** L-Form flure
    **Zimmer pro Flur:** 5 Zimmer je Seite
    **Dachgeschoss:** Offenes Dach, Bänke, Pflanzen

##Navigation & Logik
    Räume werden als Dictionary in Godot angelegt
    Keys: Raum-ID (z.B. 101, Floor_1_left)
    Werte: Beschreibung (`desc`), Richtungen (`north`, `south`, `east`, `west`, `up`, `down`)
    Story & Rätsel werden dynamisch wärend der Entwicklung erzeugt

## Hinweise
    Dieses Dokument dient als Grundlage für Storyentwicklung & Raumplanung
    Atmosphäre, Rätsel und Blockaden werden beim Coden / Spielen nach Bedarf ergänzt