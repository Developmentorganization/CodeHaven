# CodeHaven
<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>To-Do List</title>
</head>
<body>
    <h1>My To-Do List</h1>
    <input type="text" id="taskInput" placeholder="Add a new task">
    <button onclick="addTask()">Add</button>
    <ul id="taskList"></ul>

    <script>
        function addTask() {
            const input = document.getElementById('taskInput');
            const taskList = document.getElementById('taskList');
            const newTask = document.createElement('li');
            newTask.textContent = input.value;
            taskList.appendChild(newTask);
            input.value = '';
        }
    </script>
</body>
</html>
Iframe URL's used in comments are not imported, we need to add them manually.
URLs with a maximum length of 2,000 characters,  exceed this limit are skipped from the import process.


Data setup for source test site to work on cloud to cloud migration 


Worked on addons for honeywell

1. Baselines for Confluences 
2. Comala document management 
3. Scroll PDF EXporter 
4. Content Formatting macros for Confluence
5. Reporting for confluence - used for reporting 
6. Zephyr scale reporting for confluence - need to do more  
