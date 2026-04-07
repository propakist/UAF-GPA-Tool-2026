# CGPA & GPA Calculator - GitHub Pages Repository

A free, AdSense-approved GPA and CGPA calculator website for students, especially those at UAE universities. Features a beautiful UI, slider with hidden pricing, and complete compliance with Google AdSense policies.

## 🎓 Features

- **GPA/CGPA Calculator**: Calculate semester GPA or cumulative CGPA
- **Dual Mode**: Choose between Semester GPA and Cumulative CGPA calculations
- **Interactive Slider**: 3-slide carousel with hidden pricing (₨30 reveal)
- **Local Processing**: All calculations are performed client-side - no data sent to servers
- **Grade Scale Reference**: Comprehensive grade to GPA conversion table
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Professional UI**: Modern, clean design with smooth animations
- **AdSense Ready**: Fully optimized for Google AdSense monetization
- **Complete Policies**: Privacy Policy, Terms of Service, and Ad Policy included

## 📋 File Structure

```
gpa-calculator/
├── index.html              # Main calculator page
├── privacy-policy.html     # Privacy Policy page
├── terms.html             # Terms of Service page
├── ad-policy.html         # Advertising Policy page
├── styles.css             # Complete styling and animations
├── script.js              # Calculator logic and interactivity
├── README.md              # This file
├── .gitignore             # Git ignore rules
└── LICENSE                # License information
```

## 🚀 Quick Start

### Deploy to GitHub Pages

1. **Create a new repository** on GitHub named `gpa-calculator` or `[your-username].github.io`

2. **Clone the repository** to your local machine:
   ```bash
   git clone https://github.com/[your-username]/gpa-calculator.git
   cd gpa-calculator
   ```

3. **Add all files** from this project to your repository

4. **Commit and push** to GitHub:
   ```bash
   git add .
   git commit -m "Initial commit: Add GPA calculator"
   git push -u origin main
   ```

5. **Enable GitHub Pages**:
   - Go to Settings → Pages
   - Select "main" branch as source
   - Save

6. **Access your site** at: `https://[your-username].github.io/gpa-calculator/`

## 🔧 Configuration

### Google AdSense Setup

1. **Sign up for Google AdSense**: https://www.google.com/adsense/

2. **Replace AdSense Client ID** in `index.html`:
   ```html
   <!-- Find and replace this line -->
   <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-xxxxxxxxxxxxxxxx"></script>
   ```
   Replace `ca-pub-xxxxxxxxxxxxxxxx` with your actual AdSense client ID

3. **Update ad slots** in index.html:
   ```html
   <!-- Replace data-ad-slot values -->
   <ins class="adsbygoogle"
        data-ad-slot="1234567890"
        ...
   ```

### Contact Email Configuration

1. **Update contact email** in `index.html` and policy pages:
   - Find: `contact@gpacalculator.com`
   - Replace with: your actual email address

2. **Email addresses** to update:
   - `contact@gpacalculator.com` - Main contact
   - `support@gpacalculator.com` - Support inquiries
   - `privacy@gpacalculator.com` - Privacy concerns
   - `legal@gpacalculator.com` - Legal matters
   - `ads@gpacalculator.com` - Advertising inquiries

## 📱 Features Explained

### GPA Calculator

- **Add Subjects**: Click "+ Add Subject" to add more courses
- **Input Grades**: Enter grade points (0-4.0 scale)
- **Input Credits**: Enter credit hours for each subject
- **Calculate**: Click "Calculate GPA" to see results
- **Reset**: Clear all inputs and start over

**Grade Scale Reference**:
- A+ / A = 4.0
- B+ = 3.5
- B = 3.0
- C+ = 2.5
- C = 2.0
- D = 1.0
- F = 0.0

### Slider Feature

- **3 Slides**: Information about the calculator
- **Navigation**: Use arrow buttons or keyboard arrows
- **Click Numbers**: Click on slide numbers to reveal pricing (₨30)
- **Auto-Hide**: Price automatically hides after 3 seconds

