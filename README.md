# Lahanti Last Mile Services — Website

A responsive, single-page company website redesign for Lahanti Last Mile Services Private Limited.

## Run locally

No build tools or dependencies are required. Open `index.html` in a browser, or run a local static server:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Deploy to Vercel

### Option 1: GitHub
1. Create a GitHub repository and upload the contents of this folder.
2. In Vercel, choose **Add New → Project** and import the repository.
3. Select **Other** as the framework preset if prompted.
4. Leave Build Command and Output Directory empty/default (static site; `index.html` is at the project root).
5. Click **Deploy**.

### Option 2: Vercel CLI
Install the Vercel CLI, sign in, navigate to this folder and run:

```bash
vercel
```

Follow the prompts. For production deployment, run `vercel --prod`.

## Notes
- The contact form validates the fields and opens the visitor's default email application with a pre-filled message to `info@llms.in`. It does not submit to a server or store enquiries. Connect a form backend (for example, a serverless function or approved form service) if direct online submission is required.
- Company description, mission, vision, services, customer-story summaries and contact details are based on the public LLMS website. Please verify all wording, customer permissions, branch details and current product availability with LLMS before publishing.
- The reference website's location list and state-count statement are inconsistent; this redesign lists the states shown on the reference page without repeating a total count.
- Fonts load from Google Fonts; the site falls back to system sans-serif fonts if unavailable.
