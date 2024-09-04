README for Digital Clock Using JavaScript 

Overview :

This project demonstrates a simple digital clock using HTML, CSS, and JavaScript. The clock displays the current time (hours, minutes, and seconds) and updates every second.

Files :

• 	index.html: The HTML file that defines the structure and includes JavaScript for the clock functionality.

• 	style.css: The CSS file that provides styling for the clock and its container.


JavaScript Functionality :

• 	Variables -  Retrieves references to the clock's hours, minutes, and seconds elements.

• 	SetInterval -  Calls an anonymous function every second to update the clock.

• 	Date() -  Gets the current time and updates the innerHTML of the clock elements.


style.css :

Global Styles -

•   Resets margin and padding, sets font family, and applies box-sizing for all elements.

.hero Section -

•	Sets the full viewport height and a gradient background.
.container -

•	Centers the clock and sets its dimensions.

•	Positions the container absolutely in the center of the viewport.

.clock -

•	Styles the clock with a background color and a backdrop filter effect for a blurred appearance.

•	Uses flexbox to center the time within the container.
    .container::before and .container::after -

•	Adds decorative elements behind the clock using pseudo-elements.

.clock span -

•	Styles the individual time elements (hours, minutes, seconds) with a large font size and centered text.

•	Adds labels ("HOURS", "MINS", "SEC") below each time element using pseudo-elements.

.watch-link -

•	Positions a link at the bottom-right of the viewport.
 


Running the Project :

1.	Save Files -  Ensure you have both index.html and style.css saved in the same directory.

2.	Open in Browser -  Open index.html in a web browser to view the digital clock.



Features :

•	Displays current time with hours, minutes, and seconds.

•	Updates every second to reflect the current time.

Notes :

•	The clock updates using JavaScript's setInterval function.

•	Styling is achieved using CSS with flexbox and pseudo-elements for decorative effects.

