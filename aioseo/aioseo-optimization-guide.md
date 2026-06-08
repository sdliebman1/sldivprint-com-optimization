# AIOSEO Optimization Guide for sldivprint.com

**Plugin**: All in One SEO (AIOSEO) — Perfect for your site.
**Goal**: Configure AIOSEO for maximum rankings, rich results, and AI/voice visibility.

## Step-by-Step AIOSEO Setup (Do This First)

### 1. General Settings
- Go to **AIOSEO → General Settings**
- **Enable**:
  - XML Sitemap
  - Breadcrumbs
  - Schema Markup
  - Social Meta (Open Graph + Twitter Cards)
- Set your **Site Title** and **Meta Description** (use compelling version from content-improvements folder if desired).
- **Canonical URLs**: Enable (prevents duplicate content issues).

### 2. Titles & Meta (Most Important for Click-Through Rate)
- Go to **AIOSEO → Titles & Meta**
- **Global Templates**:
  - Homepage: Use something like `%site_title% | Rush Printing, Custom Apparel & Promo Products`
  - Posts/Pages: `%post_title% | SLDivPrint` or more specific per content type.
  - Add keywords naturally in front.
- Edit individual pages/posts:
  - In the page editor, scroll to AIOSEO meta box (or sidebar).
  - Set custom Title, Meta Description, and Social Image for each key page.
  - Recommended for Homepage: Title ~ "24-48 Hour Rush Printing, Custom Apparel & Promo Products | SLDivPrint"

### 3. Schema Markup (Critical for Rich Results + AI)
AIOSEO makes this easy — use the built-in tools first:

**Global Organization / LocalBusiness Schema** (do this once):
1. Go to **AIOSEO → Schema** (or Search Appearance → Schema in some versions).
2. Choose **Organization** or **LocalBusiness**.
3. Fill in:
   - Name: SL Diversified Printing (SLDivPrint)
   - Description: Family-owned rush printing experts since 1987...
   - Logo: Upload your logo
   - Address: 6501 E Greenway Pkwy, Ste 103-511, Scottsdale, AZ 85254
   - Phone: 800-960-3676
   - Email: SL@SLDivPrint.com
   - SameAs: Add your LinkedIn, Facebook, etc.
   - Founding date: 1987
4. Save. This applies site-wide.

**FAQPage Schema**:
- On any page with an FAQ section (e.g., homepage or dedicated FAQ page), go to the page editor → **AIOSEO Schema** tab.
- Enable FAQ schema or let AIOSEO detect questions.
- Or manually add Question/Answer pairs.

**Service / HowTo Schema**:
- For service pages (/rush-orders/, /printing/apparel-branding/, etc.), add relevant Service schema in the AIOSEO meta box.
- Describe the service, area served (nationwide + Scottsdale), provider (your Organization).

**Custom / Advanced JSON-LD**:
- If you need something more specific than AIOSEO's defaults, use the **Custom Schema** feature in AIOSEO (Pro has more options) or add the JSON-LD from `/schema/` folder via:
  - AIOSEO's "Custom Code" or "Additional Schema" section, or
  - A lightweight plugin like "Insert Headers and Footers" (paste the full script tag with JSON-LD in the head).
- The provided `organization.jsonld`, `localbusiness.jsonld`, and `faq.jsonld` files are ready — just adapt the logo/image URLs to your actual media library paths.

### 4. Sitemap & Indexing
- **AIOSEO → Sitemap** → Make sure XML Sitemap is enabled and includes all important post types/pages.
- Exclude admin, drafts, thin pages if needed.
- In Google Search Console → Sitemaps, submit your sitemap URL (usually https://sldivprint.com/sitemap.xml or similar — AIOSEO shows the exact URL).

### 5. Breadcrumbs & Other
- Enable Breadcrumbs in AIOSEO (improves UX and rich results).
- Social settings: Add your Facebook, Twitter, LinkedIn, Instagram profiles.

## Pro Tips for sldivprint.com
- Run AIOSEO's built-in **SEO Audit** or **Site Analyzer** regularly for automated suggestions.
- Use AIOSEO's **404 Monitor** and **Redirects** manager to clean up broken links.
- For author SEO: Add Sam Liebman as author on blog posts and enable author schema if available.
- Combine with image optimization and caching plugins for best Core Web Vitals scores.
- After major changes, use Google Search Console "URL Inspection" → "Request Indexing" on key pages.

## Validation
- After setting up schema: Test with https://search.google.com/test/rich-results
- Check structured data in Google Search Console → Enhancements.

This configuration, combined with the content and performance fixes in the repo, will give your site a massive technical SEO boost and make it highly understandable to both search engines and AI systems.

Need me to generate more specific schema for a particular service page or help with exact title templates? Just say the word.
