# Addis Ababa Landing Pages

Bilingual (Amharic/English) landing pages for established Addis Ababa businesses, built as part of a speculative landing page program.

## Projects

### Peacock Shoe Factory (Dire Industries PLC)
Leather footwear manufacturer in Addis Ababa, operating since 1994, exporting to Italy, Germany, and across Europe.
- `peacock-shoe-factory/index.html`

### Enrico Pastry
Historic Italian pastry shop in Piassa, Addis Ababa, serving the community since 1954.
- `enrico-pastry/index.html`

## Features
- Bilingual with an EN/AM toggle, Amharic as default language
- Smooth block-level scroll animations (AOS)
- Industry-specific creative design elements
- Real stock photography (Pexels)
- Fully responsive, no build step required

## Deploying
Each folder is a self-contained landing page. To deploy one to Vercel:

```bash
cd peacock-shoe-factory   # or enrico-pastry
vercel --prod
```

Or copy the `index.html` into any static host root directory.
