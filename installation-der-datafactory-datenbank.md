# DataFactory Datenbank

## Installation der DataFactory-Datenbank

Um sich in Ihrem Excel-Client oder dem Web-Client mit Ihrer eigenen DataFactory-Datenbank verbinden zu können, muss diese auf Ihrem SQL Server zunächst angelegt werden. Das bedeutet, dass über das SQL Management Studio eine Datenbank auf dem SQL Server erstellt und auf dieser Datenbank ein Skript ausgeführt wird, welches alle DataFactory-eigenen Tabellen, Sichten und Prozeduren [(API)](Grundlagen/technischer-uberblick/datenbank-und-api.md) anlegt. Gehen Sie dazu wie folgt vor:

1) Legen Sie in Ihrem SQL Management Studio eine **neue Datenbank** an.

---
![](/assets/iu10.png)

---

2) Geben Sie Ihrer Datenbank einen **Namen**.

---
![](/assets/iu11.png)

---

3) Stellen Sie sicher, dass im Reiter **Optionen** das **Wiederherstellungsmodell auf "Einfach"** gesetzt ist und klicken Sie anschließend auf **OK**.

---
![](/assets/iu12.png)

---

4) Die neue Datenbank wurde erstellt und ist zu diesem Zeitpunk noch leer.

---
![](/assets/iu13.png)

---

5) Öffnen Sie nun den **+** -Ordner in Ihrem DataFactory-Ordner und wählen Sie dort den Ordner **scripts** und dann den Ordner **create**. Dort finden Sie zwei Skripte, die aus Ihrer Datenbank eine DataFactory-Datenbank machen. Öffnen Sie das gewünschte Skript durch Anklicken.

---
![](/assets/iu14.png)

---

6) Das Skript wird in Ihrem SQL Management Studio geöffnet. Wählen Sie über das Dropdown-Menü Ihre Datenbank auf der Sie das Skript ausführen wollen und klicken Sie auf den Button **Ausführen**.

---
![](/assets/iu15.png)

---

7) Wenn das Skript erfolgreich ausgeführt wurde, wird Ihnen folgendes Ergebnis ausgegeben. Nachdem Sie Ihre Datenbank aktualisiert haben, sehen Sie nun die darin enthaltenen Tabellen, Sichten und Prozeduren.

---
![](/assets/iu16.png)

---

8) Öffnen Sie Ihren **Excel-Client** und verbinden Sie sich wie in Kapitel [Werk verbinden](werk/werk-verbinden.md) beschrieben mit Ihrer soeben erstellten DataFactory-Datenbank

## Update der API

Um die API auf Ihrem Server zu aktualisieren, gehen Sie wie folgt vor.

1) Öffnen Sie in Ihrem DataFactory-Ordner, den Ordner **+**, anschließend den Ordner **scripts** und dann den Ordner **update**. Öffnen Sie die sql-Datei zur Aktualisierung der API.

---
![](/assets/iu20.png)

---

2) Es öffnet sich Ihr SQL Management Studio. Führen Sie das Skript auf Ihrer DataFactory-Datenbank aus, indem Sie im **Dropdown-Menü** die Datenbank auswählen und anschließend auf **Ausführen** klicken.

---
![](/assets/iu21.png)

---

3) Ihre Datenbank ist nun mit der aktuellen API ausgestattet.















