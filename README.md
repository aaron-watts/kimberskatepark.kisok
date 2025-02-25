# kimberKiosk

Data for dual monitor display kiosk at Kimber Skatepark using feh and chromium-browser.

## Display 1 - feh

First display runs feh for images in `pictures/`. Accepts image files including jpeg and png formats. Convert pdf files to png using:

`pdftoppm Horizons\ <input-file> <output-filename> -png`

## Display 2 - Chromium kiosk mode

Second display runs `display/index.html` through Chromium kiosk mode.

## Installation

In root directory run `sudo bash install`
