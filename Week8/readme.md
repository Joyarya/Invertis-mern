# Week 8: Dashboard with CSS Grid

## What I built
A project manager dashboard called Planly with a top bar, a side menu, a main
area and a footer. The main area holds four stat boxes that re-arrange themselves.

## Grid used
- display: grid with grid-template-columns (fixed side menu and 1fr main) and gap
- grid-template-rows: auto 1fr auto so the footer stays at the bottom
- grid-template-areas with the names head, side, main and foot
- repeat(auto-fit, minmax(150px, 1fr)) so boxes wrap with no media query
- Flexbox inside each box to put the icon and text side by side
- On small screens only the grid-template-areas drawing changes, not the HTML

## Class naming
BEM style, for example topbar__brand, sidebar__link--active and stat__value.

## Testing
| Size | Width | Result |
|---|---|---|
| Desktop | 1280px | Side menu left, 4 boxes in a row |
| Tablet | 768px | Single column, 4 boxes in a row |
| Phone | 375px | Single column, boxes in 2 by 2 |

Screenshots of the Grid inspector: grid-layout.png and grid-boxes.png