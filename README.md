# GreenCycle website

A ready-to-deploy static website built from the supplied GreenCycle HTML.

## Deploy

### Netlify
1. Open https://app.netlify.com/drop
2. Extract this ZIP on your computer.
3. Drag the extracted `greencycle-website` folder (or its contents) onto the Netlify Drop page.

### Vercel
1. Create a new project at https://vercel.com/new
2. Import this folder from a Git repository, or use the Vercel CLI from this folder.
3. No build command is required; the site is static and the output directory is `.`.

### Local preview
Run `npm start` in this folder (requires Node.js and internet access for `npx serve`), then open the local URL it prints.

## Notes
- `index.html` is the website.
- `app.json` is included as basic app metadata; it is not required by Vercel or Netlify.
- `vercel.json` and `netlify.toml` provide lightweight hosting configuration.
- The dashboard counters are a browser-side demo saved in local storage. They are not a shared, server-backed public counter.
- Images and web fonts load from external services, so those parts need an internet connection.
