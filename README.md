# Cloud CI/CD Assignment — GitHub Actions + Pages

**Student:** YOUR NAME HERE  
**Course:** Cloud Computing  
**Instructor:** Dr. Faten F Abushmmala  

---

## 🔗 Live GitHub Pages Link

👉 [https://deyaabatsh.github.io/cloud-beginner-cicd-pages-YourName/](https://deyaabatsh.github.io/cloud-beginner-cicd-pages-YourName/)

*(Replace this URL with your actual GitHub Pages URL after deployment)*

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `index.html` | Main webpage with CI/CD content |
| `style.css` | Styling for the website |
| `script.js` | JavaScript interactive button demo |
| `README.md` | Project documentation |
| `.github/workflows/deploy.yml` | GitHub Actions CI/CD workflow |

---

## 🚀 How the CI/CD Pipeline Works

1. Developer pushes code to the `main` branch
2. GitHub Actions automatically triggers the `deploy.yml` workflow
3. The workflow checks all required files exist
4. The site files are uploaded as an artifact
5. GitHub Pages deploys the site automatically

---

## 💻 How to Open the Site Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/deyaabatsh/cloud-beginner-cicd-pages-YourName.git
   ```
2. Navigate to the project folder:
   ```bash
   cd cloud-beginner-cicd-pages-YourName
   ```
3. Open `index.html` directly in your browser:
   - **Windows:** Double-click `index.html`
   - **Mac/Linux:** `open index.html` or `xdg-open index.html`
   - Or use VS Code Live Server extension

No build tools or servers required — it's pure HTML/CSS/JS!
