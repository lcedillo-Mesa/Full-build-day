# Movies Website — Student Starter

## Goal
By the end of this activity you will have built a movies webpage that displays two movie cards, each with an image and a description sitting side by side.

---

## What You Have
- `index.html` — the raw content (headings, paragraphs, images) with no divs added yet
- `styles.css` — fully written CSS with class names already defined
- Two movie images in the project folder

---

## Your Job
The CSS is already written and waiting — but it won't do anything until you wrap the right content in `div` elements with the matching class names.

Open `styles.css` and look at the class names defined there. Your job is to go into `index.html` and wrap the content in `div` elements so the page starts to look styled.

---

## Instructions

1. Open `index.html` in your browser — notice nothing is styled yet
2. Open `styles.css` and read through the class names and their properties
3. In `index.html`, add `div` elements around the correct content and assign the matching class names
4. Refresh your browser after each div you add to see what changed
5. Keep going until your page matches the finished goal described below

---

## What the Finished Page Should Look Like

- A **black hero section** at the top with white text
- A **purple section title** that says "Latest Movies"
- Two **movie cards**, each taking up the full screen height, with:
  - The movie image on the left (half the screen width)
  - The title and description on the right (half the screen width) with a pink background

---

## Guiding Questions
If you get stuck, ask yourself:

- Which CSS class makes the background black? What content should be inside that section?
- The `.movie-section` is the full width of the screen — what two things need to sit inside it side by side?
- Why do `.picture-section` and `.info-section` each have a width of `49vw`? What happens if you change one to `50vw`?

---

## Vocabulary
| Term | Meaning |
|------|---------|
| `div` | A container element used to group HTML content |
| `class` | A label on an HTML element that CSS can target with `.classname` |
| `vw` | Viewport width — `1vw` = 1% of the browser window width |
| `vh` | Viewport height — `1vh` = 1% of the browser window height |
| `inline-block` | Displays an element on the same line as its neighbors while still allowing width/height |
