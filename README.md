# BAQA Schools - Student Exhibition Website

Welcome to the BAQA Schools Student Exhibition Website! This is a student portfolio website showcasing academic achievements, skills, and student information.

## 📋 Project Overview

This website is a student exhibition platform for BAQA Schools that features:
- Student profiles and achievements
- Course information and teachers
- Student skills (personal and professional)
- Student registration form
- Media gallery (videos and audio)
- Contact information section

## 🚀 Quick Start

### Local Development
1. Clone the repository:
```bash
git clone https://github.com/BAQA-CREATOR/school-website.git
cd school-website
```

2. Open the `index.html` file in your web browser or use a local server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (with http-server package)
npx http-server
```

3. Visit `http://localhost:8000` in your browser.

## 📁 Project Structure

```
.
├── index.html              # Main page (consolidated all sections)
├── README.md              # This file
├── .gitignore             # Git ignore rules
└── .github/
    └── workflows/
        └── deploy-pages.yml  # GitHub Pages deployment workflow
```

## 🎨 Features

- **Responsive Design**: Mobile-friendly layout
- **Navigation Menu**: Easy access to all sections
- **Student Profile**: Personal information and photos
- **Courses Table**: Academic courses and teachers
- **Skills Section**: Personal and professional skills
- **Registration Form**: Student enrollment form
- **Media Gallery**: Video and audio content
- **Contact Information**: Student contact details

## 🔧 Technology Stack

- **HTML5**: Semantic markup
- **CSS3**: Styling and layout
- **JavaScript**: (Can be added for interactivity)

## 📱 Sections

1. **Home**: Welcome section and student profile
2. **About**: Student background and ambitions
3. **Skills**: Personal and professional capabilities
4. **Courses**: Academic subjects and teachers
5. **Media**: Video and audio content
6. **Registration**: Student enrollment form
7. **Contact**: Contact information form

## 🌐 Deployment to GitHub Pages

### Automatic Setup

The repository includes a GitHub Actions workflow (`.github/workflows/deploy-pages.yml`) that automatically deploys to GitHub Pages on every push to the `main` branch.

### Manual GitHub Pages Setup

1. Go to your repository settings: `https://github.com/BAQA-CREATOR/school-website/settings`
2. Navigate to **Pages** section (left sidebar)
3. Under "Source", select **Deploy from a branch**
4. Select `main` branch and `/root` folder
5. Save the settings
6. The site will be published at: `https://BAQA-CREATOR.github.io/school-website/`

### Workflow Details

The automatic deployment will:
- Trigger on every push to `main` branch
- Automatically build and deploy changes
- Publish the website to GitHub Pages
- Provide deployment status checks

### Alternative Hosting Options
- **Vercel**: Connect repository and auto-deploy
- **Netlify**: Connect repository and auto-deploy
- **Firebase Hosting**: Manual or automatic deployment

## ✏️ Customization

### Update Student Information
Edit `index.html` and modify:
- Student name and personal details in the home section
- Profile image path (currently: `WIN_20260823_04_49_16_Pro.jpg`)
- Course information in the courses table
- Skills list under the skills section
- Contact details in the footer

### Change Styles
Modify the `<style>` section in `index.html` to:
- Change color scheme
- Adjust layouts and spacing
- Update typography and fonts
- Customize responsive breakpoints

### Add Media
Place media files (images, videos, audio) in the project root and reference them:
```html
<img src="your-image.jpg" alt="Description" width="400px">
<video src="your-video.mp4" controls></video>
<audio src="your-audio.m4a" controls></audio>
```

## 🤝 Contributing

To contribute to this project:
1. Create a new branch: `git checkout -b feature/your-feature`
2. Make your changes
3. Commit: `git commit -m "Add your message"`
4. Push: `git push origin feature/your-feature`
5. Create a Pull Request

## 📊 File Structure After Setup

```
school-website/
├── index.html              # Main website file (all sections included)
├── README.md              # Project documentation
├── .gitignore             # Git ignore file
├── .github/
│   └── workflows/
│       └── deploy-pages.yml  # GitHub Pages deployment
├── WIN_20260823_04_49_16_Pro.jpg  # Student profile image
├── WIN_20260825_01_18_58_Pro.mp4  # Student video
└── Recording (12).m4a     # Student audio
```

## 📧 Support

For questions or issues, please contact BAQA Schools administration or open an issue in the repository.

## 📄 License

This project is maintained by BAQA Schools. All rights reserved.

## 🎓 About BAQA Schools

BAQA Schools is dedicated to enhancing lives and shaping the future through quality education.

**School Motto**: "...enhancing lives, shaping the future..."

---

**Last Updated**: August 31, 2026
**Status**: Ready for GitHub Pages Deployment
**Live Website**: https://BAQA-CREATOR.github.io/school-website/