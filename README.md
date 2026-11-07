# Flames n Spirits — Website

A clean, modern, dark-luxury website for **Flames n Spirits** (Sainikpuri, Hyderabad), built with pure HTML5, CSS3, and Vanilla JavaScript.

## 🌟 Highlights
- **Zero Dependencies**: Pure HTML/CSS/JS. No Node.js, no build tools, no npm packages required.
- **Instant GitHub Pages Deployment**: Works out of the box on GitHub Pages or any static web host.
- **Animations**: CSS keyframe animations, floating elements, smooth scroll reveal, and hover effects.
- **Interactive Repertoire (Menu)**: Real-time search filter and Category pills (Veg / Non-Veg).
- **Fully Responsive**: Mobile, tablet, and desktop layouts with mobile slide-in navigation.

## 📁 Project Structure
```
flame/
├── index.html        # Main Homepage (Hero, Signatures, Ambiance, Reservation, Location, Footer)
├── menu.html         # Full interactive menu page (17 categories, search & filters)
├── images/           # All high-resolution logo, ambiance, and culinary images
└── README.md         # Deployment and usage instructions
```

## 🚀 How to Run Locally
Double-click `index.html` to open it in any web browser, or run a simple local server:
```bash
python3 -m http.server 8000
```
Then visit `http://localhost:8000`.

## 🌐 Deploying to GitHub Pages
1. Initialize git in this folder (or drag and drop into a new GitHub repo):
   ```bash
   git init
   git add .
   git commit -m "Initial commit of Flames n Spirits website"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo-name>.git
   git push -u origin main
   ```
2. Go to your repo on GitHub:
   - Click **Settings** > **Pages**
   - Under **Build and deployment**, select `Deploy from a branch`
   - Select `main` branch and `/ (root)` folder, then click **Save**
3. Your live site will be ready at:
   `https://<your-username>.github.io/<your-repo-name>/`

