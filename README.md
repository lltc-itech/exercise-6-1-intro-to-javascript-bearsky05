[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-7f7980b617ed060a017424585567c406b6ee15c891e84e1186181d67ecf80aa0.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=14211954)
# Instructions  

For this exercise, you will write a two simple programs. The goal here is to start very simple with our JavaScript and build on basic principles. These are some very classic beginner exercises that almost every programmer has had to create at the beginning of their career.

For each, you will have to use a JavaScript function that is only briefly explained in the book. The `prompt()` function, which will allow you to get input from a user. It's important to remember, that no one _really_ uses this function for a production web page, however, it's easy to use and does the job for now until we learn better ways to get user input.

The syntax looks like this:

```JavaScript
var myValue = prompt("Give me a number");
```
This will cause a dialog to open with your prompt. The function _returns_ whatever value the user enters into the dialogue. So this value will be assigned to the variable `myValue`.

## Part 1: The Greeting Generator

The first page will have you play with some strings in very simple terms. We've already seen how using the addition operator on strings causes those strings to _concatenate_ (smoosh together). So we will use this to create a greeting for our users.

Your page should prompt the user for their name and then store this to a value. And then, you should use the `document.write()` function to print a greeting on the page that addresses the user specifically.

For example, if the user enters **"Eric"** as their name, it should write out something like **"Hello, Eric!"**. You can do this with two lines of code, but you don't have to. Make sure your output has the correct spaces and punctuation!

All of your code should go inside of the `<script>` element in the `greeting.html` file.

## Part 2: Temperature Converter

Here, you will do a little simple math. You will create a page that will prompt a user for the temperature in Fahrenheit and then output the temperature in Celsius.

All the assignment requires is that you output the result. However, if you can output the result in the form of a sentence, that would be excellent practice (and not all that much harder).

So the algorithm looks like this:

* Prompt the user for a temperature in Fahrenheit expressed as a number and store it as a variable
* Apply the formula to convert Fahrenheit to Celsius (below) as a JavaScript expression and store the result as another variable.
* Print the result to the web page.

The formula for converting F to C is:

```JavaScript
tempC = (tempF - 32) * 0.5556
```

For example:

* (50&deg;F - 32) * .5556 = 10&deg;C

So if a user input `50`, valid outputs for the purposes of this exercise would be:

* "10"
* "50 degrees fahrenheit equals 10 degrees celsius."

All of your code should go inside the `<script>` element in the `temperature.html` file.

Some thoughts:

* Don't worry about rounding (though if you want to look up how to do it, that's fine by me).
* It's a good idea to store both temperature values in separate variables. Think about why that might be
* The code will just output to the bottom of the page. That's totally fine for both exercises.
* Don't worry about CSS for this. The only thing you will need for this exercise is JavaScript.
* For **both** of these exercises, make sure you test it with a few values so that you are reasonably sure it's giving good results.

As always, if you run into any problems or have any questions, you know how to reach me!