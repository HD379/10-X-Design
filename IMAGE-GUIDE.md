# 🖼️ HOW TO ADD IMAGES TO YOUR 10X DESIGN WEBSITE

## Super Simple Method (No Coding Knowledge Needed!)

### Step 1: Get Your Image URLs

You have 2 options:

#### Option A: Upload to Free Image Hosting
1. Go to **imgur.com** or **imgbb.com** (free, no account needed)
2. Upload your image
3. Right-click the image and select "Copy Image Address"
4. You'll get a URL like: `https://i.imgur.com/abc123.jpg`

#### Option B: Use Images Already on the Web
1. Find an image online
2. Right-click and select "Copy Image Address"
3. You'll get a URL ending in .jpg, .png, or .webp

---

## Step 2: Open Your Website File

1. **Download** the `10x-design-website.html` file
2. **Right-click** the file
3. Select **"Open With" → "Notepad"** (Windows) or **"TextEdit"** (Mac)

---

## Step 3: Find and Replace Image Placeholders

### 🔍 Use the "Find" Feature:
- Press **Ctrl+F** (Windows) or **Cmd+F** (Mac)
- Type: `YOUR-IMAGE-URL-HERE`
- This will highlight each image placeholder

### 📍 Where to Add Images:

#### **HERO SECTION IMAGE** (Top right of homepage)
Look for this line:
```html
<div class="hero-image" style="background-image: url('YOUR-IMAGE-URL-HERE');"></div>
```

**Replace** `YOUR-IMAGE-URL-HERE` with your image URL:
```html
<div class="hero-image" style="background-image: url('https://i.imgur.com/yourimage.jpg');"></div>
```

---

#### **PORTFOLIO IMAGES** (4 project showcase boxes)

**Portfolio Image 1:**
```html
<!-- 🖼️ PORTFOLIO IMAGE 1 -->
<div class="portfolio-item" style="background-image: url('YOUR-IMAGE-URL-HERE');
```

**Replace with:**
```html
<div class="portfolio-item" style="background-image: url('https://i.imgur.com/project1.jpg');
```

Do the same for Portfolio Images 2, 3, and 4.

---

## Step 4: Save Your Changes

1. **File → Save** (or Ctrl+S / Cmd+S)
2. Open the HTML file in your web browser
3. Your images should now appear!

---

## 🎨 IMAGE TIPS FOR BEST RESULTS:

### **Hero Image:**
- **Size:** 1200px × 1600px (portrait orientation)
- **Type:** Landscape, nature, or abstract design
- **Style:** Should complement the earthy, natural aesthetic

### **Portfolio Images:**
- **Size:** 1200px × 900px (landscape orientation)
- **Type:** Your actual project photos
- **Style:** Professional photos of your work

### **Recommended Image Sizes:**
- Keep images under 500KB for fast loading
- Use .jpg for photos
- Use .png for graphics with text

---

## 📝 QUICK EXAMPLE:

**BEFORE:**
```html
<div class="hero-image" style="background-image: url('YOUR-IMAGE-URL-HERE');"></div>
```

**AFTER:**
```html
<div class="hero-image" style="background-image: url('https://i.imgur.com/nature-scene.jpg');"></div>
```

---

## 🆘 TROUBLESHOOTING:

**Image not showing?**
- ✅ Make sure the URL ends in .jpg, .png, or .webp
- ✅ Make sure you kept the single quotes: `url('...')`
- ✅ Test the URL by pasting it directly in your browser
- ✅ If the URL opens the image, it's correct!

**Image looks stretched?**
- The CSS automatically handles sizing
- Try a different aspect ratio image

---

## 🎯 WHERE ARE THE IMAGE PLACEHOLDERS?

In your HTML file, search for these exact phrases:

1. `<!-- 🖼️ HERO IMAGE` → Top of homepage (1 image)
2. `<!-- 🖼️ PORTFOLIO IMAGE 1` → First project (1 image)
3. `<!-- 🖼️ PORTFOLIO IMAGE 2` → Second project (1 image)
4. `<!-- 🖼️ PORTFOLIO IMAGE 3` → Third project (1 image)
5. `<!-- 🖼️ PORTFOLIO IMAGE 4` → Fourth project (1 image)

**Total: 5 image spots to fill**

---

## 💡 PRO TIP:

If you want to use images from your computer:
1. Put your images in the **same folder** as the HTML file
2. Name them simply: `hero.jpg`, `project1.jpg`, etc.
3. Use just the filename: `url('hero.jpg')` instead of a full URL

---

## Need More Help?

- All images have a gradient overlay to maintain readability
- The colors will always match the site's green/cream theme
- Images show through the overlay at about 70% opacity

That's it! You're ready to add your images! 🎉
