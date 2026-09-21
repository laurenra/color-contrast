# Color Contrast
Try text color and background color combinations to see how it looks
and see if it has enough contrast to be easily readable.

[See a demo here](https://laurenra.github.io/color-contrast/).

![application page example](img/color-contrast-app-example-1440x881.jpg)

## Use

This is a one-page app contained in a single HTML file. Download the
index.html file and open it in your browser.

Optional URL parameters can prefill row colors. Rows are zero-indexed:

- `r0txt=rgb(180-100-196)` sets row 1 text color.
- `r0bak=hsl(290-49pct-48pct)` sets row 1 background color.
- `r1txt=xB464C4` sets row 2 text color with hex, using `x` instead of `#`.

For a compact hex-friendly form, use `r0=xB464C4~xFFFFFF` to set row 1
text and background colors together. Specific parameters like `r0txt`
or `r0bak` override the compact row value.

## TODO
- [x] Add hints to the column headers.
- [x] Add a subheading that explains what this is.
- [ ] Another column that automatically calculates contrasting text color from the background color.
