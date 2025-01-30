The Digital Signature Pad is a web application that allows users to draw signatures, customize brush sizes and colors, and save or retrieve the signature from local storage.

Features:
Draw Signatures: Users can use a mouse or touchpad to draw freehand signatures on the canvas.
Customize Brush Color: Users can choose their preferred pen color for drawing signatures.
Background Color Selection: Users can select the background color for the canvas.
Brush Size: Users can select different brush sizes (2px, 5px, 10px, 15px, 20px) to adjust the drawing thickness.
Clear Option: Users can clear the canvas and reset the background color to the default.
Save Signature: Users can save their signature as an image (PNG) and download it to their device.
Retrieve Saved Signature: Users can retrieve previously saved signatures from the browser's local storage.
Installation:
To run the application locally, follow these steps:

Clone the repository:
bash
Copy
Edit
git clone <repository-url>
Open index.html in a web browser.
Requirements:
A modern web browser with support for HTML5, CSS3, and JavaScript.
How to Use:
Change Brush Color: Use the color picker to select the text/pen color for drawing.
Change Background Color: Use the background color picker to customize the background of the canvas.
Adjust Brush Size: Select a brush size from the dropdown to change the line thickness.
Drawing on Canvas: Click and hold the mouse (or touch) to draw the signature on the canvas.
Clear the Canvas: Press the "Clear" button to remove the drawing and reset the background.
Save the Signature: Press the "Save & Download" button to save the signature as an image file.
Retrieve the Signature: Press the "Retrieve" button to load the previously saved signature.
Technical Details:
HTML: The structure of the signature pad with controls for customization.
CSS: Styling to create an aesthetically pleasing and responsive design.
JavaScript: Handles drawing functionality, customization, and saving/retrieving data using localStorage.
Future Enhancements:
Add options for multiple drawing modes (e.g., straight lines, circles, etc.).
Implement an undo/redo feature for the drawing.
Add an option to resize the canvas.
