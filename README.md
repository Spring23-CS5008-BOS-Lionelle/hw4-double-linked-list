# Homework 04: Doubly Linked List

Name: Hsinyen Wu 

Github Account name: ianwu0915

How many hours did it take you to complete this assignment (estimate)? 
5 hours

Did you collaborate with any other students/TAs/Professors? If so, tell us who and in what capacity.  
- one per row, add more if needed
- none


Did you use any external resources (you do not have to cite in class material)? (Cite them below)  
- one row per resource
- wikipedia 
- https://www.geeksforgeeks.org/introduction-and-insertion-in-a-doubly-linked-list/


(Optional) What was your favorite part of the assignment? 

(Optional) How would you improve the assignment? 

## Understanding Time Complexity

1. Using a markdown table and markdown/latex math, show the BigO for Arrays, Singly Linked Lists, Doubly Linked Lists (so total of 3). For the columns, you will look at the Worst Case Time Complexity for Access, Search/Find,	Insertion, and Deletion. 

| Data Structure      | Access | Search/Find | Insertion | Deletion |
| ------------------- | ------ | ----------- | --------- | -------- |
| Arrays              | O(1)   | O(n)        | O(n)      | O(n)     |
| Singly Linked Lists | O(n)   | O(n)        | O(1)      | O(1)     |
| Doubly Linked Lists | O(n)   | O(n)        | O(1)      | O(1)     |


2. Usually for singly and doubly linked lists, we reference both the head and tail for speed considerations. What would be the cost if you only had your head referenced, and you wanted to push to the tail of either?  $O(?)$

For both lists, we will have to traverse from the end to the end which costs O(n) of time complexity.

3. Name an example where an array is better than a linked list, and an example where a linked list is better than an array. Make sure to reference the big O as part of your reasoning. 

For a database of a gym that stores the info of each customer using their id as index, it would be much easier to access their files simply by their id. The time complexity for accessing data will be O(1). However, if we use linked list to stores these info, we then always have to traverse all the files to find the desired one.

On the other hand, when writing words in WORD, it will certainly be more convenient to have all the characters connected using linked list. We can easily insert or delete each characters with O(1) time complexity instead of shifting all the characters (O(n)) when using array as the data structure.


Note: Make sure look at your finished markdown in the browser hosted on github or via a markdown preview extension. To confirm the notation is showing up properly. 

## Important notes

* Your code **must compile and run** on the Khoury machines to earn credit. Make sure you test your programs on these machines, as this is where we grade your assignments.
* You must commit any additional files(if any) into your repository so we can test your code.
  * Points will be lost if you forget!
* Do not forget, once you have pushed your changes to your repo make sure that you **submit them to Gradescope before the assignment deadline!**

