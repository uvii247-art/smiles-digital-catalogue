# SMILE'S DIGITAL CATALOGUE

A mobile-friendly static product catalogue built with plain HTML, CSS and JavaScript. It is designed to work on Android phones and can be hosted free with GitHub Pages.

## Quick setup

1. Open `index.html` in a browser, or publish the repository with GitHub Pages.
2. In `script.js`, edit the `WHATSAPP_NUMBER` value. Use digits only, including the country code (for example, `2348012345678`).
3. Replace the 12 objects in the `products` array with your real products.
4. For every product, update `name`, `category`, `price`, `description`, `options`, and `colors`.
5. Replace each `image` value with a path to a real image, for example `assets/my-product.jpg`.
6. Add your real WhatsApp number, email and delivery information in `index.html`.
7. Upload the changed files to GitHub. GitHub Pages will update automatically.

## Recommended customer product fields

```js
{
  id: 13,
  name: 'Your Product Name',
  category: 'Fashion',
  price: 25000,
  image: 'assets/your-product.jpg',
  description: 'A short, clear benefit-focused description.',
  options: ['S', 'M', 'L'],
  colors: ['Black', 'Cream']
}
```

## Android workflow

Use the GitHub Mobile app or github.com in Chrome to edit `script.js` and `index.html`. For multiple images, upload them into the `assets` folder. Keep image files compressed (ideally under 300 KB each) so the catalogue loads quickly on mobile data.

## Important before sharing

- Change the sample phone number and placeholder email.
- Confirm prices, stock, delivery fees and payment instructions.
- Replace sample SVG images with your own product photography.
- Test every WhatsApp link from your own phone.
- This is a catalogue/demo, not a payment checkout; confirm orders manually on WhatsApp.
