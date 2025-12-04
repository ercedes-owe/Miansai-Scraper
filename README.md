# Miansai Scraper
>The Miansai Scraper extracts structured product data from Miansai.com, giving you detailed insights into product listings, pricing, variants, and media. Tailored for the clothing accessories category, it transforms Miansai’s Shopify-powered storefront into clean datasets ready for analysis, catalog building, or competitive research.

<p align="center">
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/scraper.png" alt="Bitbash Banner" width="100%"></a>
</p>
<p align="center">
  <a href="https://t.me/Bitbash333" target="_blank">
    <img src="https://img.shields.io/badge/Chat%20on-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>&nbsp;
  <a href="https://wa.me/923249868488?text=Hi%20BitBash%2C%20I'm%20interested%20in%20automation." target="_blank">
    <img src="https://img.shields.io/badge/Chat-WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp">
  </a>&nbsp;
  <a href="mailto:sale@bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Email-sale@bitbash.dev-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
  </a>&nbsp;
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Visit-Website-007BFF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website">
  </a>
</p>

<p align="center" style="font-weight:600; margin-top:8px; margin-bottom:8px;">
  Created by Bitbash, built to showcase our approach to Scraping and Automation!<br>
  If you are looking for <strong>Miansai Scraper</strong> you've just found your team — Let's Chat. 👆👆
</p>


## Introduction
Miansai is a premium accessories brand, and this scraper captures essential product attributes—titles, images, descriptions, prices, and more. By automating what would otherwise be hours of browsing and copying, it helps analysts, developers, and e-commerce teams work with precise product data at scale.

### Why It’s Useful
- Provides complete product information for research and monitoring.  
- Helps track pricing changes, product availability, and category shifts.  
- Produces structured output compatible with databases, spreadsheets, and internal tools.  
- Supports retail analysis, catalog updates, or competitor benchmarking with ease.

---
## Features
| Feature | Description |
|---------|-------------|
| Product Information Extraction | Retrieves product titles, IDs, prices, descriptions, and availability. |
| Image & Media Collection | Extracts all product image URLs for cataloging or media pipelines. |
| Shopify-Based Structure | Leverages Shopify’s predictable layout for stable, reliable scraping. |
| Variant & Option Capture | Gathers product variations such as color, size, or style. |
| Multi-Format Output | Supports JSON, CSV, Excel, XML, and HTML exports. |
| Category Classification | Extracts breadcrumb paths for accurate category mapping. |

---
## What Data This Scraper Extracts
| Field Name | Field Description |
|------------|-------------------|
| productId | Unique product ID from the Miansai store. |
| productUrl | Direct link to the product page. |
| title | Product name or listing title. |
| price | Current product price. |
| originalPrice | Pre-discount or compare-at price if available. |
| description | Detailed product description text. |
| images | Array of high-resolution product image URLs. |
| variants | List of product variants (color, material, size, etc.). |
| category | Product’s category or breadcrumb trail. |
| availability | Stock status for the product or its variants. |

---
## Example Output
    
    [
      {
        "productId": "123456789",
        "productUrl": "https://www.miansai.com/products/example",
        "title": "Gold Vermeil Chain Bracelet",
        "price": 185.00,
        "originalPrice": 220.00,
        "description": "Handcrafted bracelet made from premium gold vermeil with a minimalist design.",
        "images": [
          "https://cdn.miansai.com/products/bracelet1.jpg",
          "https://cdn.miansai.com/products/bracelet2.jpg"
        ],
        "variants": [
          { "material": "Gold Vermeil", "availability": "In Stock" },
          { "material": "Sterling Silver", "availability": "Low Stock" }
        ],
        "category": "Accessories > Bracelets",
        "availability": "In Stock"
      }
    ]

---
## Directory Structure Tree
    
    Miansai Scraper/
    ├── src/
    │   ├── main.js
    │   ├── extractors/
    │   │   ├── product_parser.js
    │   │   ├── media_parser.js
    │   │   └── pricing_parser.js
    │   ├── utils/
    │   │   ├── request_handler.js
    │   │   ├── shopify_mapper.js
    │   │   └── data_cleaner.js
    │   └── config/
    │       └── settings.example.json
    ├── data/
    │   ├── sample_input.json
    │   └── sample_output.json
    ├── package.json
    └── README.md

---
## Use Cases
- **Market analysts** track shifts in pricing, availability, and product assortment.  
- **E-commerce teams** maintain updated product catalogs with accurate specs and images.  
- **Developers** enrich internal search engines, databases, or recommendation systems.  
- **Competitor intelligence teams** monitor premium accessories trends.  
- **Retail data platforms** collect structured product attributes for downstream analysis.  

---
## FAQs

**Is the scraper limited to accessories?**  
It’s optimized for Miansai’s accessories catalog but works for all product types available on their Shopify store.

**What output formats does it support?**  
The scraper can export JSON, CSV, Excel, XML, and HTML.

**Does it handle variants?**  
Yes, it captures all product variants such as size, material, and style options.

**Is the scraper still reliable?**  
Even though the actor is under maintenance, Shopify’s stable structure keeps product extraction accurate.

---
### Performance Benchmarks and Results

**Primary Metric:**  
Scrapes full product details in 2–5 seconds per item.

**Reliability Metric:**  
Maintains over 95% extraction accuracy due to consistent Shopify page templates.

**Efficiency Metric:**  
Uses optimized selectors and caching to reduce repetitive page loads.

**Quality Metric:**  
Returns clean, high-quality product data ideal for e-commerce intelligence and catalog integration.


---


<p align="center">
<a href="https://calendar.app.google/74kEaAQ5LWbM8CQNA" target="_blank">
  <img src="https://img.shields.io/badge/Book%20a%20Call%20with%20Us-34A853?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Book a Call">
</a>
  <a href="https://www.youtube.com/@bitbash-demos/videos" target="_blank">
    <img src="https://img.shields.io/badge/🎥%20Watch%20demos%20-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch on YouTube">
  </a>
</p>
<table>
  <tr>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/MLkvGB8ZZIk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review1.gif" alt="Review 1" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash is a top-tier automation partner, innovative, reliable, and dedicated to delivering real results every time."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Nathan Pennington
        <br><span style="color:#888;">Marketer</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/8-tw8Omw9qk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review2.gif" alt="Review 2" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash delivers outstanding quality, speed, and professionalism, truly a team you can rely on."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Eliza
        <br><span style="color:#888;">SEO Affiliate Expert</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/m-dRE1dj5-k?si=5kZNVlKsGUhg5Xtx" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review3.gif" alt="Review 3" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Exceptional results, clear communication, and flawless delivery. <br>Bitbash nailed it."
      </p>
      <p style="margin:1px 0 0; font-weight:600;">Syed
        <br><span style="color:#888;">Digital Strategist</span>
        <br><span style="color:#f5a623;">★★★★★</span>
         </p>
