# CS5112-IT5108 Class
 Cloud Infrastructure and Services
HTML, CSS, JS Lab Exercise

# Question 1
(10pts) Write a simple HTML code that outputs the following To Do list in HTML. Use h2 tag to specify the header.

# Question 2
(14pts) Create a CSS stylesheet that satisfies the following requirements:
The entire list should have no padding or margin.
Each list item should not have a bullet.
The background color of each even list item should be gray (#eee).
The background color of each odd list item should be dark gray (#f9f9f9).
The font size for each list item should be 20px.
The top and bottom paddings of each list item should be 14px.
The right and left paddings of each list item should be 10px, and 40px respectively.
Hint: Use "li:nth-child(odd)" to style the odd list items.

The output of the code should look like the image below:

# Question 3
(6pts) Add an input field and a button that satisfies the following requirements:
Button should be placed after the input field and in the same line.
Button text should be "Add".
Input field should have "Enter a task…" as its placeholder text.

# Question 4
(10pts) Complete and embed the following JS script to create a new list item when the user clicks on the “Add” button. Use the text in the input field as text for the list item. Use “onClick” attribute on the button to specify the addListItem function as the function to be called when the button is clicked by the user. Add IDs to each element using the id attribute.

// Create a new list item when clicking on the "Add" button
function addListItem() {
    	var li = document.createElement(____);
    	var inputValue = document.getElementById(____).value;
    	var t = document.createTextNode(inputValue);
    	li.appendChild(t);
    	if (inputValue === '') {
      	alert("You must write something!");
    	} else {
      	document.getElementById(____).appendChild(li);
    	}
    	document.getElementById(____).value = "";
}

