# todo-app

#Directory Layout
const taskCompleted = function() {               // Mark a task as complete
  const listItem = this.parentNode;              // We assign it for readability
  completedTasksHolder.appendChild(listItem);  // Append the task list item to the #completed-tasks
  bindTaskEvents(listItem, taskIncomplete);    // We bind it to the opposite holder
};
