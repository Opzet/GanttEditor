
## Editing in Blazor Gantt Chart Component
Gantt Chart / Editing

![image](https://github.com/user-attachments/assets/7eab2380-eb59-4b62-b909-b28d0c66057f)

This sample demonstrates the various phases involved in constructing a residential house, from testing the soil to handing over the fully constructed property to the owner. This also demonstrates CRUD operations in Gantt Chart. You can perform CRUD operations as follows,

Add - To add a new task, click the Add toolbar button
Edit - To edit a task, double click a row or double click a taskbar or click the Edit toolbar button after selecting a row
Indent - To indent a task, click the Indent toolbar button after selecting a row
Outdent - To outdent a task, click the Outdent toolbar button after selecting a row
Delete - To delete a task, click the Delete toolbar button after selected a row
Update,Cancel - You can save or discard changes by clicking the Update and Cancel toolbar buttons respectively

![image](https://github.com/user-attachments/assets/a72fa5d3-cbd8-49a3-82b0-4eca7fbfbb8d)

CRUD operations can be configured in Gantt Chart using GanttEditSettings and AllowTaskbarEditing. Gantt Chart has two Mode to manipulate the datasource

In this demo, Auto mode is enabled for editing. On the TreeGrid side, you can start editing any row by double-clicking on it or clicking on the toolbar’s Edit button. Then, the currently selected row will be changed to edit state. On the Chart side, you can edit the tasks using the edit dialog by double-clicking on the taskbars and also you can edit the dependency connector lines using drag and drop action with connector line points available on either side of the parent taskbar, child taskbar, and milestones.

When the taskbar and connector point is dragged, the viewport shows left and right edges and the top and bottom edges, which automatically initiate horizontal and vertical scrolling.

To learn more about CRUD operations and managing tasks, refer to documentation section.

https://www.syncfusion.com/blazor-components/blazor-gantt-chart/editing


https://blazor.syncfusion.com/documentation/gantt-chart/


# Import and Export-
Microsoft project xml file in Syncfusion gantt

Demo sample and service available here to import or export Microsoft Project Planner XML file from Syncfusion Gantt

Refer the blog [here](https://www.syncfusion.com/blogs/post/microsoft-project-files-in-javascript-gantt-chart.aspx) for more information 
