PhotoPrint Services — Homepage SEO Update

Included:
- index.html: updated homepage SEO title, meta description, Open Graph text, H1 and service-section copy.
- Removed the meta keywords tag (Google does not use it for ranking).
- Added loading="lazy" and decoding="async" to below-the-fold images.
- Added fetchpriority="high" and decoding="async" to the hero image.
- Preserved existing design, service URLs, order form URL, pricing example, policies and navigation.

How to publish:
1. Download and extract this ZIP.
2. Open the GitHub repository: photoprintservices/photoprint-services.
3. Replace ONLY the existing index.html in the repository root with this index.html.
4. Commit the change.
5. Open the homepage and confirm it looks correct.

Do not replace sitemap.xml, robots.txt, the Search Console verification file, or the four service-page files.
The homepage URL has not changed, so the sitemap does not need to be resubmitted.
After deployment, use Search Console URL Inspection → Test Live URL → Request Indexing for the homepage.

Image filename note:
The current homepage uses externally hosted Unsplash images. Their filenames cannot be renamed from this HTML file. When you have your own product photos, upload them to the repository with descriptive filenames and update their image URLs and accurate ALT text.
