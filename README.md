# todo_list
body {
    font-family: Arial, sans-serif;
    background-color: #f4f6f8;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.container {
    background: white;
    padding: 20px;
    border-radius: 12px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    width: 300px;
    text-align: center;
}

h1 {
    margin-bottom: 20px;
}

.input-box {
    display: flex;
    margin-bottom: 15px;
}

input {
    flex: 1;
    padding: 8px;
    border: 1px solid #ccc;
    border-radius: 8px 0 0 8px;
    outline: none;
}

button {
    padding: 8px 12px;
    border: none;
    background: #28a745;
    color: white;
    border-radius: 0 8px 8px 0;
    cursor: pointer;
}

button:hover {
    background: #218838;
}

li {
    list-style: none;
    padding: 8px;
    background: #eee;
    margin: 5px 0;
    border-radius: 6px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

li.completed {
    text-decoration: line-through;
    color: gray;
}

.delete {
    background: red;
    color: white;
    padding: 3px 6px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}
