<img width="2868" height="1412" alt="image" src="https://github.com/user-attachments/assets/917d5253-0a4d-4557-a9b5-735d199afaac" />The Problem Of The Day was to "Remove Duplicates from Sorted Array".
In the given problem, basic array (vector) functions is used. 
First we initiate a variable "i" that equates to 0. This will be our iterator.
Next, we run a loop, with variable "j" that initiates to 1. This loop has a if-else conditioning. If the element at i index and element at j index are not equal then 
move i with 1 and [imp step] we replace the element at i index with the element at j index. This is because i keeps the track of unique elements with j iterates through
the array. When an unequal pair of elements is found, the element at i becomes that unique element hence eliminating duplicates. 
If the elements are not equal, then only j advances and no such reassigning happens.
Once the loop is executed completely, we are required to return the number of unique elements. As "i" keeps counter of unique elements, we can just return "i+1" 
(as indexing starts from 0 instead of 1)
