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
