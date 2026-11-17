# Greenoor Scitech landing page

A static, single-page website for Greenoor Scitech Private Limited. No build step and no dependencies: open `index.html` in a browser to preview it.

## Files

- `index.html`: the whole page (HTML, CSS and a small script for the enquiry form)
- `assets/logo.png`: company logo (low resolution; replace with a vector or high-resolution PNG)
- `assets/hena.jpg`, `assets/noor.jpg`: founder portraits

## Publish on GitHub Pages

1. Create a new repository on GitHub and upload the contents of this folder to the main branch, with `index.html` at the top level.
2. Open Settings, then Pages. Under "Build and deployment", choose "Deploy from a branch", select `main` and the `/ (root)` folder, and save.
3. After a minute the site is live at `https://<your-username>.github.io/<repository-name>/`.

## Placeholders to replace before launch

- **Sample figures** (95%, 99%, 250 kg/day, 30%): invented for layout review. Replace with validated lab data or remove the section.
- **Photo placeholders** in the Technology section: add real photos of the lab, equipment and team.
- **Backing strip** (MeitY, CIIC, DPIIT, MSME Udyam): currently text chips. Swap in the official logos.
- **Logo**: supply a vector (SVG) or high-resolution PNG.
- **Founder portraits**: use one consistent crop and background.

## Enquiry form

The form has no server behind it. "Send enquiry by email" opens the visitor's email app with the details filled in, addressed to greenoorscitech@gmail.com. To receive submissions directly, connect a form service such as Formspree or Netlify Forms, and use a company-domain email address instead of Gmail.
