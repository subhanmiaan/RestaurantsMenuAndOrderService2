# Stash Pizza

Red-and-white adaptation of RestaurantsMenuAndOrderService with the supplied Stash Pizza logo and menu. Plain HTML, CSS and JavaScript; no build dependencies.

## Run locally

Run `python3 -m http.server 8000` from this directory and open http://localhost:8000. Use a web server rather than opening files directly.

## Deploy to Vercel

1. Upload the contents of this folder to a new GitHub repository.
2. Import that repository in Vercel.
3. Select **Other** as the framework. Leave build and install commands empty, and use the repository root as the output directory.
4. Deploy. The included vercel.json supports all eight pages.

## Features

Home, menu, about, offers (menu picks), gallery, reviews, locations and contact; category filters, pizza sizes, portions, cart quantity controls, delivery/takeaway demo checkout, WhatsApp contact, mobile navigation, gallery lightbox, page transitions, scroll reveals and reduced-motion support.

## Content and launch notes

- Menu prices and both branch contacts are transcribed from the supplied menu. The bottom “Our Favourite” row has cropped item names and is omitted.
- Extra cheese and meat are separate menu add-ons with size-based prices. No unsupported crust choices are offered.
- The original site's checkout is a simulation. No order is sent, payment collected, or delivery booked. Delivery fee and timing are explicitly demo estimates. Connect an order backend before accepting real orders.
- WhatsApp contact opens a message draft for branch 1; users send it themselves.
- Photos are illustrative external images, and reviews are labelled samples. Verify official opening hours, delivery charges and social links before launch.
- Supplied logo and printed menu are local assets. All original Vercel project bindings and Git history are excluded so this can be deployed as a separate project.
