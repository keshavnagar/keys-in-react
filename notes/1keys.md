so in this lecture, i understand the problem when we have a todo list suppose where we use map method to show the output of todolist
so the first thing is there 

Todo List
Add Task
mango 
we create juice of mango

banana 
banana has not acid

apple 
apple has acid

so the todo list , and than an input field in which we write the input and than click on add task suppose first input is mango and we write the we create juice of mango and we are adding another input that is banana and we see the mango and their input field text is with mango not transfer to banana because we assign key to currTask as in every map's list element that is responsible to keep unique all the input field to should be unique with their element suppose we do not do like this than the react automatically do this work and suppose we add the input value of add task into task array that is our todolist like this [inputValue, ...prevTask] than it is like every time it changes their index suppose we have first we add the mango so the index of mango is 0 and we write something in this index suppose we write we create juice from mango than it assign to index 0 , and than we add the apple so apple is input value that is add in front of prevTask than it takes the index 0 and the mango is transfer to index 1 but the text we wrote we create juice from mango is still assigned to index 0 so it is attached now to new item apple but this is a mistaking thing that's why we use the unique key so we pass the key as a unique we pass the currTask name to the key that's we use the unique key to the key = {currTask} so this time key is not index but the particular name that is assign by map method and us, but the another solution is we write without passing key or passign key with index is we write [...prevTask, inputvalue] , so it is working like this first we dont have any prevtask so the our first task is input value so the index 0 is assigned to mango and we write the text inside its input , and than we create another task apple so apple assigned as a new input value and it assigned not in front but in bottom side so the bottom index is 1 , but the input that is written by us in mango on index 0 that is we create juice from mango is still on 0 and 1 is okay with their position with new element apple 
so all these experinment are done by mine so this is done 
