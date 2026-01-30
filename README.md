# Resume Builder

Simple client-side resume builder that previews a resume and exports it to PDF.

Files created:

- index.html
- css/style.css
- js/app.js


Usage:

1. Open `index.html` in your browser (double-click or use a local server).

2. Fill in your information. The preview updates in real time; you can also click **Update Preview**.

3. Click **Export to PDF** to open the print dialog and save as PDF. The app uses the browser print feature (no external libraries).

Notes:

- For best results, use Chrome or Edge and choose "Save as PDF" in the print dialog.
- Adjust print margins in the browser print dialog or tweak `css/style.css` `@media print` rules for layout.
- The UI is responsive: on small screens the preview stacks below the form.

New features:

- Extra personal fields: Age, Address, City/Country, LinkedIn/Portfolio.
- Education, Certifications, Projects, Languages, Awards sections (one-per-line).
- "Recommended Jobs" suggestions generated from resume content using a simple keyword/skill matcher.
- Click a suggested job to see matching reasons and highlight matched skills in the preview.


