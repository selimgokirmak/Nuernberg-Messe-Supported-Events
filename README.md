## 🤖 [Nürnberg Messe Exhibitor List Scraper](https://apify.com/skython/nuernberg-messe-exhibitor-list-scraper) — Trade Shows, Expos, Fairs & Exhibition Directories

Extract complete exhibitor lists from Nürnberg Messe trade shows — including Powtech, Fachpack, Embedded World, Interzoo, Euroguss, Galabau, Chillventa, Itsa 365, and more — spanning automotive, technology, energy, food & beverage, packaging, and broadcasting industries. Scrape company profiles including company details, websites, social media links, product categories, brands, and contact persons. Ideal for B2B lead generation, sales prospecting, market research, event networking, and competitive analysis.

---

## Contents

- [Features](#features)

- [Use Cases](#use-cases)

- [Supported Nürnberg Messe Events (Exhibitor Lists)](#supported-nürnberg-messe-events-exhibitor-lists)

- [Testing Exhibitor List URLs](#testing-exhibitor-list-urls-for-free)

- [Exhibitor List Scraper - All-In-One Version](#exhibitor-list-scraper---all-in-one-version)

- [Data Fields](#data-fields)

- [Example Output](#example-output)

- [My Other Exhibitor List Scrapers](#my-other-exhibitor-list-scrapers)

---

## Features

- Scrape all exhibitor profiles from supported Nürnberg Messe event websites

- Extract detailed data from every exhibitor profile page

- Company primary information (address, email, phone, website)

- Social media links (LinkedIn, Facebook, Instagram, Twitter, YouTube)

- Contact person details

- Product categories with full hierarchical structure

- Two output formats (Single-Row & Multi-Row)

- Multi-Row format for Excel-friendly product category filtering

- Export to JSON, CSV, and Excel

---

## Use Cases

- **B2B Lead Generation:** Build targeted contact lists for marketing and sales outreach. 

- **Market Research:** Analyze exhibitors by product categories, brands, and sectors.  

- **Event Networking:** Familiarize yourself with exhibitors before attending trade fairs.  

- **Competitive Analysis:** Track competitor participation and product focus areas.

---

## Supported Nürnberg Messe Events (Exhibitor Lists)

- The following partial list includes Nürnberg Messe exhibitor directory URLs that have been tested so far. Other Nürnberg Messe or different events with the same website structure may also be supported.

- Some event URLs may have been updated or canceled entirely; please check them before using.

- [embedded world 2027 Exhibitor List – embedded-world.de](https://www.embedded-world.de/en/exhibitors-products/find-exhibitors)

- [PERIMETER PROTECTION 2027 Exhibitor List – perimeter-protection.de](https://www.perimeter-protection.de/en/exhibitors-products/find-exhibitors)

- [IWA OUTDOOR CLASSICS 2027 Exhibitor List – iwa.info](https://www.iwa.info/en/exhibitors-products/find-exhibitors)

- [ENFORCE TAC 2027 Exhibitor List – enforcetac.com](https://www.enforcetac.com/en/exhibitors-products/find-exhibitors)

- [POWTECH TECHNOPHARM 2026 Exhibitor List – powtech-technopharm.com](https://www.powtech-technopharm.com/en/exhibitors-products/find-exhibitors)

- [EUROGUSS 2026 Exhibitor List – euroguss.de](https://www.euroguss.de/en/exhibitors-products/find-exhibitors)

- [HOLZ-HANDWERK 2026 Exhibitor List – holz-handwerk.de](https://www.holz-handwerk.de/en/exhibitors-products/find-exhibitors)

- [FENSTERBAU FRONTALE 2026 Exhibitor List – frontale.de](https://www.frontale.de/en/exhibitors-products/find-exhibitors)

- [Interzoo 2026 Exhibitor List – interzoo.com](https://www.interzoo.com/en/exhibitors-products/find-exhibitors)

- [GaLaBau 2026 Exhibitor List – galabau-messe.com](https://www.galabau-messe.com/en/exhibitors-products/find-exhibitors)

- [itsa 365 2026 Exhibitor List – itsa365.de](https://www.itsa365.de/en/companies/find-companies)

- [CHILLVENTA 2026 Exhibitor List – chillventa.de](https://www.chillventa.de/en/exhibitors-products/find-exhibitors)

- [care:xpo 2026 Exhibitor List – care-xpo.de](https://www.care-xpo.de/en/exhibitors-products/find-exhibitors)

- [FACHPACK 2025 Exhibitor List – fachpack.de](https://www.fachpack.de/en/exhibitors-products/find-exhibitors)

- [KOMMUNALE 2025 Exhibitor List – kommunale.de](https://www.kommunale.de/de-de/aussteller-produkte/aussteller-finden)

- [CONSOZIAL 2025 Exhibitor List – consozial.de](https://www.consozial.de/de-de/ausstellende-produkte/ausstellende-finden)

- [BERUFS-BILDUNG 2025 Exhibitor List – berufsbildung-messe.de](https://www.berufsbildung-messe.de/de-de/aussteller-produkte/aussteller-finden)

---

## Testing Exhibitor List URLs for FREE

- Since I have multiple exhibitor list scraper actors for different types of trade event websites, it might be hard to find the correct actor for your exhibitor list URL.

- Use [**Exhibitor List Scrapers URL Tester**](https://apify.com/skython/exhibitor-list-scrapers-router) actor to test your exhibitor list URLs **for FREE** and see which scraper can process them.

---

## Exhibitor List Scraper - All-In-One Version

- I also provide an **All-In-One** version that combines **my 30+ exhibitor list scrapers** into a single actor.

- Instead of searching for the correct scraper for each event URL, simply provide the event URL and the actor automatically selects the appropriate scraper.

- ➡️ [Exhibitor List Scraper - All-In-One](https://apify.com/skython/exhibitor-list-scraper)

---

## Data Fields

<table>
  <thead>
    <tr>
    <th><span style="font-size:14px;">Company</span></th>
    <th><span style="font-size:14px;">Social</span></th>
    <th><span style="font-size:14px;">Additional</span></th>
    </tr>
  </thead>
    <tbody>
        <tr>
            <td>Profile URL</td>
            <td>LinkedIn</td>
            <td>Hall Stands</td>
        </tr>
        <tr>
            <td>Company Name</td>
            <td>Facebook</td>
            <td>Product Categories</td>
        </tr>
        <tr>
            <td>Address</td>
            <td>Instagram</td>
            <td>Keywords</td>
        </tr>
        <tr>
            <td>Website</td>
            <td>Twitter / X</td>
            <td>Industries</td>
        </tr>
        <tr>
            <td>Email</td>
            <td>YouTube</td>
            <td>Co-Exhibitors</td>
        </tr>
        <tr>
            <td>Phone</td>
            <td></td>
            <td>Contact Persons</td>
        </tr>
    </tbody>
</table>

---

## Example Output

```json
{
  "___exhibitor_profile_url": "https://www.embedded-world.de/en/exhibitors/acromag-inc-2611778",
  "__company_name": "Acromag, Inc.",
  "_company_address": "30765 S. Wixom Rd., 48393, Wixom, United States",
  "_company_country": "United States",
  "_company_email": "solutions@acromag.com",
  "_company_phone": "+1 248-295-0310",
  "_company_website": "www.acromag.com",
  "_hall_stands": "Hall 1 / 1-115",
  "_social_url_linkedin": "https://www.linkedin.com/company/acromag/",
  "_social_url_facebook": "https://www.facebook.com/acromaginc",
  "_social_url_youtube": "https://www.youtube.com/acromag",
  "_social_url_twitter": "https://twitter.com/Acromag/",
  "company_type": "Manufacturer",
  "keywords": "Carrier Cards | cPCI | FPGA | PCIe | VME | VPX",
  "industries": "Aerospace / military",
  "contact_persons": [
    {
      "_name": "Russell Nieves",
      "email": "rnie***@acromag.com",
      "title": "Vice President of Sales"
    },
    {
      "_name": "Dan Willis",
      "email": "dwil***@acromag.com",
      "title": "National Sales Manager, Embedded Division"
    }
  ],
  "product_categories": [
    {
      "title": "Hardware",
      "subcategories": [
        {
          "title": "Interface and Peripheral Modules",
          "subcategories": [
            {
              "title": "Digital and Analog Input/Output Modules",
              "subcategories": null
            },
            {
              "title": "Amplifier Modules",
              "subcategories": null
            },
            {
              "title": "Motor Control Modules",
              "subcategories": null
            },
            {
              "title": "Other Interface and Peripheral Modules",
              "subcategories": null
            }
          ]
        }
      ]
    }
  ]
}
```

---

## My Other Exhibitor List Scrapers

- [Exhibitor List Scraper - All-In-One](https://apify.com/skython/exhibitor-list-scraper)

- [Koelnmesse Exhibitor List Scraper](https://apify.com/skython/koelnmesse-exhibitor-list-scraper)

- [Messe Frankfurt Exhibitor List Scraper](https://apify.com/skython/messe-frankfurt-exhibitor-list-scraper)

- [Map Your Show Exhibitor List Scraper](https://apify.com/skython/map-your-show-exhibitor-list-scraper)

- [Messe Düsseldorf Exhibitor List Scraper](https://apify.com/skython/messe-duesseldorf-exhibitor-list-scraper)

- [Xporience Exhibitor List Scraper](https://apify.com/skython/xporience-exhibitor-list-scraper)

- [Reed Expo Exhibitor List Scraper](https://apify.com/skython/reed-expo-exhibitor-list-scraper)

- [Messe München Exhibitor List Scraper](https://apify.com/skython/messe-muenchen-exhibitor-list-scraper)

- [Xporience Exhibitor List Scraper V2](https://apify.com/skython/xporience-exhibitor-list-scraper-2)

- [GSMA MWC Exhibitor List Scraper](https://apify.com/skython/gsma-mwc-exhibitor-list-scraper)

- [Messe Berlin Exhibitor List Scraper](https://apify.com/skython/messe-berlin-exhibitor-list-scraper)

- [AFAG Messe Exhibitor List Scraper](https://apify.com/skython/afag-messe-exhibitor-list-scraper)

- [Messe Stuttgart Exhibitor List Scraper](https://apify.com/skython/messe-stuttgart-exhibitor-list-scraper)

- [Messe Essen Exhibitor List Scraper](https://apify.com/skython/messe-essen-exhibitor-list-scraper)

- [Informa Markets Exhibitor List Scraper](https://apify.com/skython/informa-markets-exhibitor-list-scraper)

- [Informa Markets Exhibitor List Scraper V2](https://apify.com/skython/informa-markets-exhibitor-list-scraper-2)

- [Ungerboeck Exhibitor List Scraper](https://apify.com/skython/ungerboeck-exhibitor-list-scraper)

- [A2Z Events Exhibitor List Scraper](https://apify.com/skython/a2z-events-exhibitor-list-scraper)

- [Deutsche Messe Exhibitor List Scraper](https://apify.com/skython/deutsche-messe-exhibitor-list-scraper)

- [Newfront Exhibitor List Scraper](https://apify.com/skython/newfront-exhibitor-list-scraper)

- [Goeshow Exhibitor List Scraper](https://apify.com/skython/goeshow-exhibitor-list-scraper)

- [EasyFairs Exhibitor List Scraper](https://apify.com/skython/easyfairs-exhibitor-list-scraper)

- [IEG Expo Exhibitor List Scraper](https://apify.com/skython/ieg-expo-exhibitor-list-scraper)

- [The Smarter E Exhibitor List Scraper](https://apify.com/skython/the-smarter-e-exhibitor-list-scraper)

- [Schall Messen Exhibitor List Scraper](https://apify.com/skython/schall-messen-exhibitor-list-scraper)

- [Messe München Exhibitor List Scraper V2](https://apify.com/skython/messe-muenchen-exhibitor-list-scraper-2)

- [Comexposium Exhibitor List Scraper](https://apify.com/skython/comexposium-exhibitor-list-scraper)

- [IME Events Exhibitor List Scraper](https://apify.com/skython/ime-events-exhibitor-list-scraper)

- [ANDMORE Exhibitor List Scraper](https://apify.com/skython/andmore-exhibitor-list-scraper)

- [Comexposium Exhibitor List Scraper V2](https://apify.com/skython/comexposium-exhibitor-list-scraper-2)

- [Informa Markets Exhibitor List Scraper V3](https://apify.com/skython/informa-markets-exhibitor-list-scraper-3)

- [LIVEBUZZ Exhibitor List Scraper](https://apify.com/skython/livebuzz-exhibitor-list-scraper)

- [ASP Events Exhibitor List Scraper](https://apify.com/skython/asp-events-exhibitor-list-scraper)

- [Fortem Exhibitor List Scraper](https://apify.com/skython/fortem-exhibitor-list-scraper)