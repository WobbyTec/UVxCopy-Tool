# UVxCopy-Tool-WobbyTec
Blender Version 5.x.x erforderlich ! ! (nicht für Blender 4.x.x oder älter geeignet)
extrahiert aus einem Mesh/Shape im GIANTS Editor UV2 und/oder UV3 um sie in Blender zusammenzuführen

(extracted from a mesh/shape in the GIANTS Editor UV2 and/or UV3 to merge them in Blender)
___________________________________________________________________________________________________________________________________
Tutorial (german)
https://www.youtube.com/watch?v=O6D2IYQmtpQ
___________________________________________________________________________________________________________________________________
German

Im ersten Schritt kopieren Sie die Lua-Datei in das Verzeichnis, z. B. C:\Programme\GIANTS Software\GIANTS_Editor_10.0.11\scripts. Speichern Sie das Programm „UV2OBJ.exe“ aus diesem Paket an einem geeigneten Ort (z. B. auf dem Desktop). Starten Sie den GIANTS Editor und öffnen Sie Ihr i3D-Modell, das Sie bearbeiten möchten. Wählen Sie das Mesh/Shape aus, das Sie ändern möchten (nur eins!!). Exportieren Sie das ausgewählte Mesh/Shape und erstellen Sie außerdem zwei oder drei Kopien davon, z. B. decals2.obj, decals2_UV2.obj und decals2_UV3.obj. Starten Sie nun UVxCopyWobbyTec über das Menü „Gemeinsame Skripte“ oben im GIANTS Editor. Sie sehen nun alle VT-Linien Ihres decal2-Mesh/Shape. Klicken Sie auf die Schaltfläche „copyUV2“ und starten Sie „UV2OBJ.exe“.
Wählen Sie nun die Datei „decals2_UV2.obj“ aus. Die VT-Linien werden automatisch eingefügt.
Das selbe können Sie mit der Schaltfläche „UV3 kopieren“ und der Datei „decals2_UV3“ tun. Öffnen/importieren Sie nun die OBJ-Dateien in Blender und erstellen Sie in „decals2“ zwei neue UV-Maps: „UV-MapUV2“ und „UV-MapUV3“. Wählen Sie zuerst „UV-MapUV2“ aus (nicht aktivieren nur selektieren) und klicken Sie dann in Blender auf eine freie Stelle, um die Auswahl aufzuheben. Führen Sie nun folgende Schritte aus: Halten Sie die linke Umschalttaste gedrückt und klicken Sie auf „decals2_UV2“ und anschließend auf „decals2“ in Ihrer Szene. Drücken Sie Strg+L und wählen Sie die Funktion „UV-Maps kopieren“. Wählen Sie nun in „decals2“ die UV-MapUV3 aus und wiederholen Sie den Vorgang mit „decals2_UV3“ in Ihrer Szene. Wenn alles korrekt ausgeführt wurde, befinden sich nun alle benötigten UVs im Hauptobjekt „decals2“. Sie können nun Ihre Änderungen vornehmen und das korrekte Objekt exportieren.

______________________________________________________________________________________________________________________________________
english

First Step , copy the lua into the directory for Example: C:\Program Files\GIANTS Software\GIANTS_Editor_10.0.11\scripts
save the Program within this pack "UV2OBJ.exe" to a good available place ( Desktop or other)
Start GIANTS Editor and open your i3d Modell you want to change. select a Mesh/Shape you want change (only one)
export the selected Mesh/Shape and export also 2 or 3 Copys from , Example: decals2.obj , decals2_UV2.obj , decals2_UV3.obj
now start the UVxCopyWobbyTec out of the Menue on Top of GIANTS Editor "shared scripts"
now you will see all vt Lines were found out of your decal2 Mesh/Shape. press Button copyUV2 and start forward "UV2OBJ.exe" ... now choose the decals2_UV2.obj and the vt Lines will write into
You can do the same with the button copy UV3 and the file decals2_UV3
Now you can open/import the obj Files in Blender and you have to edit in the decals2.obj File decals2.obj 2 new UV-Maps UV-MapUV2 and UV-MapUV3
select at first UV-MapUV2 and than click on the free place in Blender to loose all selections, now do follow clicks
hold ShiftLeft and click on decals2_UV2 and than on decals2 in youre Scene , press Ctrl+L and use the function "Copy UV-Maps"
Now select in the base decals2 the UV-MapUV3 and do it again with decals2_UV3 on your scene
If all is right done you have in main decals2 object all UVs you need and now you can do your changes !! and Export a right Object to use
