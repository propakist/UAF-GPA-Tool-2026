# Complete Setup Guide - GPA Calculator for GitHub Pages & AdSense

## 📋 Table of Contents
1. [Prerequisites](#prerequisites)
2. [Create GitHub Repository](#create-github-repository)
3. [Configure AdSense](#configure-adsense)
4. [Deploy to GitHub Pages](#deploy-to-github-pages)
5. [Customize Your Site](#customize-your-site)
6. [Submit to AdSense](#submit-to-adsense)
7. [Optimization & Promotion](#optimization--promotion)

---

## Prerequisites

You'll need:
- GitHub account (free at https://github.com)
- Google account (for AdSense)
- Text editor (VS Code recommended)
- Git installed (https://git-scm.com)
- Basic understanding of HTML/CSS (optional)

---

## Step 1: Create GitHub Repository

### 1.1 On GitHub Website

1. **Login to GitHub** at https://github.com/login
2. **Create New Repository**:
   - Click "+" icon → "New repository"
   - Name: `gpa-calculator` (or `[your-username].github.io`)
   - Description: "Free CGPA & GPA Calculator for Students"
   - Choose: **Public** (required for GitHub Pages)
   - ✅ Initialize with README
   - Click "Create repository"

### 1.2 Clone Repository Locally

```bash
# Open terminal/command prompt
git clone https://github.com/[YOUR-USERNAME]/gpa-calculator.git
cd gpa-calculator
```

Replace `[YOUR-USERNAME]` with your actual GitHub username.

### 1.3 Add All Files

Copy these files to your cloned repository:
- `index.html`
- `styles.css`
- `script.js`
- `privacy-policy.html`
- `terms.html`
- `ad-policy.html`
- `README.md`
- `LICENSE`
- `.gitignore`

---

## Step 2: Configure AdSense

### 2.1 Sign Up for Google AdSense

1. Go to https://www.google.com/adsense/
2. Click "Sign up now"
3. Sign in with your Google account
4. Fill out the application:
   - Website URL: `https://[your-username].github.io/gpa-calculator/`
   - Country/Territory: Select your location
   - Website language: English
   - Category: Education/Academic

### 2.2 Get Your AdSense Code

**IMPORTANT**: Wait 24-48 hours for approval after providing your website URL.

Once approved:

1. **Go to AdSense Dashboard**
2. **Click "Ads" → "Summary"**
3. **Find your Publisher ID** (ca-pub-XXXXXXXXXXXXX)
4. **Copy the code** and continue below

### 2.3 Update HTML Files

**In index.html**, find this line:

```html
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-xxxxxxxxxxxxxxxx"></script>
```

Replace `ca-pub-xxxxxxxxxxxxxxxx` with your actual Publisher ID (looks like `ca-pub-1234567890123456`).

### 2.4 Create Ad Slots

In AdSense dashboard:

1. **Go to "Ads" → "Ad units"**
2. **Click "Create new ad unit"**
3. **Create THREE ad units** for the three placements:

**Ad Unit 1 - Top Banner**
- Name: "Top Banner"
- Type: "Display ads"
- Size: "Responsive"
- Copy the ad slot ID (looks like: `1234567890`)

**Ad Unit 2 - Middle Banner**
- Name: "Middle Banner"
- Type: "Display ads"
- Size: "Responsive"
- Copy the ad slot ID

**Ad Unit 3 - Bottom Banner**
- Name: "Bottom Banner"
- Type: "Display ads"
- Size: "Responsive"
- Copy the ad slot ID

### 2.5 Update Ad Slots in HTML

In `index.html`, replace the `data-ad-slot` values:

```html
<!-- TOP AD -->
<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-YOUR-ID"
     data-ad-slot="SLOT-ID-1"
     data-ad-format="horizontal"
     data-full-width-responsive="true"></ins>

<!-- MIDDLE AD -->
<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-YOUR-ID"
     data-ad-slot="SLOT-ID-2"
     data-ad-format="horizontal"
     data-full-width-responsive="true"></ins>

<!-- BOTTOM AD -->
<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-YOUR-ID"
     data-ad-slot="SLOT-ID-3"
     data-ad-format="horizontal"
     data-full-width-responsive="true"></ins>
```

---

## Step 3: Customize Your Site

### 3.1 Update Contact Information

In all HTML files, replace email addresses:

**Find and Replace:**
- `contact@gpacalculator.com` → Your email
- `support@gpacalculator.com` → Your support email
- `privacy@gpacalculator.com` → Your privacy email
- `legal@gpacalculator.com` → Your legal email

### 3.2 Update Site Title and Meta

In `index.html`, update:

```html
<!-- Change these -->
<title>CGPA & GPA Calculator - Calculate Your Academic Performance</title>
<meta name="author" content="Your Name">
```

### 3.3 Customize Grade Scale (Optional)

In `index.html`, find the "Grade Scale Reference" table and update if needed for your institution.

### 3.4 Update Logo

To change the logo emoji (📊):

Find this in `index.html`:
```html
<span class="logo-icon">📊</span>
```

Replace 📊 with any emoji you prefer.

---

## Step 4: Deploy to GitHub Pages

### 4.1 Commit Changes

```bash
# Navigate to your repository folder
cd gpa-calculator

# Add all files
git add .

# Commit with message
git commit -m "Add GPA calculator with AdSense integration"

# Push to GitHub
git push -u origin main
```

### 4.2 Enable GitHub Pages

1. **Go to GitHub repository**
2. **Click Settings** → **Pages**
3. **Under "Source"**:
   - Branch: `main`
   - Folder: `/ (root)`
   - Click "Save"
4. **Wait 1-2 minutes for deployment**

### 4.3 Access Your Site

Your site is now live at:
```
https://[your-username].github.io/gpa-calculator/
```

Example: `https://johndoe.github.io/gpa-calculator/`

---

## Step 5: Test Your Site

### 5.1 Test Calculator

1. Open your site in browser
2. Add a test subject:
   - Name: "English"
   - Credits: "3"
   - Grade: "3.5"
3. Click "Calculate GPA"
4. Verify result shows 3.5

### 5.2 Test Slider

1. Click the slide number to reveal price
2. Verify shows "₨30"
3. Auto-hides after 3 seconds
4. Click Previous/Next buttons

### 5.3 Test on Mobile

1. Open site on mobile device
2. Test calculator input
3. Verify responsive design
4. Check ad placements

### 5.4 Test Links

- Click all navigation links
- Verify contact form opens email
- Check policy links work

---

## Step 6: Submit to AdSense

### 6.1 Before Submitting

✅ Checklist:
- [ ] AdSense code added to index.html
- [ ] Ad slots created in AdSense
- [ ] Site is live on GitHub Pages
- [ ] All pages are accessible
- [ ] No errors in browser console
- [ ] Mobile responsive works
- [ ] Content is unique and original
- [ ] Privacy policy is complete
- [ ] Terms of service are complete
- [ ] Ad policy is complete

### 6.2 Submit Site to AdSense

1. **Go to AdSense Dashboard**
2. **Click "Sites" → "Add site"**
3. **Enter your site URL**:
   ```
   https://[your-username].github.io/gpa-calculator/
   ```
4. **Click "Add site"**
5. **Wait for review** (24-48 hours typically)

### 6.3 AdSense Review Tips

Google reviews for:
- **Original Content**: Your calculator is unique ✅
- **Quality Design**: Professional appearance ✅
- **User Experience**: Easy to use ✅
- **Valuable Content**: Helps students ✅
- **All Policies**: Privacy, Terms, Ads ✅
- **No Policy Violations**: Clean code ✅

### 6.4 If Disapproved

If AdSense denies approval:

1. **Check email** for specific reason
2. **Common issues**:
   - Insufficient traffic (need 100+ visitors)
   - Missing policies (already included)
   - Site too new (wait 2-3 months)
   - Non-policy compliant content (remove it)
3. **Reapply** after fixing issues
4. **Check** [AdSense policies](https://support.google.com/adsense/answer/48182)

---

## Step 7: Optimization & Promotion

### 7.1 SEO Optimization

1. **Google Search Console**:
   - Go to https://search.google.com/search-console
   - Add property: Your site URL
   - Submit sitemap

2. **Site Optimization**:
   - Site has meta descriptions ✅
   - Mobile responsive ✅
   - Fast loading ✅
   - Proper headings ✅

### 7.2 Promote Your Site

1. **Social Media**:
   - Share on Facebook, Instagram
   - Post to student groups
   - Use hashtags: #GPACalculator #StudentTools

2. **Student Forums**:
   - Reddit: r/students, r/UAE, r/Pakistan
   - Quora: Answer Q&A about GPA
   - Discord: Student communities

3. **Links**:
   - Submit to directories
   - Link in social profiles
   - YouTube video tutorial

### 7.3 Monitor Performance

1. **Google Analytics** (optional):
   - Add analytics tracking
   - Monitor visitor numbers
   - Track user behavior

2. **AdSense Dashboard**:
   - Monitor ad revenue
   - Track impressions/clicks
   - Optimize ad placements

### 7.4 Get More Traffic

Traffic sources:
- Search engines (SEO)
- Social media
- Direct links
- Referrals
- Student websites

---

## Troubleshooting

### AdSense Not Showing

```
Issue: Ads not displaying on site
Solutions:
1. Verify code is exactly as provided
2. Wait 24-48 hours for approval
3. Clear browser cache (Ctrl+Shift+Del)
4. Check browser console (F12) for errors
5. Use different browser to test
6. Verify ad block isn't blocking ads
7. Check AdSense account status
```

### Calculator Not Working

```
Issue: Calculator doesn't calculate
Solutions:
1. Open browser console (F12)
2. Check for JavaScript errors
3. Verify all fields are filled
4. Check grades are 0-4
5. Check credits are positive numbers
6. Try different browser
7. Refresh page (Ctrl+F5)
```

### GitHub Pages Not Updating

```
Issue: Changes not showing on site
Solutions:
1. Hard refresh browser (Ctrl+Shift+F5)
2. Wait 5-10 minutes for deployment
3. Check git push succeeded
4. Verify correct branch (main)
5. Check GitHub Actions status
6. Clear local cache
7. Try incognito window
```

---

## Important Tips

### ✅ DO's

- ✅ Use original content
- ✅ Follow Google policies
- ✅ Update regularly
- ✅ Monitor performance
- ✅ Respond to users
- ✅ Keep policies updated
- ✅ Optimize for mobile
- ✅ Promote ethically

### ❌ DON'Ts

- ❌ Click your own ads
- ❌ Incentivize clicks
- ❌ Mislead about ads
- ❌ Use copyrighted content
- ❌ Violate terms
- ❌ Use bots for traffic
- ❌ Place ads deceptively
- ❌ Hide ad policies

---

## Timeline

| Step | Timeline | Notes |
|------|----------|-------|
| Setup GitHub | 15 min | Quick setup |
| AdSense Signup | 2-3 days | Approval takes time |
| Site Configuration | 1-2 hours | Customize and deploy |
| First Traffic | 1-2 weeks | Promote on social |
| AdSense Approval | 2-4 weeks | After initial traffic |
| First Earnings | 1-2 months | Ads need traffic |

---

## Support Resources

- **GitHub Help**: https://docs.github.com/en/pages
- **AdSense Help**: https://support.google.com/adsense/
- **Web Dev**: https://web.dev/
- **Google Search Console**: https://search.google.com/search-console/

---

## Next Actions

1. ✅ Follow Step 1-4 for initial setup
2. ✅ Test thoroughly before going live
3. ✅ Apply for AdSense once traffic begins
4. ✅ Promote through multiple channels
5. ✅ Monitor and optimize continuously

---

**You're now ready to launch your GPA calculator! 🎉**

Estimated time to first earnings: 4-6 weeks
Potential monthly revenue: ₨5,000 - ₨50,000+ (depends on traffic)

Good luck! 📊✨
