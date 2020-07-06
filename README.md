# 🌌Nike's history

🌕 This project was created based on [html-css/homework](https://github.com/Advanced-JS-May/html-css/blob/master/homework.md) requirements

> Open [sabovyan.github.io](https://sabovyan.github.io/index.html) to view it in the browser.

---

## Stack

### 🌌HTML

> - Metatags
> - Open Graph tags
> - twitter cards
> - Semantic tags

### 🌌CSS

> - CSS grid
> - flexbox
> - media queries
> - BEM methodology \*

## Additional tools

> - 🚀[Gulp or Parsel]()
>
> ### Modules
>
> - 🛰[-image]()
> - 🛰[-concat]()
> - 🛰[gulp-autoprefixer]()
> - 🛰[gulp-uncss]()

---

## Each page and its implementation

### The project consists of four pages

- 🌎 [Home](https://sabovyan.github.io/index.html)
- 🌎 [History](https://sabovyan.github.io/history.html)
- 🌍 [founders](https://sabovyan.github.io/founders.html)
- 🌏 [Survey](https://sabovyan.github.io/survey.html)

---

### 🌎 [Home](https://sabovyan.github.io/index.html)

![image](https://drive.google.com/uc?export=view&id=1TFFCsg0KemRZrS6cdhynQNKkWqo4q0EM)

- 🌵 banner - CSS Grid

  - for the small screen I've left just one picture and displayed it as a block element

  ```CSS
  .banner {
    display: block
  };
  ```

  ![image](https://drive.google.com/uc?export=view&id=1i6f-tSX4KISrQICwkszPeQgotStF4PHH)

- 🌵 timeline - flexbox
  - I make shoeprints not visible for small screens

---

### 🌎 [History](https://sabovyan.github.io/history.html)

- 🌵 h1 - an animation which makes blinking effect
- 🌵 sections
  ![image](https://drive.google.com/uc?export=view&id=1Ti5vOOJTjBQDz81fJEzOOnfIPZ0oGnD4)
  - section image - `float: right` this was the only way that I have found to wrap the text around picture

_source for this page_ - [History of Nike timeline and facts](https://www.thestreet.com/lifestyle/history-of-nike-15057083) article from [Thestreet](https://www.thestreet.com/)

---

### 🌍 [founders](https://sabovyan.github.io/founders.html)

![image](https://drive.google.com/uc?export=view&id=1Jh7jKpNwGDWWSlSCh_s5UYpftbkiJOHA)

- 🌵 the whole page was aligned using flexbox
- 🌵 Each card is hover able and has a bit more information and links about the particular person

---

### 🌍 [Survey](https://sabovyan.github.io/survey.html)

- 🌵This page was lined up with CSS Grid
- 🌵 Maybe the layout is not that user-friendly, but I implemented this way to practice grid one more time

### 💫 footer

- there is a little animation with `:hover` & `:active` for the icons at the end of the footer

---

\* BEM I have tried to use BEM for the whole project I am sure that there are lots of mistakes but I've tried to stick to this methodology
