# Ujjwal Jha

Personal portfolio for a senior C# / .NET engineer with 13 years in production systems, now moving into applied AI and machine learning.

Live site: [ujjwaljha.github.io/ujjwaljha](https://ujjwaljha.github.io/ujjwaljha/)

GitHub Pages uses the repository name in the path, and that path is case-sensitive. The repo must be named `ujjwaljha` (all lowercase) for that URL to resolve. A case-only rename in **Settings → General → Repository name** often needs two steps: `Ujjwaljha` → `ujjwaljha-site` → `ujjwaljha`. Then re-check **Settings → Pages** is still **GitHub Actions**. The old mixed-case URL will not redirect.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 4173
```

Then visit `http://localhost:4173`. Resume: `http://localhost:4173/resume.html`.

## Publish

1. Merge to `main`.
2. In the GitHub repository, open **Settings → Pages**.
3. Set the source to **GitHub Actions**.

The workflow in `.github/workflows/pages.yml` deploys the static site on each push to `main`.
