# Awesome Web Scraping [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> The ultimate web scraping toolkit — curated scraping APIs, actors, proxies, headless browsers, and data extraction tools. Built for developers, data teams, and AI agents.

🤖 **AI pipeline builders (free Poe bots)** — describe your target, get the exact actor + run input + code:
[Lead List Generator](https://poe.com/leadlistgenerator) · [Job Postings Miner](https://poe.com/jobpostingsminer) · [Amazon Product Miner](https://poe.com/amazonproductminer) · [SERP Rank Tracker](https://poe.com/serpranktracker) · [Social Lead Finder](https://poe.com/socialleadfinder)

**Contents**: [Scraping Platforms](#-scraping-platforms--apis) · [Proxy Providers](#-proxy--anti-block-providers) · [Browser Automation](#-browser-automation) · [Data Extraction AI](#-ai-powered-extraction) · [Niche Scrapers](#-niche--ready-made-scrapers) · [Libraries](#-libraries--frameworks) · [Agent Skills](#-agent-skills-ai-coding) · [Datasets](#-ready-made-datasets)

---

## 🏗️ Scraping Platforms & APIs

Full-stack scraping infrastructure — actor marketplaces, cloud browsers, and structured APIs.

- **[Apify](https://console.apify.com/sign-up?fpr=dx06p)** — The biggest actor marketplace: 5,000+ ready-made scrapers (Google Maps, Instagram, Amazon, jobs) with scheduling, proxies, and datasets. Free monthly credits.
- **[Bright Data](https://brightdata.com)** <!-- AFF: add link --> — Enterprise-grade data collection: Web Unlocker, SERP API, hosted datasets, and the largest proxy network.
- **[Oxylabs](https://oxylabs.io)** <!-- AFF --> — Enterprise scraping: Web Scraper API, SERP/e-commerce scrapers, premium proxy pools.
- **[ZenRows](https://www.zenrows.com)** <!-- AFF --> — One API call handles proxies, JS rendering, and CAPTCHAs. Great success rate on hard targets.
- **[ScraperAPI](https://www.scraperapi.com)** <!-- AFF --> — Rotating proxy API with auto-retry, geotargeting, and structured endpoints for Amazon/Google.
- **[Scrape.do](https://scrape.do)** <!-- AFF --> — Affordable scraping API with strong anti-bot bypass and pay-as-you-go pricing.
- **[ScrapingBee](https://www.scrapingbee.com)** <!-- AFF --> — Headless browser API with JS execution, screenshots, and Google-focused endpoints.
- **[Crawlbase](https://crawlbase.com)** — Crawling API with CAPTCHA solving built in.
- **[Firecrawl](https://www.firecrawl.dev)** — Turn any website into clean markdown/structured data — purpose-built for LLM ingestion.
- **[Browserbase](https://www.browserbase.com)** — Serverless headless browsers for AI agents and scraping pipelines.

## 🛡️ Proxy & Anti-Block Providers

Residential, datacenter, and mobile proxies — the backbone of large-scale scraping.

- **[Bright Data Proxies](https://brightdata.com)** <!-- AFF --> — Largest network: 72M+ residential IPs, datacenter, ISP, mobile.
- **[Oxylabs Proxies](https://oxylabs.io)** <!-- AFF --> — Premium residential/datacenter pools with strong SLAs.
- **[Smartproxy / Decodo](https://decodo.com)** <!-- AFF --> — Best price/performance residential proxies for mid-market scraping.
- **[IPRoyal](https://iproyal.com)** <!-- AFF --> — Budget-friendly residential proxies with non-expiring traffic.
- **[SOAX](https://soax.com)** <!-- AFF --> — Clean residential + mobile proxy network with flexible geo-targeting.
- **[NetNut](https://netnut.io)** <!-- AFF --> — ISP-sourced residential proxies, very fast.
- **[Proxy-Cheap](https://proxy-cheap.com)** — Cheapest entry point for residential proxies.
- **[Webshare](https://www.webshare.io)** <!-- AFF --> — Generous free tier (10 proxies free forever), easy onboarding.

## 🖥️ Browser Automation

Headless browser frameworks for JS-heavy sites.

- **[Playwright](https://playwright.dev)** — Microsoft; the current standard. Multi-browser, auto-wait, stealth plugins via `playwright-stealth`.
- **[Puppeteer](https://pptr.dev)** — Google; Chrome DevTools Protocol. `puppeteer-extra` + `stealth-plugin` for evasion.
- **[Selenium](https://www.selenium.dev)** — The classic; still needed for legacy stacks.
- **[Nodriver](https://github.com/ultrafunkamsterdam/nodriver)** — Undetected Chrome automation, successor to undetected-chromedriver.
- **[Rebrowser](https://github.com/rebrowser/rebrowser-patches)** — Patches for Playwright/Puppeteer fingerprints.
- **[Camoufox](https://github.com/daijro/camoufox)** — Firefox-based fingerprint-resistant browser.
- **[Stagehand](https://github.com/browserbase/stagehand)** — AI-native browser automation on top of Playwright.

## 🤖 AI-Powered Extraction

LLM-native scraping — describe what you want, get structured data.

- **[Firecrawl](https://www.firecrawl.dev)** — Site → markdown/JSON for LLMs; `/extract` endpoint for schema-based extraction.
- **[Apify Website Content Crawler](https://apify.com)** — Crawl → markdown pipeline, the standard RAG ingestion actor.
- **[ScrapeGraphAI](https://github.com/ScrapeGraphAI/Scrapegraph-ai)** — Open-source LLM scraping pipelines (SmartScraper, SearchGraph).
- **[Reader (Jina AI)](https://jina.ai/reader)** — Free URL → markdown API, great for quick LLM ingestion.
- **[Diffbot](https://www.diffbot.com)** — Knowledge-graph-grade automatic extraction.
- **[Browse AI](https://www.browse.ai)** — No-code point-and-click robots for monitoring/extraction.

## 🎯 Niche & Ready-Made Scrapers

Pre-built extractors for the most-demanded sources (mostly on Apify Store).

- **[Google Maps Scraper](https://console.apify.com/sign-up?fpr=dx06p)** — Names, phones, websites, reviews.
- **[Google Maps + Contact Details](https://console.apify.com/sign-up?fpr=dx06p)** — Emails and socials from each business website.
- **[Amazon Crawler](https://console.apify.com/sign-up?fpr=dx06p)** — Products, prices, ASINs, reviews.
- **[Instagram Scraper](https://console.apify.com/sign-up?fpr=dx06p)** — Profiles, posts, comments, hashtags.
- **[TikTok Scraper](https://console.apify.com/sign-up?fpr=dx06p)** — Videos, trends, hashtags, profiles.
- **[Twitter/X Scraper](https://console.apify.com/sign-up?fpr=dx06p)** — Tweets, threads.
- **[Google Search Scraper](https://console.apify.com/sign-up?fpr=dx06p)** — SERPs, ads, people-also-ask.
- **[Google Jobs Scraper](https://console.apify.com/sign-up?fpr=dx06p)** — Job boards at scale.
- **[Shopify Scraper](https://console.apify.com/sign-up?fpr=dx06p)** — Full store catalogs: products, prices, variants.
- **[YouTube Scraper](https://console.apify.com/sign-up?fpr=dx06p)** — Channels, videos, comments, transcripts.

## 📚 Libraries & Frameworks

- **[Scrapy](https://scrapy.org)** — Python's industrial-strength crawling framework.
- **[Crawlee](https://crawlee.dev)** — From Apify; anti-blocking, session pools, storage.
- **[BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/)** + **[lxml](https://lxml.de)** — Python HTML parsing staples.
- **[Cheerio](https://cheerio.js.org)** — jQuery-like server-side HTML parsing for Node.
- **[Crawlee for Python](https://crawlee.dev/python)** — TypeScript's best crawler ported with Playwright support.
- **[Requests-HTML](https://requests.readthedocs.io)** — Simple HTTP + rendering for small jobs.
- **[Hrequests](https://github.com/daijro/hrequests)** — Python requests with browser-like TLS fingerprints.
- **[curl_cffi](https://github.com/lexiforest/curl_cffi)** — Impersonate browser TLS/JA3 fingerprints — bypasses most bot detection at the HTTP layer.

## 🧠 Agent Skills (AI coding)

Skills that teach Claude Code / Cursor / Codex how to scrape properly.

- **[apify-skills](https://github.com/samm4dr/apify-skills)** — `npx skills add samm4dr/apify-skills` — 8 skills: Google Maps leads, jobs, Amazon, social, SERP, e-commerce, web scraping. Routes your agent to the right actor with correct inputs.

## 📦 Ready-Made Datasets

Skip the scraping entirely.

- **[Bright Data Datasets](https://brightdata.com)** <!-- AFF --> — Pre-collected datasets: LinkedIn, Amazon, TikTok, real estate.
- **[Apify Store datasets](https://console.apify.com/sign-up?fpr=dx06p)** — Fresh datasets from scheduled actor runs.
- **[Common Crawl](https://commoncrawl.org)** — Free petabyte-scale web crawl archive.
- **[Kaggle](https://www.kaggle.com/datasets)** — Community datasets, business/scraped collections.

## 📖 Guides & Learning

- **[How to scrape without getting blocked](https://github.com/niespodd/browser-fingerprinting)** — Fingerprinting deep-dive.
- **[Crawlee docs](https://crawlee.dev)** — Best modern intro to crawling architecture.
- **[The Web Scraping Club](https://substack.com/@thewebscrapingclub)** — Newsletter on anti-bot techniques.

---

## Contributing

PRs welcome — add tools with a one-line description, keep alphabetical order inside sections.

## License

CC0 — public domain. Star ⭐ the repo if it saved you a build!
