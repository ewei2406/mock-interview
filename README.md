# mock-interview

This is a simple TODO list application, with the ability to add, edit, and delete TODO list items.

Each item has the following properties:

- Date created (Date)
- Name (String)
- Category (String: school, career, other)
- Completed (Boolean)

Currently, the user can see all their TODO list items, but has a few requests. Your tasks will be involving
implementing the new features, and debugging the features that do not work correctly.

1. Completed tasks should have a checkmark ("✓"), while incomplete should have nothing, instead of the "true" and "false".
2. There looks like a bug with filtering the tasks by start and end date. 
3. The user wants to be able to filter by category.
4. The user wants to be able to filter by completion status.
5. The user wants to sort their list effectively, on any category.
6. The user wants to sort their list in both ascending and descending order.
7. When there are ties in sorting, the user wants the tasks with the alphebetically first name to appear first.