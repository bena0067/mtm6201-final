# mtm6201-final

Figma Link layout: https://acrobat.adobe.com/id/urn:aaid:sc:US:ce1eeb67-30f2-46cf-b4cb-c88ff4c3eb83



# FurEver Home – Final Web Development Project  
_Web Development II – MTM6201_

## Overview  
FurEver Home is a three-page responsive website built using Bootstrap, custom CSS, and assets designed in Figma.  
The site focuses on helping users adopt pets, join campaigns, volunteer, or donate.  
All layouts (desktop, tablet, and mobile) were fully planned in Figma and then converted into real HTML/CSS/Bootstrap pages.

---

## My Development Process  

### 1. **Planning & Design**  
- Started by building complete wireframes and high-fidelity mockups in Figma.  
- Created layouts for desktop, iPad, and mobile following a consistent visual style.  
- Exported required assets and organized them before beginning development.

### 2. **Building the Structure**  
- Set up a new GitHub repository (`mtm6201-final`) following naming conventions.  
- Created three main pages: **Home**, **Campaigns**, and **Donate**.  
- Used semantic HTML5, ARIA attributes, and proper structure for accessibility.

### 3. **Styling & Frameworks**  
- Used **Bootstrap 5** to create a responsive grid and navigation system.  
- Overrode Bootstrap using **CSS variables**, custom buttons, spacing, cards, and layout.  
- Added an additional CSS animation library (Animate.css).

### 4. **Responsive Design**  
- Ensured all layouts match the original Figma mockups using media queries.  
- Adjusted spacing, font sizes, images, and navigation behavior for:  
  - Desktop  
  - Tablet (1024px / 1366px)  
  - Mobile (<768px)  

### 5. **Interactivity & Finishing Touches**  
- Created working navigation links between pages.  
- Added jump links (“Go Back Up”).  
- Added dropdown menus, interactive buttons, and hover states.  
- Optimized all images using `object-fit`, `max-width: 100%`, and `<picture>` where needed.

---

## Challenges & How I Overcame Them  

### **1. Responsive Navigation (Mobile & iPad)**
The biggest difficulty was ensuring the navigation matched the Figma layout on all screen sizes.  
Bootstrap’s default behavior caused alignment issues, but I fixed them by:  
- Using custom media queries  
- Repositioning the navbar toggler  
- Adjusting flexbox alignment for each breakpoint  

### **2. Background Images Overflowing on Tablet/Mobile**  
Some hero images and sections would overflow the frame.  
I solved this by using:  
- `background-size: cover;`  
- `background-position: center;`  
- Specific breakpoint adjustments to reduce image height  

### **3. Form Overflow on Tablet/Mobile**  
The donate form was too wide on iPad.  
Solution:  
- Added custom max-width rules  
- Wrapped form in Bootstrap column constraints  
- Adjusted padding per breakpoint  

---

## What I Learned  

- How to convert a complete Figma design into a fully functioning website  
- How to customize Bootstrap using CSS variables and overrides  
- How to handle responsive design across desktop, tablet, and mobile  
- How to structure a multi-page website with consistent components  
- Increased understanding of accessibility, semantic HTML, and UX considerations  

---

## Assets, Frameworks & External Resources  

### **Frameworks & Libraries**
- **Bootstrap 5.3.3**  
- **Animate.css** (CSS animation library)  

### **Fonts**
- Google Fonts: **Playfair Display**, **Poppins**

### **Images & Icons**
- All primary images were created or edited by me.
-some images were AI generated  
- If any stock images were used, they came from free-to-use resources such as:  
  - Unsplash  
  - Icons8 (for trust/security icons)  

### **Design Tools**
- Figma (all mockups and layouts)  
- VS Code (development)  
- GitHub Pages (deployment)

---

## Author  
**Benadjaoud Ahcene**  
Web Development II – Algonquin College  
