# HTML_CSS_task_7
## Topic: Animation

[Preview Page <img src="images/favicon.svg" width="45">](https://zura-papiashvili.github.io/HTML_CSS_task_7/)


#### Tree Structure:
```bash
├── HTML_CSS_Task_7
│   ├── css
│   │   ├── **/*.css
│   ├── fonts
│   │   ├── **/*.ttf/eot/otf/svg/woff
│   ├── images
│   │   ├── **/*.png/jpg/svg
│   ├── index.html
│   ├── .gitignore
│   ├── README.md
```
### index.html
There are two animation Using @keyframes rule.
* Skill-bar animation
* Race simulation


#### The @keyframes Rule
When you specify CSS styles inside the @keyframes rule, the animation will gradually change from the current style to the new style at certain times.

To get an animation to work, you must bind the animation to an element.

The following example binds the "example" animation to the <div> element. The animation will last for 4 seconds, and it will gradually change the background-color of the <div> element from "red" to "yellow":

``` css
/* The animation code */
@keyframes example {
  from {background-color: red;}
  to {background-color: yellow;}
}

/* The element to apply the animation to */
div {
  width: 100px;
  height: 100px;
  background-color: red;
  animation-name: example;
  animation-duration: 4s;
}
```

### Source:[www.w3schools.com](https://www.w3schools.com/css/css3_animations.asp)




