# Mathematical Fraction

An interactive educational tool for understanding fractions through circles, pizza, cake, muffins, cookies, and pancakes. Explore 1/x of a whole and its equivalent percentage (%) and per mille (‰).

## Accurate shrinking fractions

The main object stays the same size as x changes. Its highlighted area is 1/x of that fixed-size whole, so increasing x makes the fraction visibly smaller. Automatic object growth has been removed because it could counteract the shrinking slice and obscure comparisons.

For x ≥ 100, an optional separate detail view enlarges the slice angle 50×. This view is explicitly labeled and does not change the true-scale main view. Very small slices can be thinner than a screen pixel.

## Adjustable defaults, not limits

- Plain circle: 1–1,000, to illustrate hundredths (%) and thousandths (‰).
- Pizza: 1–8.
- Cake: 1–16.
- Muffin and cookie: 1–4.
- Pancake: 1–8.

Every object accepts a custom start and end point, including endpoints above its default. Only the plain circle offers an automatic range-extension option: releasing the slider at its endpoint doubles the range. This changes the slider range, not the object's size.

## Features

- Interactive fraction slider.
- Percent and per mille equivalents.
- Custom ranges and colors.
- Fixed-size circular objects for clear visual comparisons.
- Optional, separately labeled magnified detail for small slices.
- Responsive layout.

## Use

Open `index.html` in a browser. No installation or external libraries are required.

“Unlimited” means automatic range extension, not literal infinity. Whole-number inputs are subject to JavaScript's safe-integer limit. Displayed results are rounded to up to eight significant digits.
