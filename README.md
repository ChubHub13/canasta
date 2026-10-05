# Judd Game Night — Canasta

A three-player Hand & Foot Canasta game for Judd Game Night. It includes a live player, two bots, configurable house rules, round scoring, rolling into Foot, and clean/dirty book requirements.

## Files to publish

```text
index.html
assets/card-back.png
assets/player-portraits-reference.png
```

This is a static site: no build command, package manager, server code, or environment variables are required.

## Run locally

Open `index.html` in a browser.

## Deploy on Render

1. Push these files to the root of the `canasta` GitHub repository.
2. In Render, choose **New +** → **Static Site**.
3. Connect the `canasta` repository and use:
   - Build Command: leave blank
   - Publish Directory: `.`
4. Click **Create Static Site**.

Render will serve `index.html` automatically.
