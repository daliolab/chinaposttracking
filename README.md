# China Post Tracking — Version 1 Template

This repository contains the first-version website template for ChinaPostTracker.com. It explores how a parcel tracking site can serve two common needs: checking a shipment quickly and understanding what a carrier update actually means. The three pages connect those tasks through a shared layout, so a visitor can move between the tracking form and a guide without losing their place in the site.

## About ChinaPostTracker.com

[China Post Tracker](https://www.chinaposttracker.com/) is a parcel tracking website for China Post, EMS, and ePacket shipments. Visitors can enter a tracking number to see the latest available shipment updates without creating an account. The site also publishes guides about tracking-number formats, delivery times, customs clearance, and handoffs to local delivery carriers. These articles give readers context when a scan is unclear or when tracking has gone quiet between facilities. Use the live website to look up an actual shipment or read the current guides.

## What the template includes

- [Tracking homepage](parcel-tracking.html) — A labelled tracking form, a sample shipment summary with a waybill-inspired layout, a shipment timeline, and answers to common tracking questions.
- [Guide index](parcel-guides.html) — An article listing layout with a featured guide and space for more entries as the guide library grows.
- [Article detail page](parcel-guide-tracking-statuses.html) — A sample article explaining parcel tracking statuses, with a linked table of contents and a clear route back to the tracker.

The pages share a paper-white background, dark navy type, and a shipping-orange accent drawn from the visual language of parcel labels. The layout adapts to narrower screens by stacking the tracking form and shipment preview, and by placing the article contents below the title and introduction. The form uses a visible label and gives feedback for missing or unsupported entries.

## Preview locally

Clone or download this repository and open `parcel-tracking.html` in a browser. Keep the HTML files and `parcel-guides.css` together so the links and styles resolve. Select **Try a sample tracking number** or enter `PR123456789` to see the demonstration timeline. Open **Guides** in the navigation to visit the article list and follow the featured link to the sample article.

The template runs as static HTML, CSS, and JavaScript with sample shipment data. It requires no build step, account, or API key. For current carrier updates, visit: `www.chinaposttracker.com`
