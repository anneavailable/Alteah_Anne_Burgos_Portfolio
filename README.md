# Alteah Anne Q. Burgos — Portfolio Website

A responsive portfolio site built with plain HTML, CSS, and JavaScript. Your personal details and portfolio content are already filled in.

## Included
- `index.html` — portfolio content, metadata, and structured data
- `styles.css` — responsive plum-and-pink styling
- `script.js` — mobile navigation, theme toggle, project search/filter, contact email, and active section navigation
- `images/` — add your profile and project images here
- `assets/favicon.svg` — browser tab icon
- `robots.txt` and `sitemap.xml` — basic search-engine discovery files

## Add your images
Copy image files into the `images` folder and use these exact filenames:

1. `profile.jpg` — your profile photo
2. `brew-haven.png` — Brew Haven café-themed design
3. `vertical-logo.png` — Vertical Logo — About Me
4. `horizontal-logo.png` — Horizontal Logo — About Me
5. `icon-logo.png` — Icon Logo — About Me
6. `qed-club-logo.png` — QED Club Logo
7. `eaterlist-website.png` — Eaterlist website screenshot

The website shows a styled placeholder if an image is missing. You can use JPG, PNG, or WebP, but if you choose another filename or extension, update the corresponding `src` in `index.html`.

## Open in VS Code
1. Extract the ZIP file.
2. Open the extracted `Alteah_Portfolio_Website` folder in VS Code.
3. Recommended: install the **Live Server** extension.
4. Right-click `index.html` and choose **Open with Live Server**.

## Deploy for a public URL
This is a static website, so it does not need a build step or backend. You can deploy it using GitHub Pages, Netlify, or Cloudflare Pages.

### GitHub Pages
1. Create a GitHub repository.
2. Upload the contents of this folder so `index.html` is at the repository root.
3. Open **Settings → Pages** and select your publishing source.
4. After publishing, your site will have a public URL.

### Search-engine indexing
The site includes a page title, meta description, robots.txt, sitemap.xml, and Person structured data. A website is not searchable just because the code has SEO metadata; you must deploy it first, and indexing can take time.
After deployment, replace `https://your-domain.example/` in `sitemap.xml` and `robots.txt` with your actual public URL. You may also submit the sitemap in Google Search Console.

## Contact form note
The contact form now submits through FormSubmit to `aqburgos@ccc.edu.ph` without opening the visitor's email app. **Important:** on the first test, FormSubmit may send an activation/confirmation email to that inbox. Open it and confirm the form before expecting messages to arrive. The deployed website needs an internet connection for this service. If the form service is not activated or unavailable, the page shows a fallback message telling visitors to email you directly.

## Your details already included
- Alteah Anne Q. Burgos
- IT Student & Aspiring UI Designer
- Third-year BSIT student
- City College of Calamba
- Calamba, Laguna
- aqburgos@ccc.edu.ph
- 09633272077
- Graphic design / logo design experience
- Eaterlist front-end website project
- NC II, Wadhwani Foundation, freeCodeCamp, and Cisco Packet Tracer credentials


## CV PDF buttons (important)
The website now includes prominent **Download CV** and **View CV Online** buttons in the hero area and a dedicated CV section.

Upload your latest CV PDF into the `cv/` folder and name it exactly:
`Alteah_Anne_Q_Burgos_CV.pdf`

Expected path: `cv/Alteah_Anne_Q_Burgos_CV.pdf`

Both buttons already point to this file:
- **Download CV (PDF):** downloads the PDF.
- **View CV Online:** opens the PDF in a new browser tab.

The current CV PDF is included at the expected path in this ZIP. The Download CV links use a direct relative PDF link with the HTML download attribute. This works when you open `index.html` directly from the extracted folder on your computer (`file://`) and does not require deployment or internet access. View CV Online opens the same PDF in a new tab. If you replace the CV later, keep the exact filename so both buttons continue working.

### Test locally (no deployment required)
After deploying the updated site and the PDF:
1. Extract the ZIP completely (do not open `index.html` from inside the ZIP preview).
2. Keep the `cv` folder beside `index.html`.
3. Double-click `index.html` to open the portfolio in your browser.
4. Click **Download CV**; the browser should download `Alteah_Anne_Q_Burgos_CV.pdf`.
5. Click **View CV Online** to open the PDF separately. No deployment or internet connection is needed for either action.


## Latest updates
- Kept all existing image files unchanged.
- Added clickable project-image previews with a lightbox and Escape-to-close support.
- Fixed project image framing to show the full design instead of cropping/zooming it.
- Used `images/icon-logo.png` for the navbar and footer logo.
- Added Facebook and Instagram links in the contact section and footer.
- Added reveal animations, hover details, and responsive adjustments for desktop/tablet/mobile (including around 1200px, 720px, and 360px widths).
- Updated the contact form to submit through FormSubmit to `aqburgos@ccc.edu.ph`; first-time activation may be required.


## Latest interface updates
- Project previews open in an accessible gallery with a reusable placeholder for additional screenshots or design variations.
- Certificate previews open centered, with a placeholder for adding another certificate scan or photo later.
- Responsive layout uses balanced side gutters and full-width header sizing at desktop, tablet (720px), and mobile (360px) breakpoints.
- The close button stays fixed at the upper-right of the image viewer.

## Latest portfolio polish (October 2026)
- Added a few low-opacity ribbon decorations across the page background.
- Updated the project and certificate lightbox to respect each image's natural proportions, keeping complete logos and certificate scans visible.
- Improved both Download CV actions to fetch the same-site PDF and trigger a named file download, with a native-download fallback.


## CV download + animation update (October 2026)
- Download CV now preloads and validates the actual PDF, converts it into an `application/pdf` Blob, and triggers a named device download (`Alteah_Anne_Q_Burgos_CV.pdf`) from the Download CV controls.
- The CV buttons remain separate: Download CV saves a file; View CV Online opens the PDF in a browser tab.
- Keep `cv/Alteah_Anne_Q_Burgos_CV.pdf` deployed at that exact relative path alongside `index.html`. Deploy the entire folder together; do not upload only the HTML file.
- Added staggered scroll reveals, refined hover lift and shimmer, drifting ribbons, twinkling accents, and gentle ambient motion. Reduced-motion preferences are respected.
