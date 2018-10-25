# Userscript Typescript template

Use Typescript to write user scripts for Tampermonkey/Greasemonkey/etc.

## Setup

- `npm install`

## How to use

(Currently only tested with [Violentmonkey]())

In two separate terminals, run

- `npm run dev`
- `npm run serve`

The generated user script can now be found at http://localhost:8000/build/script.user.js .

Refer to the "Hard Way" section of the [Violentmonkey local scripts](https://violentmonkey.github.io/2017/03/14/How-to-edit-scripts-with-your-favorite-editor/#install-a-local-script) instructions. Don't forget to tick the "track local file changes" box.
