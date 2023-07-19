# Talis Information
<h1>Talis - Aspire</h1>

<h2>Description</h2>
<br/>This project gives detailed information of the various modes of resources (Module items) used in various modules which are taught in the University across all campuses, their significance, total item count and total Users Count in accessing those resources.
<br />


<h2>Platform Used</h2>

- <b>Power BI</b> 
- <b>SQL Server Management Studio</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
<br/>This report gives the detail information of all the aspects in regards to module resources usage.<br/>
<br/>The data is obtained by using multiple joins to connect various table in SQL Database and is imported into Power BI to represent that data visually.<br/> 
<br/>
Visuals Used: <br/>
<br/>Slicer for Modules: To select the specific module and to see its Item count, Status, Type, Significance and User's count per time intervals<br/>
<br/>Card Visual: To display the total number of items and users for respective modules.<br/>
<br/>Pie Chart: To display the % of the item status and types individually used in the module.<br/>
<br/>Tree Graph: To categorise the item significance which provides detailed information to users on what should be considered mandatorily to prepare for exams, assignments and additional information in regards to the module.
<br/>Stacked Column Chart: To see total users counts in different academic years: <br/>
<img src="https://i.imgur.com/yYckAex.png" height="80%" width="80%"/>
<br />
The button Item information is added which has an action of Drill through to navigate to other page of the Power BI report which gives detail information of the item such as module_code, Item Title and its ID used, Item type and Significance and status of the item.
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/Yz4cOpj.png" height="80%" width="80%"/>
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
