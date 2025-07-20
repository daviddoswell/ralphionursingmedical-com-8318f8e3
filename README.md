# Nurse Practitioner Website Template

A professional, responsive website template designed specifically for Nurse Practitioners and healthcare providers. Built with Next.js, TypeScript, and Tailwind CSS.

## Features

✅ **Professional Design** - Clean, modern healthcare-focused design  
✅ **Responsive Layout** - Mobile-first design that works on all devices  
✅ **SEO Optimized** - Built-in SEO best practices  
✅ **Fast Performance** - Optimized for speed and Core Web Vitals  
✅ **Easy Customization** - Simple to customize colors, content, and branding  
✅ **Appointment Integration** - Ready for Healthie or other booking systems  

## Sections Included

- **Hero Section** - Compelling introduction with call-to-action
- **About Section** - Professional background and credentials
- **Services Section** - Healthcare services offered
- **Contact Section** - Appointment booking and contact information
- **Footer** - Professional footer with copyright

## Quick Start

1. **Install Dependencies**
   ```bash
   pnpm install
   ```

2. **Set Environment Variables**
   ```bash
   cp .env.example .env.local
   # Edit .env.local with your Healthie URL
   ```

3. **Run Development Server**
   ```bash
   pnpm dev
   ```

4. **Open in Browser**
   Visit [http://localhost:3000](http://localhost:3000)

## Customization

### Environment Variables

```bash
HEALTHIE_URL=https://secure.helloalma.com/providers/book-with-your-name
```

### Content Customization

Edit `src/app/page.tsx` to customize:
- Provider name and credentials
- Services offered
- About section content
- Contact information

### Styling

The template uses Tailwind CSS for styling. Key colors:
- Primary: `indigo-600` (can be changed throughout)
- Background: `blue-50` to `indigo-100` gradient
- Text: `gray-900`, `gray-600`, `gray-500`

## Deployment

### Vercel (Recommended)

1. Push to GitHub repository
2. Connect to Vercel
3. Set environment variables in Vercel dashboard
4. Deploy automatically

### Other Platforms

This template works with any platform that supports Next.js:
- Netlify
- AWS Amplify
- Railway
- DigitalOcean App Platform

## Built With

- **Next.js 15** - React framework
- **TypeScript** - Type safety
- **Tailwind CSS 4** - Utility-first CSS
- **React 19** - UI library

## License

MIT License - feel free to use for your practice!

## Support

For questions or customization help, contact the Oma Health team.
