# True North VBS 2026 - Website

Welcome to the True North Vacation Bible School website for St. Jude Thaddeus Catholic Church!

## Overview

This is a single-page website designed for the 2026 True North VBS, featuring:
- Event information and registration
- Daily schedule with animal characters
- Volunteer opportunities
- Photo gallery from previous events
- Responsive design for all devices

## Quick Start

1. **Update Google Form Links**
   - Open `index.html` in a text editor
   - Find `YOUR_GOOGLE_FORM_LINK_HERE` (line ~275)
   - Replace with your child registration Google Form URL
   - Find `YOUR_VOLUNTEER_GOOGLE_FORM_LINK_HERE` (line ~320)
   - Replace with your volunteer registration Google Form URL

2. **Add Photos**
   - Save your photos in the `assets/images/` folder
   - Open `index.html` and replace the placeholder sections:
     - Hero image placeholder (line ~217)
     - About section images (lines ~342-350)
     - Gallery photos (lines ~481-537)

3. **Update Contact Information**
   - Scroll to the footer section (lines ~543-600)
   - Update email, phone, and address as needed

## Hosting on GitHub Pages

### Option 1: Enable GitHub Pages (Recommended)
1. Go to your repository on GitHub
2. Click on "Settings"
3. Scroll to "Pages" section
4. Under "Source", select the branch `claude/vbs-true-north-website-3CFUH`
5. Click "Save"
6. Your site will be published at: `https://[username].github.io/vacation-bible-school-st-jude/`

### Option 2: Manual Deployment
Simply push your changes to the repository and the site will be live!

## File Structure

```
vacation-bible-school-st-jude/
├── index.html           # Main website file
├── README.md           # This file
├── assets/
│   └── images/         # Store your photos here
│       ├── hero/       # Hero section images
│       ├── about/      # About section images
│       └── gallery/    # Photo gallery images
```

## Customization Guide

### Update Event Dates
Search for "June 8-12, 2026" in `index.html` and update all occurrences.

### Change Colors
The color scheme is defined in the Tailwind config (lines 11-20):
- `forest`: Primary green
- `sky`: Light blue
- `aurora-teal` and `aurora-purple`: Accent colors

### Add/Remove Volunteer Roles
Find the volunteer section (lines ~287-315) and add or remove roles as needed.

### Modify Daily Schedule
Each animal card is in the schedule section (lines ~396-496). Update text, emojis, or add more days as needed.

## Image Placeholders

There are **17 image placeholders** throughout the site:
1. **Hero Section**: 1 large banner image
2. **Event Details**: 1 church/VBS scene image
3. **About Section**: 2 images (activities and group photos)
4. **Photo Gallery**: 12 smaller photos + 1 large feature photo

To replace placeholders:
1. Add your image to `assets/images/`
2. Find the placeholder div in `index.html`
3. Replace with: `<img src="assets/images/your-photo.jpg" alt="Description" class="w-full h-full object-cover rounded-xl">`

## Animal Characters

The website features all 6 animal characters:
1. 🦦 Ponder the River Otter
2. 🦀 Clawdia the Crab
3. 🐻 Kody the Kodiak Bear
4. 🦅 Earnest the Bald Eagle
5. 🫎 Bruce the Moose
6. 🐺 Juneau the Siberian Husky (bonus companion)

## Browser Compatibility

This website works on:
- Chrome, Firefox, Safari, Edge (latest versions)
- Mobile devices (iOS and Android)
- Tablets and desktops

## Technical Details

- **Framework**: Vanilla HTML with Tailwind CSS (via CDN)
- **Fonts**: Fredoka and Nunito from Google Fonts
- **Responsive**: Mobile-first design
- **No build step**: Ready to deploy as-is

## Support

For questions or issues with the website, contact your web administrator or the VBS coordinator.

## License

© 2026 St. Jude Thaddeus Catholic Church. All rights reserved.

---

**Let's make True North VBS 2026 unforgettable!** 🧭🌲
