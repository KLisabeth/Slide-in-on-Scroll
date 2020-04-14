# Development Strategy


| Step Name | User Story | Changes in HTML | Changes in CSS | Change in JS |
| --- | --- | --- | --- | --- |
| __dom__ | User see text and pictures on website | Creating some text with html and linking it with images from folder that we created | nothing | nothing |
| __Css__ | Hiding images from user, so only when he scroll down the page they appear | Adding link for css file | Styling page a lil, and transleting images off screen | nothing |
| __Data__ | As developers we want to select all images we are going to work with | Adding link to js file | nothing | Selecting all images by class |
| __Handler/checkSlide__ | As developers we want user to see images come out with some annimation and in a certain way | Adding link to js file | nothing | Lopping throug all images with **forEach**, and setting some rules for them to appear in a certain way with **if** statement |
| __Handlers/debounce__ | As a developers, we want to avoid function run to many times | nothing | nothing | Passing a function checkSlide to debounce, so it runs only every 20 ms. |
| __Listener__ | When user scrolls down the text, images appear from sides | Adding link to js file | nothing | Adding scroll listener, attached to the handler |
