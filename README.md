# InnovaIdea AI (InnovaIdea-AI)

This is a deployable prototype of the business idea analyzer (InnovaIdea AI).
It is implemented with Vite + React + Tailwind and runs fully in the browser using deterministic heuristics.

## How to run locally (desktop preferred)
1. Install Node.js (>=16) and npm.
2. Unzip the project and open the folder in terminal.
3. Run:
   ```
   npm install
   npm run dev
   ```
4. Open the shown local URL (http://localhost:5173) in your browser.

## How to deploy on Vercel (mobile or desktop)
1. Go to https://vercel.com and sign in (Google recommended).
2. Click "New Project" -> "Import" -> choose "Upload" (or drag & drop the ZIP).
3. Upload the ZIP you downloaded from here.
4. For build command, Vercel should auto-detect `npm run build`. If asked, use:
   - Install command: `npm install`
   - Build command: `npm run build`
   - Output directory: `dist`
5. Click "Deploy". Vercel will install dependencies and publish a live URL.

If you prefer, I can deploy this for you and share the live link.

-- End
