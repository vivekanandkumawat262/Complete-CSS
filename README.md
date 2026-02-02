# Airbnb-Style Search Bar (Frontend Module)

## 📌 Overview
Today, I built an **Airbnb-style interactive search bar** using **HTML, CSS, and JavaScript** as part of my larger **custom booking marketplace** project.

This component focuses on clean UI, professional UX behavior, and reusable structure, similar to real-world booking platforms like Airbnb.

---

## ✨ Features Implemented

- Fully responsive **search bar layout**
- Individual search sections:
  - Where (destination)
  - Check-in (date)
  - Check-out (date)
  - Who (guests)
- **Dropdown selection** for destinations
- Only **one dropdown open at a time**
- Dropdown closes automatically when clicking outside
- Input value updates on option selection
- Smooth hover effects and dividers
- Airbnb-style rounded design and search button

---

## 🧠 Key Concepts Used

- HTML semantic structure
- CSS Flexbox for layout
- CSS hover effects and border-radius styling
- JavaScript DOM manipulation
- Event handling (`click`)
- `closest()` for DOM traversal
- Dropdown toggle logic
- Click-outside detection pattern

---

## 🗂️ Project Structure
```bash
booking-marketplace/
│
├── pages
├── css
└── dashboard
```

---

## ⚙️ JavaScript Logic Summary

- `toggleDropdown(item)`
  - Opens the clicked dropdown
  - Closes all other open dropdowns
- `selectOption(el)`
  - Sets selected option text into the input field
  - Closes the dropdown
- Global click listener
  - Detects clicks outside `.search-item`
  - Closes all dropdowns for clean UX

---

## 🎯 Learning Outcome

- Understood how real booking platforms handle dropdowns
- Practiced clean DOM traversal and event handling
- Built reusable UI components with scalability in mind
- Strengthened frontend fundamentals for full-stack development

---

## 🚀 Next Steps

- Add guest counter (+ / −)
- Integrate calendar picker
- Improve mobile responsiveness
- Convert to React component
- Connect backend APIs for search functionality

---

## 👤 Author
**Vivek Kumawat**  
Building in public 🚀 | Learning full-stack development | Freelancing journey
