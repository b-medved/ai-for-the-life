# AI for the Life

A curated AI content platform designed to help people master their daily life with artificial intelligence.

## 🚀 Features

- **Curated Content Showcase** - Handpicked AI articles, tools, and guides
- **Email Waitlist** - Collect early access signups with validation
- **Search & Filter** - Find content by type, category, and keywords
- **Responsive Design** - Works perfectly on desktop, tablet, and mobile
- **Modern UI** - Built with React, Tailwind CSS, and Shadcn/UI components

## 🛠️ Tech Stack

- **Frontend**: React 19, Vite
- **Styling**: Tailwind CSS, Shadcn/UI
- **Icons**: Lucide React
- **Database Ready**: Supabase integration structure
- **Deployment**: Static hosting compatible

## 📦 Installation

```bash
# Clone the repository
git clone <repository-url>
cd ai-for-the-life

# Install dependencies
npm install
# or
pnpm install

# Start development server
npm run dev
# or
pnpm dev
```

## 🏗️ Build

```bash
# Build for production
npm run build
# or
pnpm build

# Preview production build
npm run preview
# or
pnpm preview
```

## 🌐 Deployment

The project builds to static files in the `dist/` folder, making it compatible with:

- **Static Hosting**: Netlify, Vercel, GitHub Pages
- **Traditional Hosting**: Namecheap, GoDaddy, cPanel
- **CDN**: Cloudflare Pages, AWS S3 + CloudFront

### Deploying to Namecheap

1. Run `npm run build` to create the `dist/` folder
2. Upload all files from `dist/` to your hosting's `public_html` folder
3. Ensure `index.html` is in the root directory

## 🔧 Configuration

### Supabase Setup (Optional)

To connect to a real database:

1. Create a Supabase project
2. Update the configuration in `src/lib/supabase.js`
3. Add your Supabase URL and anon key
4. Create the necessary database tables

### Content Management

Content is currently managed in `src/components/ContentShowcase.jsx`. To add new content:

1. Add items to the `mockContent` array
2. Include title, description, source, url, type, category, and tags
3. Rebuild and redeploy

## 📝 License

This project is built for educational and commercial use.

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

---

**Built with ❤️ by Medved.ai**

