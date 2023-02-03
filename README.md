# JS-Day-11
Event Key Codes
The HTML file has the following components:

A declaration of the document type as HTML5 using <!DOCTYPE html>.
An HTML tag with the language attribute set to "en".
A head tag with meta information about the document, including the character set and viewport, and a link to the stylesheet file.
A title tag that sets the title of the document in the browser tab.
A body tag that contains a div with an ID of "insert", which is used to display information about the key events.
A script tag that includes the JavaScript file.

The CSS file contains the styles for the document. It starts with an import of a Google Fonts stylesheet and sets some global styles for the document, including the background color, font family, and display properties.

The .key class sets the styles for the key event information displayed in the body of the document, including the border, background color, shadow, display, font, padding, margin, and position.
The .key small class sets the styles for the small text that describes the key event properties.

The JavaScript file contains the code for capturing the keydown events and displaying information about the events in the "insert" div.

The first line of code gets a reference to the "insert" div using the document.getElementById() method and stores it in the "insert" variable.
The next line sets an event listener on the window object for the "keydown" event, which is triggered when a key is pressed down. The event listener takes an anonymous function as an argument that updates the content of the "insert" div with information about the key event.
The anonymous function accesses the properties of the event object and displays the key, keyCode, and code properties using template literals. The event.key property is tested for a space character and is displayed as "Space" if it is a space.
