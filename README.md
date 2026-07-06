# CDNJS Landing Page Clone
 
A pixel-focused front-end clone of the [cdnjs.com](https://cdnjs.com) homepage, built with plain HTML5 and CSS3. It recreates the animated hero background, sticky navigation bar, hero search section, support banner, and multi-column footer.
 
## 🔗 Live Preview
 
> Add your GitHub Pages link here once deployed, e.g.
> `https://sharifshaik173.github.io/CDNJS-cloning/`
 
## 📸 Preview
 
> Add a screenshot of the page here, e.g.
> `![Preview](Screenshot 2026-07-06 094341.png)`
 
## ✨ Features
 
- **Animated SVG background** – decorative "network path" illustration with moving dots (`animateMotion`) representing cdnjs's CDN concept.
- **Sticky, responsive-style navbar** with brand logo, social icons (Twitter, GitHub Discussions), and nav links (About, Libraries, API, GitHub, Status).
- **Hero section** with headline, description, and a styled search bar with a magnifying glass icon.
- **Support/donation banner** encouraging GitHub contributions and donations (Open Collective / Patreon).
- **Footer** with logo, copyright, social links, and three link columns (About, Libraries, Sponsors).
- Uses **Font Awesome** icons via CDN.
## 🛠️ Built With
 
- HTML5
- CSS3 (Flexbox, absolute/sticky positioning, pseudo-classes)
- [Font Awesome](https://cdnjs.com/libraries/font-awesome) (via cdnjs CDN)
## 📁 Project Structure
 
```
├── index.html
├── style.css
├── Assets/
│   ├── logo.svg
│   └── icon.png
└── README.md
```
 
> Note: `index.html` references `./Assets/logo.svg` and `./Assets/icon.png`. Make sure an `Assets/` folder with these files is included in the repo, or update the paths accordingly.
 
## 🚀 Getting Started
 
### Run Locally
 
1. Clone the repository
```bash
   git clone https://github.com/<your-username>/<repo-name>.git
```
2. Open the project folder
```bash
   cd <repo-name>
```
3. Open `index.html` directly in your browser, or use a live server (e.g. VS Code "Live Server" extension) for the best experience.
### Deploy with GitHub Pages
 
1. Push the project to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under "Build and deployment", select **Deploy from a branch**, choose `main` and `/root`.
4. Save — your site will be live at `https://<your-username>.github.io/<repo-name>/`.
## 📄 Credits
 
This project is a front-end clone built for learning/practice purposes, inspired by the design of [cdnjs.com](https://cdnjs.com). All original branding, content, and trademarks belong to their respective owners (cdnjs / Cloudflare). Not intended for commercial use.
 
## 📝 License
 
This project is open source and available.
