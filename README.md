# HNG Stage 1B - Profile Card

## 📌 Overview
This project is part of the HNG Internship Stage 1B task.  
It is a responsive and accessible Profile Card built using **HTML, CSS, and Vanilla JavaScript**.

The goal is to demonstrate:
- Semantic HTML structure
- Accessibility best practices
- Responsive design
- Dynamic JavaScript rendering (current time in milliseconds)
- Proper use of `data-testid` attributes for automated testing

---

## 🚀 Live Demo
https://hng-stage-1-b-vert.vercel.app/



## 🧩 Features

### 👤 Profile Card Includes:
- User avatar image
- Full name display
- Short biography section
- Current time in milliseconds (live or on render)
- Social media links (clickable and keyboard accessible)
- Hobbies list
- Dislikes list

---

## ⚙️ Functional Requirements

- Displays current time using `Date.now()`
- Time updates dynamically (if implemented with interval)
- All required elements include correct `data-testid` attributes
- Social links open in a new tab safely using:
  - `target="_blank"`
  - `rel="noopener noreferrer"`

---

## 🛠️ Built With
- HTML5 (Semantic Elements)
- CSS3 (Flexbox / Grid)
- Vanilla JavaScript (DOM manipulation, Date API)

---

## ♿ Accessibility Features
- Proper semantic HTML (`article`, `section`, `nav`, `figure`)
- Meaningful `alt` text for avatar image
- Keyboard navigable links
- Focus styles for interactive elements
- ARIA support where necessary
- `data-testid` attributes for automated testing

---

## 📱 Responsiveness
The profile card is fully responsive:
- Mobile (320px): stacked layout
- Tablet (768px): balanced layout
- Desktop (1024px+): side-by-side layout

No horizontal scrolling or overflow issues at any screen size.

---

## 🧪 Test IDs Included

All required test IDs are implemented exactly as specified:

- test-profile-card
- test-user-name
- test-user-bio
- test-user-time
- test-user-avatar
- test-user-social-links
- test-user-social-twitter (and other platforms if used)
- test-user-hobbies
- test-user-dislikes

---

## 📌 How to Run Locally

1. Clone the repository:
```bash
git clone https://github.com/your-username/your-repo-name.git