# Xpense Landing Page

## Overview
A modern, responsive landing page for the Xpense income & expense tracker app built with Svelte 5, SvelteKit, and Tailwind CSS.

**Web App URL**: https://app.xpense.web.id

## Key Features

The landing page promotes the web-based nature of the app with:
- Direct links to the web app (`app.xpense.web.id`)
- Emphasis on "Access Anywhere, Anytime"
- No-download, browser-based access
- Responsive design for all devices

## Features Showcased

### 1. **Hero Section**
- Eye-catching gradient background (blue to indigo)
- Clear value proposition
- Call-to-action buttons
- Visual dashboard preview card

### 2. **Features Section**
- 6 key features in a responsive grid:
  - Multiple Projects
  - Multiple Wallets
  - Smart Categories
  - Offline Support
  - Real-time Analytics
  - Privacy First
- Hover effects with glowing gradient backgrounds
- Icon-based visual hierarchy

### 3. **Benefits Section**
- Highlights "Why Choose Xpense" with 5 key benefits
- "Access Anywhere, Anytime" showcase
- Feature breakdown:
  - 🌐 Web-Based: Access from any browser, no installation needed
  - 📱 Responsive Design: Perfect experience on mobile, tablet, or desktop
  - ⚡ Instant Access: No app store needed, works with just a web link

### 4. **Use Cases Section**
- 6 targeted use cases for different user types:
  - Personal Finance
  - Freelancers
  - Family Budget
  - Side Hustlers
  - Home Projects
  - Travel Planning

## Call-to-Action Section
- Primary CTA: "Start Using Xpense" → links to `https://app.xpense.web.id`
- Secondary CTA: "Learn More" → scrolls to features section
- Strong value proposition about browser-based access
- Opens app in new tab for seamless navigation

### 6. **Footer**
- Multi-column layout
- Quick links to product, company, and legal pages
- Social media links
- Copyright information

## Design Highlights

- **Responsive Design**: Works seamlessly on mobile, tablet, and desktop
- **Tailwind CSS**: Utility-first CSS framework for consistent styling
- **Lucide Icons**: Beautiful, scalable icons throughout
- **Color Scheme**: 
  - Primary: Blue (#0066CC) to Indigo (#4F46E5)
  - Supporting: Green, Purple, Orange, Red, Yellow
- **Accessibility**: Semantic HTML, proper contrast ratios, keyboard navigation support

## Technology Stack

- **Framework**: SvelteKit 2.57.0 with Svelte 5.55.2
- **Styling**: Tailwind CSS 4.2.2
- **Icons**: Lucide-svelte 0.484.0
- **Build Tool**: Vite 8.0.7

## Installation

```bash
npm install
# or
bun install
```

## Development

```bash
npm run dev
# Navigate to http://localhost:5173
```

## Build

```bash
npm run build
npm run preview
```

## Web App Access

Xpense is a web-based application accessible at **app.xpense.web.id**. This approach offers several advantages:

### Benefits of Web-Based Access
- ✅ No installation required - just open the URL in any browser
- ✅ Works on any device - phone, tablet, desktop, laptop
- ✅ Always up-to-date - updates are deployed server-side
- ✅ Offline support - Progressive Web App (PWA) enables offline functionality
- ✅ Easy sharing - simply share the link with users
- ✅ No app store approval needed - instant updates

### Offline Capability
While Xpense is web-based, it includes offline support:
- Data is cached locally using IndexedDB or LocalStorage
- Users can continue working without internet connection
- Changes sync automatically when connection is restored
- Perfect for on-the-go expense tracking

## Customization Tips

1. **Update Company Name**: Replace "Xpense" with your app name
2. **Modify Colors**: Update Tailwind color classes (e.g., `from-blue-600` → `from-green-600`)
3. **Add Your Logo**: Place logo in `static/` folder and update the Hero section
4. **Update Web App Link**: Replace `app.xpense.web.id` with your actual web app URL
5. **Social Media Links**: Update footer social media links with your actual profiles

## SEO Optimization

Consider adding:
- Meta descriptions in `+page.server.ts`
- Open Graph tags in `+layout.svelte`
- Structured data for rich snippets
- Sitemap generation

## Performance Notes

- All icons are inline SVGs for optimal performance
- CSS is tree-shaken and minified automatically
- No external fonts are loaded (relies on system fonts)
- Smooth animations using CSS transitions

## Accessibility

- Semantic HTML structure
- ARIA labels where appropriate
- Sufficient color contrast
- Keyboard-navigable
- Mobile-friendly touch targets
