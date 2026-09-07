# Portfolio

[![Netlify Status](https://api.netlify.com/api/v1/badges/65343cef-d79c-4fa3-90b7-bc99e4c0dedc/deploy-status)](https://app.netlify.com/projects/eahiyakhan/deploys)

Personal site for Eahiya Khan, full stack developer.
Live at [eahiyakhan.netlify.app](https://eahiyakhan.netlify.app).

## What this is

One static page. No framework, no build step, no dependencies. Open
`index.html` in a browser and it works.

```
index.html          the whole site, styles and script inline
assets/img/         project screenshots and the portrait
og-image.jpg        link preview card, 1200x630
Eahiya_Khan_CV.pdf  the CV the Download button serves
netlify.toml        security headers, long cache on images
robots.txt          crawler rules
sitemap.xml         single url
```

## Deploying

Netlify builds nothing. It serves the repository root as is, so a push to
`main` publishes the site.

```bash
git add -A
git commit -m "your message"
git push
```

## Changing the CV

Replace `Eahiya_Khan_CV.pdf`, keeping the filename, then commit and push.
The Download button in the hero links to that path.

## A note on the images

Project screenshots are taken from the live sites and resized to 1280x800.
Anything client owned is only included where the site is publicly reachable.
