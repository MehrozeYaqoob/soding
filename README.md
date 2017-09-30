# Simple TODO List

Task given by a recruitment company in Malaysia


**To Do** is an android app that allows building a todo list and basic todo items management functionality including adding new items, editing, deleting an existing item and reminder of todo items using local notifications.

Submitted by: **Mehroze Yaqoob**

## User Stories

The following **required** functionality is completed:

* [x] User can **successfully add and remove items** from the todo list
* [x] User can **tap a todo item in the list and bring up an edit screen for the todo item** and then have any changes to the text reflected in the todo list.
* [x] User can **persist todo items** and retrieve them properly on app restart

Database Schema

ToDoID | ToDoTaskDetails | ToDoTaskPriority | ToDoTaskStatus | ToDoNotes |
--- | --- | --- | --- | --- |
Unique ID for each Task | Task Details | Task Priority- High, Normal, Low | Completed? | Extra Notes
`Int Primary Key` | `String` | `String` | `String` | `String` |
