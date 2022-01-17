<p align="center">
	<img
		width="300"
		alt="4Geeks Academy"
		src="https://github.com/4GeeksAcademy/About-4Geeks-Academy/blob/master/site/static/background_art.jpg?raw=true">
</p>


<h1 align="center">Welcome to 4Geeks Academy</h1>


<h3 align="center">&lt;Todo List API in Python Flask&gt;</h3>

## Content

1. Language
2. Project instructions

## 👩‍💻Language

<p>This project contains:</p>

<ol>
    <li>PYTHON</li>
    <li>APIS</li>
</ol>

## 📝Proyect instructions

We are going to be building a REST API that exposes 3 endpoints to the internet:

GET /todos
POST /todos
DELETE /todos/<int:position>

<h3><b>GET /todos</b></h3>

Will return the list of all todos like this:

[
    {
        "done": true,
        "label": "Sample Todo 1"
    },
    {
        "done": true,
        "label": "Sample Todo 2"
    }
]

<h3><b>POST /todos</b></h3>

It's going to add a new todo to the list, it will receive the following request body:

{
    "done": true,
    "label": "Sample Todo 1"
}
And return the updated list of todos.

<h3><b>DELETE /todos/<int:position></b></h3>

It's going to remove one todo based on a given position at the end of the url, and return the updated list of todos.
