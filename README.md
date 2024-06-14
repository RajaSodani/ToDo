# ToDo

Re-commit as previous repo is removed

# Deployed Link

https://to-do-rs.vercel.app/


# ***Testing Guidelines***


### Functional Testing

1. **Add Task**
   - Enter a valid task in the input field and click the "Add Task" button.
   - Try adding an empty task and verify that an alert or validation message is displayed.

2. **Complete Task**
   - Click the "Complete" button next to a task.
   - Verify that the task is marked as completed (e.g., text is struck through).
   - Click the "Unmark" button and ensure the task returns to its original state.

3. **Remove Task**
   - Click the "Remove" button next to a task.
   - Ensure the task is removed from the list.

4. **Edit Task**
   - Click the "Edit" button next to a task.
   - Update the task text and click "Save".
   - Verify the task is updated in the list.

5. **Filter Tasks**
   - Use the filter dropdown to switch between "All", "Completed", and "Pending" tasks.
   - Verify that only the relevant tasks are displayed for each filter option.


### Boundary Value Testing

1. **Long Task Text**
   - Add a task with a very long text.
   - Ensure the text is displayed properly and no UI elements break.

2. **Rapid Task Addition**
   - Quickly add multiple tasks one after another.
   - Ensure all tasks are added correctly without any UI or functional issues.

### Browser Compatibility

1. **Test on Different Browsers**
   - Verify the application works on major browsers like Chrome, Firefox, Safari, and Edge.

2. **Responsive Design**
   - Test the application on different screen sizes, including mobile devices.
   - Ensure the layout is responsive and usable on all devices.


