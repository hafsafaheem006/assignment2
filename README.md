# WanderWise Travel — Web Technologies Assignment

**Course:** Web Technologies, BSCS Semester 5  
**Topic:** Travel Agency  
**Student name:** Replace with your name  
**Roll number:** Replace with your roll number  
**Section:** Replace with your section  

## Project files
- `index.html` — home page using inline CSS.
- `information.html` — tour information, table, audio, and video; uses embedded CSS.
- `registration.html` — booking inquiry form; links to external `style.css`.
- `media/` — local image, audio, and video files.
- `validation-screenshots/` — add your own validator screenshots here.

## CSS and HTML explanation (200–300 words)

CSS (Cascading Style Sheets) controls how HTML content looks. It helps separate presentation from content, keeps pages readable, supports consistent colors and spacing, and makes layouts easier to maintain. For example, in `style.css`, the rule `input[type="email"] { border: 2px solid #4c8795; }` uses the attribute selector `input[type="email"]`; the property is `border`; and the value is `2px solid #4c8795`. This gives the email field a distinct visible border.

The project demonstrates three CSS methods. Inline CSS is written in an element's `style` attribute and is used on `index.html`. Embedded CSS is written inside a `<style>` element in the `<head>` of `information.html`. External CSS is stored in `style.css` and linked from `registration.html`. External styles are usually easiest to reuse and maintain, while inline styles are limited to individual elements and embedded styles apply to one document.

CSS1 established foundational styling such as fonts, colors, and spacing. CSS2 and CSS 2.1 expanded layout, positioning, media types, and clarified the specification. Modern CSS is developed as separate modules, including Flexbox, Grid, media queries, custom properties, and newer selectors, which evolve at different rates.

Browser support matters because a feature may render or behave differently across browsers and devices. Test this project in two browsers, such as Google Chrome and Mozilla Firefox, and record your actual results below; do not claim tests you have not performed. Semantic HTML gives meaning to content: `<nav>` identifies the navigation area, while `<div>` is a non-semantic generic container without a built-in meaning. This project uses semantic elements such as `<header>`, `<main>`, `<section>`, `<article>`, `<aside>`, and `<footer>`.

## Testing checklist
- [ ] Validate `index.html` at https://validator.w3.org/ and save a screenshot.
- [ ] Validate `information.html` at https://validator.w3.org/ and save a screenshot.
- [ ] Validate `registration.html` at https://validator.w3.org/ and save a screenshot.
- [ ] Test required fields, an invalid email, and a password shorter than 8 characters.
- [ ] Test the website in two browsers and record real differences below.
- [ ] Check all navigation links and play the local audio/video.
- [ ] Replace the student details above before submission.

### Browser test record
| Browser and version | Date tested | Result / differences |
|---|---|---|
| Google Chrome: fill in version | Fill in date | Record your actual result |
| Mozilla Firefox: fill in version | Fill in date | Record your actual result |

## GitHub Pages submission
1. Create a GitHub repository and upload all project files, including the `media` folder.
2. Open **Settings → Pages**. Select deployment from the `main` branch and the root folder, then save.
3. Wait for GitHub Pages to publish and copy the live URL.
4. Enter your name, roll number, section, repository URL, and live URL into your class Google Sheet.
5. Put the three validator screenshots in `validation-screenshots/` and upload them to the repository.

**Note:** This is a front-end coursework demo. The form does not store data or create accounts. Prices and contact details are fictional examples.
