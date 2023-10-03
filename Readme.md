# Frontend Mentor - Age calculator app solution

This is a solution to the [Age calculator app challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/age-calculator-app-dF9DFFpj-Q). 

## Table of contents

- [Overview](#overview)
  - [App description](#app-description)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### App description

Users are be able to:

- View an age in years, months, and days after submitting a valid date through the form
- Receive validation errors if:
  - Any field is empty when the form is submitted
  - The day number is not between 1-31
  - The month number is not between 1-12
  - The year is in the future
- View the optimal layout for the interface depending on their device's screen size (mobile view was set to a max-width of 500px)
- See hover and focus states for all interactive elements on the page

### Screenshot
Desktop view

![](./image/Desktop%20preview.png)

Mobile view

![](./image/Mobile%20preview.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Live site URL here](https://maryuba.github.io/Age-Calculator/)

## My process

### Built with

- HTML
- CSS
- Javascript
- Flexbox
- Desktop-first workflow


### What I learned

For html I used the 'small' tag for the first time

To see how you can add code snippets, see below:

```html
<small class="error-day"></small>
```
```css
.submit-btn img{
        transform: scale(0.5);
    }

    .submit-btn{
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%,-50%);
    }
```
I learnt to use 'return' in javascript
```js
if(input_day.value > 31){
        error_day.textContent = "Must be a valid date";
        isValid = false;
        return;
}
```

## Author

- Github - [MaryUba](https://github.com/MaryUba)
- Frontend Mentor - [@MaryUba](https://www.frontendmentor.io/profile/MaryUba)
