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

## Error 2

**Task I was working on:** Task 1 — CSS Cascade & Specificity

**What I was trying to do:**

I was creating the heading for my Lab 3 page using an `<h1>` element.

**The exact error or problem I saw:**

I forgot the opening `<` before `h1`. I wrote `h1>ELE-IWS-521 Lab 3</h1>` instead of `<h1>ELE-IWS-521 Lab 3</h1>`. When I opened the page in the browser, the `h1>` part appeared as text on the webpage instead of being interpreted as an HTML heading.

**Steps I took to fix it:**

1. I looked at the text displayed in the browser.
2. I went back to my `index.html` file.
3. I checked the opening `<h1>` tag and noticed that the `<` symbol was missing.
4. I added the missing `<` symbol.
5. I saved the file and refreshed the browser.
6. The text was then correctly displayed as an H1 heading.

**What I learned from this:**

I learned that HTML tags must have the correct opening and closing syntax. A missing `<` can cause the browser to interpret what I intended to be an HTML tag as ordinary text.