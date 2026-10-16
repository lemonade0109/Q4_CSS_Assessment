# BCM Assessment Q4

Files:

- index.html
- styles.css

Screenshots:

- screenshots_desktop.png
- screenshots_mobile.png

Breakpoint: 768px.

## How I built it:

I put the HTML sections in this order: A, D, B, C, G, E, F, H.

That's the order they show up in on a phone. So on mobile, what you see is the same order a screen reader reads out loud, and the same order the Tab key moves through. Everything lines up.

## What happens on desktop:

On desktop, I used CSS to rearrange the boxes into three columns. The visual order changes. It becomes A, B, C on the top row, D, E in the middle, F, G, H on the bottom.

But the HTML order stays the same. CSS only changes where things look. It doesn't change the order the screen reader or Tab key follows.

## So on desktop:

A sighted user sees one order. A screen reader user hears a different order. That's a mismatch.

## Why I chose this:

I had to pick which layout to match the HTML to. I chose mobile because most people browse on phones. So on phones, nothing is confusing. On desktop, there's a mismatch, but it's the lesser problem.

## What I did with E, F, and H:

I hid them on mobile with display: none. That removes them completely, so screen readers skip them too. That's correct, because they're not part of the mobile layout.
