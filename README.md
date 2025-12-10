# That Christian Coder

Personal Astro blog for stories on code, church tech, faith, worship, and life. Based on the [Ryze theme](https://github.com/8366888C/Ryze).

## Stack
- Astro v5, Tailwind CSS v4, TypeScript
- React islands for interactive bits
- Shiki for syntax highlighting

## Content
- Posts live in `src/blog/` as Markdown with frontmatter (`slug`, `title`, `description`, `date`, `author`, `tags`, `featured`, `editable`).
- Archive and tags pages are generated automatically.

## Development
```
npm install
npm run dev -- --host --port 4321
```
Site: http://localhost:4321

## Build
```
npm run build
```
Static output goes to `dist/`.

## Newsletter (Netlify Forms)
The subscribe form is wired to Netlify Forms. On Netlify, submissions will appear under Forms and redirect to `/thanks`.

## Deploy
- Target: Netlify (static build). Netlify will run `npm run build`.

## License
MIT
