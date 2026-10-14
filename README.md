

A responsive, GitHub Pages-ready personal portfolio built with plain HTML, CSS and JavaScript.

## Structure

```text
cybersecurity-portfolio/
├── index.html
├── assets/
│   ├── profile.jpg
│   └── cv.pdf
├── css/
│   └── style.css
├── js/
│   └── script.js
└── README.md
```

## Run locally

Open `index.html` directly in a browser, or use VS Code Live Server.

## Deploy to GitHub Pages

1. Create a GitHub repository, for example `portfolio`.
2. Upload `index.html`, the `css` folder and the `js` folder.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select your main branch and `/root`.
6. Save and wait for GitHub Pages to publish.

## Customize

Search `index.html` for:
- `your.email@example.com`
- `https://github.com/`
- `https://www.linkedin.com/`

Replace those placeholders with your real links.

You can also replace project descriptions, add screenshots, and connect each project card to its actual repository.


## Add your photo and CV

Place your files in the `assets` folder:

- `profile.jpg` — your profile photo. A square portrait works best.
- `cv.pdf` — your actual CV. The **Download My CV** button is already linked to this file.

For the best profile-photo result, use a clear head-and-shoulders photo with good lighting.


### Important: photo filename

The current HTML expects the photo to be exactly:

```text
assets/AYJ.jpeg
```

GitHub Pages is case-sensitive, so `AYJ.jpeg`, `ayj.jpeg`, and `AYJ.JPG` are different filenames.


## Certificates

Certificate images go in:

```text
assets/certificates/
```

The starter layout supports six certificates:

```text
cert-1.jpg
cert-2.jpg
cert-3.jpg
cert-4.jpg
cert-5.jpg
cert-6.jpg
```

Edit the certificate name, description, year and issuer directly in `index.html`.
Copy a certificate card if you want to add more.
