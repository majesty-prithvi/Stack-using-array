# Stack-using-array
<br>The Array implementation of stacks involves allocation of fixed size array in the memory.Both stack operations (push and pop) are made on this array with a constant check being made to ensure that the array does not go out of bounds.</br>

<b><br><ins>Push Operation:-</b></ins> The Push operation involves checking whether or not the stack pointer is pointing at the upper bound of the array. If it is not,the stack pointer is incremented by 1 and the new item is pushed (inserted) at the top of the stack</br>

<b><br><ins>Algorithm to implement push operation under array representation of stacks:-</b></ins></br>
<br>Step 1:Start</br>
<br>Step 2:If top=max-1 go to Step 3 else go to Step 4</br>
<br>Step 3:Display message "Stack full" and exit</br>
<br>Step 4:top=top+1</br>
<br>Step 5:stack[top]=element</br>
<br>Step 6:Stop</br>

<br><b><ins>Pop Operation:-</b></ins> The pop operation involves checking whether or not the stack pointer is already pointing at NULL(empty stack). If it is not, the item that is being currently pointed is popped(removed) from the stack (array) and the stack pointer is decremented by 1.</br>

<br><b><ins>Algorithm to implement pop operation under array representation of stacks:-</b></ins></br>
<br>Step 1:Start</br>
<br>Step 2:If top=-1 go to Step 3 else go to Step 4</br>
<br>Step 3:Display message "Stack Empty" and Exit</br>
<br>Step 4:Return stack[top] and set top=top-1</br>
<br>Step 5:Stop</br>

<br>This program uses the Push and Pop algorithms for realizing common stack operations.</br>
<br>This program code shows storage of an integer type element into the stack. However, we may store other built-in or user defined type elements in the stack as per our own requirements.</br>
<br><b><ins>For application of stack refer to the following website:-</b></ins></br>
https://www.javatpoint.com/applications-of-stack-in-data-structure
![image](https://user-images.githubusercontent.com/125802204/221756817-8ed25a35-495c-4ec5-b624-65640b65f19b.png)

