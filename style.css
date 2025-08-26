const taskInput = document.getElementById("in");
const listElement = document.getElementById("task");
const addBtn = document.getElementById("btn");

addBtn.addEventListener('click',()=>
{

    if(taskInput.value != '')
    {
        const task = taskInput.value.trim();
        const listItem = document.createElement("li");
        listItem.innerHTML = `
                        ${task}
                        <button class = "dbtn">Delete</button>
                        
                        `;
        listItem.querySelector(".dbtn").addEventListener('click', () => {
            listElement.removeChild(listItem);
    })
        listElement.appendChild(listItem);
        taskInput.value='';

    }
    else{
        alert("Please enter a task");
    }
});
