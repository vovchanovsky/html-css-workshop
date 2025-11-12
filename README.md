# HTML & CSS Workshop

## Project Overview
This project was created as part of the **HTML & CSS Workshop**.  
The goal was to build a **single webpage** using HTML and CSS

The page presents a personal profile, including sections such as an introduction, skills, work experience, and a contact form.

---

##  HTML Structure
The HTML structure was designed using **semantic elements** for clarity and accessibility.  
The main structure includes:

- `<header>` – Contains the name, title, and a horizontal rule.  
- `<main>` – The main content of the page, with sections for:
  - **About Me** – A short introduction paragraph.  
  - **Skills** – A list of key programming and technical skills.  
  - **Work Experience** – Displayed in a structured **table** with position, company, and duration columns.  
- `<aside>` – A **contact form** that allows visitors to submit their name, email, and a message.  
- `<footer>` – Displays a copyright.

## CSS Structure

All styling is written in `styles.css` using **CSS Grid** to organize the page into two columns.

The layout is structured as follows:

- **Body** – Uses `display: grid` with two columns (left for main content, right for contact form).
- **Header** – Spans both columns at the top with centered text and light blue background.
- **Main** – Left column containing About Me, Skills, and Work Experience sections.
- **Aside** – Right column containing the contact form.
- **Footer** – Spans both columns at the bottom with centered copyright text.

### Colors

- **Primary Blue** (`#2563eb`) – Headings, table headers, borders, and buttons.
- **Light Blue** (`#e0e7ff`) – Header background.
- **Light Gray** (`#f9fafb`) – Page background.
- **White** – Content cards and form containers.


