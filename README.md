I took all the URLs from [collusion.wiki](https://collusion.wiki), which is a mirror of "~18,000 posts from autonomous AI agents (self-identifying as from OpenAI) using the public internet to communicate during a web-retrieval task" discovered by Sydney Von Arx, Cormac Slade Byrd, Spencer Kitts, Thomas Larsen and made public on 4 September 2026 and downloaded them. 

```
  "generated_at": "2026-09-04T23:05:01.095Z",
  "manifest": "collusion-wiki-scraper/scrape-output/manifest.jsonl",
  "total_entries": 22636,
  "ok": 18655,
  "failed": 3981,
  "total_bytes": 598466882,
  "status_counts": {
    "0": 157,
    "200": 18653,
    "202": 2,
    "400": 396,
    "401": 85,
    "403": 442,
    "404": 340,
    "405": 2,
    "408": 1,
    "409": 2,
    "410": 225,
    "415": 5,
    "429": 1337,
    "500": 907,
    "502": 41,
    "504": 18,
    "522": 23
  },
```

I didn't retry any URLS. I omitted ~1900 URLs which were the same JSON file from sec.gov with '?' query parameters added. 

I did this because I expect many of these links will prove to be ephemeral, and someone might be curious about what the bots were reading. 

Why would anyone find this interesting? What prompted me to do this is I noticed that one URL in the wiki was a PDF from the piv.max.gov domain, proxied through a markdown scraping service. From everything I can find, most of that website is only accessible by federal employees and contractors. While some parts of it are public, the 'piv' subdomain does not appear to be among them. 

Scrape logs in this repo, full output containing 22,592 items, totaling 600.1 MB available in [Releases](https://github.com/JonGerhardson/collusion_wiki_scrape/releases/tag/tag) 

<img width="775" height="320" alt="Screenshot from 2026-09-04 19-45-38" src="https://github.com/user-attachments/assets/450b1d16-5679-4a45-a09a-7c73a9e4dbdb" />



