# DILIP — THE UNSTOPPABLE | N SERIES

A React + TypeScript + Vite cinematic personal portfolio.

## Included improvements
- Safe session storage access: the opening flow still works if browser storage is blocked.
- Search now includes career and education cards as well as episodes, journey, projects, and dance.
- Copy-email action reports clipboard failures clearly instead of showing a false success message.
- Existing responsive design, profile selection, cards, modal details, and Vercel configuration are preserved.

## Run locally
Requires Node.js 20+ and an internet connection for the first dependency install.

```bash
npm install
npm run build
npm run dev
```

Open the local URL printed by Vite. The production build is created in `dist/`.

## Deploy to Vercel
1. Extract this ZIP.
2. Upload/commit the **contents** of `Dilip_N_Series_Clean_Start` to the GitHub repository root (not the enclosing folder).
3. In Vercel, select the **Vite** framework preset.
4. Set Build Command to `npm run build` and Output Directory to `dist`.
5. Deploy.

## Notes
- Portfolio artwork uses remote Unsplash image URLs, so those images need an internet connection. CSS backgrounds have a dark fallback color.
- Clipboard copy requires a supported browser context (normally HTTPS or localhost); the app shows the email address if copying is unavailable.
- This is a personal portfolio concept inspired by streaming interfaces and is not affiliated with Netflix.
- No project can honestly be guaranteed to have zero bugs. Run `npm install` and `npm run build` in your environment before deployment.
