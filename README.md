# robots.txt Generator VK Style

A simple web interface for generating `robots.txt` files — styled like VK interfaces. Quickly and easily configure rules for search engine bots on your website.

## 🧰 Features

- Add multiple `User-agent` blocks with `Allow` and `Disallow` fields
- Configure additional parameters:
  - `Crawl-delay` — delay between requests
  - `Host` — primary domain of your website
  - `Sitemap` — sitemap URL
- Generate `robots.txt` content with one click
- Download the file directly

## 🚀 How to Use

1. Download or open `index.html` in your browser.
2. Fill out the fields:
   - Specify one or more bots (`User-agent`)
   - Add paths to allow or disallow
   - Optionally configure `Crawl-delay`, `Host`, and `Sitemap`
3. Click **"Create robots.txt"** — the result will appear in the output field.
4. Click **"Save robots.txt"** to download the file.

## 📂 Project Structure

```
robots-generator/
├── index.html      # Main HTML file with layout, styles, and scripts
├── README.md       # Documentation (this file)
```

## 💻 Example Output

```txt
User-agent: *
Allow: /
Disallow: /admin

Crawl-delay: 1
Host: example.com
Sitemap: https://example.com/sitemap.xml
```

## 📌 Tips

- If unsure what to enter in `User-agent`, leave it as `*` (applies to all bots).
- `/` means the root of the website, while `/store` refers to a specific folder or page to restrict.

---

Made with ❤️ for webmasters and SEO specialists.

