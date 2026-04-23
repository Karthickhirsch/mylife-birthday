# 🚀 GitHub Pages Deployment Guide

## 📋 Pre-Deployment Checklist

### 1. Add Your Photos
Place 12 photos in the `images/` folder with these names:
```
images/
  ├── photo1.jpg
  ├── photo2.jpg
  ├── photo3.jpg
  ├── photo4.jpg
  ├── photo5.jpg
  ├── photo6.jpg
  ├── photo7.jpg
  ├── photo8.jpg
  ├── photo9.jpg
  ├── photo10.jpg
  ├── photo11.jpg
  └── photo12.jpg
```

**Tips for choosing photos:**
- Use JPG or PNG format
- Recommended size: 400x500px (or similar aspect ratio)
- Mix of portraits, fun moments, and memorable events
- Include photos from different years/occasions

### 2. Customize Content (if not already done)
- Update her real name in the Hero section
- Personalize the letter in "From My Heart" section
- Adjust gift description
- Update wishes from family/friends with real names

---

## 🌐 Deploy to GitHub Pages

### Step 1: Initialize Git Repository
```bash
cd c:\Users\skarthick-a\Music\Anusiya21
git init
```

### Step 2: Create GitHub Repository
1. Go to [github.com](https://github.com)
2. Click "New Repository"
3. Name it: `anusiya-birthday` (or any name you prefer)
4. Set to **Private** (recommended for personal gift)
5. **Don't** initialize with README
6. Click "Create repository"

### Step 3: Connect and Push
```bash
git add .
git commit -m "Add birthday surprise website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/anusiya-birthday.git
git push -u origin main
```

### Step 4: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **Settings** tab
3. Scroll to **Pages** section (left sidebar)
4. Under "Source":
   - Select branch: **main**
   - Select folder: **/ (root)**
5. Click **Save**
6. Wait 1-2 minutes for deployment

### Step 5: Get Your URL
Your website will be live at:
```
https://YOUR_USERNAME.github.io/anusiya-birthday/
```

---

## 🔐 Keeping It Secret

Since this is a surprise:

### Option 1: Private Repository (Recommended)
- Keep repo private
- Only you can access the code
- Website is still publicly accessible via the URL
- Share URL only with her on her birthday

### Option 2: Custom Domain (Optional)
If you want a custom URL like `anusiya-birthday.com`:
1. Buy a domain from Namecheap, GoDaddy, etc.
2. In GitHub Pages settings, add custom domain
3. Update DNS settings per GitHub instructions

### Option 3: Password Protection (Already Built In!)
The website already has password protection (`panda21`)
- Even if someone finds the URL, they need the password
- Change password in the code if needed (search for `PASSWORD`)

---

## 📁 File Structure

```
Anusiya21/
├── index.html          # Main website (single file)
├── images/             # Photo gallery images
│   ├── photo1.jpg
│   ├── photo2.jpg
│   └── ... (12 total)
├── README.md           # Documentation
├── DEPLOYMENT.md       # This file
└── THEME_GUIDE.md      # Color theme guide
```

---

## 🎨 Before Going Live

### Final Checks:
- [ ] All 12 photos added to `images/` folder
- [ ] Her real name updated (if needed)
- [ ] Letter personalized with your message
- [ ] Gift description customized
- [ ] Wishes updated with real family/friend names
- [ ] Password tested (`panda21`)
- [ ] Birthday date correct (May 9, 2026)
- [ ] Test on mobile device
- [ ] Test all interactive elements

---

## 🔧 Troubleshooting

### Images Not Loading?
- Ensure images are in `images/` folder
- Check file names match exactly (case-sensitive on Linux servers)
- Use `.jpg` or `.png` extensions
- Verify GitHub uploaded all files

### Website Not Loading?
- Wait 2-3 minutes after enabling GitHub Pages
- Check repository is public or Pages is enabled for private repo
- Verify the URL format: `https://username.github.io/repo-name/`

### Password Not Working?
- Default password is `panda21`
- Case-sensitive and must be lowercase
- To change: search for `PASSWORD = 'panda21'` in code

---

## 📱 Testing Before Sharing

1. Open in **incognito/private mode** to test fresh experience
2. Test on **mobile** (iPhone/Android)
3. Try on different **browsers** (Chrome, Safari, Firefox)
4. Solve the puzzle to test proposal flow
5. Check all sections load properly

---

## 🎁 Sharing With Her

### Delivery Ideas:
1. **Text message** on her birthday morning
2. **QR code** printed on a card
3. **Email** with mysterious subject line
4. **Social media** DM at midnight
5. Tell her in person and watch her discover it!

### Sample Message:
```
Happy Birthday! 🐼💕
I made something special just for you...

🔗 [Your GitHub Pages URL]
🔑 Password hint: Your favorite animal

Enjoy the adventure! 🎉
```

---

## 🚀 You're Ready!

Once you:
1. ✅ Add photos to `images/` folder
2. ✅ Push to GitHub
3. ✅ Enable GitHub Pages

Your website will be live and ready to surprise her! 🐼💕✨

---

**Need help?** Check GitHub Pages documentation: https://pages.github.com/
