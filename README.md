# Vineet Davre — Personal Portfolio
Responsive dark-premium portfolio built with React + Vite.

## Add your portrait
Copy your own photo into `public/profile.jpg` (vertical JPG/WEBP recommended, ideally 800x1000px or larger). The page references this path. Until then, an initials placeholder appears.

## Run locally
Install Node.js LTS, open a terminal in this folder, then run:

```bash
npm install
npm run dev
```

Open the local URL shown by Vite, usually http://localhost:5173.

## Production build
```bash
npm run build
npm run preview
```

## Deploy on Vercel
1. Create a GitHub repository and upload the project files.
2. Sign in to Vercel and choose **Add New → Project**.
3. Import the GitHub repository.
4. Framework preset: **Vite** (usually detected automatically).
5. Build command: `npm run build`; output directory: `dist`.
6. Click **Deploy**. Future pushes to the connected branch redeploy automatically.

## Before sharing with clients
- Add `public/profile.jpg`.
- Check every project description and publish only claims you can substantiate.
- Add approved project screenshots, client names, live links and measurable outcomes.
- Add LinkedIn, GitHub and Upwork profile links if desired.
- Check Vercel's current plan terms for commercial portfolio use.

Edit content in `src/main.jsx` and styling in `src/style.css`.
