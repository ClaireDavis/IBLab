# IBLab
In this lab, you'll make your way around the Xcode Interface Builder, creating a simple view that responds to user input.  

## The goal 
1. Use Storyboard to layout a view
2. Get comfortable with some of the key UIKit classes 
3. Write the IBAction implementation to change the text displayed on the screen.

## Instructions
1. Navigate to Main.Storyboard.
2. Start by putting a UILabel on the screen- this is where your text will be displayed.
3. Next add a UIButton to the screen- this is how you will tell the label to update.
4. Open the assistant editor (the button that looks like a venn diagram) and make sure that the file on the right is the ViewController.swift file.
5. Now, you will create outlets for the UI items that you just put onto the screen.
    -Control-drag the label to the view controller file and name your label as an outlet.
    -Do the same with the button, this time creating an action instead of an outlet.  Name your method.
6. Now comes the fun part- write some code inside of the button action method that updates the label to say "Hello World" whenever the button is tapped.

## Advanced
Good job completing part one!
In this part of the lab, you will make the label update to display text that the user inputs.
1. Move back to the main storyboard file and slap a text field onto the screen.  This is where the user will input her text.
2. Create an outlet from the text field to the ViewController file.  
3. Change the method that you wrote to control the button to instead update the label to display the text that the user has entered into the text field.

Voila!  You created an app!
