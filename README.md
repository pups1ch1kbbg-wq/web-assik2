link: https://pups1ch1kbbg-wq.github.io/web-assik2/

# Assignment 3: Advanced CSS (Flexbox & Grid)

> **Course:** Front-End Development / Web Technologies  
> **Student Name:** [Kairov Zhangir]
> **Group:** [SE-2526]

---

## 📌 Project Overview
This project showcases modern, responsive CSS layout techniques implemented using **Flexbox** and **CSS Grid** without relying on floats or external frameworks. The repository contains multiple standalone HTML pages, each demonstrating specific alignment, grid area, and layout strategies linked via a unified navigation bar.

---

## 🚀 Navigation & Structure

| Page | File | Layout Concept | Description |
| :--- | :--- | :--- | :--- |
| **Home** | `index.html` | Flexbox Header/Footer | Overview of the assignment and student details. |
| **Task 1** | `task1-flexbox.html` | Flexbox Layout | Responsive card container with equal height and hover effects. |
| **Task 2** | `task2-grid-layout.html`| CSS Grid Areas | Classic page structure using named grid areas (`header`, `sidebar`, `main`, `footer`) |
| **Task 3** | `task3-gallery.html`| CSS Grid Gallery. | 9-image grid layout with equal columns and interactive hover overlays. |
| **Task 4** | `task4-portfolio.html` | Combined Flexbox & Grid| Grid-based portfolio layout containing cards styled internally with Flexbox. |

---

## 🛠️ Task Implementations

### Task 0: Navigation Bar
* Implemented a flexible header (`.main-header`) containing a logo aligned to the left and navigation links aligned to the right.
* Utilized `display: flex`, `justify-content: space-between`, and `align-items: center` for alignment across all pages.

### Task 1: Card Row (Flexbox)
* Created a multi-card container (`.card-container`) using Flexbox.
* Ensured uniform height across all cards while preserving consistent gaps (`gap`).
* Included interactive hover effects (`transform`, `box-shadow`) on each card.

### Task 2: Page Layout (CSS Grid)
* Built a page wrapper using `display: grid`.
* Assigned layout sections using `grid-template-areas`:
  * Header across the top
  * Sidebar on the left
  * Main content on the right
  * Footer across the bottom

### Task 3: Image Gallery
* Arranged a 9-image responsive grid using `display: grid` and `grid-template-columns`.
* Applied regular spacing using CSS `gap`[cite: 1].
* Added a CSS hover animation that displays a caption overlay over each gallery image.

### Task 4: Portfolio Page (Flexbox + Grid Combination)
* Structured the main page using **CSS Grid** to separate the project showcase area from the sidebar.
* Applied **Flexbox** inside individual project cards to vertically organize the content (title, description, and action button).
* Created a full-width footer spanning across the bottom of the page layout.

---

## 📂 Directory Tree

```text
.
├── css/
│   └── style.css            # Centralized CSS stylesheet
├── index.html               # Main landing page (Task 0)
├── task1-flexbox.html       # Flexbox card row (Task 1)
├── task2-grid-layout.html   # CSS Grid area layout (Task 2)
├── task3-gallery.html       # CSS Grid image gallery (Task 3)
└── task4-portfolio.html     # Combined Flexbox + Grid portfolio (Task 4)
