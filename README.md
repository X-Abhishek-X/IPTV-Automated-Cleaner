# 📺 Automated IPTV Playlist Cleaner

> **Always-fresh, automatically validated IPTV playlist.**
>
> This project scrapes public IPTV sources, tests every stream, and generates a clean `m3u` file with working channels only.

![GitHub Actions](https://img.shields.io/github/workflow/status/X-Abhishek-X/IPTV-Automated-Cleaner/Update%20Playlist)
![License](https://img.shields.io/github/license/X-Abhishek-X/IPTV-Automated-Cleaner)

---

## 🚀 How to Use

### Direct Link (Auto-Updated)

Copy this URL into your IPTV Player (VLC, Tivimate, Televizio):

```
https://raw.githubusercontent.com/X-Abhishek-X/IPTV-Automated-Cleaner/gh-pages/clean_playlist.m3u
```

_(Note: This link will become active after the first GitHub Action run completes successfully)_

---

## ✨ Features

- 🔄 **Daily Updates:** Runs every 6 hours to ensure fresh links.
- ✅ **Validated Streams:** Automatically tests stream URLs to remove dead channels.
- 🌍 **Global Content:** Aggregates channels from US, UK, News, and Movies.
- ⚡ **Fast:** Concurrent checking of hundreds of streams.

---

## 🛠️ How it Works

1.  **Scrape:** Fetches raw M3U lists from `iptv-org` and other open sources.
2.  **Validate:** A Python script checks each stream URL for connectivity (HTTP 200 OK).
3.  **Publish:** The working list is pushed to the `gh-pages` branch, making it accessible via a raw URL.

---

## ⚠️ Disclaimer

This project does **not host** any content. It merely aggregates publicly available links found on the internet.
The availability of streams depends entirely on the third-party providers.

---

**Credits:**

- Data Source: [iptv-org](https://github.com/iptv-org/iptv)
