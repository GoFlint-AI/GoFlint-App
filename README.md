# GoFlint-App

## Vercel Deployment

This project is a static site. To deploy to Vercel, you have two simple options.

- **One-time / CLI deploy:** Install the Vercel CLI, log in, and run a deploy.

```bash
npx vercel login
npx vercel --prod
```

- **Git integration:** Push this repository to GitHub and connect it in the Vercel dashboard for automatic deployments on every push to the selected branch.

The configuration file [vercel.json](vercel.json#L1) is included to serve `index.html` as a static site with SPA fallback.
