# Portfolio — Md Mahamudul Hasan Shuvo

A responsive **HTML + CSS + vanilla JavaScript** personal portfolio customized using the provided internship CV and public GitHub projects. No build tools or framework required.

## Run locally

1. Unzip the folder.
2. Open `index.html` in your browser.
3. Optional: use the VS Code Live Server extension for automatic reload.

## What's included

- Real name and internship focus, Daffodil International University CSE education (CGPA 3.76), contact email, GitHub, LinkedIn, and Facebook.
- Featured work: **BhumiGuard BD**, **PantryLoop**, **Routine Finder**, and **DIU Fee Calculator**.
- Links to code and to publicly listed demos, when known.
- Research interest in eggplant leaf disease image classification, explicitly noted as exploration.
- Light/dark toggle, responsive mobile menu, proper external-link attributes, accessible navigation.
- CV download button (`resume.pdf`) and portrait extracted from the supplied CV (`headshot.jpeg`).
- Reference-inspired footer with navigation, featured-project links, and Facebook/GitHub/LinkedIn icons.

## Customize

- Edit the `PROFILE` object near the top of `script.js` for your name, links, email and project URLs.
- Edit the HTML text to change descriptions and statuses.
- Update `styles.css` for colors, typography or card layouts.
- Replace `headshot.jpeg` or `resume.pdf` whenever your photo/CV changes.

**Privacy note:** If you deploy the folder as written, `resume.pdf` will be publicly downloadable and includes the personal details shown in your supplied CV, including a phone number and local address. Remove/redact the PDF before publishing if you prefer not to share these details publicly.

**Accuracy note:** Project details and skills come from the provided CV and public GitHub READMEs; the site does not claim unverified metrics. The Routine Finder URL comes from the supplied CV and may require you to check it in your browser. The BhumiGuard Streamlit public app URL is in its public README, but external access may require authentication depending on current app status.

## Publish on GitHub Pages

1. Create a **new public repository** (e.g. `shuvo-portfolio`).
2. Extract the ZIP, open the `portfolio` folder, and upload **the files inside that folder** to the repository root (not the ZIP and not the containing folder). Ensure `index.html` is directly at the repository root.
3. Open **Settings → Pages → Build and deployment**.
4. Select **Deploy from a branch**, `main`, `/ (root)`, then Save.
5. Wait for GitHub Pages to display the deployed URL. For a repository called `shuvo-portfolio`, the expected address is `https://mhshuvo1830.github.io/shuvo-portfolio/` (provided the repository name is exactly `shuvo-portfolio`). Use the confirmed URL on your CV and LinkedIn.

**Do not publish into your existing `mhshuvo1830.github.io` repository without checking it first**, because your PantryLoop repository README names that path as a deployment target.
