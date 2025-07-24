# TechFlow Solutions - IT Company Website

A modern, responsive website for an IT services company built with Next.js, TypeScript, and Tailwind CSS.

## Features

- 🎨 Modern, professional design
- 📱 Fully responsive layout
- ⚡ Built with Next.js 15 and TypeScript
- 🎭 Tailwind CSS for styling
- 📧 Contact form
- 🏢 Service showcases
- 👥 Client testimonials
- 🌐 SEO optimized

## Services Showcased

- Web Development
- Mobile App Development
- Database Management
- Cybersecurity Solutions
- Cloud Services
- 24/7 IT Support

## Tech Stack

- **Framework**: Next.js 15
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Build Tool**: Webpack (via Next.js)

## Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn or pnpm

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd it-company-website
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

### Building for Production

```bash
npm run build
npm start
```

## Project Structure

```
src/
├── app/
│   ├── globals.css      # Global styles and Tailwind imports
│   ├── layout.tsx       # Root layout component
│   └── page.tsx         # Main homepage component
└── components/          # Reusable components (future expansion)
```

## Key Sections

1. **Hero Section** - Professional introduction with call-to-action
2. **Services** - Comprehensive IT service offerings
3. **About** - Company statistics and value propositions
4. **Testimonials** - Client feedback and reviews
5. **Contact** - Contact form and company information
6. **Footer** - Additional links and company info

## Customization

To customize for your IT company:

1. Update company name and branding in `src/app/page.tsx`
2. Modify services in the services section
3. Replace testimonials with real client feedback
4. Update contact information
5. Customize color scheme in Tailwind config if needed

## Deployment

This Next.js application can be deployed to:

- **Vercel** (recommended)
- **Netlify**
- **Railway**
- **Docker** containers

### Docker Deployment

```bash
# Build the Docker image
docker build -t it-company-website .

# Run the container
docker run -p 3000:3000 it-company-website
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the ISC License.