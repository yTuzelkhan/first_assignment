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
* **Step 9 – Intro to CSS:** Added CSS rules to style typography, background colors, borders, positioning, and container layouts.
* **Step 10 – Inline CSS:** Applied inline styling directly on the header paragraph using `style="color:rgb(0, 0, 0)"` and on the section title using `style="color: #243b53; text-align: center;"`.
* **Step 11 – Internal CSS:** Added an internal `<style>` tag inside the `<head>` of `index.html` setting global `body` background color to `#f4f7fb` and font family to `Arial`.
* **Step 12 – External CSS:** Created `style.css` and linked it using `<link rel="stylesheet" href="style.css">` to manage external styles.
* **Step 13 – CSS Syntax & Selectors:** Used element selectors (`body`), class selectors (`.highlight`, `.section-title`, `.header`, `.main_content`, `.footer`, `.box-container`, `.left-box`, `.right-box`), and ID selectors (`#name`, `#main-heading`, `#expo`, `#1`) to style elements.
* **Step 14 – Classes vs. IDs:** Created the class `.highlight` to format navigation links (`color: #34495e; font-size: 20px`), and used ID selectors (`#name`, `#main-heading`) for primary headings with Georgia serif font (`color: #1e3a5f; font-size: 50px`).

<img width="1541" height="810" alt="изображение" src="https://github.com/user-attachments/assets/4203f8fd-a407-4a0b-a0c0-ed5ec1715b82" />
<img width="1403" height="54" alt="изображение" src="https://github.com/user-attachments/assets/12662e36-6d6e-451a-9f88-02586d38c690" />
<img width="783" height="36" alt="изображение" src="https://github.com/user-attachments/assets/83deb6f1-5245-46f3-8999-e5af3a50b351" />
<img width="862" height="318" alt="изображение" src="https://github.com/user-attachments/assets/84a76a30-4b5b-4f06-883e-35661a77e6f2" />
<img width="1591" height="933" alt="изображение" src="https://github.com/user-attachments/assets/022fca61-fb2b-424a-a83c-20b84fd884c1" />




### Part 4: Intermediate CSS
### Part 4: Intermediate CSS
* **Step 15 – Favicons:** Linked a tab icon to the webpage inside the `<head>` section using `<link rel="icon" type="image/png" href="248595983.jpeg">`.
* **Step 16 – HTML Divs:** Grouped page content into structured container sections (`<div class="header">`, `<div class="main_content">`, `<div class="footer">`, and `.box-container`).
* **Step 17 – Box Model:** Configured `padding: 20px`, `margin-bottom`, and custom borders (`4px solid #3b82f6` with `border-radius: 15px` for header/footer; `4px solid #64748b` for main content).
* **Step 18 – CSS Positioning:** Styled `body` with `position: relative`, configured `.header` with default `position: static`, shifted `.main_content` using `position: relative` (`top: 2em; margin-bottom: 180px;`), and pinned `.footer` using `position: absolute` (`bottom: 20px; left: 20px; right: 20px;`).
* **Step 19 – CSS Sizing:** Applied sizing units including pixels (`font-size: 50px; padding: 20px`), percentages (`width: 30%` on `#expo`, `width: 45%` on floated boxes), and relative em units (`top: 2em`).
* **Step 20 – Float and Clear:** Built a `.box-container` containing a floated `.left-box` (`float: left; width: 45%; background-color: #fff3e0; border: 2px solid #e67e22;`) for HTML and a floated `.right-box` (`float: right; width: 45%; background-color: #eaf2ff; border: 2px solid #3498db;`) for CSS, cleared using `<div class="clear-fix"></div>` with `clear: both;`.
* **Step 21 – Publish Your First Website:** Committed and pushed all code files to GitHub and published the sit

<img width="611" height="52" alt="изображение" src="https://github.com/user-attachments/assets/0a0e326f-3745-4343-9721-fd53e0633ff0" />
<img width="1142" height="736" alt="изображение" src="https://github.com/user-attachments/assets/9f1deadb-c8c9-4ecf-8fc7-4f4d0a64b952" />
<img width="901" height="711" alt="изображение" src="https://github.com/user-attachments/assets/308763ff-9d48-418c-88f9-f089ab2fa840" />
<img width="641" height="108" alt="изображение" src="https://github.com/user-attachments/assets/2ece5926-b406-4884-b557-789f92d794f8" />
<img width="1009" height="753" alt="изображение" src="https://github.com/user-attachments/assets/cbb9fbfb-170c-4d89-a6ed-a716c2d22306" />



---
## Work Process Summary

I started by setting up VS Code, creating the project directory, and writing the basic HTML5 boilerplate structure in `index.html`. I built the core page structure for Part 1 using heading tags (`<h1>` to `<h3>`), structured paragraphs, an ordered list for hobbies, an unordered list for websites, an image tag, hyperlinks, and action buttons. 

For Part 2, I implemented a weekly schedule table, designed a two-column table menu layout, added Unicode emojis, and created a form with text, email, color, and submit inputs.

For Parts 3 and 4, I implemented inline CSS, internal `<style>` rules, and an external stylesheet `style.css`. I structured the layout into semantic section wrappers (`.header`, `.main_content`, `.footer`) and configured box model margins, padding, and borders. 

I demonstrated CSS positioning using `static`, `relative`, and `absolute` rules, applied sizing units (`px`, `%`, `em`), and created side-by-side floated boxes (`float: left`/`float: right`) cleared with `clear: both`. Finally, I pushed the completed project to my public GitHub repository and deployed it live via GitHub Pages.


