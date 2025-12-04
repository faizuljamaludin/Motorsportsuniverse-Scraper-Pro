# MotorsportsUniverse Scraper Pro
>This scraper digs through MotorSportsUniverse.com to pull rich, structured listings for ATVs, motorcycles, UTVs, dirt bikes, snowmobiles, and other motorsport vehicles. It’s built for people who need clean, reliable data for research, pricing intelligence, or lead generation—without the headache of manual collection.

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
  If you are looking for <strong>MotorsportsUniverse Scraper Pro</strong> you've just found your team — Let's Chat. 👆👆
</p>

## Introduction
This project extracts detailed motorsports vehicle data at scale. It captures pricing, specifications, seller information, location data, and high-quality images directly from the source.  
It’s ideal for analysts, dealership teams, marketplaces, and anyone working with motorsport market data.

### What Makes It Useful
- Handles multiple vehicle categories with the same workflow  
- Collects complete listing details including seller contacts  
- Supports pagination for deep crawling  
- Returns structured JSON ready for pipelines or dashboards  
- Reduces manual lookup time dramatically

---
## Features
| Feature | Description |
|---------|-------------|
| Comprehensive Vehicle Scraping | Extracts listings across ATVs, UTVs, motorcycles, dirt bikes, snowmobiles, and more. |
| Pricing & Specs | Captures pricing, mileage, specs, categories, and technical attributes. |
| High-Quality Media | Pulls full-resolution image URLs for each listing. |
| Seller Contact Extraction | Retrieves seller names, phone numbers, and location info. |
| Robust Navigation | Supports deep searches using keywords and max page limits. |
| Clean JSON Output | Provides structured data suitable for analysis or integration. |
| Error Tolerance | Built to handle unexpected page formats or missing fields. |

---
## What Data This Scraper Extracts
| Field Name | Field Description |
|------------|-------------------|
| listingId | Unique identifier for the listing. |
| title | Full vehicle listing title. |
| category | Category such as Cruiser, ATV, UTV, Dirt Bike, etc. |
| imageUrls | Array of all extracted images for the listing. |
| price | Price shown on the listing. |
| viewDetailsLink | URL to the detailed listing page. |
| mileage | Reported mileage of the vehicle. |
| location | Geographic location of the seller. |
| sellerName | Name of the seller or dealership. |
| sellerPhoneNumber | Contact phone number extracted from the listing. |

---
## Example Output
    
    [
      {
        "listingId": "231129115",
        "title": "2023 HARLEY DAVIDSON ROAD KING",
        "category": "Cruiser",
        "imageUrls": [
          "https://example.com/example.jpg",
          "https://example.com/example2.jpg"
        ],
        "price": "USD $24,995",
        "viewDetailsLink": "https://example.com/view/231129115",
        "mileage": "450 Miles",
        "location": "Denver, Colorado",
        "sellerName": "Rocky Mountain Motorsports",
        "sellerPhoneNumber": "+1 303-555-1234"
      }
    ]

---
## Directory Structure Tree
    
    motorsportsuniverse-scraper-pro/
    ├── src/
    │   ├── main.js
    │   ├── crawler/
    │   │   ├── playwright_engine.js
    │   │   ├── pagination.js
    │   │   └── extractors.js
    │   ├── utils/
    │   │   ├── normalization.js
    │   │   ├── logger.js
    │   │   └── phone_formatter.js
    │   └── config/
    │       └── input_schema.json
    ├── data/
    │   ├── sample_input.json
    │   └── sample_output.json
    ├── package.json
    ├── Dockerfile
    └── README.md

---
## Use Cases
- **Market researchers** collect nationwide motorsports pricing to identify trends and competitive gaps.  
- **Dealers** track competitor inventory and pricing to adjust offers dynamically.  
- **Lead generation agencies** extract seller contact information for outreach campaigns.  
- **Data marketplaces** aggregate structured motorsport listing feeds.  
- **Analysts** build dashboards using mileage, pricing, and location data to compare regional markets.

---
## FAQs

**Can I search by VIN, model, or manufacturer?**  
Yes, the scraper accepts keywords including VINs, model names, vehicle types, and manufacturers.

**Does it support multiple pages of results?**  
It can crawl as many pages as you specify using the `maxPages` setting.

**What happens if some listings have missing fields?**  
The scraper applies fallback extraction rules to keep the JSON structured and consistent.

**Does it extract all images?**  
Yes—every available listing image URL is captured for full visual reference.

---
### Performance Benchmarks and Results

**Primary Metric:**  
Efficiently processes dozens of listings per minute, even on image-heavy pages.

**Reliability Metric:**  
High extraction accuracy thanks to adaptive selectors and fallback logic.

**Efficiency Metric:**  
Low overhead through optimized Playwright automation and smart pagination.

**Quality Metric:**  
Consistent, complete vehicle profiles with normalized pricing, mileage, and contact details.



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