## 🛡️ AdSense Compliance

This site meets all Google AdSense policies:

✅ **Original Content**: 100% unique calculator tool
✅ **Quality Design**: Professional, user-friendly interface
✅ **User Experience**: Sufficient content with balanced ads
✅ **Security**: No malware, spyware, or unsafe content
✅ **Legitimate Ads**: Only Google AdSense ads displayed
✅ **No Click Fraud**: Clear separation of ads from content
✅ **Mobile Friendly**: Responsive design for all devices
✅ **Privacy Compliant**: Privacy Policy, Terms, and Ad Policy included
✅ **Local Processing**: User data not stored on servers
✅ **GDPR/COPPA**: Compliant with data protection regulations

## 📊 SEO Optimization

The site includes SEO best practices:

- Meta descriptions on all pages
- Proper heading hierarchy
- Semantic HTML structure
- Responsive design
- Fast loading times
- Mobile-first approach
- Accessible content
- Schema markup ready

## 🎨 Customization

### Colors
Edit CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2563eb;      /* Blue */
    --secondary-color: #10b981;    /* Green */
    --accent-color: #f59e0b;       /* Amber */
    --danger-color: #ef4444;       /* Red */
}
```

### Grade Scale
Modify the table in `index.html` under the "Grade Scale Reference" section to match your institution's grading system.

### Slider Content
Edit the slide content in the "Slide Section" of `index.html`:
```html
<div class="slide-card">
    <!-- Edit this content -->
</div>
```

## 📧 Contact Form

The contact form uses mailto links. When users submit:
1. Their email client opens
2. Pre-filled with form content
3. They send to your configured email

To enable email form submission on a server, you'll need to implement a backend service.

## 🔐 Privacy & Security

- **No Data Storage**: Calculations are done in-browser only
- **No Databases**: No user tracking or data collection
- **Privacy Policy**: Comprehensive privacy policy included
- **Terms of Service**: Clear terms for website usage
- **Ad Policy**: Transparent about advertising practices
- **GDPR Compliant**: Ready for European users
- **COPPA Compliant**: Safe for all ages

## 🐛 Troubleshooting

### AdSense Not Showing
- Verify client ID is correct
- Wait 24-48 hours after adding code
- Check AdSense account approval
- Clear browser cache
- Check browser console for errors

### Calculator Not Working
- Open browser console (F12)
- Check for JavaScript errors
- Verify all fields are filled
- Check input is numeric

### Slider Not Working
- Verify JavaScript is enabled
- Check console for errors
- Ensure DOM is fully loaded

## 📈 Performance Tips

1. **Optimize Images**: Compress any images you add
2. **Minimize CSS/JS**: Remove unused code in production
3. **Enable Caching**: Use GitHub Pages caching
4. **Monitor Performance**: Use Google PageSpeed Insights
5. **Test Mobile**: Regularly test on mobile devices

## 🔄 Updates

To update the site:

1. Make changes locally
2. Test thoroughly
3. Commit with clear messages
4. Push to GitHub
5. Changes deploy automatically

## 📝 License

This project is open source. See LICENSE file for details.

## 🤝 Contributing

Feel free to fork, modify, and improve this project. Consider:
- Adding more features
- Improving design
- Fixing bugs
- Translating to other languages

## 📞 Support

For issues or questions:

1. Check the troubleshooting section
2. Review policy pages
3. Contact via email links in the site
4. Check GitHub issues

## 🎯 Next Steps

1. **Customize** with your information
2. **Test** on multiple devices
3. **Deploy** to GitHub Pages
4. **Request** AdSense approval
5. **Monitor** performance
6. **Promote** your site
7. **Earn** from advertising

## 📚 Resources

- [Google AdSense Help](https://support.google.com/adsense/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Google Search Console](https://search.google.com/search-console/)
- [Web.dev Performance Guide](https://web.dev/performance/)

---

**Created for students by developers** ✨

Make your GPA calculator profitable with proper AdSense integration!
