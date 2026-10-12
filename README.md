# Sunday's Bloody Mary Mix: concept storefront

Static concept redesign of sundaysbloodymary.com. No build step: Vercel serves this folder as is.

- `index.html`: the whole page (styles and script inline)
- `f/`: 233 frames for the scroll-driven pour sequence
- `hero.mp4`, `hero.jpg`: hero loop and its poster
- `robots.txt`, `sitemap.xml`: crawler access, written for the production domain

Cart, checkout and email signup are demo placeholders for Shopify. Dashed tags on the page mark details the owners need to confirm.

## Before going live on the real domain

1. Remove `<meta name="robots" content="noindex">` from `index.html`.
2. Replace every dashed placeholder (shelf life, shipping rate, monthly box terms, founder story, location).
3. Check the product schema in the page head: prices, stock status and product URLs must match Shopify. Do not add star-rating markup unless ratings are per product.
4. Verify the site in Bing Webmaster Tools and Google Search Console, submit the sitemap, and turn on IndexNow.
5. Make the name, description, address and links identical on Google Business Profile, Facebook, Instagram, X and any retailer or directory listings.
6. Ask the awards (Drunken Tomato, NYC Bloody Mary Festival), stockists and local press to link to the site. Independent mentions do more for AI answers than anything on the page.
7. Review the facts block and FAQ each quarter and update the "last reviewed" date only when something was actually checked.
