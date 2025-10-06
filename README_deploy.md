# NotYetDrawn — Deploy to Vercel (Local Save)

1. Unzip the project folder.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Test locally:
   ```bash
   npm run dev
   ```
   Open http://localhost:5173
4. Build for production:
   ```bash
   npm run build
   ```
5. Deploy to Vercel:
   - Go to https://vercel.com
   - Create account or login with GitHub
   - Click "New Project" → "Import" → Drag & drop the project folder (or link the GitHub repo)
   - For framework preset choose "Vite"
   - Deploy — within seconds you get a public URL like https://notyetdrawn.vercel.app

Note: All data is saved locally in the browser using localStorage.
