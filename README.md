# Assignment #1: HTML & CSS Basics

**Student Name:** Yermek Tuzelkhan  
**Group:** IT-2513  
**Course:** Front-End Development 
**Live Site (GitHub Pages):** [https://ytuzelkhan.github.io/first_assignment](https://ytuzelkhan.github.io/first_assignment/)

---

## Tasks & Implementation Screenshots

### Part 1: Introduction to HTML
* **Step 0 – Create HTML File & Boilerplate:** Created `index.html` with standard HTML5 boilerplate structure (`<!DOCTYPE html>`, `<html>`, `<head>`, `<title>`, `<body>`) and titled the page "My First Webpage".
* **Step 1 – Structure Text:** Added `<h1>`, `<h2>`, and `<h3>` tags for my name, course name, and section headers, along with a `<p>` paragraph describing myself.
* **Step 2 – HTML Lists:** Created an ordered list (`<ol>`) listing my hobbies (Playing football, Reading books, Watching movies) and an unordered list (`<ul>`) with links to my favorite websites.
* **Step 3 – Images and Links:** Used `<img>` to insert an EXPO photo and added clickable `<a>` links targeting external sites (Codeforces, YouTube, Instagram) and internal page anchors.
* **Step 4 – HTML Buttons:** Placed a `<button>` element with the text "Click Me" inside the main content section.


<img width="1914" height="277" alt="изображение" src="https://github.com/user-attachments/assets/e5402931-e313-4ace-8163-9cdc475de6b1" />
<img width="1906" height="832" alt="изображение" src="https://github.com/user-attachments/assets/05756d3c-d62a-4a86-bd9b-fa99b22ae5ca" />
<img width="1908" height="855" alt="изображение" src="https://github.com/user-attachments/assets/be4f9ddc-eb8e-4210-9c1b-2468cfc750b8" />
<img width="1549" height="862" alt="изображение" src="https://github.com/user-attachments/assets/45539ec4-7854-4a00-948a-0b13e1367ac3" />
<img width="750" height="289" alt="изображение" src="https://github.com/user-attachments/assets/77e73e14-4d25-4ce2-8c71-1afa4d9d0fc7" />



---

### Part 2: Intermediate HTML
* **Step 5 – Tables:** Created a schedule table using `<table>`, `<tr>`, `<th>`, and `<td>` tags with columns for "Subject", "Day", and "Time".
* **Step 6 – Using Tables for Layout:** Built a two-column layout table inside the header dividing the page menu links on the left from main description text on the right using `rowspan="3"`.
* **Step 7 – Typing Emojis:** Inserted Unicode emoji entities (`&#128293;&#128077;&#128640;`) inside the header paragraph to display 🔥, 👍, and 🚀.
* **Step 8 – HTML Forms:** Created an interactive form in the footer with `<input>` fields for Name (`text`), Email (`email`), Favorite Color (`text`), and a Submit button.


<img width="1695" height="508" alt="изображение" src="https://github.com/user-attachments/assets/891376f6-25bd-4682-b74d-6e250d954079" />
<img width="1912" height="223" alt="изображение" src="https://github.com/user-attachments/assets/508ba63a-3d30-4a78-94fc-46b26330d353" />
<img width="1470" height="898" alt="изображение" src="https://github.com/user-attachments/assets/055d9c4a-d3e0-46ff-b9b9-59f7f4794c9e" />
<img width="1459" height="383" alt="изображение" src="https://github.com/user-attachments/assets/7ab0f4ed-9e76-440a-b6d5-26c47082bdf7" />

---

### Part 3: Introduction to CSS
* **Step 9 – Intro to CSS:** Added CSS rules to style typography, text sizes, element colors, backgrounds, and layout structure across the webpage.
* **Step 10 – Inline CSS:** Applied inline styling directly on the top paragraph tag using `style="color:blue"`.
* **Step 11 – Internal CSS:** Added an internal `<style>` tag inside the `<head>` of `index.html` to set global `body` background color to `lightblue` and font family to `Arial`.
* **Step 12 – External CSS:** Created `style.css` and linked it to `index.html` using `<link rel="stylesheet" href="style.css">` to manage external styles.
* **Step 13 – CSS Syntax & Selectors:** Used element selectors (`body`), class selectors (`.highlight`, `.section-title`), and ID selectors (`#name`, `#main-heading`) to target and style specific elements.
* **Step 14 – Classes vs. IDs:** Created the class `.highlight` to apply black text color across multiple navigation links, and used unique ID selectors `#name` and `#main-heading` to style specific `<h1>` elements.

<img width="1545" height="775" alt="изображение" src="https://github.com/user-attachments/assets/d54d5c31-89ab-4b8b-8376-e285c71b9f11" />
<img width="1546" height="926" alt="изображение" src="https://github.com/user-attachments/assets/d6851d7f-ffe3-4dbd-92ed-bd63f2693493" />

### Part 4: Intermediate CSS
* **Step 15 – Favicons:** Linked a tab icon to the webpage inside the `<head>` section using `<link rel="icon" type="image/png" href="248595983.jpeg">`.
* **Step 16 – HTML Divs:** Grouped the page content into three main layout sections using `<div class="header">`, `<div class="main_content">`, and `<div class="footer">`.
* **Step 17 – Box Model:** Applied `padding: 20px`, `margin-bottom`, and borders (`5px dotted black` for header/footer, `5px solid rgb(101, 19, 19)` for main content) to demonstrate box model spacing.
* **Step 18 – CSS Positioning:** Set `.header` to `position: static`, shifted `.main_content` using `position: relative` (`top: 2em;`), and anchored `.footer` using `position: absolute` (`bottom: 20px; left: 20px; right: 20px;`).
* **Step 19 – CSS Sizing:** Applied different sizing units across elements including pixels (`font-size: 50px`), percentages (`width: 30%` on `#expo`), and relative em units (`top: 2em`).
* **Step 20 – Float and Clear:** Created a `.box-container` containing `.left-box` (`float: left; width: 45%`) and `.right-box` (`float: right; width: 45%`), and used `<div class="clear-fix"></div>` with `clear: both;` to fix layout collapsing.
* **Step 21 – Publish Your First Website:** Committed and pushed all code files to GitHub and published the site live using GitHub Pages.

<img width="1247" height="306" alt="изображение" src="https://github.com/user-attachments/assets/970bd2a5-9d6d-4d36-aed5-c47a166598e2" />
<img width="1620" height="819" alt="изображение" src="https://github.com/user-attachments/assets/4b4f2eb9-0b5e-458c-a3fe-3165c22139ea" />
<img width="1537" height="666" alt="изображение" src="https://github.com/user-attachments/assets/a10ff16e-ce70-420a-b1c1-be1fe69ee577" />
<img width="1586" height="719" alt="изображение" src="https://github.com/user-attachments/assets/57f98b4e-8079-43d1-95ba-9eac2817bf13" />
<img width="1455" height="304" alt="изображение" src="https://github.com/user-attachments/assets/8a2116cc-64b3-4b93-8aae-5cbea07eb47a" />
<img width="1280" height="682" alt="изображение" src="https://github.com/user-attachments/assets/696a40ec-a4b5-4422-a56b-a3f9b99b8b12" />

---
## Work Process Summary

I started by setting up VS Code, creating the project directory, and writing the basic HTML5 boilerplate structure in `index.html`. I built the core page structure for Part 1 using heading tags (`<h1>` to `<h3>`), structured paragraphs, an ordered list for hobbies, an unordered list for websites, an image tag, hyperlinks, and action buttons. 

For Part 2, I implemented a weekly schedule table, designed a two-column table menu layout, added Unicode emojis, and created a form with text, email, color, and submit inputs.

For Parts 3 and 4, I implemented inline CSS, internal `<style>` rules, and an external stylesheet `style.css`. I structured the layout into semantic section wrappers (`.header`, `.main_content`, `.footer`) and configured box model margins, padding, and borders. 

I demonstrated CSS positioning using `static`, `relative`, and `absolute` rules, applied sizing units (`px`, `%`, `em`), and created side-by-side floated boxes (`float: left`/`float: right`) cleared with `clear: both`. Finally, I pushed the completed project to my public GitHub repository and deployed it live via GitHub Pages.


