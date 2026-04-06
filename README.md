# todo-app
Nice app for frotend developer 
<h1>Hello</h1>
<p>This is my first website</p>
<!DOCTYPE html>
<html>
<head>
    <title>My First Website</title>
</head>
<body>

<h1>My Name is Prathmesh</h1>
<p>I am learning frontend development 🚀</p>

<button>Click Me</button>

</body>
</html>
<style>
body {
    background-color: lightblue;
    text-align: center;
}

h1 {
    color: darkblue;
}

p {
    font-size: 20px;
}

button {
    background-color: black;
    color: white;
    padding: 10px;
    border-radius: 5px;
}
</style>
<h1>Hello</h1>
<p>This is my first website</p>
<!DOCTYPE html>
<html>
<!DOCTYPE html>
<html>
<head>
    <title>My First Website</title>
</head>
<body>

<h1>My Name is Prathmesh</h1>
<p>I am learning frontend development 🚀</p>

<button>Click Me</button>

</body>
</html>
<style>
body {
    background-color: lightblue;
    text-align: center;
}

h1 {
    color: darkblue;
}

p {
    font-size: 20px;
}

button {
    background-color: black;
    color: white;
    padding: 10px;
    border-radius: 5px;
}
</style>
.container {
    display: flex;
    justify-content: center;
    gap: 20px;
}
<div class="container">
    <button>Login</button>
    <button>Signup</button>
</div>
justify-content: space-between;
justify-content: space-around;
<!DOCTYPE html>
<html>
<head>
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Arial;
            margin: 0;
            background-color: #f5f5f5;
        }

        .navbar {
            background: black;
            color: white;
            padding: 15px;
            display: flex;
            justify-content: space-between;
        }

        .container {
            text-align: center;
            padding: 50px;
        }

        button {
            padding: 10px 20px;
            background: blue;
            color: white;
            border: none;
            border-radius: 5px;
        }
    </style>
</head>
<body>

<div class="navbar">
    <div>Prathmesh</div>
    <div>Home | About | Contact</div>
</div>

<div class="container">
    <h1>Hello, I am Prathmesh 👋</h1>
    <p>Frontend Developer in progress 🚀</p>
    <button>Hire Me</button>
</div>

</body>
</html>
@media (max-width: 600px) {
    .navbar {
        flex-direction: column;
        text-align: center;
    }

    .container {
        padding: 20px;
    }

    h1 {
        font-size: 22px;
    }
}
button {
    width: 100%;
}
<script>
function showMessage() {
    alert("Hello Prathmesh 🚀 You clicked the button!");
}
</script>
<button onclick="showMessage()">Click Me</button>
<h2 id="text">Hello Prathmesh 👋</h2>
<button onclick="changeText()">Change Text</button>
<script>
function changeText() {
    document.getElementById("text").innerText = "You are becoming a Frontend Developer 🚀";
}
</script>
document.getElementById("text").style.color = "red";
<input type="text" id="taskInput" placeholder="Enter task">
<button onclick="addTask()">Add</button>

<ul id="taskList"></ul>
<script>
function addTask() {
    let input = document.getElementById("taskInput");
    let task = input.value;

    if (task === "") return;

    let li = document.createElement("li");
    li.innerText = task;

    li.onclick = function() {
        li.remove();
    };

    document.getElementById("taskList").appendChild(li);

    input.value = "";
}
</script>
