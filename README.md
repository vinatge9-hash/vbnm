# Niyantri Care - Dog Care Website

A ready-to-run static multi-page website for a modern dog care brand.

What you get
- 5 main pages (plus a Checkout page for PayPal integration):
  - index.html (Home)
  - menu.html (Dog Care Menu)
  - cart.html (Cart with localStorage persistence)
  - about.html (About/Niyantri Care)
  - contact.html (Contact page with placeholder Hyderabad address)
  - checkout.html (PayPal Sandbox integration in USD)
- Tailwind CSS via CDN, responsive navigation with a mobile hamburger menu
- Page-load fade-in animation and scroll-reveal effects (via Tailwind classes)
- Inline SVG icons and placeholder images
- PayPal Sandbox integration (client-id=sb) for demo checkout
- Placeholder content tailored to Hyderabad, India
- README with setup and usage notes

How to run (local)
1) Save all files in a single project folder.
2) Open index.html in a modern browser.
3) Navigate through Home, Menu, Cart, About, and Contact.
4) Add items to the cart from Menu.html. The cart uses localStorage to persist data across pages.
5) Go to Checkout to see the PayPal Sandbox flow. A successful demo will clear the cart.

Notes
- This is a front-end demo. For real deployments, replace the PayPal sandbox client-id with your live credentials and implement server-side order validation.
- All content uses the provided current year 2025 for copyright notices.
