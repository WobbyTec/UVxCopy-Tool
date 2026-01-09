# UVxCopy-Tool-WobbyTec
UVxCopyWobbyTec läuft unter folgenden Blender Versionen:  ✅ v4.0.1  ✅ v4.1.1   ✅v4.5.4   ✅ v5.x.x  --- nicht mit  ❌ 4.2.x   ❌ 4.3.x  ❌ 4.4.x

Es extrahiert aus einem Mesh/Shape im GIANTS Editor UV2 und/oder UV3 um sie in Blender zusammenzuführen

(extracted from a mesh/shape in the GIANTS Editor UV2 and/or UV3 to merge them in Blender)
___________________________________________________________________________________________________________________________________
Tutorial (german)
https://www.youtube.com/watch?v=O6D2IYQmtpQ
___________________________________________________________________________________________________________________________________
German

Installation:
- die UVxCopyWobbyTecFS22.lua in das Verzeichnis C:\Program Files\GIANTS Software\GIANTS_Editor_10.0.11\scripts kopieren
- Blender öffnen und unter Einstellungen > AddOns > Install from Disk .. wählen und die UVxMergeWobbyTec.py auswählen

Ausführung :
- Im GIANTS Editor das Mesh/Shape auswählen das exportiert/bearbeitet werden soll und es einmal als OBJ exportieren und speichern
- Das Script "UVX-Copy-WobbyTec" aus dem Scipt Menü ausführen...
- das Fenster das sich öffnet wenn alle Zeilen ausgelesen wurden (FS22 Version bitte warten bis Buttons wieder klickbar )
- das Fenster kann geschlossen werden 
- den GIANTS Editor aber geöffnet lassen bzw. nach dem Schliessen nicht starten !! bis die Arbeit an der OBJ abgschlossen ist in Blender !!!
- In Blender die exportierte OBJ importieren und in den UV_Editor wechseln
- den UV Bereich auf der rechten Seite in den Blick Bereich hoch schieben
- mit der Maus auf der rechten Seite die Taste "N" drücken und im Seiten Menü "WOBBYTEC" Register anklicken
- im Ersten Eingabefeld oben rechts mit dem "Ordner- Symbol" die exportiert OBF Datei auswählen
- bei Start der LS25 Version ist wenn der GIANTS Editor v10.x genutzt wird nichts weiter zu tun weil die LOG Datei Default eingestellt ist
  sollte sich die LOG Datei woanders befinden als angezeigt wird diese bitte manuell einstellen
- das Objekt das die UV2/UV3 empfangen soll rechts in der Szene selektieren !!
- "UV2 + UV3 erzeugen" anklicken und die UVs werden in das selktierte Objekt geschrieben

Sollten Fehler auftreten, ggf. den Vorgang wiederholen

______________________________________________________________________________________________________________________________________
english:

Installation
- Copy UVxCopyWobbyTecFS22.lua to the directory C:\Program Files\GIANTS Software\GIANTS_Editor_10.0.11\scripts
- Open Blender and go to Preferences > AddOns > Install from Disk... and select UVxMergeWobbyTec.py

Executing:
- In the GIANTS Editor, select the mesh/shape you want to export/edit, export it as an OBJ file, and save it.
- Run the script "UVX-Copy-WobbyTec" from the Script menu...
- The window that opens after all lines have been read (FS22 version, please wait until the buttons are clickable again)
- This window can be closed.
- Leave the GIANTS Editor open, or do not start it after closing it, until the work on the OBJ file in Blender is complete!
- Import the exported OBJ file into Blender and switch to the UV Editor.
- Move the UV area on the right side up into view.
- Press the "N" key on the right side of the screen and click the "WOBBYTEC" tab in the side menu.
- In the first input field in the upper right, select the exported OBF file using the folder icon.
- When starting the LS25 version, if you are using the GIANTS Editor v10.x, no further action is required because the LOG file is set to the default location.
  If the LOG file is located elsewhere than displayed, please configure it manually.

- Select the object in the scene on the right that should receive the UV2/UV3.
- Click "Generate UV2 + UV3" and the UVs will be written to the selected object.

If errors occur, repeat the process.
