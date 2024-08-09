# sass-functions

This code includes two SCSS functions, `hsba` and `hsb`, used to convert HSB (Hue, Saturation, Brightness) color values to HSLA (Hue, Saturation, Lightness, Alpha) color values. Below is a brief introduction to each function:

### @function hsba($hue, $saturation, $brightness, $alpha: 1):

Calculates `$x` and `$l`, which represent intermediate variables and lightness, respectively. Based on different `$x` values, it calculates saturation `$saturation` and then returns the corresponding `hsla` value.

### @function hsb($hue, $saturation, $brightness):

Calls the `hsba` function with the alpha set to 1.

These functions are mainly used to convert HSB colors to HSLA colors supported by CSS, making them convenient for use in styles.
