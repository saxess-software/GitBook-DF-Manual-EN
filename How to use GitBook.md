#### Verknüpfung GitHub und GitBook
GitBook kann mit GitHub verknüpft werden. Zunächst wird ein GitBook-Repository in GitHub angelegt. Danach muss auf GitBook unter Settings der Owner der Organisation das GitHub-Repository "GitBook" mit dem GitBook Account der Organisation verknüpft werden. Dieser Schritt kann nicht als Member der Organisation durchgeführt werden, da man in diesem Fall GitBook nur mit einem privaten GitHub-Repository verknüpfen kann.

Die Synchronisation zwischen GitBook und GitHub funktioniert nur in eine Richtung. D.h. man nimmt Änderungen in GitHub vor und schiebt sie dann zu GitBook oder umgekehrt. Gleichzeitiges Arbeiten auf beiden Plattformen zerstört den Link zwischen den beiden. 

![](/Bilder/GitBook/GitBook8.png)

Ist dieser Fall eingetreten, kann durch Klick auf "Force sync using..." der Link wieder hergestellt werden

![](/Bilder/GitBook/GitBook7.PNG)

Um ein Buch in GitBook zu erstellen, welches mit GitHub verknüpft ist, muss dieses bei der Anlage als GitHub-Book definiert werden.

![](/Bilder/GitBook/GitBook1.PNG)

#### Buch erstellen
Um ein neues Buch zu erstellen, auf welches alle Mitglieder der Organisation zugreifen bzw. dieses editieren können, muss dieses Buch durch den Owner der Organisation erstellt werden.

#### Kapitel anlegen

Klick auf "add article". In Reiter "Table of contents" wird ein neues Kapitel angelegt und in  Reiter "Files" wird eine neue .md Datei angelegt.

![](/Bilder/GitBook/GitBook2.PNG)

#### Unterkapitel anlegen

Rechtsklick auf das Kapitel, in welchem das Unterkapitel angelegt werden soll. In Reiter "Table of contents" wird ein neues Unterkapitel angelegt und in  Reiter "Files" wird eine neue .md Datei angelegt.

![](/Bilder/GitBook/GitBook4.PNG)

#### Bilder einfügen

Zunächst muss das Bild in GitBook importiert werden. 

**Option 1:** Ein Ordner "Bilder" angelegt, in welchem alle Bilder, die in diesem Buch genutzt werden sollen, importiert werden.

![](/Bilder/GitBook/GitBook5.PNG)

Klick in die Zeile, in welche das Bild eingefügt werden soll. Auswahl des gewünschten Bildes über das Icon "Insert image".

![](/Bilder/GitBook/GitBook6.PNG)

**Option 2:** 

Klick in die Zeile, in welche das Bild eingefügt werden soll.

Im Fenster "Insert Image" **"From Computer"** auswählen und dann das Bild in das Drag&Drop-Feld ziehen. Hierbei wird automatische ein Ordner "assets" angelegt, in welchen alle Bilder eingefügt werden

#### In PDF umwandeln

Das Buch kann als PDF, Mobi oder ePub heruntergeladen werden. Dazu muss der Owner der Organisation in den **Settings** des Buches das Feature **E-Books** aktivieren. 

![](/assets/PDF.png)

Sobald die Aktivierung vollzogen wurde, muss noch einmal ein Update des Buches veröffentlicht werden (**Publish** im GitBookEditor).

Dann erscheint im Eingangsfenster des Buches der Download-Button.

![](/assets/PDf2.PNG)













