# ORGANIZM — Fitness Club Website

Multi-page website for the ORGANIZM sports club: training directions, class schedule, coaches, opening hours, club rules, membership prices and a gallery of the space. Dark design with large display typography and scroll animations.

## Pages

| File | Content |
|---|---|
| `index.html` | Main page: hero, training directions, class schedule, team, opening hours, club rules |
| `prices.html` | Membership prices |
| `price_v2.html` | Alternative layout of the price page |
| `gallery.html` | Zones and equipment of the club |

## Stack

Static HTML, Tailwind CSS (CDN, theme in `js/config.js`), GSAP with ScrollTrigger, Lucide icons. No build step.

```bash
npx serve .
```

Brand colours and fonts are configured in `js/config.js`, custom styles in `css/style.css`, interactions in `js/main.js`.

A copy of this site is part of the [template store](https://github.com/vadymzelenko/templates_store) (`public/projects/organizm`).

© Vadym Zelenko. Client project; texts, logo and contact details belong to the club.
