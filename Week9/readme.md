# Week 9: Responsive Landing Page (Planly)

## What I built
A responsive landing page for a made-up project manager called Planly, with a
navbar, hero, features, pricing and footer. It works on phone, tablet and laptop.

## Responsive techniques used
- Mobile-first: the normal CSS is the phone layout; media queries use min-width
- Viewport meta tag so phones use their real width
- Media queries at 768px (tablet) and 1024px (laptop)
- max-width: 100% and height: auto on images, plus aspect-ratio and object-fit on the hero image
- rem units for font sizes
- CSS variables for colours and spacing; the media queries change --page-pad and --section-space
- Grid for the hero, features and pricing sections
- Flexbox for the navbar, the footer and inside each pricing card

## Class naming
BEM style, for example navbar__links, hero__title and plan--featured.

## Testing
| Screen | Width | Result |
|---|---|---|
| Phone | 375px | One column, navbar wraps to two rows, no sideways scroll |
| Tablet | 768px | Navbar in one row, 3 cards per row |
| Laptop | 1280px | Hero side by side, content centred |

Screenshots: phone.png, tablet.png, laptop.png