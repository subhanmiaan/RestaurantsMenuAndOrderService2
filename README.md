<div align="center">

# STASH PIZZA 🍕

**A bold red-and-white restaurant experience, built for browsing, discovery and motion.**

Eight pages · Size-aware menu · Demo checkout · WhatsApp contact

![HTML](https://img.shields.io/badge/HTML5-Static_site-C5162E?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-Responsive-3D1019?style=flat-square&logo=css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=flat-square&logo=javascript&logoColor=111111)

[Features](#features) · [Run locally](#run-locally) · [Deployment](#deployment) · [Content notes](#content--demo-boundaries)

</div>

## Overview

Stash Pizza adapts the [GOODFILLERS restaurant project](https://github.com/subhanmiaan/RestaurantsMenuAndOrderService) to a new restaurant identity, using the supplied Stash Pizza logo, printed menu and branch information.

The implementation uses **HTML, CSS and vanilla JavaScript**. There are no build dependencies, API keys or database requirements. Ordering is a **frontend simulation**, not a live fulfillment service.

## Features

- Categorized menu with pizza sizes and applicable portion selectors.
- Size-aware extra cheese and meat add-ons.
- Session-persistent bag with quantity controls and item removal.
- Delivery and takeaway demo checkout with native form validation.
- WhatsApp contact that prepares a message for the visitor to send.
- Gallery filters and lightbox, sample-review carousel and mobile navigation.
- Page transitions, scroll reveals, image parallax, card tilt and add-to-bag motion.
- Reduced-motion support and keyboard focus styles.

## Pages

| Page | Route |
|---|---|
| Home | `/` |
| Menu | `/menu/` |
| About | `/about/` |
| Offers / menu picks | `/offers/` |
| Gallery | `/gallery/` |
| Reviews | `/reviews/` |
| Locations | `/locations/` |
| Contact | `/contact/` |

A custom `404.html` is also included.

## Run locally

Install Python 3 or use your preferred static web server.

```bash
git clone https://github.com/subhanmiaan/RestaurantsMenuAndOrderService2.git
cd RestaurantsMenuAndOrderService2
python3 -m http.server 8000
```

Open **http://localhost:8000**. Root-relative routes require a web server; avoid opening HTML files directly.

## Source guide

| Location | What to edit |
|---|---|
| `app.js` | Menu data, reusable sections, page content and interactions |
| `style.css` | Red-and-white theme, layouts and animation |
| `index.html` and route HTML files | Shared shell and static page content |
| `assets/logo.jpg` | Supplied restaurant logo |
| `assets/printed-menu.jpg` | Original printed menu |
| `vercel.json` | Hosting configuration |

Keep generated or static page content aligned with the shared JavaScript when changing the menu or page copy.

## Deployment

Import the repository into Vercel with the **Other** framework preset. Leave the build and install commands empty, and use **`.`** as the output directory. No environment variables are needed. The included configuration supports trailing-slash page URLs.

This repository is ready for static hosting at a domain root. A GitHub Pages project subdirectory requires path adjustments.

## Content & demo boundaries

- **No real orders or payments:** checkout generates a demo confirmation only. Delivery charges and timing are demo estimates.
- **WhatsApp is a draft:** the visitor reviews and sends the prepared message themselves.
- **Source menu:** prices and both branch contacts are transcribed from the supplied menu. The cropped “Our Favourite” row was omitted because item names were not readable.
- **Menu fidelity:** add-ons use size-based prices; unsupported crust options are not offered.
- **Illustrative media:** food and lifestyle photography use external image hosts; reviews are labeled samples.
- **Before commercial launch:** verify restaurant details, social accounts, hours, prices, delivery terms and the ordering workflow.
- Original deployment bindings are excluded so this project can be configured independently.

## Suggested review

Check the menu at mobile and desktop widths, add different pizza sizes, adjust quantities, switch delivery/takeaway, test keyboard navigation and reduced-motion preferences, and confirm that the WhatsApp draft opens with the expected details.

---

By [**Muhammad Subhan**](https://github.com/subhanmiaan) · [Email](mailto:wsubhan5969@gmail.com)
