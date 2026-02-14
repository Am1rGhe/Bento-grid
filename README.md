# Bento Grid - Social Media Management Showcase

A modern, responsive bento grid layout showcasing a social media management tool powered by AI. This project demonstrates a visually appealing card-based design using CSS Grid to create an asymmetric, magazine-style layout.

![Bento Grid Layout](https://img.shields.io/badge/Layout-Bento%20Grid-purple) ![Responsive](https://img.shields.io/badge/Responsive-Yes-green) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Design Details](#design-details)
- [Responsive Design](#responsive-design)
- [Color Palette](#color-palette)
- [Typography](#typography)

## 🎯 Overview

This project is a Frontend Mentor challenge that creates a bento grid layout to showcase a social media management platform. The design features seven distinct content boxes arranged in an asymmetric grid pattern, highlighting key features like AI-powered content creation, scheduling, multi-platform management, and audience growth.

## ✨ Features

- **Asymmetric Bento Grid Layout**: Seven content boxes arranged in a visually interesting grid pattern
- **Fully Responsive**: Optimized for desktop (1440px), tablet (768px), and mobile (375px) screens
- **Modern Design**: Clean, colorful design with purple and yellow color scheme
- **Semantic HTML**: Well-structured markup for accessibility
- **CSS Grid**: Advanced grid layout with custom grid areas
- **Custom Typography**: DM Sans font family with multiple weight variations

## 🛠 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: 
  - CSS Grid for layout
  - CSS Custom Properties (Variables) for theming
  - Flexbox for component alignment
  - Media queries for responsive design
- **Google Fonts**: DM Sans font family
- **WebP Images**: Optimized image format for better performance

## 📁 Project Structure

```
Bento-grid/
├── assets/
│   ├── fonts/
│   │   ├── DMSans-VariableFont_opsz,wght.ttf
│   │   ├── DMSans-Italic-VariableFont_opsz,wght.ttf
│   │   └── static/
│   └── images/
│       ├── favicon-32x32.png
│       ├── illustration-ai-content.webp
│       ├── illustration-audience-growth.webp
│       ├── illustration-consistent-schedule.webp
│       ├── illustration-create-post.webp
│       ├── illustration-five-stars.webp
│       ├── illustration-grow-followers.webp
│       ├── illustration-multiple-platforms.webp
│       └── illustration-schedule-posts.webp
├── index.html
├── style.css
├── style-guide.md
└── README.md
```

## 🚀 Getting Started

### Prerequisites

No build tools or dependencies required! This is a pure HTML/CSS project.

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser
3. That's it! No build process needed.

### Viewing the Project

Simply open `index.html` in any modern web browser. For the best experience, use:
- Chrome (recommended)
- Firefox
- Safari
- Edge

## 🎨 Design Details

### Grid Layout

The bento grid consists of 7 content boxes:

- **Box 1**: "Create and schedule content quicker" - Yellow background
- **Box 2**: Main hero section - "Social Media 10x Faster with AI" - Purple background
- **Box 3**: "Schedule to social media" - Light purple background
- **Box 4**: "Write your content using AI" - Yellow background
- **Box 5**: Two-column section with multiple accounts and consistent schedule features
- **Box 6**: ">56% faster audience growth" - White background
- **Box 7**: "Grow followers with non-stop content" - Purple background

### Grid Areas (Desktop)

```
box1 | box2 | box2 | box3
box1 | box2 | box2 | box3
box1 | box2 | box2 | box3
box1 | box5 | box5 | box3
box4 | box5 | box5 | box3
box4 | box5 | box5 | box3
box4 | box6 | box7 | box7
box4 | box6 | box7 | box7
```

## 📱 Responsive Design

The layout adapts to different screen sizes:

### Desktop (1440px+)
- 4-column grid layout
- Full asymmetric bento grid pattern

### Tablet (≤768px)
- 2-column grid layout
- Reorganized grid areas for better mobile viewing

### Mobile (≤375px)
- Single-column layout
- Stacked content boxes
- Optimized spacing and image sizes

## 🎨 Color Palette

The design uses a carefully selected color scheme:

- **Purple 100**: `hsl(254, 88%, 90%)` - Light purple background
- **Purple 500**: `hsl(256, 67%, 59%)` - Primary purple
- **Yellow 100**: `hsl(31, 66%, 91%)` - Light yellow background
- **Yellow 500**: `hsl(39, 100%, 71%)` - Primary yellow
- **Black**: `hsl(0, 0%, 7%)` - Text color
- **White**: `hsl(0, 0%, 100%)` - Background and text

## 📝 Typography

### Font Family
- **DM Sans** from Google Fonts
- Weights: 400 (Regular), 500 (Medium)
- Variable font support for flexible sizing

### Text Presets

The project uses CSS custom properties for consistent typography:

- **Preset 1**: 62px, weight 500, line-height 0.935
- **Preset 2**: 40px, weight 500, line-height 0.9
- **Preset 3**: 32px, weight 500, line-height 0.875
- **Preset 4**: 18px, weight 400, line-height 0.111

## 🎯 Key Features Highlighted

1. **AI-Powered Content Creation**: Generate content faster with AI
2. **Smart Scheduling**: Optimize post timings for maximum engagement
3. **Multi-Platform Management**: Manage multiple accounts and platforms
4. **Consistent Posting**: Maintain a regular posting schedule
5. **Audience Growth**: Achieve 56% faster audience growth
6. **Non-Stop Content**: Grow followers with continuous content

## 📄 License

This project is a Frontend Mentor challenge. Feel free to use this code for learning purposes.

## 🙏 Acknowledgments

- **Frontend Mentor** for providing the design challenge
- **Google Fonts** for the DM Sans font family
- Design inspiration from modern bento grid layouts

---

**Note**: This is a Frontend Mentor challenge project. The design and requirements are provided by Frontend Mentor, and this implementation is a solution to that challenge.
