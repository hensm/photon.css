# photon.css

Photon UI style for extension/Firefox-related use. Adjusts to light/dark theme based on system theme (`prefers-color-scheme`).

Based partially on:
https://design.firefox.com/photon/

## Usage

Include the photon.css stylesheet and keep it alongside the image assets.

````html
<link rel="stylesheet" href="photon/photon.css">
````
````css
@import "photon/photon.css";
````

See `examples/` for more detailed usage.


## Building

### Instructions

````sh
git clone https://github.com/hensm/photon.css
cd photon.css
npm install
npm run build
````

Output will be at `dist/photon.css`.
