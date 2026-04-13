# PrintForge

A 3D model sharing platform built with Next.js 15, TypeScript, and Tailwind CSS. Browse and discover community-submitted 3D printing files.

## Live Demo

https://printforge80.netlify.app/

## Features

- Browse a gallery of 3D models with category tags and likes
- Individual model detail pages with dynamic routing
- Responsive layout with mobile-friendly navigation
- Optimized Google Fonts (Albert Sans + Montserrat Alternates)
- Fully typed with TypeScript

## Tech Stack

- **Framework:** Next.js 15 (App Router)
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **Icons:** React Icons

## Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/printforge.git
cd printforge

# Install dependencies
npm install

# Start the development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm start` | Start production server |
| `npm run lint` | Run ESLint |

## Key Concepts Used

| Concept | Where |
|---|---|
| File-based routing | `app/` folder structure |
| Nested routes | `app/3d-models/[id]/` |
| Root layout | `app/layout.tsx` |
| Server components | `ModelsPage`, `ModelDetailPage` |
| Dynamic routes | `app/3d-models/[id]/page.tsx` |
| Google Fonts optimization | `layout.tsx` via `next/font/google` |

## Deployment

This project is ready to deploy on [Vercel](https://vercel.com):

```bash
npm install -g vercel
vercel
```

## Author

Cary Zhu — [caryzhu.com](https://caryzhu.com) · [GitHub](https://github.com/CodeCary80)