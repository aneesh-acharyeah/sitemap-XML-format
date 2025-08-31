# 🗺️ Sitemap for SEO

This repository contains a `sitemap.xml` file that helps search engines like **Google** and **Bing** discover and index the pages of your website more effectively.

---

## 📘 What is a Sitemap?

A **sitemap** is an XML file that lists the important URLs of your site.  
It tells search engines:
- Which pages are available.
- When they were last updated.
- How frequently they change.
- How important they are relative to other pages.

Sitemaps improve **SEO (Search Engine Optimization)** by making sure crawlers don’t miss any important pages.

---

## 📄 Sitemap File Structure

Example `sitemap.xml`:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">

  <!-- Home Page -->
  <url>
    <loc>https://yourdomain.com/</loc>
    <lastmod>2025-08-31</lastmod>
    <changefreq>daily</changefreq>
    <priority>1.0</priority>
  </url>

  <!-- About Page -->
  <url>
    <loc>https://yourdomain.com/about</loc>
    <lastmod>2025-08-25</lastmod>
    <changefreq>monthly</changefreq>
    <priority>0.8</priority>
  </url>

</urlset>
