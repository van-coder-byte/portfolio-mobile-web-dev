# Deployment Instructions

## Local Development

1. **Clone Repository**
   ```bash
   git clone https://github.com/van-coder-byte/portfolio-mobile-web-dev.git
   cd portfolio-mobile-web-dev
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Start Development Server**
   ```bash
   npm run dev
   ```

## Production Deployment

### Using Vercel
1. Connect GitHub repository to Vercel
2. Configure build settings:
   - Build Command: `npm run build`
   - Output Directory: `dist`

### Using Netlify
1. Connect repository to Netlify
2. Configure build settings:
   - Build Command: `npm run build:client`
   - Publish Directory: `client/dist`

## Technologies Used

- **Frontend**: React, TypeScript, Tailwind CSS, Vite
- **Backend**: Node.js, Express, TypeScript  
- **UI Components**: Radix UI, Shadcn/ui
- **Icons**: Lucide React, React Icons
- **Deployment**: Vercel, Netlify, or custom hosting

## Features

- ✅ Responsive design (mobile-first)
- ✅ Dark/light mode support
- ✅ Interactive portfolio showcase
- ✅ Skills with progress indicators  
- ✅ Professional experience timeline
- ✅ Contact integration
- ✅ SEO optimized
- ✅ GitHub deployment ready

---

**Portfolio Status**: 🟢 Live and Ready for Deployment
**Last Updated**: 2025-09-22