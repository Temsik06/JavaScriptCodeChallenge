Read Me For Kevin's Javascript code challenge.

There are two HTML files which house the code that was created for this challange. 
They are the calculator.HTML and ToDoList.HTML that are both located in the bootstrap-3.3.7-dist folder.
In order for them to display properly they must stay within that folder and have all of the corrisponding bootstrap
files downloaded with them. Bootstrap files are in the css, fonts, and js folders and must stay there as well.

Calculator.HTML
This is a simple calculator that is hard coded to call on the add, subtract, multiply and divide functions with a
supplied x and y value.  If given more time I would have liked to create a button GUI that would resemble an
acutal calculator and tie those buttons to values that would create valuse for x and y so that the webpage would be
completely interactive.

ToDoList.HTML
This is a simple table created using bootstrap that displays a to-do list and each to do item in that table. If 
given more time, I would have like to stylize the table and made the boolean of completed or not a checkable or 
uncheckable bock. I would also have liked to make the Topic columns a drop down box with preselected topics to choose
from.

Problem #2
	The difference is that $(“.todo-item”).on(“click”, function(e){ console.log(e) }); will specifially only
act upon something that has an Id of ".todo-item" where $(document).on(“click”, “.todo-item”, function(e){ console.log(e) });
has the ability to affect the entire document, or HTML page.


Currently at 3:08pm github is not working, the page loads as a broken unformatted page of github and the file uploads
are not finishing so this will be send via email, to give a completion time and uploaded to github later.