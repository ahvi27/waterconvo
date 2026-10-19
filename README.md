# 💧 AquaWise

A responsive water conservation website built with HTML, CSS, and JavaScript. Explore how everyday habits affect water consumption using an interactive calculator.

## Features

- Interactive daily water-use calculator
- Adjustable shower time and flow rate
- Running-tap time and laundry inputs
- Estimated savings from shorter showers
- Animated water visualization
- Water-saving tips
- Responsive layout
- Reduced-motion support
- Reset button

## Getting Started

1. Download or clone the repository.
2. Open `index.html` in your browser.
3. Adjust the sliders to explore your estimated water use.

No installation or API keys required.

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts — DM Sans

## Project Structure

    aquawise/
    ├── index.html
    └── README.md

The HTML file includes all styles and JavaScript.

## Calculator Formula

Daily water use in liters:

    (shower minutes × shower flow rate)
    + (running-tap minutes × 6)
    + (weekly laundry loads × 50 ÷ 7)

Illustrative assumptions:

- Tap flow: 6 liters per minute
- Laundry: 50 liters per load
- Shower flow: adjustable by the user

The savings estimate compares the selected shower duration
with a shower up to two minutes shorter, at the same flow rate.

## Limitations

- Results are illustrative estimates, not measured consumption.
- Actual use depends on equipment and habits.
- The calculator excludes toilets, drinking water, food production,
  gardening, and other water uses.
- The animated fill level is decorative, not a conservation score.
- Settings reset when the page reloads.
- Google Fonts requires internet access; system fonts serve as a fallback.

## Customization

Edit the CSS variables in `index.html` to change the colors.
Update the JavaScript calculation and explanatory text together
if you change the water-use assumptions.

## Purpose

Encourage awareness of water consumption and help users explore
simple ways to reduce everyday water use.
