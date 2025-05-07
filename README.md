# Peak Strategy Website

This is the official website for Peak Strategy, built with [React](https://reactjs.org/) and [Vite](https://vitejs.dev/), designed for content consulting, coaching, and leadership development services.

## 🚀 Live Demo

Once deployed, your site will be live at:

```
https://peak-strategy.netlify.app
```

## 🧱 Project Structure

- `src/pages/` — Contains all route components: Home, Services, Philosophy, Schedule a Call
- `App.jsx` — Routing logic using `react-router-dom`
- `public/_redirects` — Handles Netlify form routing
- `netlify.toml` — Netlify deployment configuration

## 💻 Run Locally

1. Clone the repo:
```bash
git clone https://github.com/YOUR_USERNAME/peak-strategy-site.git
cd peak-strategy-site
```

2. Install dependencies:
```bash
npm install
```

3. Start the dev server:
```bash
npm run dev
```

Site will run at: [http://localhost:5173](http://localhost:5173)

## 🚢 Deploy on Netlify

1. Go to [Netlify](https://www.netlify.com)
2. Click "Add new site" > "Import from GitHub"
3. Connect your repo
4. Set the following build settings:
   - **Build command:** `npm run build`
   - **Publish directory:** `dist`

5. Click **Deploy**

## 📬 Form Handling

The **Schedule a Call** form uses [Netlify Forms](https://docs.netlify.com/forms/setup/) and sends submissions directly to the Netlify dashboard.

Make sure to enable the form in your Netlify settings if needed.

---

© 2025 Peak Strategy | Built by Andrew McPeak
