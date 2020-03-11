---
title: "0.8 Arrays"
slug: arrays
---

> [action]
> Access the assignment [0.8 Arrays](https://repl.it/@MakeSchoolRAMP/08-Arrays).
>

Remember to view the p5.js documentation as needed: [http://p5js.org/reference/](http://p5js.org/reference/).

## Watch [Video 7.1 What is an array?](https://www.youtube.com/watch?v=VIQoUghHSxU)

![ms-video-youtube](https://www.youtube.com/watch?v=VIQoUghHSxU)

Follow along with the [video guide](https://repl.it/@MakeSchoolRAMP/p5js-Video-Guide-71-What-is-an-array)

# Watch [Video 7.2 Arrays and Loops](https://www.youtube.com/watch?v=RXWO3mFuW-I)

![ms-video-youtube](https://www.youtube.com/watch?v=RXWO3mFuW-I)

Follow along with the [video guide](https://repl.it/@MakeSchoolRAMP/p5js-Video-Guide-72-Arrays-and-Loops)

# Watch [Video 7.3 Arrays of Objects](https://www.youtube.com/watch?v=fBqaA7zRO58)

![ms-video-youtube](https://www.youtube.com/watch?v=fBqaA7zRO58)

Follow along with the [video guide](https://repl.it/@MakeSchoolRAMP/p5js-Video-Guide-73-Arrays-of-Objects)

# Challenge 1: Add your name

**in `index.html`**

> [action]
> Find the `h1` tags in `index.html` and add your name so that it says `YOURNAME's...`
>

# Challenge 2: Save new spots

**in `sketch.js`**

The `mousePressed` function calls `saveSpot` but nothing happens yet. The goal is to save a spot that has the color that the canvas is when the mouse is clicked.

> [action]
> Inside of `saveSpot`, create a `new Spot` using the current mouse location and `currentColor()`.
>

You can add the new spot to the `spots` array using either the `push` or `append` functions.

Click a few times and then check the results of `print(spots)` in the console to see if new `Spot` objects are being added:

![console](assets/console.png "console")

# Challenge 3: Draw the spots

**in `sketch.js`**

Now you are saving spots, but not using them. Next, add code to display each one on the canvas.

> [action]
> Use a `for loop` to get each spot in `spots` and then call the `show` function on it.
>

Each time you click your mouse you should see a new colored spot where you just clicked:

![spot 0](assets/spot_0.png "spot 0")

![spot 1](assets/spot_1.png "spot 1")

# Challenge 4: Get the last color

**in `sketch.js`**

Right now the `lastColor` function is just returning a default value of white, that is being used to color the box in the upper left corner.

> [action]
> Update `lastColor` so that it returns the color of the most recently added spot. Return the default white when there are no spots yet.
>

There are a few steps that you can break this challenge into:

- check if there are any spots yet, if not, return white
- if there are spots, get the number of the last index in the array
- use the index to get the last spot object
- update `lastColor` to be the value of the color property of the last spot

> [info]
> In programming, [counting often starts at 0](https://en.wikipedia.org/wiki/Zero-based_numbering), especially when working with arrays.
>

When your logic is working correctly, the upper left square should correctly match the color of the most recently added spot:

![last color](assets/last_color.png "last color")

# Bonus 1: Add functionality

**in `sketch.js`**

> [challenge]
> Use 1 or more new array functions from [https://p5js.org/reference/](https://p5js.org/reference/) to add new effects to your program.
>
