# PrintForge

A modern platform for discovering and sharing 3D printing files. Built with Next.js 15, React 19, and Tailwind CSS.

## Features

- Browse a curated library of 3D printable models
- Filter models by category (Art, Tools, Toys & Games, Miniatures, etc.)
- View model details including descriptions and community likes
- Responsive design for desktop and mobile devices

## Tech Stack

- **Framework:** Next.js 15 (App Router)
- **UI:** React 19
- **Styling:** Tailwind CSS
- **Language:** TypeScript
- **Icons:** React Icons

## Getting Started

### Prerequisites

- Node.js 18.17 or later
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd PrintForge
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm run start` | Start production server |
| `npm run lint` | Run ESLint |

## Project Structure

```
PrintForge/
├── app/
│   ├── 3d-models/           # Model browsing pages
│   │   ├── categories/      # Category filtered views
│   │   └── [id]/            # Individual model pages
│   ├── about/               # About page
│   ├── components/          # Reusable UI components
│   ├── data/                # JSON data files
│   ├── lib/                 # Utility functions
│   ├── types/               # TypeScript type definitions
│   ├── globals.css          # Global styles
│   ├── layout.tsx           # Root layout
│   └── page.tsx             # Home page
├── public/                  # Static assets
└── package.json
```

## Categories

- 3D Printer
- Art
- Education
- Fashion
- Hobby & DIY
- Household
- Miniatures
- Props & Cosplay
- Tools
- Toys & Games

## License

This project is private.
