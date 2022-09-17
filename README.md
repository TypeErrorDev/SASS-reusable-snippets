# Partials Table of Contents:

1. [Flexbox](https://github.com/TypeErrorDev/SASS-reusable-snippets/blob/main/sass/partials/_flexbox.scss)
2. [Simple Keyframe Animation](https://github.com/TypeErrorDev/SASS-reusable-snippets/blob/main/sass/partials/_keyframeAnimations.scss)
3. [Media Query](https://github.com/TypeErrorDev/SASS-reusable-snippets/blob/main/sass/partials/_mediaquery.scss)
4. [Absolute Positioning](https://github.com/TypeErrorDev/SASS-reusable-snippets/blob/main/sass/partials/_absolute.scss)
5. [Padding and Margin function](https://github.com/TypeErrorDev/SASS-reusable-snippets/blob/main/sass/partials/_paddingmargin.scss)
6. [Opposite Color on the ColorWheel](https://github.com/TypeErrorDev/SASS-reusable-snippets/blob/main/sass/partials/_ColorFunctions.scss)
7. [Biggest RGB color](https://github.com/TypeErrorDev/SASS-reusable-snippets/blob/main/sass/partials/_ColorChannel.scss)
8. [PX to REM converter](https://github.com/TypeErrorDev/SASS-reusable-snippets/blob/main/sass/partials/_pxtorem.scss)

# SASS Tips and Tricks to setting up!

## Setting up SASS with NPM already installed:

1. Run in terminal: ` npm install sass -g`
2. Create your index.html and then create a sass folder and add your index.scss inside
3. Create a folder inside your sass folder, and create an index.scss and another partial.scss file
4. Once that is done, run your watch cmd: `sass --watch sass/index.scss:css/styles.css`
5. Verify that your css folder was created
6. Verify that your styles.css file (and the styles.css.map file) was created and has /_# sourceMappingURL=styles.css.map _/ automatically included in the file

---

## Creating your own run script for SASS

1. In the terminal, run `npm init`
2. In the package.json file, change the script object to read:

```json
"scripts": {
    "script-name": "sass --watch pathToMainIndex.scss:pathToStyles.css"
  },
```

3. In the terminal, run `npm run script-name`

---
