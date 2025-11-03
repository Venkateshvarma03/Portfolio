# Portfolio Website

Personal portfolio website showcasing projects, skills, and achievements.

## 🚀 Deployment on Render

This project is configured to be deployed on Render. Follow these steps:

### Prerequisites

- A GitHub account
- A Render account (sign up at https://render.com)

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

2. **Create a new Web Service on Render**
   - Log in to your Render dashboard
   - Click "New +" and select "Web Service"
   - Connect your GitHub repository
   - Render will auto-detect the configuration from `render.yaml`

3. **Configure the service**
   - Name: `portfolio` (or your preferred name)
   - Region: Choose the closest region to your users
   - Branch: `main`
   - Root Directory: Leave empty (or enter `/` if needed)

4. **Deploy**
   - Click "Create Web Service"
   - Render will automatically build and deploy your site
   - You'll get a URL like `https://portfolio.onrender.com`

### Manual Configuration (if needed)

If you prefer not to use `render.yaml`, use these settings:

- **Build Command**: `npm install`
- **Start Command**: `npm start`
- **Environment**: `Node`

## 🛠️ Local Development

To run the project locally:

```bash
# Install dependencies
npm install

# Start the server
npm start

# Open http://localhost:3000 in your browser
```

## 📁 Project Structure

```
portfolio/
├── images/          # Images and assets
├── index.html       # Main HTML file
├── style.css        # Styles
├── script.js        # JavaScript
├── server.js        # Express server
├── package.json     # Dependencies
└── render.yaml      # Render configuration
```

## 🔧 Technologies Used

- HTML5
- CSS3
- JavaScript (jQuery)
- Node.js
- Express.js

## 📝 License

MIT License - feel free to use this template for your own portfolio!

## 👤 Author

Malyala Venkatesh
- GitHub: [Venkateshvarma03](https://github.com/Venkateshvarma03)
- LinkedIn: [malyala-venkatesh](https://www.linkedin.com/in/malyala-venkatesh)
- Email: malyalavenkatesh26@gmail.com

