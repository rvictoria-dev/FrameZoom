# FrameZoom

### ₊⊹ About

**FrameZoom** is a simple, modern interface component that creates a smooth zoom effect when you hover over an image. Built entirely with **HTML5** and **CSS3**, this project is ideal for creating photo galleries or art portfolios that require a more dynamic and interactive browsing experience.

[framezoom.webm](https://github.com/user-attachments/assets/c2f56b05-5b4c-4fb4-ab1a-93aed0d2f486)

---

### ★ Features

- **Dynamic Zoom:** A smooth zoom effect triggered when you hover over an element.

- **Smart Frame:** Perfect image cropping with rounded corners and overflow masking.

- **Centered Focus:** Perfect alignment in full-screen mode using modern positioning techniques (Flexbox).

- **Clean Design:** Minimalist, lightweight code that integrates easily into any art portfolio or web gallery.

---

### ⚙️ Tech Stack

- HTML5
- CSS3

---

### 🖿 Project structure

```
framezoom/
├── Assets/
│   ├── alita-battle-angel.jpg
├── index.html
├── style.css
└── README.md
```

---

### .ᐟ.ᐟ How It Works

- **Overflow Masking:** The .picture-frame class acts as a fixed-size frame (500x400px) that hides anything that extends beyond its boundaries using `overflow: hidden`.

- **Smooth Transition:** The inner image has a transition property (transition: transform 0.5s ease), ensuring that any size change is gradual and visually pleasing.

- **Hover Scale:** When the user hovers over the frame (:hover), the CSS triggers an event that increases the image size by 15% (transform: scale(1.15)), creating a zoom-in effect without distorting the layout.
