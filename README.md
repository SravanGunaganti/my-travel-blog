# **Sravan Travel Blog \- Project Documentation**


## **Project Overview**

Sravan's Travel Blog is a travel blog website designed to share travel experiences, advice, and destination guides. This project features a vibrant and user-friendly design to enhance reader engagement while showcasing captivating travel stories.

---

## **Project Live Link**

[https://sravantravelblog.netlify.app/](https://sravantravelblog.netlify.app/)

---

## **Technologies Used**

* **HTML:** for structuring the content of the website  
* **CSS:** for styling and enhancing the website's appearance  
* **Media Queries:** for responsive design to adapt to various screen sizes

---

## **Features**

### **Header Section**

* Includes a title, introduction, and background video with a fallback background image.  
* Animated title color using texclip and gradient for a linear color-changing effect.

### **Navigation Menu**

* Clear navigation links with dropdown support for blogs.  
* Interactive hover effects for the links.  
* Smooth scroll behavior for navigation between sections.

### **Dark/Light Theme Toggle (Integrated Beyond Assignment Requirements)**

* Theme toggle using an input checkbox hidden by default.  
* Label toggle switch displays "Dark" and "Light" mode text based on the selected theme.  
* Theme styles update for all major sections, including background, text, and navigation.

### **Blog Section**

* Grid layout for structured design with equal spacing between blogs.  
* Images and embedded videos for each blog with smooth hover effects.

### **About Me Section**

* Personal introduction and the purpose behind the blog.  
* Highlights travel goals and tech-based ideas.

### **Contact Section**

* Contact form for users to get in touch.  
* Social media links with interactive icons.

### **Newsletter Subscription (Integrated Beyond Assignment Requirements)**

* Form to subscribe to travel updates.

### **Footer Section**

* Copyright information and additional navigation links.  
* Button for navigating to the top of the page.

---

## **Folder Structure**

SravanTravelBlog/  
├── index.html      \# Main HTML file  
├── index.css        \# Stylesheet  
├── images/          \# Folder for images  
├── videos/          \# Folder for background and blog videos  
└── fonts/           \# Folder for custom fonts

---

## 

## **Design Choices**

### **Color Palette**

* **Light Mode:** Light and pastel shades for a clean and inviting look.  
* **Dark Mode:** Dark grey and white shades for a modern look.

### **Font Selection**

* Used custom fonts: **Futura Bold** for titles and a lighter font for the rest of the page.

### **Layout Techniques**

* **CSS Grid** and **Flexbox** for structured and responsive design.

### **Interactive Elements**

* Hover effects on navigation links and blog images,blogs  
* Video backgrounds and embedded media for dynamic content.

### **Animations**

* Smooth scaling effects and hover interactions.

### **Responsiveness**

* Used media queries to ensure responsiveness across various screen sizes.  
* By default, CSS styles are applied for mobile devices.  
* Added media queries for:  
  * **min-width: 768px** for tablets  
  * **min-width: 1024px** for large screens  
* Styled font sizes, gaps, and grid layouts for blogs and etc accordingly.

---

## **Challenges Faced**

### **Responsive Design**

* **Challenge:** Ensuring that all sections adapt seamlessly across screen sizes.  
* **Solution:** Used CSS Grid, Flexbox, and media queries.

### **Dropdown Menu Challenge**

* **Challenge:** Properly displaying the dropdown submenu on hover.  
* **Solution:** Placed the submenu within the Blogs nav list item and used `position: absolute; top: 100%` in CSS.

### **Dark/Light Theme Implementation**

* **Challenge:** Controlling the theme and changing background and text colors for every section.  
* **Solution:** Implemented a checkbox label and used the CSS selector `:has(input:checked)` to handle color and background changes for all sections.

---



