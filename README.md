# Mohammad_Ansari-Student-Attendace-Dashboard
Objectives: The main objective of this project is to convert legacy labour-intensive cumbersome process to fully automated using latest Interactive Dashboard technology which will facilitates to visualize the comprehensive Student Attendance record as well as to keep track to ensure they are developing their technical competencies as well as taking appropriate actions on the defaulters. The Student data is extracted from the available database using the combination of SQL Views and parameterized Stored Procedures. The Dashboard uses the reporting services template within the SQL Server Data tools, it also uses the number of gadgets i.e. Tables, Gauges and Bar Charts to provide dynamic representation of the data basis on the user’s input. SQL Server Reporting Services (SSRS) provides a set of on-premises tools and services that create, deploy, and manage paginated reports. The SSRS solution flexibly delivers the right information to the right users. Users can consume the reports via a web browser, on their mobile device, or via email. Roadblocks and Solutions:
1.	Since this Dashboard is made to provide the solution to the real-world problem and convert legacy manual process into Dynamic automated solution, so there are iterations required to make Dashboard user-friendly
2.	Initial I tested the Dashboard with Input parameters where the user needs to provide the Student ID in the text box, but it looks like somewhere manual intervention. So, thought of making it automated and created a dropdown list which wasn’t working at first, however, I was able to make it working by exploring parameter options.
3.	Since each KPI returns single integer value in two digits, therefore, it was challenging how to present and which tool will be the best. By exploring other tools and tried a few of them but finally selected Table with Gauge and had some issues in making them work but with the previous assignment experience and online search made them work as expected.
Contents of the Report This project has collection of reporting Server widgets, the SQL Server Views, and the stored procedures. There are 3 Views, 18 stored procedures, 1 data source, Data sets, tables, Gauge and Bar Charts exist in the project each one provides unique functionality to make this Dashboard interactive. Functionality This reporting Server project accepts 5 input parameters aligned with the respective tools i.e. Student ID, Select Lecture Week, Select Lab Week and Select Lecture and lab Percentage and lecture Percentage fetches the data for the database and display on the available reporting tools i.e. tables, Gauge and Bar Charts and works as follows:
1.	When the user run the project or hit the Target Server Web URL i.e. http://machine_name/reportServer_SSRS.
2.	then it asks to select the report name
3.	It then opens the Dashboard Interface in the browser and asks for the input values.
4.	Basis on the input values the Dashboard updates the respective tools and displays the records.
