---
title: "Classes"
slug: classes
---

## Watch [Video 6.2 Classes in Javascript](https://www.youtube.com/watch?v=T-HGdc8L-7w)

![ms-video-youtube](https://www.youtube.com/watch?v=T-HGdc8L-7w)

Follow along with the [video guide](https://repl.it/@MakeSchoolRAMP/p5js-Video-Guide-62-Classes-in-JavaScript)

# Watch [Video 6.3 Constructor Arguments with Classes in Javascript](https://www.youtube.com/watch?v=rHiSsgFRgx4)

![ms-video-youtube](https://www.youtube.com/watch?v=rHiSsgFRgx4)

Follow along with the [video guide](https://repl.it/@MakeSchoolRAMP/p5js-Video-Guide-63-Constructor-Arguments-with-Classes)

# Challenge 1: Add your name

**in `index.html`**

> [action]
> Find the `h1` tags in `index.html` and add your name so that it says `YOURNAME's...`
>

# Challenge 2: Create a new flower class

**in `sketch.js`**

> [action]
> Add a new `FancyFlower` class with the same `constructor` arguments: `x`, `y`, and `petalColor`.
>

Use the `PlainFlower` class as a guide. Ensure that you are including all of the same properties in your `FancyFlower` class.

> [action]
> Adjust the values of the default and random default properties to your liking.
>

# Challenge 3: Add two flower objects

**in `sketch.js`**

> [action]
> In `draw`, call `new FancyFlower()` to create two new flower objects - `flowerThree` and `flowerFour`.
> Pass in unique colors and good `x`, `y` values so that they will be nicely spaced out.
>

<!--  -->

> [action]
> Uncomment `garden = [flowerOne, flowerTwo, flowerThree, flowerFour];` in `draw` to include your new flowers in the `garden` array.
>

You should now see two new flowers growing alongside the original flowers:

![new flowers](assets/new_flowers.png "new flowers")

# Challenge 4: Design a custom bloom

**in `sketch.js`**

Right now your `FancyFlower` class doesn't have a custom `drawBloom` function like the `PlainFlower` class does. If you look inside the `drawPlant` function you can see that it will call `drawDefaultBloom(flower)` instead, which just draws a simple ellipse.

```
if (flower.drawBloom) { // check if the function exists
  flower.drawBloom(); // call the function
} else {
  drawDefaultBloom(flower); // call the default helper instead
}
```

> [action]
> Add a custom `drawBloom` function to `FancyFlower` so that it can create it's own custom bloom shape.
>
> - Don't forget to use `this.x`, `this.y`, and `this.bloomSize` to properly place the bloom relative to the sprout.
> - Don't draw a bloom when `bloomSize` is 0.
> - Your new bloom must be fancier than just another ellipse - be sure that it looks different from the `PlainFlower`!
>

You should now have a garden with 4 flowers, all different colors, and with two different overall appearances:

![custom bloom](assets/custom_bloom.png "custom bloom")

# Bonus 1: Custom sprouts and blooms

> [challenge]
> Now that you have custom blooms for each class, make changes that give both classes custom seeds and custom sprouts in the same way.
>

This challenge requires making updates to some of the existing functions.
