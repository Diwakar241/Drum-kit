# Drum-kit
The main concepts presented in the project are DOM , key events and CSS animations.

The project is based on a number of keys on the webpage that represents different drums in a typical drum set and when we click on any of those buttons then we will get the corresponding sound of the drum. And in addition we can also use the keys on the keyboard to have a sound effect.

Designing the HTML Layout: For the website, we only have seven buttons to display on the page, clicking upon which sound would be played. First we would add the DOCTYPE HTML format, then give a suitable title to the web page, in our case it is The Drum Kit . Inside the body tag, we would give a heading, say, The Drum Kit using h1 tag and display those seven buttons.

Adding CSS Styling: CSS is used to style the different portions and make it more visually appealing. But, this is a personal opinion as to which style does the developer like the most. Feel free to use any styling but keep these main points in your mind:

1)Give whatever color, background color, font-family, margin and font size you want to give to the body and the heading.
2)We have given background images of drums, cymbals, etc. to every button to make the page more attractive. All the images are in “images” directory. 3)Additionally, we have given some common styling to all the buttons.
3)We have also given styling as to how each button will look when pressed in the class animation. We would append this class using JavaScript whenever a button is pressed.

To append these classes we have to add the classes in HTML tags also and link the stylesheet.

Adding Functionality with JavaScript:
Add event listeners to all the buttons 
Add keypress function which will describe what will happen when a particular key is produced. Here we will produce the sound effect and animation effect.
Now we will code sound() function. It will tell which sound should be played when we press or/and click a specific key. Here we have already stored some basic sound effects of drums, cymbals and other percussion instruments, and we will play those sounds (using new Audio) when their respective key is clicked or pressed.  All the sounds are in same directory

Now we will code animation() function. This will animate the button differently when it is being clicked. To do this, we will add pressed (which we have already defined in CSS file) class to the respective button when it is being clicked.
