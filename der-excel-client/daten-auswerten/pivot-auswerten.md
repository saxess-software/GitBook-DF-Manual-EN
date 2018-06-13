### Pivot Evaluation 

Pivot evaluations can be set up on DataFactory work, factory and product line levels, and contain all information of the selected work, factory or product line as well as that of the levels below. 

When an http-connection is created, a .csv file is generated with all numeric values recorded in the products of the selected hierarchical level. The .csv file is saved in the csv folder in the source directory of your DataFactory. If you are using a DataFactory database on your own SQL server, a connection with Excel will be established that updates directly over the server.

#### Pivot Evaluation on the Work Level

To create a pivot evaluation on the work level, proceed as follows:

1\) In the factory and product overview, click on the ActionLink. 

---

![](/assets/lf1.png)

---

2\) Select the **Pivot View** option.

---

![](/assets/piv1.png)

---

3\) If you are using a DataFactory Database on your own SQL server, the pivot view will open automatically. If you are using an http-connection, a dialog box will open in which you can choose from the following options:

---

![](/assets/piv2.png)

---

| Selection | Description |
| --- | --- |
| Download CSV for numeric values and download pivot table | A .csv file will be downloaded and saved in the DataFactory folder "csv". A new spreadsheet containing the pivot table will be created in your Excel folder. |
| Download CSV for numeric values | A .csv file will be downloaded and saved in the DataFactory folder “**csv**”. |
| Generate pivot table from local CSV | The DataFactory “**csv**” will open. You may then select a .csv file to show in your Excel folder.  |

---

![](/assets/piv4.png)

---

4\) All values for all factories and product lines will be displayed in the pivot table. 

---

![](/assets/piv3.png)

---

> **Note:** The pivot table can be customized according to your preferences.



