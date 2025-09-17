# Mirelle - Modern Nail Ideas & Trends

A premium, Pinterest-inspired website for the brand "Mirelle" focusing on nail ideas, nail care, seasonal looks, and product recommendations.

## 🌟 Features

### Homepage Sections
- **Hero Section**: Eye-catching banner with brand logo and call-to-action buttons
- **About Section**: Engaging introduction to Mirelle with premium imagery
- **Featured Topics**: 6 comprehensive topic sections with beautiful cards
- **Shop Section**: 3 product categories with 15 products each
- **Pinterest Showcase**: 9 Pinterest-inspired showcase sections
- **Subscribe Section**: Email collection with success feedback

### Pages & Content
- **About Page**: Detailed brand story with premium formatting
- **Topic Pages**: 6 detailed topic pages with engaging content:
  - Nail Care Guide
  - For Skin Tones
  - Nail Art Guides
  - Seasonal Trends
  - At-Home Nail Hacks
  - Modern Women Inspiration
- **Shop Pages**: 3 category pages with 15 product cards each:
  - Halloween Nails
  - Winter Nails
  - Trendy Nails
- **Pinterest Page**: Dedicated Pinterest inspiration page

### Design Features
- **Premium Color Palette**: Soft nudes, blush pinks, muted purples, deep charcoal
- **Typography**: Modern serif (Playfair Display) for headlines, clean sans-serif (Inter) for body
- **Responsive Design**: Optimized for desktop and mobile devices
- **Free Stock Images**: High-quality images from Unsplash throughout
- **Hover Effects**: Smooth transitions and interactive elements
- **Pinterest-Inspired Layout**: Image-rich, engaging design

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Installation

1. Navigate to the project directory:
```bash
cd mirelle-site
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## 🛠️ Tech Stack

- **Framework**: Next.js 14 with App Router
- **Styling**: Tailwind CSS
- **Language**: TypeScript
- **Icons**: Heroicons
- **Fonts**: Google Fonts (Playfair Display, Inter)
- **Images**: Unsplash (free stock images)

## 📁 Project Structure

```
mirelle-site/
├── src/
│   ├── app/
│   │   ├── about/
│   │   ├── pinterest/
│   │   ├── shop/
│   │   │   ├── halloween/
│   │   │   ├── winter/
│   │   │   └── trendy/
│   │   ├── topics/
│   │   │   ├── nail-care-guide/
│   │   │   ├── skin-tones/
│   │   │   ├── nail-art-guides/
│   │   │   ├── seasonal-trends/
│   │   │   ├── at-home-hacks/
│   │   │   └── modern-women/
│   │   ├── globals.css
│   │   ├── layout.tsx
│   │   └── page.tsx
│   └── components/
│       ├── Header.tsx
│       ├── Footer.tsx
│       ├── HeroSection.tsx
│       ├── AboutSection.tsx
│       ├── FeaturedTopicsSection.tsx
│       ├── ShopSection.tsx
│       ├── PinterestShowcaseSection.tsx
│       └── SubscribeSection.tsx
├── tailwind.config.js
└── package.json
```

## 🎨 Customization

### Colors
The color palette is defined in `tailwind.config.js`:
- **Nude**: Warm, skin-tone inspired colors
- **Blush**: Soft pink tones
- **Purple**: Muted purple accents
- **Charcoal**: Deep, sophisticated grays

### Fonts
- **Headlines**: Playfair Display (serif)
- **Body Text**: Inter (sans-serif)

### Images
All images are sourced from Unsplash and are free to use. To replace images, simply update the `src` attributes in the components.

## 📱 Responsive Design

The website is fully responsive with breakpoints:
- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🔗 Affiliate Links

Product cards include placeholder affiliate URLs. Replace these with your actual affiliate links:
- Halloween products: `https://example.com/halloween-collection`
- Winter products: `https://example.com/winter-collection`
- Trendy products: `https://example.com/trendy-collection`

## 📧 Email Subscription

The subscribe section includes a basic form handler. To implement actual email collection:
1. Set up an email service (Mailchimp, ConvertKit, etc.)
2. Update the form action in `SubscribeSection.tsx`
3. Add proper form validation and error handling

## 🚀 Deployment

### Vercel (Recommended)
1. Push your code to GitHub
2. Connect your repository to Vercel
3. Deploy with zero configuration

### Other Platforms
The project can be deployed to any platform that supports Next.js:
- Netlify
- AWS Amplify
- Railway
- DigitalOcean App Platform

## 📄 License

This project is created for the Mirelle brand. All rights reserved.

## 🤝 Contributing

This is a private project for the Mirelle brand. For any modifications or updates, please contact the development team.

---

Built with ❤️ for Mirelle - Modern Nail Ideas & Trends for Every Mood