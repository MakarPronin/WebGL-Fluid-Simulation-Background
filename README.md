# WebGL Fluid Simulation Background

This project adapts the amazing [WebGL Fluid Simulation by Pavel Dobryakov](https://github.com/PavelDoGreat/WebGL-Fluid-Simulation) for use as an interactive website background.

While the original implementation is incredible, it spans multiple files and can be computationally heavy. To make it more suitable for a background, I simplified and optimized the codebase, restricted the effects to hover interactions, and updated the styling.

You can use this lightweight version to easily add interactive fluid backgrounds to your own website (including on platforms like Tilda).

## Screenshots

<!-- Replace the paths below with the actual paths to your image files -->
![Webpage screenshot](WebpageScreenshot.png)
*Fluid simulation as a background on a webpage.*

![Base version screenshot](BaseVersionScreenshot.png)
*Standard version.*

## Folder Structure & Available Versions

1. `html_fluid`: The original simulation by Pavel Dobryakov, bundled into a single HTML file.
2. `html_fluid_lite`: A lightweight version optimized for performance by removing Bloom, Sunrays, and shading effects.
3. `html_fluid_lite_onhover`: Adapts the lightweight version to trigger fluid effects on mouse hover rather than click.
4. `html_fluid_lite_onhover_element`: Configured to be embedded as a standalone, localized element within a webpage.
5. `html_fluid_lite_onhover_background`: Configured specifically for use as a full-page website background.
6. `html_fluid_lite_onhover_background_lightTheme`: The background version, pre-styled for light-themed websites.
7. `html_fluid_lite_onhover_background_mobileFixed`: The background version extended with mobile device support *(Note: this replaces native scrolling logic with Lenis)*.
8. `html_fluid_lite_onhover_background_mobileFixed_lightTheme`: The mobile-optimized background version, pre-styled for light themes.

**I recommend using 7 and 8.**


## How to Add to Your Website

1. Choose your preferred version by selecting the corresponding folder.
2. Copy all the HTML content from inside the `<body>` element (excluding the `<body>` tags themselves).
3. Paste it into your website's HTML body.

*Note: You may need to adjust the `config` or `lenis` values within the script and/or tweak the CSS styles to match your specific design needs.*

## Live Example

You can interact with a live demo of this fluid simulation background at https://fama.marketing.

## License

MIT License

Copyright (c) 2017 (Pavel Dobryakov)[https://github.com/PavelDoGreat/WebGL-Fluid-Simulation]
Copyright (c) 2026 (Darkroom Engineering)[https://github.com/darkroomengineering/lenis]
Copyright (c) 2026 (Makar Pronin)[https://github.com/MakarPronin/WebGL-Fluid-Simulation-Background]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
