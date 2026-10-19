# Little Stitch Studio

Website for Little Stitch Studio, a small business selling hand-knitted scarves made to order.

Customers design their scarf in the browser and see a live preview as they choose:

- **Style:** classic scarf or infinity loop
- **Yarn:** lambswool, merino or alpaca blend, in fine, medium or chunky thickness
- **Size:** preset sizes plus length and width sliders
- **Colours:** a main colour and a pop colour
- **Stitch pattern:** classic knit, ribbed, seed stitch, stripes, cable knit or little hearts
- **Ends:** neat edge, fringe, chunky tassels or pom-poms
- **Extras:** a sewn-on name tag and a gift box

The page shows a live price and an estimated ship-by date, then builds an order request the customer copies and sends.

## Running it

It's a single static file with no build step. Open `index.html` in a browser, or host it on any static host such as GitHub Pages.

## Things to set before going live

- `WHATSAPP_NUMBER` near the top of the script in `index.html`: add your WhatsApp business number (country code and digits only, for example `919820000000`) to show a "Send on WhatsApp" button on the order screen.
- Prices (`rate` per square metre for each yarn, and the add-on prices) and knitting times live in the `WOOLS`, `YARNS`, `PATTERNS` and `FRINGES` lists in the same script.
