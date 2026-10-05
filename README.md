# Priyansh Khandelwal | Personal Portfolio

A bold, colorful personal portfolio website built from scratch using only HTML and CSS.

## 📖 About the Project

This is my personal portfolio, where I introduce myself and show my work. I'm a Computer Science undergrad at BITS Pilani, and I wanted a site that feels energetic instead of a generic template. The whole thing is hand-coded with no frameworks or libraries.

The page has a navbar with my email and availability status, a scrolling marquee strip, a hero section with my name and a short bio, a "Selected Works" section, and a footer with a call-to-action and social links.

## 🛠️ Technologies Used

- **HTML5**: semantic page structure (`header`, `main`, `section`, `article`, `footer`)
- **CSS3**: all styling, animations and responsive layout
- **Google Fonts**: [Outfit](https://fonts.google.com/specimen/Outfit) (weights 300, 600, 900), imported with `@import`

No JavaScript is used in this project.

## ✨ Features

- Navbar with a clickable email button and a pulsing "Available for hire" indicator
- Infinite scrolling marquee strip
- Large hero name that switches to an outlined style on hover
- Bio card with highlighted keywords and a few quick facts about me
- "Selected Works" section with two project cards
- Footer with a big "Let's Build Something." email link, plus GitHub and LinkedIn buttons
- Custom text selection color

## 🎨 Design / UI Details

The design is inspired by a neo-brutalist style: thick borders, hard offset shadows and flat, bright colors.

**Color palette**

| Color | Hex |
|-------|-----|
| Background (cream) | `#F4F0EA` |
| Text / borders (black) | `#1A1A1A` |
| Accent (lime) | `#D4FF00` |
| Accent (blue) | `#0055FF` |
| Accent (pink) | `#FF007F` |

**CSS features used**

- **Animations (`@keyframes`)**: a pulsing availability dot and the infinitely scrolling marquee text
- **Transitions**: smooth movement and color changes on interactive elements
- **Hover effects**:
  - Email button fills in and lifts with a colored shadow
  - Name words turn into outlined text (`-webkit-text-stroke`)
  - Highlighted words (`<mark>`) expand to fill the full text height
  - Quick-fact tags and project cards lift up, and the second project card turns pink
  - Footer CTA and social buttons shift and change color
- **Transforms**: the marquee strip and bio card are slightly rotated for a playful look
- **Layout**: Flexbox for the navbar, bio card and footer, and CSS Grid for the project cards
- **Viewport units** (`vw`) for the large, scalable headings

## 📱 Responsive Design

The layout adapts using media queries:

- **Up to 900px**: the project cards stack into a single column, the bio card top section and footer switch to a vertical layout, and the headings are adjusted
- **Up to 600px**: the navbar stacks vertically, the marquee and bio card rotation is removed, and spacing and font sizes are reduced for small screens

## 📁 Project Structure

```
portfolio/
├── index.html
├── style.css
└── README.md
```

## 🚀 How to Run Locally

1. Download or clone the repository:
```bash
   git clone <your-repository-url>
```
2. Open the project folder.
3. Double-click `index.html` to open it in your browser.

Optionally, you can use the **Live Server** extension in VS Code to see changes instantly while editing.

> **Note:** An internet connection is needed to load the Outfit font from Google Fonts. Without it, the site falls back to a default sans-serif font.

## 📬 Contact

- 📧 Email: [priyanshkhandelwal4230@gmail.com](mailto:priyanshkhandelwal4230@gmail.com)
- 💻 GitHub: [priyanshkhandelwal4230-coder](https://github.com/priyanshkhandelwal4230-coder)
- 🔗 LinkedIn: [Priyansh Khandelwal](https://www.linkedin.com/in/priyansh-khandelwal-13051a426/)

## 🔮 Future Improvements

- Add more projects to the "Selected Works" section as I build them
- Link each project card to its live demo and GitHub repository
- Add screenshots of the site to this README
- Add subtle JavaScript interactions
- Improve accessibility, such as reduced-motion support for the animations
