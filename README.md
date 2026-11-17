# Northstar Studio

A simple, multi-page business website for the fictional Northstar Studio.
The Home page introduces the studio and highlights its services. The About
and Services pages describe the studio and its offerings, and the Contact page
includes a project inquiry form.

## Pages

- [Home](index.html)
- [About](about.html)
- [Services](services.html)
- [Contact](contact.html)

All pages share [styles.css](styles.css), a header with navigation, and a footer.

## Local preview

Open `index.html` in a web browser. No installation or build step is required.

## Deployment

The site is hosted on [Netlify](https://m370d1-business-website.netlify.app).
Netlify is connected to the [GitHub repository](https://github.com/M370D1/BusinessWebsiteProject)
and deploys changes pushed to the `main` branch. The publish directory is the
repository root, and no build command is required.

The Contact form uses Netlify Forms. Submissions are available in the
project's Netlify dashboard; form processing requires a Netlify deployment and
does not work when opening the page directly from a local file.
