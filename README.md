# 🛡️ CyberSafe – A Web-Based Cyber Security Toolkit

A free, open-source, browser-based cybersecurity toolkit built for the MCA project by **Shradha Mahesh Kuril** at IIMS Vishnupuri, 2025-26.

## 🔧 Tools Included

| Tool | Description |
|---|---|
| 🔍 Password Strength Analyzer | Real-time password strength scoring with 8 criteria |
| 🔑 Secure Password Generator | Cryptographically random passwords via `crypto.getRandomValues()` |
| 🔐 Text Encryption & Decryption | AES-256-GCM using the browser's Web Crypto API |
| 🧮 File Hash Generator | MD5, SHA-1, SHA-256, SHA-512 for files and text |
| 🎣 Phishing URL Detector | Heuristic URL analysis for phishing indicators |
| 💡 Cyber Security Tips | 20+ categorized cybersecurity best practices |

## 🚀 Deploy to GitHub Pages (Step by Step)

### Step 1 – Create a GitHub Repository
1. Go to [github.com](https://github.com) and sign in
2. Click **New Repository**
3. Name it: `cybersafe` (or any name you prefer)
4. Set it to **Public**
5. Click **Create Repository**

### Step 2 – Upload the Files
**Option A – GitHub Web UI (Easiest):**
1. Open your new repository
2. Click **Add file → Upload files**
3. Upload ALL files maintaining this folder structure:
   ```
   cybersafe/
   ├── index.html
   ├── README.md
   ├── css/
   │   └── style.css
   └── pages/
       ├── password-checker.html
       ├── password-generator.html
       ├── encryption.html
       ├── hash-generator.html
       ├── phishing-detector.html
       └── tips.html
   ```
4. Commit the files

**Option B – Git Command Line:**
```bash
git init
git add .
git commit -m "Initial commit: CyberSafe toolkit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/cybersafe.git
git push -u origin main
```

### Step 3 – Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **Settings** (top menu)
3. Scroll down to **Pages** (left sidebar)
4. Under **Source**, select **Deploy from a branch**
5. Set branch to **main**, folder to **/ (root)**
6. Click **Save**

### Step 4 – Access Your Live Site
After 1–2 minutes, your site will be live at:
```
https://YOUR_USERNAME.github.io/cybersafe/
```

## 🛠️ Technologies Used

- **HTML5** – Semantic page structure
- **CSS3** – Custom design with CSS variables and animations
- **JavaScript (ES6+)** – All tool logic and DOM manipulation
- **Web Crypto API** – AES-GCM encryption and SHA hashing (browser-native)
- **Google Fonts** – Share Tech Mono, Rajdhani, Exo 2
- **GitHub Pages** – Free static hosting

## 📁 Project Structure

```
cybersafe/
├── index.html                  ← Home page with all tool links
├── README.md                   ← This file
├── css/
│   └── style.css               ← Shared styles for all pages
└── pages/
    ├── password-checker.html   ← Password Strength Analyzer
    ├── password-generator.html ← Secure Password Generator
    ├── encryption.html         ← Text Encryption & Decryption (AES-256-GCM)
    ├── hash-generator.html     ← File Hash Generator (MD5/SHA-256/SHA-512)
    ├── phishing-detector.html  ← Phishing URL Detector
    └── tips.html               ← Cyber Security Tips Library
```

## 🔒 Privacy

All processing happens **100% in your browser**. No data is ever sent to any server. No backend, no database, no tracking.

## 📄 License

Open-source for educational purposes. MCA Project 2025-26.
