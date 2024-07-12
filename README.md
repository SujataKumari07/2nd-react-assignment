React-Assignment-2
CELEBAL TECHNOLOGIES - REACT JS TRAINING, ASSIGNMENT-2 : TO-DO LIST Develop a React To-Do List component allowing task addition, removal, and completion marking. 
Validate task input, display tasks dynamically, and offer optional sorting, filtering, and localStorage integration. Submit code on Git with brief testing guidance. 

Input Validation:
Attempt to add an empty task (just spaces or no input).
Verify that an empty task is not added and no changes occur in the task list.

Dynamic Task Display:
Add multiple tasks and verify that all tasks are displayed correctly.
Check that tasks remain in the correct order after additions and removals.

Sorting (Optional):
Implement sorting functionality (e.g., alphabetical order) and test by adding tasks in random order.
Verify that tasks are displayed in the expected sorted order.

Filtering (Optional):
Implement filtering functionality (e.g., show/hide completed tasks).
Test by marking tasks as completed and verifying they can be filtered out.

localStorage Integration:
Refresh the page and verify that previously added tasks persist.
Add new tasks and ensure they are stored and retrieved correctly from localStorage.

Tools and Techniques:
Manual Testing: Perform the above steps manually by interacting with your application in the browser.
Console Logging: Use console.log() statements in your React components (e.g., in useEffect hooks) to log task states, input values, and localStorage interactions. 
                 This helps in verifying that data is being stored and manipulated correctly.
React Developer Tools: Use browser extensions like React Developer Tools to inspect component states and props during interactions. This can help in debugging 
                       and verifying component behavior.
Cross-browser Testing: Ensure your application works correctly across different browsers (Chrome, Firefox, Safari, etc.) to catch any browser-specific issues.
