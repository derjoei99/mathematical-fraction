# Mathematical Fraction

An interactive educational tool that makes fractions easy to understand through visual exploration. Divide a circle, pizza, cake, muffin, cookie, or pancake into equal parts and see the equivalent percentage (%) and per mille (‰).

The plain circle defaults to a range of 1–1,000 parts to illustrate hundredths and thousandths. This is a default, not a limit: the range is adjustable for every object. Food objects start with practical ranges—pizza 1–8, cake 1–16, muffin and cookie 1–4, and pancake 1–8—without imposing food-specific caps.

## Learning features

- Drag a slider to explore 1/x of a whole.
- Compare fractions with percentages and per mille.
- Set custom start and end points.
- Choose circular objects and customize their colors.
- Enable proportional growth for any object, with an optional minimum size to keep small objects visible.
- Inspect small fractions in a clearly labeled, angle-enlarged detail view while the main view remains accurate.
- Optionally auto-extend the plain circle’s range when reaching the slider endpoint.

## Use

Open `index.html` in a browser. The website is self-contained and needs no installation or external libraries.

## Visualization notes

Exact proportional growth uses diameter proportional to the square root of x divided by the range endpoint. With a fixed endpoint, this keeps the selected slice’s area constant. The optional 72% minimum-size setting prioritizes visibility and overrides exact scaling below that size. Changing the endpoint recalibrates sizes.

The small-slice detail view enlarges the angle 50× and is labeled accordingly; it does not represent the actual fraction of a full circle.

“Unlimited” means automatic range extension, not literal infinity. Whole-number inputs are subject to JavaScript’s safe-integer limit. Displayed results are rounded to up to eight significant digits.
