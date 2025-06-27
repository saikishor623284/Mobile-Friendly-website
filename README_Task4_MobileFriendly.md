
# Task 4: Make a Website Mobile-Friendly Using CSS Media Queries

# Objective
Convert an existing desktop-only webpage into a responsive, mobile-friendly layout using CSS media queries.



# Tools Used
- HTML & CSS
- VS Code
- Chrome DevTools (for responsive testing)



# How to Use

1. Open Project  
   Open the index.html and style.css files in VS Code.

2. View Desktop Version  
   Open index.html in your browser. This is the default desktop layout.

3. Test Mobile View  
   - Open Chrome.
   - Press Ctrl + Shift + I or right-click and select Inspect.
   - Toggle the Device Toolbar (Ctrl + Shift + M).
   - Choose a mobile device (e.g., iPhone SE, Galaxy S).
   - The layout should stack vertically and images/text should resize properly.



# Project Files

- index.html – Sample HTML structure (desktop-first)
- style.css – Contains base styles and responsive media queries
- README.md – This file



#  Media Query Highlights

css
@media (max-width: 768px) {
  .container {
    flex-direction: column;
  }
  .left, .right {
    width: 100%;
  }
  nav ul {
    flex-direction: column;
  }
  img {
    max-width: 100%;
    height: auto;
  }
}




# Features
- Mobile-responsive layout
- Flexible images and text
- Stacked navigation on small screens
- No horizontal scrolling issues



# Author
Made for Task 4 – Responsive Web Design Practice
