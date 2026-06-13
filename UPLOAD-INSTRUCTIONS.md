# Somewhen Survival Society — Website Update

This bundle contains everything new for the site. Three pages now, all sharing one
cohesive menu (Home · Past Events · Tickets · About Us · Contact).

## What's in this folder

| File / folder            | What it is                                              |
|--------------------------|---------------------------------------------------------|
| `index.html`             | **Replaces** your existing index.html. New Harvest Moon Chapter events + holding line. |
| `past-events.html`       | **New page.** "Reconnect with the Land" report + photo gallery + Kimmi's quote. |
| `about.html`             | **New page.** Project story + team photo with click-to-reveal bios. |
| `images/`                | **New folder.** 12 optimised images used by the pages (gallery, team, faces, logo). |

## How to upload to GitHub (web interface)

1. Go to your repository on github.com.
2. Click **Add file → Upload files**.
3. Drag in **`index.html`**, **`past-events.html`**, **`about.html`**, and the whole
   **`images`** folder together. (Dragging the folder keeps the `images/` structure,
   which the pages rely on.)
4. When it asks, choose **"Replace"** for `index.html`.
5. Scroll down and click **Commit changes**.

That's it — GitHub Pages will rebuild and your new pages go live in a minute or two at
your domain (`somewhensurvivalsociety.org`).

## Keep these existing files (don't delete them)

The pages still use the files already in your repo, so leave them in place:

- `CNAME` (your custom domain)
- `Vensfolk.otf` (the site font)
- `favicon.ico`
- `SWSC.mp4` and `SWSC-portrait.mp4` (homepage hero video, desktop + mobile)
- `LANDSCAPE OVER FILM.jpg` and `PORTRAIT on black.jpg` (video poster frames)
- `README.md`, `sss animation .mp4`

## Notes

- **Booking:** the three Harvest Moon shows (Shalfleet 19 Sept, Niton 26 Sept,
  Freshwater 3 Oct) show a "Booking opens in early July" holding banner and a
  "Booking July" tag instead of ticket buttons. When your Eventbrite links are ready,
  send them over and I'll drop them straight in (each `<span class="booking-soon">Booking July</span>`
  becomes a link, exactly like the old spring walk cards).
- **Team bios:** on About Us, the four faces below the group photo are clickable —
  selecting one reveals that person's bio and their link. It defaults to showing Peter.
- All new images are resized and compressed for fast loading (~3.4 MB total for all 12).
