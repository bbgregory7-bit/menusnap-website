# MenuSnap Website

Comprehensive website for MenuSnap - Tampa's ultimate foodie experience app.

## Files

- `index.html` - Full-featured landing page with app info, features, and release date
- `privacy.html` - Privacy policy page required for App Store submission

## Features

### 🎨 Design
- Professional, responsive design optimized for desktop and mobile
- Fixed navigation header with smooth scrolling
- Orange gradient theme matching the app branding
- Modern card-based layout with hover effects
- Full-screen hero section with release date prominence

### 📱 Content Sections
- **Hero**: App introduction with November 20, 2024 release date
- **Features**: 6 detailed feature cards showcasing app capabilities
- **How It Works**: 4-step process explanation
- **Tampa Focus**: Local statistics and featured areas
- **Pre-Launch CTA**: Final call-to-action with release date
- **Footer**: Links and contact information

### 🚀 Key Information
- **Release Date**: November 20, 2024 (prominently featured)
- **Target Market**: Tampa foodies and food enthusiasts
- **Platform**: iPhone-only (no iPad support)
- **Features Highlighted**:
  - Photo documentation of dishes
  - Gamified XP and leveling system
  - Streaks and challenges
  - Local restaurant discovery
  - Foodie community features
  - Personal dining analytics

### 📊 Tampa Statistics
- 40+ Featured Restaurants
- 15+ Cuisine Types
- Featured Areas: Downtown Tampa, Westshore, Hyde Park, Seminole Heights, Ybor City, South Tampa

## Setup Instructions

1. **Deploy to Netlify:**
   - Go to [netlify.com](https://netlify.com)
   - Drag and drop the `website` folder to deploy
   - Or connect to Git repository for automatic deployments

2. **Configure Custom Domain:**
   - In Netlify dashboard, go to Site Settings > Domain management
   - Add your custom domain from Squarespace
   - Follow Netlify's instructions to update DNS settings

3. **When App Goes Live (November 20, 2024):**
   - Update `APP_STORE_URL` in `index.html` with actual App Store link
   - Change `isAppLive` to `true` to enable the download button
   - All "Coming November 20, 2024" text will automatically change to "Available Now!"
   - Optionally enable auto-redirect for mobile users

## Technical Features

- Smooth scrolling navigation
- Mobile-responsive grid layouts
- CSS Grid and Flexbox for modern layouts
- Optimized for SEO with proper meta tags
- Social media ready with Open Graph tags
- Performance optimized with minimal external dependencies

## DNS Configuration

When setting up your domain, you'll need to:
1. Point your domain's DNS to Netlify
2. Update nameservers in Squarespace to point to Netlify
3. Or use CNAME records if keeping Squarespace as registrar

Netlify will provide specific instructions based on your domain setup.

## Content Updates

The website is designed to automatically transition from "coming soon" to "live" state. Simply update these variables in `index.html`:

```javascript
const APP_STORE_URL = 'your-actual-app-store-url';
const isAppLive = true;
```

This will:
- Enable the download button
- Update all release date text to "Available Now!"
- Optionally enable mobile auto-redirect (if uncommented)