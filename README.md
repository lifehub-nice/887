# 887 Studio — site vitrine

Site statique bilingue FR / EN pour 887 Studio.

## Lancer en local

```bash
cd 887-studio-site-v11-logo-integrated
python3 -m http.server 5173
```

Puis ouvrir :

```text
http://localhost:5173
```

## Déployer sur Vercel

```bash
cd 887-studio-site-v11-logo-integrated
vercel --prod
```

## Formulaire de contact

Le formulaire utilise FormSubmit avec l’adresse :

```html
https://formsubmit.co/vbenoist@gmail.com
```

Au premier envoi, FormSubmit peut demander de confirmer l’adresse email de réception.

## Modifier les liens des participations

Dans `app.js`, modifier `projects.fr` et `projects.en`, champ `link`.


## V3 changes

- SVG monogram replaced by text-based 887 mark.
- Floating labels removed.
- Background black thread / serpentine line added.
- Typography changed to DM Serif Display + Manrope, with more readable spacing and line-height.

## V4 changes

- Removed the standalone strategy-to-movement statement block after the hero.

## V5 changes

- Removed the participations section title.
- Replaced the working section title with “Producteur de mouvement.” / “Producer of movement.”

## V6 changes

- Reduced large display title sizes across the landing.
- Reduced participation card titles, method titles and oversized numeric headings.

## V7 changes

- Contact form now posts to `https://formsubmit.co/vbenoist@gmail.com`.
- Removed the Formspree placeholder note.

## V8 legal changes

- Added `mentions-legales.html`.
- Added footer link to legal notice.
- Added publisher information: Vincent BENOIST Entrepreneur individuel, SIRET 900 588 765 00017.
- Added Vercel hosting information.
- Added basic privacy/contact-form notice.

Domiciliation address completed: 17 rue Gioffredo, 06000 Nice, France.

## V9 changes

- Legal page updated with domiciliation address: 17 rue Gioffredo, 06000 Nice, France.
- Domain planned: 887studio.fr.

## V10 changes

- Science Brief renamed to Praxio.
- BECOME renamed to Blue Hour.
- BizGame repositioned as AI deployment consulting for customer experience.
- Project cards now align content from the top.
- Added a logo placeholder area on each project card.
- Added a small 887 stamp on each project card.

## V11 changes

- Added new smoothed 887 logo as `assets/887-logo-smooth.svg`.
- Integrated the new logo into the website header and legal page header.
- Replaced the working-section text mark with the new SVG logo.

## V12 changes

- Added `assets/887-logo-slick.svg` based on the latest uploaded logo.
- Set Ventures and Growth area on a black background.
- Added “VENTURE & GROWTH STUDIO” under the 887 logo in the final black block.

## V13 changes

- Removed manifesto line: “Moins de bruit. Plus de signal. Moins de théâtre. Plus de mouvement.”
- Restored Ventures & Growth / Two pillars section to a light background.
- Added 887 logo + “VENTURE & GROWTH STUDIO” at the very top of the landing hero.

## V14 changes

- Desktop navigation now shows 887 logo + “VENTURE & GROWTH STUDIO”.
- Desktop navigation reduced to À propos / Participations / Contact + FR/EN.
- Desktop navigation bar is hidden on mobile.
- Mobile keeps a standalone FR/EN toggle.
- Top hero keeps 887 logo + “VENTURE & GROWTH STUDIO”.
- Includes previous V13 removals/light pillars.
