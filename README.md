# FOODY

A food delivery web app demo, built as **one self-contained `index.html`**: plain HTML, CSS and vanilla JavaScript, with no frameworks, packages, build step or network requests.

## Run it

Open `index.html` in a modern browser. That's it.

## What's inside

- **Discover** 8 restaurants with search, cuisine filters, sorting and a free-delivery toggle
- **Menus** with photos, category tabs that follow your scroll, and quantity steppers
- **Cart** with live totals (delivery, platform fee, GST), a one-restaurant-per-cart rule and `localStorage` persistence
- **Checkout** with inline validation, Cash on Delivery or a simulated, animated Demo UPI payment
- **Order tracking** on an illustrated, zoomable map with a rider that moves along the route and a five-step timeline
- **Dark mode** (follows the system, with a manual toggle) and small interaction animations throughout
- Respects `prefers-reduced-motion`, keyboard accessible, and responsive from desktop to small phones

## Demo only

Restaurants, menus and prices are sample data. Payment, order placement, the map and rider location are **simulated in the browser**. No real restaurant or rider receives an order and nothing is charged.

## Structure

Everything lives in `index.html`, organised into commented sections: design tokens and styles, the app shell, views (discover, menu, checkout, tracking), an embedded JSON block of product photos (base64 JPEG), and the JavaScript (data, state, rendering, events, order simulation).
