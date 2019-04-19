# Trig-Drills
A monolithic trig drill program written using python (and tkinter for gui)

## Instructions

1. Run the program
2. Press the start button
3. Enjoy!

### Additional Things to Note

#### Numbers

Answers are evaluated as Python expressions, which means that fractions are specified as `x/y` and square root can be specified by `sqrt(x)`.  However, `undefined` will be interpreted as `undefined`.

The exact specifications are: the program first tries to directly call `eval()` on your answer.  If that throws an error, the answer will default to `undefined` as long as you gave an answer.  Note that the `sqrt` function from the `math` library has already been imported in the code, so don't worry about that.

Let's take a look at some examples:

- `sin(30 deg)` = `1/2` (`1 / 2` works too, spacing does not matter)
- `sin(60 deg)` = `sqrt(3)/2`
- `cos(0 deg)` = `1`
- `cos(180 deg)` = `-1`
- `tan(90 deg)` = `undefined`

#### Changing the Difficulty

The default settings will create a 5 row, 6 column grid and give 120 seconds to you for answering the questions.  If that's too difficult or easy for you, you can always change the settings of the program.  To change them, simply open the file with a text editor and change them as you wish.  You can also change the program behaviour yourself, but it is not advised as it can mess things up.

<img src="https://files.catbox.moe/00luv1.png">

These should be fairly self-explanatory.
