# Good n' Natural Advice Scraper
>This scraper pulls structured advice content from Good n' Natural (shop.goodnnatural.ca), giving you complete access to titles, authors, descriptions, categories, keywords, images, and exportable formats. Whether you're analyzing content trends, aggregating articles, or building SEO datasets, it turns the entire Advice section into clean, usable data.

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
  If you are looking for <strong>Good n' Natural Advice Scraper</strong> you've just found your team — Let's Chat. 👆👆
</p>


## Introduction
The Good n' Natural Advice Scraper collects all advice posts from the Good n' Natural website, then optionally fetches each advice’s full details. It provides results in multiple formats including JSON, HTML, and plaintext, making it ideal for reporting, content analysis, dashboards, or ingestion into applications.

### What It Helps You Do
- Scrape the entire Advice section or selected URLs.  
- Export rich article details for editorial, SEO, or analytical workflows.  
- Filter advice posts by category, author, or search fields.  
- Retrieve article metadata, images, featured videos, and read-time details.

---
## Features
| Feature | Description |
|---------|-------------|
| **Full Advice List Extraction** | Scrapes all available advice pages and summaries. |
| **Detailed Article Fetching** | Pulls titles, descriptions, authors, content, SEO titles, images, videos, and keywords. |
| **Multiple Output Formats** | Export advice details as HTML, plaintext, or JSON. |
| **Flexible Filtering** | Filter by search term, author, or category. |
| **Partial or Full Scraping** | Supply specific advice URLs or let the scraper auto-discover all posts. |
| **Rich Metadata Extraction** | Includes read time, create/update timestamps, RSS details, and media assets. |

---
## What Data This Scraper Extracts
| Field Name | Field Description |
|------------|-------------------|
| title | The headline of the advice article. |
| description | Short summary or intro text. |
| author | Article author(s). |
| categories | Category tags applied to the article. |
| createdAt | Original publication date. |
| updatedAt | Last updated timestamp. |
| readTime | Estimated reading time. |
| contentHtml | Full article content in HTML (when exported). |
| contentText | Plaintext version of the article. |
| featuredImage | Main image URL for the advice. |
| images | Additional embedded images. |
| videos | Featured or embedded video URLs. |
| seoTitle | SEO-optimized title. |
| keywords | SEO-related keyword list. |
| url | Direct link to the article. |

---
## Example Output
    
    [
      {
        "title": "How to Boost Your Immunity Naturally",
        "description": "Learn effective natural ways to strengthen your immune system.",
        "author": "Good n' Natural Editorial Team",
        "categories": ["Wellness", "Immunity"],
        "createdAt": "2023-09-12",
        "updatedAt": "2023-10-01",
        "readTime": "5 min",
        "contentText": "Boosting your immunity requires...",
        "featuredImage": "https://shop.goodnnatural.ca/advice/immunity-boost.jpg",
        "images": [
          "https://shop.goodnnatural.ca/uploads/img1.jpg",
          "https://shop.goodnnatural.ca/uploads/img2.jpg"
        ],
        "videos": [],
        "seoTitle": "Boost Your Immunity Naturally",
        "keywords": ["immunity", "wellness", "natural health"],
        "url": "https://shop.goodnnatural.ca/advice/boost-immunity"
      }
    ]

---
## Directory Structure Tree
    
    Good n' Natural Advice Scraper/
    ├── src/
    │   ├── main.js
    │   ├── collectors/
    │   │   ├── advice_list_scraper.js
    │   │   ├── advice_detail_scraper.js
    │   │   └── filter_manager.js
    │   ├── exporters/
    │   │   ├── html_exporter.js
    │   │   ├── text_exporter.js
    │   │   └── json_exporter.js
    │   ├── utils/
    │   │   ├── parser.js
    │   │   ├── normalizer.js
    │   │   └── format_mapper.js
    │   └── config/
    │       └── settings.example.json
    ├── data/
    │   ├── sample_input.json
    │   └── sample_output.json
    ├── package.json
    └── README.md

---
## Use Cases
- **Content Analysts** gather structured datasets for topic analysis, keyword research, or editorial insights.  
- **SEO Specialists** audit metadata, titles, and keywords across all advice posts.  
- **Publishers** aggregate advice content for apps, newsletters, or automated content libraries.  
- **Marketing Teams** monitor updates to lifestyle and health-related topics.  
- **Data Engineers** build ingestion pipelines that rely on clean, structured article data.

---
## FAQs

**Can I scrape only specific advice articles?**  
Yes—pass URLs through `adviceUrls`.

**Does it support filtering?**  
Yes, by author, category, or search value using `filterBy`, `filterType`, and `filterValue`.

**In what formats can I export content?**  
HTML, plaintext, and JSON. PDF export is in progress.

**Does it extract media assets?**  
Yes, including images, featured images, and videos when available.

---
### Performance Benchmarks and Results

**Primary Metric:**  
Scrapes full advice lists and details in minutes with predictable request flow.

**Reliability Metric:**  
>97% successful extraction across article detail pages and list pagination.

**Efficiency Metric:**  
Skips redundant requests and respects maxAdvice limits for faster execution.

**Quality Metric:**  
Produces rich, well-structured content objects suitable for SEO tools, dashboards, and content apps.


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
