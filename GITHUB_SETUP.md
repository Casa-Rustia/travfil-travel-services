# 📦 How to Upload to GitHub

## Step-by-Step Instructions

### 1️⃣ Create a GitHub Repository

1. Go to **github.com** and sign in to your account
2. Click the **+** icon (top right) → **New repository**
3. Name it: `travfil-website` (or any name you prefer)
4. Add description: "Travfil Travel Services - Educational & Group Tours Website"
5. Choose **Public** (if you want it visible to everyone)
6. Click **Create repository**

---

### 2️⃣ Prepare Your Local Files

1. **Download all files from the outputs folder:**
   - `index.html`
   - `style.css`
   - `script.js`
   - `README.md`
   - `.gitignore`
   - `assets/` folder (contains images)

2. **Create this folder structure:**
   ```
   travfil-website/
   ├── index.html
   ├── style.css
   ├── script.js
   ├── README.md
   ├── .gitignore
   └── assets/
       ├── Main_BG.png
       └── Travfil_Logo.jpg
   ```

---

### 3️⃣ Upload Using GitHub Desktop (Easiest)

1. **Download GitHub Desktop:** https://desktop.github.com/
2. **Sign in** with your GitHub account
3. Click **File** → **New Repository**
4. Name: `travfil-website`
5. Local Path: Choose where to save
6. Initialize with: Check all boxes
7. Click **Create**
8. **Copy all your files into this folder**
9. Return to GitHub Desktop
10. You'll see all files listed as changes
11. Write a commit message: "Initial commit - Travfil website"
12. Click **Commit to main**
13. Click **Publish repository**

---

### 4️⃣ Upload Using Git Command Line

1. **Open Terminal/Command Prompt** in your project folder
2. **Run these commands:**

```bash
# Initialize git
git init

# Add all files
git add .

# Create initial commit
git commit -m "Initial commit - Travfil website with orange circle button and scrolling background"

# Add remote repository
git remote add origin https://github.com/YOUR_USERNAME/travfil-website.git

# Push to GitHub
git branch -M main
git push -u origin main
```

---

### 5️⃣ Enable GitHub Pages (Make it Live!)

1. Go to your GitHub repository
2. Click **Settings** (top right)
3. Scroll down to **GitHub Pages** section
4. Under "Source", select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**
6. Wait 1-2 minutes
7. Your site will be live at: `https://YOUR_USERNAME.github.io/travfil-website`

---

## 📋 Files Checklist

✅ `index.html` - Main HTML file
✅ `style.css` - CSS stylesheet
✅ `script.js` - JavaScript functionality
✅ `README.md` - Documentation
✅ `.gitignore` - Git ignore file
✅ `assets/Main_BG.png` - Background image
✅ `assets/Travfil_Logo.jpg` - Logo image

---

## 🔍 What's Included

### Features:
- ✅ Orange solid circle button with "Why Choose Us" text
- ✅ Dropdown menu with services list
- ✅ Scrolling background image in hero section
- ✅ Responsive design (mobile, tablet, desktop)
- ✅ Contact form with validation
- ✅ Interactive tabs
- ✅ Professional animations
- ✅ SEO optimized

### Services in Dropdown:
- DOT ACCREDITED TRAVEL AGENCY
- DOT ACCREDITED TOURIST BUS
- Bus Transport
- Airlines Ticketing
- Fieldtrips
- Company Outing
- Team Building
- Hotel Bookings
- Bisita Iglesia
- And More

---

## 🎨 Customization

### Edit Colors
Open `style.css` and find (lines 16-35):
```css
:root {
  --navy:         #1B2A5E;
  --orange:       #F47C20;
  --teal:         #2E8B7A;
}
```

### Edit Services List
Open `index.html` and find (lines 62-74):
```html
<div class="why-choose-dropdown" id="whyChooseDropdown">
  <ul class="dropdown-list">
    <li>• Your Service</li>
  </ul>
</div>
```

### Edit Contact Info
Open `index.html` and find Contact section (around lines 431-450)

### Replace Images
- Replace `assets/Main_BG.png` with your background
- Replace `assets/Travfil_Logo.jpg` with your logo

---

## 🚀 After Upload

### Test Your Site
1. Go to: `https://YOUR_USERNAME.github.io/travfil-website`
2. Test on mobile, tablet, and desktop
3. Click the orange circle button to test dropdown

### Make Updates
1. Edit files locally
2. Run git commands:
   ```bash
   git add .
   git commit -m "Description of changes"
   git push
   ```
3. Wait 1-2 minutes for GitHub Pages to update

---

## 💡 Tips

- **Use meaningful commit messages** for tracking changes
- **Test locally first** before pushing
- **Keep file names lowercase** (no spaces)
- **Check responsive design** on mobile
- **Update README.md** with your actual info

---

## ❓ Troubleshooting

### Site not loading?
- Wait 2-3 minutes for GitHub Pages to build
- Check repository settings (must be Public for Pages)
- Check that `index.html` is in the root folder

### Images not showing?
- Verify `assets/` folder exists
- Check image file names match in HTML
- Ensure capitalization is correct

### Need help?
- GitHub Help: https://docs.github.com
- GitHub Pages: https://pages.github.com

---

**Your website is ready! Good luck! 🎉**
