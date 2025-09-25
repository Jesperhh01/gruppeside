# Gruppe 12 - Bachelor Group Portfolio

A modern, responsive portfolio website showcasing our bachelor group of 6 talented developers and designers from UiA (University of Agder).

## 🚀 About Our Team

**ShiftOps** - Gruppe 12 is a diverse team of developers and designers with different ages, backgrounds, and skill sets. We collaborate effectively and each member brings unique expertise to our projects.

### Team Members

- **[Jesper Heidenberg Hansen](src/data/members.js)** - Full Stack Developer
- **[Adrian van Mallinckrodt Øien](src/data/members.js)** - Team Leader & Scrum Master  
- **[Liv Gudrun Staaland](src/data/members.js)** - UI/UX Designer & Frontend Developer
- **[Ole Hagberg](src/data/members.js)** - Full Stack Developer
- **[Camilla Uglem Remøy](src/data/members.js)** - Database Administrator & Developer
- **[Mathias Thorsell](src/data/members.js)** - Full Stack Developer

## 🛠 Tech Stack

- **Framework**: [Astro](https://astro.build) 5.13.11
- **Styling**: CSS with modern gradients and responsive design
- **Fonts**: JetBrains Mono, system fonts
- **Deployment**: GitHub Pages
- **Development**: TypeScript support

## 🏗 Project Structure

```
src/
├── components/
│   ├── MemberCard.astro     # Individual member cards
│   └── Welcome.astro        # Welcome component
├── data/
│   └── members.js           # Team member data
├── layouts/
│   └── Layout.astro         # Main layout template
├── pages/
│   ├── index.astro          # Homepage
│   └── [member].astro       # Dynamic member pages
└── styles/
    └── global.css           # Global styles
```

## 🚀 Getting Started

### Prerequisites
- Node.js (version 18 or higher)
- npm

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Jesperhh01/gruppeside.git
cd gruppeside
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and visit `http://localhost:4321`

## 📜 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally

## 🌐 Deployment

The site is automatically deployed to GitHub Pages via GitHub Actions when changes are pushed to the main branch.

**Live site**: https://jesperhh01.github.io/gruppeside/

## 📁 Adding Team Member Images

Place member photos in `public/images/` with these filenames:
- `jesper.jpg`
- `adrian.jpg` 
- `liv.jpg`
- `ole.jpg`
- `camilla.jpg`
- `mathias.jpg`

**Image specifications**:
- Format: JPG or PNG
- Size: 400x400px (square aspect ratio)
- File size: < 500KB for optimal loading

## 🎨 Features

- **Responsive Design** - Optimized for all device sizes
- **Dynamic Member Pages** - Individual pages for each team member
- **Modern UI** - Gradient backgrounds, smooth animations
- **Social Links** - Email, LinkedIn, GitHub, and portfolio links
- **Skills Display** - Visual skill tags for each member
- **SEO Friendly** - Proper meta tags and semantic HTML

## 🤝 Our Philosophy

As a group, we aim high and strive to deliver excellent results. We see this as an opportunity to build connections, explore possibilities, and demonstrate our collective skills in software development and design.

---

Built with ❤️ by Gruppe 12 using [Astro](https://astro.build)