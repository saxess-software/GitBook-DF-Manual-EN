# DataFactory Database

## Installation of the DataFactory Database

To enable the DataFactory database to connect to your Excel client or the web client, it will first need to be set up on your SQL server. This means that a database must be created on the SQL server via the SQL Management Studio. A script will then be executed on this database which creates all DataFactory-specific tables, views and procedures \([API](/Grundlagen/technischer-uberblick/datenbank-und-api.md)\). Proceed as follows:

1\) Create a **new database** in your SQL Management Studio.

---

![](/assets/iu10.png)

---

2\) Enter a **name** for your database.

---

![](/assets/iu11.png)

---

3\) In the **Options** tab, make sure that your recovery model is set to **Basic** and click **OK** to confirm.

---

![](/assets/iu12.png)

---

4\) The new database has been created and is at this time still empty.

---

![](/assets/iu13.png)

---

5\) Open the **+** folder in your DataFactory folder and select the **Scripts** folder, followed by the **Create** folder. Here you will find two scripts which will create a DataFactory database from your database. Click on your chosen script to open it.

---

![](/assets/iu14.png)

---

6\) The script will be opened in your SQL Management Studio. In the drop-down menu, select the database on which you wish to execute the script and click the **Execute** button. 

---

![](/assets/iu15.png)

---

7\) If the script has been successfully executed, the results will now be presented as shown. Once you have updated your database you will be able to view the tables, views and procedures contained within. 

---

![](/assets/iu16.png)

---

8\) Open your **Excel client** and connect to your newly-created DataFactory database as described in the chapter [Connecting a Work](/der-excel-client/werk/werk-verbinden.md).

## Updating the API

To update the API on your server, proceed as follows:

1\) Open the **+** folder in your DataFactory folder, followed by the **Scripts**  folder. Select the **Update** folder. Open the SQL file to update the API.

---

![](/assets/iu20.png)

---

2\) Your SQL Management Studio will open. Execute the script on your DataFactory database by selecting the database in the drop-down menu and clicking on **Execute**. 

---

![](/assets/iu21.png)

---

3\) Your database is now equipped with the current API.

