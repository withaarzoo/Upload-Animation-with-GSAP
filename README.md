# Upload Animation with GSAP
This code demonstrates an upload animation implemented using GSAP (GreenSock Animation Platform). It provides a button with an upload icon and progress indication, which transforms into a progress bar during the upload process. After the upload completes, the button transitions into a checkmark animation to indicate a successful upload. The animation effects are achieved using CSS and GSAP library.

## How to Use
To use this code, follow these steps:

1. Include the GSAP library by adding the following script tag to your HTML file:

```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js" integrity="sha512-16esztaSRplJROstbIIdwX3N97V1+pZvV33ABoG1H2OyTttBxEGkTsoIVsiP1iaTtM8b3+hu2kB6pQ4Clr5yug==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
```

2. Copy and paste the provided CSS and JS code into separate files, such as `style.css` and `script.js`, respectively.

3. Link the CSS file by adding the following link tag inside the head section of your HTML file:

```html
<link rel="stylesheet" href="style.css" />
```
4. Add the JavaScript file by adding the following script tag just before the closing body tag of your HTML file:

```html
<script src="script.js" defer></script>
```
5. Customize the animation properties by modifying the CSS variables defined in the `:root` selector of the CSS code. You can adjust the button size, colors, progress bar dimensions, and more according to your preference.

6. Save the files and open the HTML file in a web browser. You should now see the upload button with the animation effect.

7. Click on the upload button to trigger the animation. The button will transform into a progress bar, indicating the progress of the upload. After completion, the button will transition into a checkmark animation.

8. After 5 seconds, the button and container will return to their original state, ready for another upload.

## Dependencies
This code relies on the following dependencies:

* [GSAP](https://greensock.com/gsap/) A powerful JavaScript animation library used to create smooth and performant animations.
  
Make sure to include the GSAP library using the provided script tag or by downloading it from the GSAP website.

## Compatibility
The code provided is compatible with modern web browsers that support HTML5, CSS3, and JavaScript. It utilizes GSAP's animation capabilities, so it requires a browser with JavaScript enabled.

## Preview

