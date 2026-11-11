# RV Resin Gifts

A responsive, static catalogue and enquiry website. No paid services, build dependencies, database or server are needed.

## Preview

From this folder run `python3 -m http.server 8080 --directory public`, then visit http://localhost:8080.

## Deploy on Render

1. Upload this folder's contents to a GitHub repository (keep `render.yaml` and `public` at the repository root).
2. Sign into Render and choose **New → Static Site**, then connect the repository.
3. Build command: `echo "Static website ready"`
4. Publish directory: `public`
5. Create the static site. Render provides an HTTPS `onrender.com` URL.

Alternatively use Render's **New → Blueprint** and select the repository to use `render.yaml`.

Render documentation: https://render.com/docs/static-sites . Static hosting is free subject to Render workspace usage allowances.

## Before launch

- Replace original concept SVG artwork in `public/assets` with actual business product photos; update image paths, alt text and illustration notices in `public/index.html` and `public/app.js`.
- Verify the supplied Instagram handle. Set the business WhatsApp number in `public/config.js` (country code, digits only) to switch enquiry messages to WhatsApp.
- Confirm product availability, delivery terms and business copy. No made-up prices or customer reviews are included.
- Enquiry bag stores product IDs in the visitor's browser. The custom form prepares a message locally; it does not submit orders. The visitor reviews and sends through Instagram or WhatsApp. There is no online payment processing.
- Typography uses Google Fonts with local system font fallbacks. Product artwork is bundled locally.

## Edit

`public/index.html`: page copy and sections. `public/styles.css`: appearance and responsive layout. `public/app.js`: catalogue and enquiry behavior. `public/config.js`: contact channel. Artwork is original vector concept imagery.
