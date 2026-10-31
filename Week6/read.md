# Week 6: Profile Card (Box Model, Display and Positioning)

## What I built
A profile card for Jwaydeep Sagar with a circle avatar, a scrolling bio box,
a sticky top bar and a fixed floating + button. Three colour versions share
one card class and only change CSS variables.

## Concepts used
- box-sizing: border-box, padding, border, margin, border-radius
- overflow: auto on a fixed-height bio box
- position: sticky (top bar) vs position: fixed (+ button)
- z-index: top bar 100, + button 200

## Class naming
Block__element--modifier, for example profile-card__avatar and profile-card--teal.

## Testing checklist
- [x] DevTools box model screenshot saved as box-model.png
- [x] Avatar stays a circle (object-fit: cover)
- [x] Bio box scrolls, card height does not change
- [x] Top bar stays on screen while scrolling
- [x] + button stays bottom-right and is not hidden behind cards
- [x] Checked phone width with the device toolbar (Ctrl+Shift+M)