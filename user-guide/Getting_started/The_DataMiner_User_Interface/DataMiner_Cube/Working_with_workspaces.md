---
uid: Working_with_workspaces
---

# Working with workspaces

A workspace is a Cube screen layout, which can be saved. Saving a workspace can be useful if you often use the same set of cards. If you open the workspace, you will immediately open those cards in the layout you saved.

To manage workspaces, click the Workspace button at the bottom of the Cube sidebar.

![Workspace](~/user-guide/images/Workspace.gif)

> [!NOTE]
>
> - The saved layout can include apps, like for instance Automation, and undocked alarm tabs, but not the position of the complete Alarm Console.
> - For each card, the page selected on the card, the position of the navigation pane, and the size of the card are also stored.
> - The icon indicating the workspace in the list shows the number of cards and their layout.
> - From DataMiner 10.2.3 onwards, [EPM cards](xref:EPM) can be saved in workspaces; however, this is only supported when the card layout is set to *Tab layout*.

The following actions are possible in the *Workspaces* pane:

- To open a workspace, click a workspace in the list.

- To open a workspace in a new, undocked window, right-click a workspace in the list and select *Open workspace in undocked window*.

- To delete a saved workspace, right-click the workspace in the list and select *Delete workspace*.

- To rename a workspace, right-click the workspace in the list and select *Rename workspace*.

- To change the description of a workspace, right-click the workspace in the list and select *Edit description*.

- To close all open cards, at the top of the list, click *Clean workspace*.

- To create a workspace containing all cards that are currently open:

   1. At the top of the list, click *Save workspace*.

   1. In the *Name* field, enter the name of the workspace.

   1. Optionally, add a description in the *Description* field.

   1. Exceptionally, if the workspace is to be used for elements, services or views that do not necessarily always have the same ID, but do always have the same name, select *Save the name of the open cards*.

> [!NOTE]
> With certain kinds of elements, it is possible to make a workspace that appears as an app in the *Apps* list. To do so, when you create a workspace, enter the description "\[Workspace for xxx\]", where xxx is the name of an element using a protocol with the tag \<App type="...">, specifically created for this purpose.
