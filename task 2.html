<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Contact Form & To-Do List</title>
  <style>
    * {
      box-sizing: border-box;
    }
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      margin: 0;
      padding: 20px;
    }
    h1 {
      text-align: center;
      color: #333;
    }
    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }
    .form-container, .todo-container {
      background: #fff;
      padding: 20px;
      border-radius: 10px;
      width: 100%;
      max-width: 400px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    input, textarea, button {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      background-color: #4CAF50;
      color: white;
      cursor: pointer;
    }
    button:hover {
      background-color: #45a049;
    }
    .error {
      color: red;
      font-size: 0.9em;
    }
    .todo-list {
      list-style: none;
      padding: 0;
    }
    .todo-list li {
      background: #eee;
      margin: 5px 0;
      padding: 10px;
      border-radius: 5px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .todo-list li button {
      background: #e74c3c;
      color: white;
      padding: 5px 10px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    @media (max-width: 600px) {
      .container {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>
  <h1>Contact Form & To-Do List</h1>
  <div class="container">
    <!-- Contact Form -->
    <div class="form-container">
      <h2>Contact Us</h2>
      <form id="contactForm">
        <input type="text" id="name" placeholder="Your Name" />
        <div class="error" id="nameError"></div>

        <input type="email" id="email" placeholder="Your Email" />
        <div class="error" id="emailError"></div>

        <textarea id="message" placeholder="Your Message"></textarea>
        <div class="error" id="messageError"></div>

        <button type="submit">Submit</button>
        <div id="formSuccess" style="color: green; margin-top: 10px;"></div>
      </form>
    </div>

    <!-- To-Do List -->
    <div class="todo-container">
      <h2>To-Do List</h2>
      <input type="text" id="todoInput" placeholder="Add a new task..." />
      <button onclick="addTodo()">Add Task</button>
      <ul class="todo-list" id="todoList"></ul>
    </div>
  </div>

  <script>
    // Form Validation
    document.getElementById('contactForm').addEventListener('submit', function(e) {
      e.preventDefault();
      let isValid = true;
      let name = document.getElementById('name').value.trim();
      let email = document.getElementById('email').value.trim();
      let message = document.getElementById('message').value.trim();

      document.getElementById('nameError').textContent = "";
      document.getElementById('emailError').textContent = "";
      document.getElementById('messageError').textContent = "";
      document.getElementById('formSuccess').textContent = "";

      if (name === "") {
        document.getElementById('nameError').textContent = "Name is required.";
        isValid = false;
      }
      if (email === "" || !/^\S+@\S+\.\S+$/.test(email)) {
        document.getElementById('emailError').textContent = "Valid email is required.";
        isValid = false;
      }
      if (message.length < 10) {
        document.getElementById('messageError').textContent = "Message must be at least 10 characters.";
        isValid = false;
      }

      if (isValid) {
        document.getElementById('formSuccess').textContent = "Form submitted successfully!";
        document.getElementById('contactForm').reset();
      }
    });

    // To-Do List
    function addTodo() {
      let input = document.getElementById('todoInput');
      let task = input.value.trim();
      if (task === "") {
        alert("Please enter a task.");
        return;
      }

      let li = document.createElement('li');
      li.textContent = task;

      let btn = document.createElement('button');
      btn.textContent = "Delete";
      btn.onclick = function() {
        this.parentElement.remove();
      };

      li.appendChild(btn);
      document.getElementById('todoList').appendChild(li);
      input.value = "";
    }
  </script>
</body>
</html>