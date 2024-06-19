<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TO-DO List</title>
<style>

body{
    background-color:powerblue;
    display: flex;
    justify-content: center;
    align-items: center;
    boarder
    height: 100px;
}
div{
    border:10px groove red ;
}
div form{
padding:10px 50px 10px 50px;
}
</style>

</head>
<body style="background-color:skyblue">
    <div class="container">
        <h1 style="color:green">TO-DO List</h1>
        <form id="todo-form"><br><br>
            <input type="text" id="todo-input" placeholder="Add a new task..." required>
            <button type="submit">Add</button><br><br>
	    <input type="text" id="todo-input" placeholder="Add a new task..." required>
            <button type="submit">Add</button><br><br>

	    <input type="text" id="todo-input" placeholder="Add a new task..." required>
            <button type="submit">Add</button><br><br>
	    <input type="text" id="todo-input" placeholder="Add a new task..." required>
            <button type="submit">Add</button>

        </form>
        <ul id="todo-list"></ul>
    </div>
</body>
</html>
