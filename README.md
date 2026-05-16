# beiQ

Hugo + PaperMod personal academic website for `https://beiq.paperresearch.site/`.

## Local Preview

Install Hugo extended `0.156.0` or newer, then run:

```powershell
hugo server -D
```

This workspace also has a local portable Hugo binary at `.tools/hugo/hugo.exe`:

```powershell
.\.tools\hugo\hugo.exe server -D
```

## Production Build

```powershell
hugo --gc --minify
```

or:

```powershell
.\.tools\hugo\hugo.exe --gc --minify
```

The generated site is written to `public/`.

## Cloudflare Pages

- Framework preset: Hugo
- Production branch: `main`
- Build command: `hugo --gc --minify`
- Build output directory: `public`
- Root directory: `/`
- Environment variable: `HUGO_VERSION = 0.156.0`
- Custom domain: `beiq.paperresearch.site`
