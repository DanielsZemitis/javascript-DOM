# DOM Atomic 02: Hide Many Elements

## Questions

---

> How did you go about selecting the DOM elements to hide? Describe the "contract" for that function.

Your reply here... I used querySelectorAll() to get all elements with the '.hide_me'. This function goes through every object of the element that it was assigned and returns every element which contains the specified selector as a list.

---

> Describe how you were able to hide each element. Were you able to do it as one operation, or did you use a loop of some kind? Describe the "contracts" that were utilized to accomplish your goal.

Your reply here... I used ForEach() to hide every element which allowed me to preform a function on each of the elements in the list which was returned by querySelectorAll()