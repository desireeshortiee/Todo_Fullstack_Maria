Django API endpoints

Get All Tasks (GET) = https://backendmaria-d9eg.onrender.com/mytodo/
Create a Task (POST) = https://backendmaria-d9eg.onrender.com/mytodo/
Get a Specific Task (GET) = https://backendmaria-d9eg.onrender.com/mytodo/{id}/
Update a Task (PUT) = https://backendmaria-d9eg.onrender.com/mytodo/{id}/
Delete a Task (DELETE) = https://backendmaria-d9eg.onrender.com/mytodo/{id}/

Report on the mytodo app:

Overview: The mytodo app helps users organize their tasks with ease, offering features like adding new tasks, editing existing ones, and deleting tasks. It also includes a filtering option to sort tasks by their status (completed or pending) and offers a dark mode for a more comfortable user experience.

Key Features:
Dark Mode: Switch between dark and light themes for better readability.

Task Management:
Add Task: Create new tasks with a simple input.
Edit Task: Modify the title of any existing task.
Delete Task: Remove tasks you no longer need.
Task Filters: Easily filter tasks by their status—view all, completed, or pending tasks.

Challenges Faced:
Deployment Issues (Render): I initially had trouble deploying the app on Render due to a misconfiguration in the ALLOWED_HOSTS setting in Django. I fixed this by updating the setting to include the correct domain for the deployed app.
Installing Dependencies: I ran into issues while installing dependencies from requirements.txt. The problem was resolved by ensuring the Python environment was correctly set up and reinstalling the necessary packages.

Solutions:
Deployment Issue: I adjusted the ALLOWED_HOSTS setting in Django to match the deployed URL on Render, ensuring the app could handle requests properly.
Dependency Installation: I verified the environment and manually reinstalled the dependencies, making sure all packages were compatible with the project.

Conclusion: The mytodo app is now fully operational and live. It offers all the core features for managing tasks, enhanced with dark mode and task filtering options. The issues I faced during deployment and setup have been resolved, and the app is now accessible online for users to enjoy.
