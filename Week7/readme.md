# Week 7: Landing Page Header with Flexbox

## What I built
The top of a portfolio website for Jwaydeep Sagar: a navbar, a centred banner
and a row of three cards. Everything is laid out with Flexbox only.

## Flexbox used
- display: flex on the navbar, banner, cards, banner buttons and footer
- justify-content and align-items to place the logo, menu and centred banner text
- flex-direction: column for the banner and landing-top wrapper
- flex-wrap: wrap with flex: 1 1 200px so the cards drop to the next line on small screens
- flex: 1 so the banner fills the first screen under the navbar

## Class naming
BEM style, for example navbar__logo, banner__title, card__text and banner__button--ghost.

## Testing
| Size | Width | Result |
|---|---|---|
| Desktop | 1280px | Navbar in one row, 3 cards in one row |
| Tablet | 768px | 3 cards in one row, tighter spacing |
| Phone | 375px | Navbar stacked, cards stacked one per line |

Screenshots: desktop.png, tablet.png, phone.png