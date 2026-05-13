# Yi O CCTV – Static Website

A static HTML/CSS website for the Yi O CCTV Digital Policing Pilot Scheme
(Lantau District, Hong Kong Police Force).

## Pages

| File | Description |
|---|---|
| `index.html` | Main page – English |
| `index-tc.html` | Main page – Traditional Chinese |
| `index-sc.html` | Main page – Simplified Chinese |
| `privacy-en.html` | Privacy Policy – English |
| `privacy-tc.html` | Privacy Policy – Traditional Chinese |
| `privacy-sc.html` | Privacy Policy – Simplified Chinese |

## Assets

Place the following image files in the `assets/` folder before deploying:

| Filename | Used for |
|---|---|
| `logo-hkpf.png` | Hong Kong Police Force logo (header) |
| `logo-lantau.png` | Lantau District logo (header) |
| `cctv-sign.png` | "CCTV in Operation" notice sign |

If the images are missing, the pages fall back gracefully (logos hidden, sign replaced by a styled div).

## Deploy to Vercel via GitHub

1. Push this entire folder as the **root** of a new GitHub repository.
2. Log in to [vercel.com](https://vercel.com) → **Add New Project** → import the GitHub repo.
3. Framework preset: **Other** (no build step needed).
4. Root directory: `/` (default).
5. Click **Deploy**.

Every `git push` to `main` will trigger an automatic re-deploy.

## Local preview

Open any `.html` file directly in a browser, or run a local server:

```bash
npx serve .
# or
python3 -m http.server 8080
```
