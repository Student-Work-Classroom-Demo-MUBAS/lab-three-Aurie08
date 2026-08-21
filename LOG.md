## Error 1

**Task I was working on:** Task 3 — CSS Positioning

**What I was trying to do:**

I was trying to position the "NEW" badge in the top-right
corner of the card using position: absolute.

**The exact error or problem I saw:**

The "NEW" badge did not appear in the top-right corner
of the card. It appeared in the wrong position on the page.

**Steps I took to fix it:**

1. I inspected the card and badge using browser DevTools.
2. I checked the position properties of both elements.
3. I added `position: relative` to the `.card` element.
4. I refreshed the browser and checked the badge position again.

**What I learned from this:**

I learned that an absolutely positioned element is positioned
relative to its nearest positioned ancestor. Therefore, the
card needs `position: relative` so that the badge can be
positioned relative to the card.