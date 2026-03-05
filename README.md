# ajao.dev

Personal portfolio site built with [Astro](https://astro.build) and [Tailwind CSS](https://tailwindcss.com).

## Stack

- **Astro** — Static site generator, zero JS by default
- **Tailwind CSS** — Utility-first styling
- **TypeScript** — Type safety

## Development

```bash
npm install
npm run dev
```

Open [http://localhost:4321](http://localhost:4321).

## Build

```bash
npm run build
npm run preview
```

Static output goes to `dist/`.

## Project Structure

```
src/
├── components/        # Astro components (Header, Hero, About, Skills, etc.)
├── layouts/           # Page layouts (Layout, ProjectLayout)
├── pages/             # Routes
│   ├── index.astro    # Home page
│   └── projects/      # Project detail pages
├── styles/            # Global CSS + Tailwind
public/                # Static assets (favicon, images)
```

## Deployment

Outputs static HTML. Deploy anywhere:

```bash
npm run build
```

Then upload `dist/` to Vercel, Netlify, Cloudflare Pages, or any static host.

## License

MIT
