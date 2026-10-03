# 🎨 CSS Animation Examples

This project demonstrates different types of **CSS animations** using HTML and CSS. It includes color changing, movement, rotation, scaling, fading, loading animation, square path animation, and a Google-style bouncing animation.

## 🌐 Project Overview

The webpage contains multiple animated elements arranged in two sections:

### Top Section

The top section demonstrates six different CSS animation effects:

1. 🎨 Color Animation
2. ↕️ Move Animation
3. 🔄 Rotate Animation
4. 💓 Pulse Animation
5. 👻 Fade Animation
6. 🔃 Loading Animation

### Bottom Section

The bottom section contains:

* ⬛ Square Path Animation
* 🔴🟠🟡🟢🔵 Google-style Animation

---

## ✨ Features

### 1. Color Animation

The first box continuously changes its background color.

```css
@keyframes color {
    0% {
        background-color: red;
    }

    33% {
        background-color: blue;
    }

    66% {
        background-color: green;
    }

    100% {
        background-color: orange;
    }
}
```

It demonstrates how `background-color` can be animated using `@keyframes`.

---

### 2. Move Animation

The second box moves vertically up and down.

```css
@keyframes move {
    0% {
        transform: translate(0, 0);
    }

    33% {
        transform: translate(0, 50px);
    }

    66% {
        transform: translate(0, -50px);
    }

    100% {
        transform: translate(0, 0);
    }
}
```

This uses the CSS `translate()` transform.

---

### 3. Rotate Animation

The third box rotates continuously from `0°` to `360°`.

```css
@keyframes rotate {
    0% {
        transform: rotate(0deg);
    }

    25% {
        transform: rotate(90deg);
    }

    50% {
        transform: rotate(180deg);
    }

    75% {
        transform: rotate(270deg);
    }

    100% {
        transform: rotate(360deg);
    }
}
```

This demonstrates the `rotate()` transform function.

---

### 4. Pulse Animation

The fourth box increases and decreases its size.

```css
@keyframes pulse {
    0% {
        transform: scale(1);
    }

    50% {
        transform: scale(1.5);
    }

    100% {
        transform: scale(1);
    }
}
```

The `scale()` function is used to create the pulsing effect.

---

### 5. Fade Animation

The fifth box repeatedly changes its opacity.

```css
@keyframes fade {
    0% {
        opacity: 1;
    }

    50% {
        opacity: 0.5;
    }

    100% {
        opacity: 1;
    }
}
```

This demonstrates the CSS `opacity` property.

---

### 6. Loading Animation

The sixth box creates a circular loading spinner using borders.

```css
.box6 {
    border: 10px solid white;
    border-top: 10px solid red;
    border-radius: 50%;
    animation-name: vi;
    animation-duration: 5s;
    animation-iteration-count: infinite;
}
```

The spinner rotates using:

```css
@keyframes vi {
    100% {
        transform: rotate(360deg);
    }
}
```

---

## ⬛ Square Path Animation

The square path animation moves a brown box around the four corners of a dotted square.

```css
@keyframes moving {
    0% {
        transform: translate(0, 0);
    }

    25% {
        transform: translate(196px, 0);
    }

    50% {
        transform: translate(196px, 196px);
    }

    75% {
        transform: translate(0, 196px);
    }

    100% {
        transform: translate(0, 0);
    }
}
```

The animation creates a continuous square-shaped movement.

---

## 🔴 Google-style Animation

The bottom-right section contains five colored circular elements.

Each circle uses the same animation but starts at a different time using `animation-delay`.

```css
.google {
    height: 50px;
    width: 50px;
    border-radius: 50%;
    animation-name: vikash;
    animation-duration: 2s;
    animation-iteration-count: infinite;
    animation-timing-function: ease-in-out;
}
```

The animation:

```css
@keyframes vikash {
    0%, 100% {
        transform: translate(0);
    }

    33% {
        transform: translate(0, -30px);
    }
}
```

Different delays create a wave-like bouncing effect:

```css
.v2 {
    animation-delay: .3s;
}

.v3 {
    animation-delay: .6s;
}

.v4 {
    animation-delay: .9s;
}

.v5 {
    animation-delay: 1.2s;
}
```

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* CSS `@keyframes`
* CSS `transform`
* CSS `translate()`
* CSS `rotate()`
* CSS `scale()`
* CSS `opacity`
* CSS `animation-delay`
* CSS `animation-timing-function`
* Flexbox

---

## 📁 Project Structure

```text
CSS-Animation/
│
├── index.html
└── README.md
```

---

## 🚀 How to Run

1. Create a project folder.
2. Save the HTML code as `index.html`.
3. Save this documentation as `README.md`.
4. Open `index.html` in a web browser.
5. The different CSS animations will start automatically.

---

## 🎯 Learning Objectives

This project helps beginners understand:

* How CSS animations work
* How to create animations using `@keyframes`
* How to use `animation-duration`
* How to use `animation-iteration-count`
* How to use `animation-delay`
* How to use `animation-timing-function`
* How CSS transforms work
* How to animate colors
* How to create loading spinners
* How to create path-based animations
* How multiple animations can be combined with Flexbox

---

## 📚 Important CSS Properties

| Property                    | Purpose                                   |
| --------------------------- | ----------------------------------------- |
| `animation-name`            | Defines the animation to use              |
| `animation-duration`        | Sets animation duration                   |
| `animation-iteration-count` | Controls how many times animation repeats |
| `animation-delay`           | Delays the start of an animation          |
| `animation-timing-function` | Controls animation speed                  |
| `transform`                 | Changes position, rotation, or size       |
| `opacity`                   | Controls transparency                     |
| `@keyframes`                | Defines animation stages                  |

---

## 👨‍💻 Author

Created as an **HTML & CSS practice project** to understand different CSS animation techniques.
