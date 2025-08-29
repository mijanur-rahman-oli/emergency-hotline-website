1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

Answer: 
getElementsById- It use to call by id. it returns element.
getElementByClassName- it use to call the all elements under in a class. it returns HTMLCollection.
querySelector- It only finds first element of any id or class.
querySeelctorByAll- It finds all elements of a css selector, it returns NodeList.


2.  How do you create and insert a new element into the DOM?

Answer:
let name = document.getElementById("first-name");
name.innertText = "Oli";
document.body.appendChild(name);



3. What is Event Bubbling and how does it work?

Answer:
If clicks any element,  first it starts from that elements then it's parent then parent's parent and so on it's called Event Handling. 



4. What is Event Delegation in JavaScript? Why is it useful?

Answer:
when use addEventListener to a parent for better implement in code, it's called Event Delegation. its use fro handle childrens.




5. What is the difference between preventDefault() and stopPropagation() methods?

Answer:
preventDefault(): It's use for stop default action. example: after using form its uses for prevent auto refreshing.
stopPropagation(): its use for stopping Event Bubbling. prevent parents from running.

