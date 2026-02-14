# Valentine's Day Proposal Website 💕

A beautiful Bridgerton-themed proposal website for Ammu!

## 📸 Setup Instructions

### Step 1: Add Your Personal Photos

Add your photos to the `images/` folder with these names:

- `photo1.jpg` - For Section 1 (Valentine's question)
- `photo2.jpg` - For Section 1 (Valentine's question)
- `photo3.jpg` - For Section 1 (Valentine's question)
- `photo4.jpg` - For Section 2 (Marriage proposal)
- `photo5.jpg` - For Section 2 (Marriage proposal)
- `photo6.jpg` - For Section 2 (Marriage proposal)
- `photo7.jpg` - For Section 3 (Success/Celebration)
- `photo8.jpg` - For Section 3 (Success/Celebration)

**Tips:**
- Use JPG or PNG format
- Compress images for web (recommended max 1MB per photo)
- Square or portrait orientation works best
- Photos will be displayed in 150x150px frames (mobile: 120x120px)

### Step 2: Add Pink Flower Video

Add your pink flower destination video to the `videos/` folder:

- `pink-flowers.mp4` - Main video file

**Optional:**
- `pink-flowers.webm` - For better browser compatibility
- `video-poster.jpg` - Thumbnail image shown before video loads

**Tips:**
- Recommended max video size: 10-20MB for fast loading
- Use MP4 format (H.264 codec)
- Compress video using HandBrake or online tools
- Aspect ratio: 16:9 or 4:3 works well

### Step 3: Test Locally

1. Open `index.html` in your browser
2. Test all three sections:
   - Section 1: Valentine's question with Ammu
   - Section 2: Marriage proposal with Dhan
   - Section 3: Success celebration
3. Test NO button escape behavior
4. Verify photos and video display correctly
5. Test on mobile device or browser DevTools

### Step 4: Deploy to Vercel

#### Option A: Using Vercel CLI

```bash
# Install Vercel CLI globally
npm install -g vercel

# Login to Vercel
vercel login

# Deploy
vercel
```

#### Option B: Using Vercel Dashboard

1. Go to [vercel.com](https://vercel.com)
2. Sign up/login with GitHub
3. Click "Add New..." → "Project"
4. Import this folder (drag & drop or connect Git repo)
5. Deploy!

#### Option C: Using Git + Vercel

```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit - Valentine's proposal website"

# Push to GitHub
# (Create a new repo on GitHub first)
git remote add origin YOUR_GITHUB_REPO_URL
git push -u origin main

# Then connect GitHub repo to Vercel dashboard
```

### Step 5: Share the URL

Once deployed, Vercel will give you a URL like:
`https://your-project-name.vercel.app`

Share this URL with Ammu! 💕

## 🎨 Features

- ✨ Bridgerton-themed elegant design
- 🌸 Animated flower petals
- 💕 Two-step proposal journey
- 🎥 Pink flower video integration
- 📸 Personal photo gallery
- 🐶 Puppy GIF interactions
- 🎉 Celebration animations with confetti and hearts
- 📱 Fully responsive (mobile-optimized)
- 💛 Pastel yellow & red color scheme
- 🏆 Impossible-to-click NO button

## 🔧 Customization

You can customize the website by editing `index.html`:

- **GIF URLs**: Change the Giphy links (lines with `giphy.com`)
- **Bridgerton Quotes**: Modify the quote text
- **Success Message**: Update the celebration message
- **Colors**: Adjust CSS color variables
- **Names**: Already set to "Ammu" and "Dhan"

## 📂 Folder Structure

```
C:\Users\Pranesh\Downloads\temp love\
├── index.html          # Main website file
├── vercel.json         # Vercel deployment config
├── .gitignore          # Git ignore file
├── README.md           # This file
├── images/             # Personal photos folder
│   ├── photo1.jpg
│   ├── photo2.jpg
│   ├── ... (photo3-8)
│   └── video-poster.jpg (optional)
└── videos/             # Video folder
    ├── pink-flowers.mp4
    └── pink-flowers.webm (optional)
```

## 💝 Good Luck!

May this proposal bring you both a lifetime of happiness! 💍✨
