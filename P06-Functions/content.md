---
title: "Functions"
slug: functions
---

## Watch [Video 5.1 Function Basics](https://www.youtube.com/watch?v=wRHAitGzBrg)

![ms-video-youtube](https://www.youtube.com/watch?v=wRHAitGzBrg)

# Watch [Video 5.2 Function Parameters and Arguments](https://www.youtube.com/watch?v=zkc417YapfE)

![ms-video-youtube](https://www.youtube.com/watch?v=zkc417YapfE)

# Watch [Video 5.3 Functions and Return](https://www.youtube.com/watch?v=qRnUBiTJ66Y)

![ms-video-youtube](https://www.youtube.com/watch?v=qRnUBiTJ66Y)

# Challenge 1: Add your name

**in `index.html`**

> [action]
> Find the `h1` tags in `index.html` and add your name so that it says `YOURNAME's...`
>

# Challenge 2: Implement the `growOrReset` function

**in `sketch.js`**

The `growOrReset` calls other functions depending on the situation.

> [action]
> The `growOrReset` function should call `plantGrow()` if the mouse is on the right half of the canvas, and should call `plantReset()` if the mouse is on the left side.
>

<!--  -->

> [action]
> Uncomment `growOrReset();` inside of `draw`
>

 Check in the console to see if `plant.size` is changing correctly:

![console](assets/console.png "console")

# Challenge 3: Implement the `drawPlant` function

**in `sketch.js`**

The `drawPlant` function needs to pass down it's `x` and `y` parameters to the other functions it calls.

> [action]
> Inside of `drawPlant`, if `plant.size` is 0, call `drawSeed`, otherwise call both `drawSprout` and `drawBloom`. Don't forget to pass the required parameters!
>

<!--  -->

> [action]
> Uncomment the two lines calling `drawPlant()` inside of `draw` .
>

Watch the two plants grow and bloom:

![draw plant](assets/draw_plant.png "draw plant")

# Challenge 4: Implement the `plantLabel` function

**in `sketch.js`**

The `plantLabel` function needs to `return` a string label.

> [action]
> Based on `plant`'s current properties, return the correct string: `"seed"`, `"growing"`, or `"blooming"`
>

<!--  -->

> [action]
> Uncomment `text(plantLabel(), 10, 20);` inside of `draw`
>

 You should now see correct labels in the upper left corner:

![seed](assets/seed.png "seed")

![growing](assets/growing.png "growing")

![blooming](assets/blooming.png "blooming")

# Bonus 1: Display a field of plants

**in `sketch.js`**

> [challenge]
> Display a whole field of plants instead of just two.
>

![field](assets/field.png "field")
