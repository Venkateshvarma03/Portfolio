# Portfolio Website

Personal portfolio website showcasing projects, skills, and achievements.

## 🚀 Deployment on Render (100% FREE Static Site)

This project is configured to be deployed as a **Static Site** on Render, which is **completely FREE** with no costs whatsoever!

### Prerequisites

- A GitHub account
- A Render account (sign up at https://render.com - completely free!)

### Deployment Steps

1. **Push your code to GitHub**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin <your-github-repo-url>
   git push -u origin main
   ```

2. **Create a new Static Site on Render**
   - Log in to your Render dashboard
   - Click "New +" and select **"Static Site"** (not Web Service!)
   - Connect your GitHub repository: `Venkateshvarma03/Portfolio`
   - Branch: `main`

3. **Configure the Static Site**
   - Name: `portfolio` (or your preferred name)
   - Build Command: **Leave empty** (no build needed for static HTML)
   - Publish Directory: **Leave empty** (serves from root)
   - Click "Create Static Site"

4. **Deploy**
   - Render will automatically deploy your static site
   - You'll get a URL like `https://portfolio.onrender.com`
   - ✅ **Completely FREE** - no credit card required!

### Why Static Site instead of Web Service?

- **Static Sites are 100% FREE** on Render (no limits, no credits)
- No server needed for your HTML/CSS/JS portfolio
- Faster loading times
- Perfect for portfolios, landing pages, and static websites
- Web Services on free tier have usage limits and spin down after inactivity

## 🛠️ Local Development

To view the project locally:

```bash
# Simply open index.html in your browser
# Or use any local server like:
python -m http.server 8000
# Then open http://localhost:8000
```

## 📁 Project Structure

```
portfolio/
├── images/          # Images and assets
├── index.html       # Main HTML file
├── style.css        # Styles
├── script.js        # JavaScript
├── package.json     # Project metadata
└── .gitignore       # Git ignore rules
```

## 🔧 Technologies Used

- HTML5
- CSS3
- JavaScript (jQuery)
- Typed.js (typing animations)
- Owl Carousel (carousel slider)

## 📝 License

MIT License - feel free to use this template for your own portfolio!

## 👤 Author

Malyala Venkatesh
- GitHub: [Venkateshvarma03](https://github.com/Venkateshvarma03)
- LinkedIn: [malyala-venkatesh](https://www.linkedin.com/in/malyala-venkatesh)
- Email: malyalavenkatesh26@gmail.com

