---
title: "1.0 Hello OOP"
slug: hello-oop
---

Note:
Start here if you are already comfortable with the fundamentals of programming (variables, objects, functions, etc) and are ready to take on the challenge of building a larger object-oriented programming (OOP) project.

If you need a refresher on coding fundamentals, or are less comfortable working with JavaScript and the p5.js library, you are encouraged to start at Level 0 instead (assignment 0.0 Hello World).

If you just completed Level 0, *a hearty congratulations to you!* There is a big jump in difficulty between Level 0 and Level 1, but you've got this. :)

Happy coding!


> [action]
> Access the assignment [1.0 Hello OOP](https://repl.it/@MakeSchoolRAMP/10-Hello-OOP).
>

Remember to view the p5.js documentation as needed: [http://p5js.org/reference/](http://p5js.org/reference/).

> [info]
> You can also always go back and refer to your previous assignments to remind yourself of how to do things!
>

# Challenge 1: Add your name

**in `index.html`**

> [action]
> Find the `h1` tags in `index.html` and add your name so that it says `YOURNAME's...`
>

# Challenge 2: Answer a question using the print function

**in `sketch.js`**

> [action]
> Type your answer using the `print` function:
>
> Question: What is the difference between a class and an instance?
>

View the console tab in the results panel to see your answer.

# Challenge 3: Modify the Avatar constructor to take parameters

**in `sketch.js`**

> [action]
> Modify the Avatar constructor to take the following parameters
> - `name`
> - `height`
> - `width`
> - `eyeColor`
> - `hairColor`
> - `hatColor`
>

Remember that your constructor also needs to *use* the parameters to assign values.

# Challenge 4: Create an instance of the Avatar class

**in `sketch.js`**

Now you can create an instance of your `Avatar` class.

> [action]
> Create an instance of your `Avatar` class.
>

Ensure that:
- the instance is assigned to a global variable so you can access it in later steps.
- you are passing in ALL of the required parameters.


# Challenge 5: Add a show() function to the Avatar class

**in `sketch.js`**

Add code so that your Avatar is visible on the canvas.

> [action]
> Add a `show()` function to the `Avatar` class
>

Ensure that:
- the `show()` function is using all 8 of the Avatar properties to control the appearance
- you call `show()` on your avatar instance in the `draw` function

# Challenge 6: Add an updateLocation() function to the Avatar class

**in `sketch.js`**

> [action]
> Add an `updateLocation()` function to the `Avatar` class that takes two parameters: `newX` and `newY`
>

Ensure that you:
- Update the avatar's `x` and `y` values from the passed in parameters

> [action]
> Call your new `updateLocation()` function with parameter values so that your avatar is always at the mouse location
>
-

# Bonus 1: Make your avatar speak when the mouse is pressed

**in `sketch.js`**

> [challenge]
> - Give your avatar a catchphrase
> - Display the catchphrase on the canvas when the mouse is pressed
> - Use OOP to think about where your new code makes the most sense!
>

# Bonus 2: Make your avatar speak random phrases

**in `sketch.js`**

> [challenge]
> - Modify your code so that avatars can have more than one catchphrase
> - Modify your code so that when the mouse is pressed, they speak one of their phrases at random
>
