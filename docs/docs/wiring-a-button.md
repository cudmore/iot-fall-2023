
To begin, we will wire a button and then a RGB LED.

<IMG SRC="../img/fritzing-button-rgb-led.png" width=600>

<p style="clear: both;"></p>

## Wiring a button

<IMG SRC="../img/button.png" width=300 align="right">

The button has four legs. When the button is pushed, it connects diagonal legs.

- Connect one leg to ground.
- Connect a diagonal leg to the Arduino Pin D10.

All your wires are the same. They are just different colors to tell them apart.

<p style="clear: both;"></p>

## Wiring a RGB LED

<IMG SRC="../img/rgb-led.png" width=300 align="right">

The RGB LED has four pins corresponding to:

 - Ground (-)
 - Red (R) to D2
 - Green (G) to D3
 - Blue (B) to D4

 Why red, green, and blue? The RGB color model is an additive color model where different levels of red, green, and blue can create any color in the visible spectrum. This is used for displaying colors on a screen like you phone.
 
 If each of R/G/B have equal amount the produced light is white. If all are off, there is no light.

For those interested, there is another color space that specifies cyan/magenta/yellow and is used for printing a document. There are also the three primary colors for painting which are red, blue, yellow.

 See for more info [https://techterms.com/definition/rgb](https://techterms.com/definition/rgb).