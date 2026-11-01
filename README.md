# Virtual business card

Contact page for Kristiina Martin, Project Officer, Circular Economy, at EIT RawMaterials GmbH.

Live at: https://kristiinamartin.github.io/businesscard/

## Files

- `index.html`: the card page (all text and styling are in this one file)
- `kristiina-martin.vcf`: the contact file behind the "Save contact" button
- `qr.png` / `qr.svg`: QR code that opens the page. Use the SVG for print, the PNG for slides and email signatures
- `fonts/`: Titillium Web (the typeface named in the EIT Community web design guidelines), hosted here so no visitor data goes to a font service

## Publishing

In the GitHub repo, open Settings, then Pages. Under "Build and deployment", set Source to "Deploy from a branch", choose `main` and `/ (root)`, and save. The site goes live within a minute or two.

## Changing details

Edit the phone, email or address in both `index.html` and `kristiina-martin.vcf` so the page and the saved contact stay in sync. If the page address changes, the QR code has to be regenerated.

The page asks search engines not to list it, so it is only found through the QR code or the link.
