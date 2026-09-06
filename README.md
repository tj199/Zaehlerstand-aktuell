STROMZÄHLER PRO – Version 1.0
============================

Enthaltene Funktionen
---------------------
- Mehrere Stromzähler verwalten
- Name und optionale Zählernummer je Zähler
- Eigener aktueller Strompreis je Zähler
- Familien-/Haushaltsname frei änderbar
- Zählerstände mit Systemdatum/Systemuhrzeit erfassen
- Datum und Uhrzeit alternativ manuell auswählen
- Verbrauch zwischen zwei Messwerten automatisch berechnen
- Kosten je Messintervall automatisch berechnen
- Historische Preise bleiben je Eintrag erhalten
- Übersicht mit aktuellem Stand, Verbrauch, Kosten und Preis
- Scrollbare Tabelle aller Einträge
- Diagramm für Verbrauch und Kosten
- PDF-Bericht mit schönem Layout
- Drucken über den Windows-Druckdialog
- System-Tray: Programm kann beim Schließen im Hintergrund weiterlaufen
- Optionaler Windows-Autostart
- Daten werden lokal in SQLite gespeichert

Wo werden die Daten gespeichert?
--------------------------------
Unter Windows:
%APPDATA%\StromzaehlerPro\stromzaehler.db

Die Daten bleiben dadurch auch erhalten, wenn du eine neue Programmversion installierst.

Programm direkt aus Python starten
----------------------------------
1. Python 3.11 oder 3.12 installieren.
2. In diesem Ordner eine Eingabeaufforderung öffnen.
3. Eingeben:
   py -m pip install -r requirements.txt
4. Danach:
   py main.py

Windows-EXE erstellen
---------------------
Am einfachsten INSTALLATION_ERSTELLEN.bat doppelklicken.
Alternativ nur für die EXE: build_windows.bat doppelklicken.
Danach liegt die Anwendung unter:
dist\StromzaehlerPro\StromzaehlerPro.exe

Schöne Installationsdatei erstellen
-----------------------------------
1. Inno Setup installieren.
2. Zuerst build_windows.bat ausführen.
3. Danach installer.iss mit Inno Setup öffnen.
4. "Compile" anklicken.
5. Die fertige Installationsdatei liegt in:
   installer_output\StromzaehlerPro_Setup.exe

Hinweis
-------
Eine echte Windows-EXE kann in dieser Linux-Arbeitsumgebung nicht zuverlässig
kompiliert werden. Die Projektdateien sind deshalb so vorbereitet, dass die EXE
und die Setup-Datei auf einem Windows-PC mit wenigen Klicks erzeugt werden können.


Startbild / Splash-Screen
--------------------------
Beim Start des Programms wird das von dir gewünschte Bild automatisch fuer 5 Sekunden angezeigt. Danach oeffnet sich die Hauptoberflaeche. Das gleiche Bild wird auch als Programmsymbol (Icon) verwendet.

## Download

Die aktuelle Windows-Version von **Zählerstand aktuell** kannst du hier herunterladen:

⬇️ [Zählerstand aktuell herunterladen](https://github.com/tj199/Zaehlerstand-aktuell/releases/tag/v1.0.0)

---

Entwickelt von **TJ** ⚡
