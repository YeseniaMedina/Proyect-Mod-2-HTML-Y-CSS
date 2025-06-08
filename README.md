# Every Detail Matters - Responsive Layout Using Flexbox & Grid

This project is a responsive landing page focused on demostrate proper use of CSS Flexbox and Grid.

---

## 🌐 Technologies Used

- HTML5
- CSS3
- Flexbox & Grid layout systems
- CSS Media Queries
- CSS Custom Properties (Variables)
- Custom Fonts with `@font-face`

---

## 🎯 Project Focus

The main objective is to apply "Flexbox and Grid appropriately" to create a responsive design. The layout is mobile-first and adapt in the same way to desktop sizes.

### Flexbox is used for:

- Center and stack content in column and row.
- Align elements within containers (like `.hero-text`)

### Grid is used for:

- Do a gallery images in both mobile and desktop views
- Creating a two-column layout in desktop view (text and images)

---

project-root/
│
├── index.html
├── css/
│ ├── reset.css # Reset default browser styles
│ ├── variables.css # Font and color variables
│ ├── fonts.css # Custom fonts
│ └── main.css # Main layout styles using Flex & Grid
├── images/
│ ├── hero1.avif
│ ├── hero2.avif
│ └── hero3.avif
└── README.md

---

## Responsive Design

Built with a mobile-first approach, then expanded using a `min-width: 1024px` media query.

### Mobile View

- Flexbox for vertical stacking and alignment in columns and rows (in the second part)
- Grid used to arrange 3 images:
  - 1 large image (spanning two columns)
  - 2 smaller images side by side

### 💻 Desktop View

- Grid used for full-page layout:
  - Left vertical text (`DETAILS`)
  - Right column with centered text (Flexbox) and an image gallery (Grid)
    -Flex used for align the cards-container and card-content

---

## ✅ Best Practices Followed

- Clean semantic HTML structure
- Proper Flexbox for alignment and spacing.
- Grid for layout
- Mobile-first responsive design
- Use some selectors.
- Use of `rem` and `em` for scalable spacing and typography

👨‍💻 Author
Name: Yesenia Medina

NOTE:

This project was created as part of an intermediate HTML & CSS course, focusing on mastering Flexbox and Grid to build scalable and professional layouts.
