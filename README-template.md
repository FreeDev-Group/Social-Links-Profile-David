# Profile Card Project

##  Project Overview
This project is a **Profile Card UI component**, inspired by the Frontend Mentor design.  

The goal was to **enhance the interface** by adding **hover effects on social links**, improving spacing, adjusting typography, and creating a **responsive design** for both mobile and desktop.

This project also documents the **learning process**, including how **AI assisted** during development.

---

##  Features
- Interactive **hover effects** on social links  
- Improved **spacing and layout**  
- Optimized **button padding and font sizes**  
- Fully **responsive design** for mobile & desktop  
- Smooth and tested **user interactions**

---

##  Technologies Used
- **HTML5** – structure of the profile card  
- **CSS3** – styling, hover effects, Flexbox/Grid layout  
- **Responsive Design** – mobile-first approach  

---

##  How AI Assisted This Project
AI helped me to:  

- Suggest **design improvements** and hover interactions  
- Optimize and debug **HTML & CSS**  
- Write a **clear and professional README**  
- Learn **best practices** in front-end design  

AI support allowed me to **work faster** and **deliver a polished UI**.

---

## 📂 Project structure 
/Index.html-main profile card page 
/style/-images, icons, GIFs 
README.md - project documentation 

## HTML
<div class="profile-card">
  <img src="./assets/avatar.jpg" alt="Profile Avatar" class="avatar">
  <h1>Jessica Randal</h1>
  <p>Frontend Developer</p>
  <div class="social-links">
    <a href="https://github.com/David-max-tech" class="social-link">GitHub</a>
    <a href="https://linkedin.com/in/David-mumeme" class="social-link">LinkedIn</a>
  </div>
</div>

## CSS
.social-link:hover {
  transform: scale(1.1);
  transition: 0.3s ease;
  filter: brightness(1.2);
}

