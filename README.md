### Digital Store — One-Page Digital Products Site

A modern, clean, and responsive single-page website to showcase and sell digital products without a traditional cart. Uses Tailwind CSS via CDN and placeholder images from `https://placehold.co`.

### Features
- **Hero**: Headline, description, and prominent CTA
- **Featured products**: 3 cards with image, title, description, price, and Buy button
- **How it works**: 3 simple steps with emojis
- **About / FAQ**: Brief intro and collapsible questions
- **Footer**: Social links and dynamic year
- **Responsive**: Mobile-first layout with Tailwind

### Requirements
- **Modern browser** (Chrome, Edge, Firefox, Safari)
- **Internet connection** for Tailwind CDN and placeholder images
- No build tools or server required

### Getting Started
1. Open `index.html` directly in your browser (double-click).
2. Optional: use a lightweight local server for best results:
   - VS Code: install “Live Server” extension, then “Open with Live Server”.
   - Python: `python -m http.server 5500` and open `http://localhost:5500/`.
   - Node: `npx serve` (or any static server) in the project folder.

### Customize
- **Products**: Edit product cards in `index.html` under the `#products` section.
- **Buy links**: Replace `href="#"` on “Buy Now” buttons with your payment URLs.
- **Branding**: Adjust colors and fonts in the Tailwind config block inside `<head>`.
- **Images**: Replace `https://placehold.co/...` with your product images.
- **Meta**: Update `<title>` and description meta tag in `<head>`.

### Deploy
- **GitHub Pages**: Push this folder to a repo and enable Pages (root).
- **Netlify / Vercel**: Drag-and-drop the folder, or connect the repository.
- **Any static hosting**: Upload files as-is; no build step needed.

### Notes
- This is a static site; there are no runtime dependencies or frameworks.
- Tailwind is loaded via CDN; to self-host or customize at scale, consider a build pipeline later.

### Author
Built for Ajay. Replace text and links to match your brand.

