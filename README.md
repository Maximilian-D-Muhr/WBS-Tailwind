# WBS Tailwind Project

![Project Status](https://img.shields.io/badge/status-in%20development-yellow)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-v3-38B2AC?logo=tailwind-css)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)

## 📋 Project Description

A modern, responsive website built with **Tailwind CSS** following a mobile-first design approach. This project demonstrates best practices in semantic HTML structure, utility-first CSS, and collaborative development through GitHub.

## 🎯 Project Requirements

This project fulfills the following functional requirements:

- ✅ **FR001** - Figma Wireframe Creation
- ✅ **FR002** - Public GitHub Repository
- ✅ **FR003** - GitHub Pages Deployment
- ✅ **FR004** - Semantic HTML Structure
- ✅ **FR005** - Tailwind CSS Integration (via CDN)
- ✅ **FR006** - Mobile-First Design
- ✅ **FR007** - Incremental Development with Pull Requests
- ✅ **FR008** - Design Personalisation
- ✅ **FR009** - Single Layout System (Flexbox/Grid)

## 🚀 Live Demo

🌐 **[View Live Site](https://maximilian-d-muhr.github.io/WBS-Tailwind/)**

## 🎨 Design

📐 **[View Figma Wireframe](#)** *(Link to be added)*

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first CSS framework
- **GitHub Pages** - Hosting and deployment
- **Git** - Version control

## 📁 Project Structure

```
WBS-Tailwind/
├── index.html          # Main HTML file
├── assets/             # Images, icons, and other assets
│   ├── images/
│   └── icons/
├── README.md           # Project documentation
└── .gitignore         # Git ignore rules
```

## 🔄 Pull Request Workflow

We follow a strict PR-based workflow to maintain code quality and enable collaboration:

### 1. Create a Feature Branch

```bash
# Make sure you're on the main branch and it's up to date
git checkout main
git pull origin main

# Create a new feature branch
git checkout -b feature/your-feature-name
```

### 2. Make Your Changes

- Write semantic HTML
- Use Tailwind CSS utility classes
- Follow mobile-first approach
- Test on multiple screen sizes

### 3. Commit Your Changes

```bash
# Stage your changes
git add .

# Commit with a descriptive message
git commit -m "Add: brief description of your changes"
```

**Commit Message Conventions:**
- `Add:` - New feature or file
- `Update:` - Modifications to existing features
- `Fix:` - Bug fixes
- `Refactor:` - Code restructuring
- `Docs:` - Documentation changes

### 4. Push to GitHub

```bash
# Push your branch to remote
git push -u origin feature/your-feature-name
```

### 5. Create a Pull Request

1. Go to the repository on GitHub
2. Click **"Pull requests"** → **"New pull request"**
3. Select your feature branch as the source
4. Select `main` as the target
5. Fill in the PR template:
   - **Title**: Clear, concise description
   - **Description**: What changed and why
   - **Screenshots**: If UI changes were made
6. Request review from team members
7. Wait for approval before merging

### 6. Code Review Process

- At least **one approval** required before merging
- Address all review comments
- Keep discussions constructive and professional
- Make requested changes and push updates

### 7. Merge and Deploy

- Once approved, merge the PR into `main`
- Delete the feature branch after merging
- GitHub Pages will automatically deploy the changes

## 💻 Local Development

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code recommended)
- Git installed

### Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/Maximilian-D-Muhr/WBS-Tailwind.git
   cd WBS-Tailwind
   ```

2. **Open the project**
   ```bash
   # Open in VS Code
   code .

   # Or open index.html directly in your browser
   open index.html
   ```

3. **Start developing**
   - Make changes to HTML files
   - Use Tailwind CSS utility classes
   - Test responsiveness using browser DevTools
   - Follow mobile-first approach

## 📱 Responsive Breakpoints

Following Tailwind CSS default breakpoints:

| Breakpoint | Min Width | Target Devices |
|------------|-----------|----------------|
| `sm`       | 640px     | Large phones, small tablets |
| `md`       | 768px     | Tablets |
| `lg`       | 1024px    | Laptops |
| `xl`       | 1280px    | Desktops |
| `2xl`      | 1536px    | Large desktops |

## ✅ Testing Checklist

Before creating a PR, ensure:

- [ ] Code validates with W3C HTML Validator
- [ ] Tested on mobile devices (320px - 768px)
- [ ] Tested on tablets (768px - 1024px)
- [ ] Tested on desktop (1024px+)
- [ ] All links work correctly
- [ ] Images load properly
- [ ] Semantic HTML is used throughout
- [ ] Tailwind classes follow mobile-first approach
- [ ] No console errors in browser DevTools

## 👥 Team Members

- Team Member 1
- Team Member 2
- Team Member 3

## 📚 Resources

- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [GitHub Pages Guide](https://pages.github.com/)
- [Semantic HTML Reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
- [Git Workflow Guide](https://guides.github.com/introduction/flow/)

## 📄 License

This project is created for educational purposes as part of the WBS Coding School curriculum.

---

**Built with ❤️ using Tailwind CSS**
