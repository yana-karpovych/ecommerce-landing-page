# Bang & Olufsen - Responsive Landing Page for Audio Products

This project is a responsive landing page for a premium audio brand (B&O). It is designed to showcase high-end audio products, highlight key categories, and provide users with a clear overview of recommended items and brand information. The website focuses on clean UI, modern layout, and adaptive design across all devices.

## Experience the live website:
[B&O Landing Page Demo](https://yana-karpovych.github.io/ecommerce-landing-page/)

## Design Reference:
[B&O](https://www.figma.com/design/DtkQmQ797hk0nI4KfMi2Uq/BOSE-New-Version?node-id=6817-212&t=MskwNhVCsr1vgUzc-0)

## Technologies Used

Core
- HTML5 (semantic markup)
- SCSS (modular styles, BEM methodology)
- JavaScript (ES6+) used for simple form interaction handling

UI / Layout
- Flexbox
- CSS Grid
- Responsive Design (media queries)
- BEM naming convention

Assets & Optimization
- Responsive images (<picture>, srcset)
- SVG icons

Build Tools / Development
- Parcel (bundler)
- Node.js / npm

Code Quality
- ESLint
- Stylelint
- Prettier

## How to run this project locally:

1. Clone the repository:
git clone https://github.com/yana-karpovych/ecommerce-landing-page.git
cd ecommerce-landing-page

2. Install dependencies:
npm install

3. Run the project locally:
npm start

## Features

Responsive Images
- Implemented responsive image loading using <picture> and srcset to serve optimized images for mobile, tablet, and desktop screen sizes.

Interactive Navigation
- Navigation links use anchor-based navigation for smooth scrolling between page sections. The sidebar menu provides quick access to key sections of the page.

Contact Actions (Semantic Links)
- Implemented semantic link behavior:
- tel: links initiate phone calls on supported devices
- mailto: links open the default email client with prefilled recipient
- External location links open Google Maps with predefined coordinates

Section-based Architecture
- Page is structured into independent semantic sections (header, recommended products, categories, about, contact) with clear hierarchy and reusable layout blocks.

Mobile-first UI Behavior
- Layout is built with responsive breakpoints ensuring proper adaptation across different screen widths, including mobile-first optimization.
