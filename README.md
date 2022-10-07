# Project: JavaScript for CS Professor Home Page

<aside>

**👥 This is a team project.**

Find a teammate (or two teammates, for a maximum of three students per team) from your squad, and schedule time to work on the project together.

If you have trouble finding a partner, or have trouble with the project, use the **#help-web** channel in Discord. You can work with anyone, you are not restricted to your squad. You are also allowed to work on your own, but it’s good practice to work together.

You can work together by sharing your screen and reading each other's code on GitHub. You should each submit a copy of the project, but it can be copied from your teammate’s version (**which you all created together**!).

</aside>

## Introduction

In this project, you'll be adding JavaScript to your CS Professor page to make it interactive. You're going to implement a toggle, so that when a visitor clicks on one of your headings, the paragraph text is displayed.

This is an example
![toggle example](kibo-js-toggle-demo_large.gif)

### Disclaimer

Just like before, since it's a fake page, we've added a disclaimer to the top of the page letting folks know that it's not real. **Leave the disclaimer and its styles alone at the top of the page**, so that no one thinks we're trying to fool them.

## Instructions

**Before you get started**
Have a read of this [document](https://developer.mozilla.org/en-US/docs/Web/API/Element/classList), note how `toggle` is used in the example code being called on the `classList` method.

Prepare what you'll need to build the site. Write down all of the facts and info you'll put on the website. You can use the file `site-plan.md` to take notes, or write things somewhere else.

You'll be editing both the `index.html` and `main.js` files, so make sure you're adding the correct code in the correct file.

### HTML
1. Add an ID to each of your headings except the title of the page. Make sure the IDs are unique.
2. Add an ID to the corresponding paragraphs.

### CSS
3. Change the display of the paragraphs so that they're hidden on the page.
4. Create a class called `.show` or `.visible` that sets the `display` to `block` (or what the paragraph elements were before).

### JS
5. Create variables that store your heading elements.
6. Create variables that store your paragraph elements.
You should have as many heading variables as you do headings in the HTML, and you should have as many paragraph variables as you do paragraph elements in the HTML.
7. Add a click event listener to each heading variable.
8. Within the event listener, get the corresponding paragraph for the heading and call toggle on its classList. (If you get stuck remember to revisit the [MDN document](https://developer.mozilla.org/en-US/docs/Web/API/Element/classList))
9. Open your index.html file in your browser and test that it works

## Rubric

Use this checklist to confirm that you've included everything you need:

- [ ] You should have an equal number of heading variables as heading elements
- [ ] You should have an equal number of paragraph variables as paragraph elements
- [ ] You should have a click event listener on each heading variable
- [ ] You should have a toggle on the classList of each paragraph variable
- [ ] You should have a `.show` or `.visible` class
- [ ] Your paragraph elements should be hidden from the page by default.
- [ ] Still has the Disclaimer at the top of the page

## Bonus
