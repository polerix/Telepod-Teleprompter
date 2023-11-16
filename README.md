# Telepod-Teleprompter
A Multi Layer Teleprompter with variable web page backgrounds


AnyPage TelePrompter

As you open the Teleprompter page you are presented with a Full Screen Blue Background.
The default background is Full Screen Blue extending to the entire browser page.

100 pixels from the top is the Teleprompter Function Toolbar. 
The Teleprompter Function Toolbar will always be available, hoving over any and all content, 100 pixels from the top.

The Teleprompter Function Toolbar is coplored red and covers the entire page from left to right. The Teleprompter Function toolbar is 100 pixels high.


Rectangle areas on the Teleprompter Toolbar indicates different Teleprompter modes. 
The 4 Teleprompter Toolbar Rectangle Button areas are black, 90 pixels high, centered vertically and horizontally in the Teleprompter Function Toolbar.
There is a 20 pixel space between each Teleprompter Toolbar Rectangle Button.

Each Teleprompter Toolbar Rectangle Button indicates a different Teleprompter page function.

Teleprompter Toolbar Rectangle Button 1) 

URL Background

Show web-link.svg and a rectangular text field with a button 'submit'
Wait for input.
The text field is white and has the pre-entered text 'Type URL', 
If you click to type in the text field the pre-entered text 'Type URL' disappears.
Wait for the typed in URL.
WAIT for 'enter' from the keyboard, or the user may click on button 'submit'. 

Once the address is entered, check to make sure it is accessible.
If the URL is accessible display the entered user URL in green,
then display the page as the new background.

If the URL is accessible display the entered user URL in red,
then display Full Screen Blue Background.

If the user clicks any other Teleprompter Toolbar Rectangle Buttons,
then display Full Screen Blue Background.


Teleprompter Toolbar Rectangle Button 2) 

Webcam Background
 
 Show ./webcam-icon.svg and a rectangular button labelled 'Start Webcam' small text next to the button indicates "You may be prompted to allow from browser"
Wait for the button 'Start Webcam' 

If the browser prompt has been accepted, set the background to Webcam Full Screen, instead of Full Screen Blue Background
If there is no Webcam input, display Full Screen Blue Background.

If the user clicks any other Teleprompter Toolbar Rectangle Buttons,
then display Full Screen Blue Background.


Teleprompter Toolbar Rectangle Button 3) 

Solid Color Background

Show a colour picker with 50 pixel by 100 pixel color sample rectangles. 
IF the user picks a colour fill the background with the selected color.

If the user clicks any other Teleprompter Toolbar Rectangle Buttons,
then display Full Screen Blue Background.


Teleprompter Toolbar Rectangle Button 4) 

display https://github.com/manifestinteractive/teleprompter#project-support over the background chosen above as a layer, opacity 50%
