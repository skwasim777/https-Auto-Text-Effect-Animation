
# Auto Text Effect Animation

This project is a simple web page that showcases an auto text effect animation. It cycles through a list of career options, revealing them character by character. The animation utilizes HTML, JavaScript, and CSS to create a visually engaging effect.


## Usage
To use this project, follow these steps:

1.Clone or download the repository to your local machine.
2.Open the 'index.html' file in your web browser.
## How It Works
The web page is composed of three main components:

1.HTML (index.html): This file defines the structure of the web page. It includes references to external styles and JavaScript files and provides a container element for the text effect.

2.JavaScript (index.js): The JavaScript code handles the text animation. It contains an array of career options and dynamically updates the text to create the animation effect. The animation works as follows:

-It iterates through the career options character by character.
-It determines whether to use "an" or "a" based on the first letter of the current career option.
-It updates the text in the container element.
-When it reaches the end of a career option, it moves to the next one.
-Once all career options have been cycled through, it restarts from the beginning.
3.CSS (style.css): The CSS file defines the styling of the web page. It sets the background color, font-family, and other visual aspects to create an appealing presentation.
## Dependencies
This project uses the "Permanent Marker" font from Google Fonts for a stylish text appearance. It's imported in the CSS file.
## Customization
You can customize this project by:

-Modifying the list of career options in the JavaScript code (the 'careers array'').
-Adjusting the animation speed by changing the 'setTimeout' duration in the 'JavaScript' code.
## Screenshots

![App Screenshots](<![Alt text](Screenshot (161).png>))
![App Screenshot](![Alt text](<Screenshot (162).png>))


