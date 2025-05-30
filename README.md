# Birthday Celebration Web App

A vibrant web application to celebrate Damien Papers and Chris Dennis's birthdays on May 17th and May 23rd respectively. The app features countdown timers, celebration effects, and a section for uploading celebration videos.

## Features

- Interactive countdown timers for both birthdays
- Automatic celebration effects on birthday dates
- Video upload section for sharing celebration videos
- Responsive design for all devices
- Festive animations and confetti effects

## Dependencies

This project uses:
- Next.js 14+
- React 18+
- Tailwind CSS
- Lucide React (for icons)
- TypeScript

## Getting Started

### Prerequisites

- Node.js 18.17 or later
- npm or yarn or pnpm

### Installation

1. Clone the repository:
\`\`\`bash
git clone https://github.com/your-username/birthday-celebration.git
cd birthday-celebration
\`\`\`

2. Install dependencies:
\`\`\`bash
npm install
# or
yarn install
# or
pnpm install
\`\`\`

3. Start the development server:
\`\`\`bash
npm run dev
# or
yarn dev
# or
pnpm dev
\`\`\`

4. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## Project Structure

\`\`\`
birthday-celebration/
├── app/
│   ├── page.tsx         # Main page component
│   ├── layout.tsx       # Root layout
│   └── globals.css      # Global styles
├── components/
│   ├── birthday-card.tsx # Birthday card component
│   ├── confetti.tsx     # Confetti animation
│   └── video-section.tsx # Video upload section
├── public/              # Static assets
└── package.json         # Project dependencies
\`\`\`

## Deployment

### Pushing to GitHub

cd "F:\Douglas Kings\Software Development\GitHub\Birthady App"

git init

notepad .gitignore

git add .

git commit -m "first commit"

git branch -M master

git remote add origin https://github.com/DouglasKings/birthday-app.git

git push -u origin master

git status

# Deploying on vercel
npm i -g vercel

vercel login

vercel

When you modify files, repeat:
git add .
git commit -m "New update"
git push origin master
vercel --prod