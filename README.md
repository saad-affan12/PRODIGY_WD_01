# Prodigy Infotech Task 1 – Responsive Landing Page

This is my Task 1 submission for the **Prodigy Infotech Internship Program**.

## Features
- Responsive navigation bar with hamburger menu
- Navbar changes color on scroll
- Clean and modern landing page sections

## Live Demo
[Click here to view the project](https://saad-affan12.github.io/prodigy-task1-landingpage/)

## How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/saad-affan12/prodigy-task1-landingpage.git

## **C. Add Subtle Hover Effects**
Inside `<style>` in `index.html`, add:
```css
.nav-links a:hover {
  color: #ffcc00;
  transition: color 0.3s ease;
}

.section1, .section2, .section3 {
  transition: transform 0.3s ease;
}

.section1:hover, .section2:hover, .section3:hover {
  transform: scale(1.02);
}
