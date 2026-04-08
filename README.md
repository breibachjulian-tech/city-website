# Rotterdam City Website

A modern, responsive website showcasing Rotterdam, Netherlands' second-largest city known for its innovative architecture, vibrant culture, and world-class port.

## 📋 Project Overview

This project is a single-page website built with HTML5 and CSS3, designed to introduce visitors to Rotterdam and highlight its key attractions, statistics, and cultural significance. The website features a clean, modern design with smooth interactions and responsive layout principles.

## � Live Preview

**View the live website here:** https://breibachjulian-tech.github.io/city-website/

The project is hosted on GitHub Pages for easy access and preview.

## �🎨 HTML Techniques Used

### Semantic Structure
- **Semantic HTML5**: Uses meaningful `<div>` containers with descriptive class names to organize content logically
- **Proper Heading Hierarchy**: Implements `<h1>`, `<h2>`, `<h3>`, and `<h4>` tags for accessibility and SEO
- **Descriptive Alt Text**: All images include detailed alt attributes for accessibility and screen readers

### Content Organization
- **Section-based Layout**: Content is divided into distinct sections:
  - Hero section: Eye-catching introduction
  - Discover section: City information and statistics
  - Landmarks section: Image gallery of iconic locations
  - Guide section: Personal testimonial

### Document Structure
- **DOCTYPE Declaration**: HTML5 (`<!DOCTYPE html>`)
- **Meta Elements**: Links to external CSS stylesheet for separation of concerns
- **Image Elements**: Uses `<img>` tags with descriptive alt text for better accessibility

## 🎯 CSS Techniques Used

### Layout & Responsive Design

#### **CSS Grid**
```css
.discover {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 40px;
}
```
- Used in the Discover section to create a two-column layout
- `1fr 1fr` creates equal-width columns
- `gap` provides consistent spacing between elements

#### **Flexbox**
```css
.hero {
    display: flex;
    flex-direction: column;
    justify-content: center;
}
```
- Hero section uses flexbox for centered vertical alignment
- `flex-direction: column` stacks content vertically
- `justify-content: center` centers content on the page

### Visual Effects & Styling

#### **Background Images with Overlays**
```css
.hero {
    background-image: url('images/hero/rotterdam-hero.jpg');
    background-size: cover;
    background-position: center;
    background-color: rgba(0, 0, 0, 0.4);
}
```
- Full-width background image that covers the entire section
- Semi-transparent dark overlay (`rgba(0, 0, 0, 0.4)`) improves text readability

#### **Hover Effects & Transitions**
```css
.landmarks img:hover {
    transform: scale(1.05);
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.3);
    transition: 0.3s ease;
}
```
- `transform: scale(1.05)` creates a subtle zoom effect on hover
- `box-shadow` adds depth with a shadow effect
- `transition: 0.3s ease` smoothly animates the effect

#### **Border Radius**
```css
.landmarks img {
    border-radius: 5px;
}
```
- Rounded corners applied to images and cards for a modern, polished look

#### **Text Shadow**
```css
.hero h1, .hero h2 {
    text-shadow: 2px 2px 4px #000000;
}
```
- Adds depth and readability to white text on the background image

### Responsive & Flexible Spacing

#### **Max-Width & Auto Margins**
```css
.discover {
    max-width: 1200px;
    margin: 0 auto;
}
```
- `max-width` constrains content width for readability
- `margin: 0 auto` centers content on the page

#### **Object-Fit**
```css
.landmarks img {
    height: 400px;
    width: 400px;
    object-fit: cover;
}
```
- `object-fit: cover` ensures images maintain aspect ratio and fill their containers

### Color Palette

The design uses a cohesive color scheme:
- **Primary Dark Blue**: `#1D3557` (headings)
- **Secondary Blue**: `#457B9D` (text, stat boxes)
- **Light Accent**: `#A8DADC` (background highlights)
- **White**: Text on colored backgrounds

### Typography

- **Font Family**: Sans-serif for modern, clean appearance
- **Font Sizing**: Scalable font sizes using `em` units for responsiveness
- **Line Height**: `1.6` for improved readability

## 📁 Project Structure

```
city-website/
├── index.html          # Main HTML file with all content
├── styles.css          # All CSS styling
├── README.md           # This file
└── images/
    ├── hero/
    │   ├── rotterdam-hero.jpg
    │   └── julian-breibach.jpg
    └── activities/
        ├── kubus.jpg
        ├── markthal.jpg
        └── oude-haven.jpg
```


## 💡 How to Use This Project

1. Open `index.html` in a web browser
2. All styling is automatically applied via `styles.css`
3. Replace image paths with your own images in the `images/` directory
4. Modify text content directly in `index.html`
5. Customize colors in `styles.css` by updating the hex values

## 🔧 Next Steps for Enhancement

- Add media queries for mobile responsiveness
- Implement navbar with smooth scrolling
- Add more interactive elements (buttons, modals)
- Optimize images for web performance
- Add animations on scroll using JavaScript
- Create additional pages with more detailed information

## 📚 Resources for Learning

- [MDN Web Docs - CSS Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)
- [MDN Web Docs - Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout)
- [MDN Web Docs - CSS Transforms](https://developer.mozilla.org/en-US/docs/Web/CSS/transform)
- [WebAIM - Accessibility](https://webaim.org/)

---

**Created as a learning project showcasing modern HTML5 and CSS3 techniques.**
