# Electronic Shop (Front-End)

A static front-end for an electronics online store. It shows a home page with a hero banner, offers, and product listings, plus About, Contact, Login, and Register pages. It is built with plain HTML, a custom CSS file, and Bootstrap 5.

This is a design and UI prototype. It has no backend, database, or working cart, so the forms and buttons do not submit or save data yet.

## Pages

- **index.html (Home):** Navigation bar with a product dropdown, search box, hero banner with "Shop Now" buttons, a product grid, promotional banners ("Up To 50% Off"), category tiles, and a footer.
- **about.html (About):** Company introduction, service highlights (free shipping on orders over $1000, free returns within 30 days, fast worldwide delivery, wide product choice), and a newsletter signup.
- **contact.html (Contact):** Contact details and a message form with Name, Email, and Phone fields.
- **login.html (Login):** Login form with User Name and Password fields and a "Forgot Password" link.
- **register.html (Register):** Sign-up form with Name, User Name, Phone, Email, and Password fields.

## Product Categories

The navigation dropdown lists: Smart Phone, Mobile Phone, Cameras, Fridge, AC, Smart Watch, Headphone, Laptop, and PC Monitor.

Sample products on the home page include iPhone 13 Pro, iPhone X, AirPods, Laptop, iPad, Smart Watch, PC Monitor, Headphone, Washing Machine, AC, Microwave Oven, Fridge, Fan, and Gaming PC. Prices are static sample values.

## Tech Stack

- HTML5
- CSS3 (`style.css`)
- Bootstrap 5.0.2 (loaded from jsDelivr CDN): grid, navbar, dropdowns, and buttons
- Font Awesome 6.2.0 (loaded from cdnjs)
- Google Fonts (Merriweather)

## Project Structure

```
electronic shop/
├── index.html
├── about.html
├── contact.html
├── login.html
├── register.html
├── style.css
└── images/        # Product, category, banner, and icon images
```

## Getting Started

No build step or installation is needed.

1. Download or clone the repository.
2. Open `electronic shop/index.html` in a web browser.

An internet connection is needed to load Bootstrap, Font Awesome, and Google Fonts from their CDNs.

## Current Limitations

- **Cart does not work:** The "Add to Cart" buttons have the class `add-to-cart`, but no JavaScript file is included to handle them.
- **Search does not work:** The search form is not connected to any logic.
- **Login and register do not save data:** There is no authentication backend.
- **Contact and newsletter forms do not send messages:** The subscribe and message buttons have no submit handler.
- **Placeholder content:** Some text is still generic (for example, "Lorem ipsum", "[Industry Name]", and "+0000000000000000000"). Several links use `href="#"`.
- **Typos in visible text:** Examples include "Samrt Phone", "ELCTRONIC", "Usefull Links", "Privacy policey", and "amanzing".

## Suggested Next Steps

- Add a `script.js` file for cart behavior, such as storing items in `localStorage`.
- Fix the typos and replace placeholder text and contact details.
- Replace the `#` links with real pages.
- Connect the login, register, and contact forms to a backend.
- Add a README image preview of the pages in `images/`.
