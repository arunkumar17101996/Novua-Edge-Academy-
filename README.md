# Novua Edge Academy

A React + Vite application for Novua Edge Academy courses and classes.

## Tech Stack

- **Frontend Framework**: React 18.3.1
- **Build Tool**: Vite 5.4.10
- **Language**: TypeScript 5.6.3
- **Styling**: Tailwind CSS 3.4.14
- **UI Components**: Lucide React (icons)
- **Animation**: Motion 11.11.9
- **Linting**: ESLint

## Development

### Prerequisites
- Node.js 16.x or higher
- npm or yarn

### Installation

```bash
npm install
```

### Development Server

```bash
npm run dev
```

The app will be available at `http://localhost:5173`

### Build

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

### Linting

```bash
npm run lint
```

## Deployment

### Deploy to Vercel

This project is configured to deploy on Vercel. Simply push to your repository and Vercel will automatically detect and deploy it.

**Automatic Deployment:**
1. Connect your GitHub repository to Vercel
2. Vercel will automatically deploy on every push to the main branch

**Manual Deployment:**
```bash
npm install -g vercel
vercel
```

## Project Structure

```
├── src/
│   ├── App.tsx
│   ├── main.tsx
│   └── index.css
├── public/
├── vite.config.ts
├── tsconfig.json
├── tailwind.config.js
├── vercel.json
└── package.json
```

## Environment Variables

Create a `.env.local` file in the root directory for local development:

```env
VITE_API_URL=your_api_url_here
```

## License

Private project - All rights reserved.
