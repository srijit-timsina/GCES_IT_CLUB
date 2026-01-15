# GCES IT Club Website

Modern, professional IT Club website built with Next.js 14 (App Router) and Tailwind CSS.

## Features

- **Responsive Design**: Mobile-first approach with dark mode support
- **Event Management**: Display upcoming and past events with registration
- **Dynamic Routing**: Individual event detail pages
- **Form Validation**: Registration and contact forms with validation
- **Admin Panel**: Interface for managing events
- **SEO Optimized**: Metadata and semantic HTML
- **Modern UI**: Tech-inspired design with smooth animations

## Tech Stack

- Next.js 14 (App Router)
- TypeScript
- Tailwind CSS
- MongoDB (optional)
- Lucide Icons

## Getting Started

### Installation

```bash
npm install
```

### Environment Variables

Create a `.env` file:

```
MONGODB_URI=mongodb://localhost:27017/gces-it-club
SMTP_HOST=smtp.gmail.com
SMTP_PORT=587
SMTP_USER=your-email@gmail.com
SMTP_PASS=your-app-password
```

### Run Development Server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000)

### Build for Production

```bash
npm run build
npm start
```

## Project Structure

```
src/
├── app/
│   ├── about/
│   ├── events/
│   ├── register/
│   ├── contact/
│   ├── admin/
│   └── api/
├── components/
│   ├── Navbar.tsx
│   ├── Footer.tsx
│   └── ThemeProvider.tsx
└── lib/
    ├── events.ts
    └── mongodb.ts
```

## Pages

- **Home**: Hero section with CTA buttons
- **About**: Mission, vision, and technologies
- **Events**: List of upcoming and past events
- **Event Details**: Dynamic route for each event
- **Register**: Event registration form
- **Contact**: Contact form and social links
- **Admin**: Event management panel

## Theme Color

Primary: #1D74F5

## License

MIT
# GCES_IT_CLUB
