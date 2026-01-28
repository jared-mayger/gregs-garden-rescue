# SEO Setup Guide for Greg's Garden Rescue

## Files Included for SEO:
✅ robots.txt - Tells search engines what to crawl
✅ sitemap.xml - Lists all pages for search engines
✅ structured-data.html - Schema markup for rich snippets
✅ Meta tags in all HTML files

## Setup Steps:

### 1. BEFORE YOU GO LIVE - Customize These:

**In each HTML file, update:**
- Domain name: Replace `https://www.gregsgardenrescue.com` with YOUR actual domain
- Location: Replace "Your City, State" with your actual location
- Phone: Replace (555) 123-4567 with real phone
- Email: Replace info@gregsgardenrescue.com with real email

**In sitemap.xml:**
- Update all URLs with your actual domain
- Update lastmod dates to current date

**In structured-data.html:**
- Add real business address and coordinates
- Update phone, email, hours
- Add real social media links (or remove if not applicable)
- Add real latitude/longitude (Google Maps will give you these)

### 2. Add Structured Data to HTML Files:

Copy the code from `structured-data.html` and paste it in the `<head>` section of:
- index.html
- testimonials.html  
- booking.html

(Place it right before the closing `</head>` tag)

### 3. Domain Hosting Options:

#### OPTION A: GitHub Pages + Custom Domain (FREE)
1. Create GitHub account
2. Create repository named: `yourusername.github.io`
3. Upload all files to repository
4. Settings → Pages → Enable GitHub Pages
5. Settings → Pages → Add custom domain
6. In your domain registrar (GoDaddy, Namecheap, etc.):
   - Add CNAME record: `www` → `yourusername.github.io`
   - Add A records for apex domain:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
7. Wait 24 hours for DNS propagation
8. Enable HTTPS in GitHub settings

**Pros:** Free, easy, automatic HTTPS
**Cons:** Limited server-side functionality

#### OPTION B: Netlify (EASIEST)
1. Go to netlify.com
2. Drag & drop your folder
3. Settings → Domain management → Add custom domain
4. Follow Netlify's DNS instructions
5. Auto HTTPS enabled

**Pros:** Dead simple, free SSL, continuous deployment
**Cons:** None for static sites

#### OPTION C: Traditional Web Host
- Hostinger ($2-3/month)
- Bluehost ($3-8/month)
- SiteGround ($3-15/month)

Upload files via FTP/cPanel file manager

### 4. After Going Live - Register with Search Engines:

**Google Search Console:**
1. Go to: search.google.com/search-console
2. Add your property (domain)
3. Verify ownership (DNS or HTML file method)
4. Submit sitemap.xml
5. Monitor indexing and search performance

**Bing Webmaster Tools:**
1. Go to: bing.com/webmasters
2. Similar process to Google
3. Submit sitemap

### 5. Local SEO Boosters:

✅ **Google Business Profile** (CRITICAL for local business)
   - Go to: google.com/business
   - Create free listing
   - Add photos, hours, services
   - Get reviews from customers
   - Shows up in Google Maps and local search

✅ **Get Listed in Local Directories:**
   - Yelp
   - Angie's List / Angi
   - HomeAdvisor
   - Thumbtack
   - Yellow Pages
   - Local Chamber of Commerce

✅ **Build Backlinks:**
   - Get featured in local news
   - Partner with local nurseries/hardware stores
   - Join local business associations
   - Start a blog with garden tips

### 6. Content SEO Best Practices Already Included:

✅ Semantic HTML (proper heading hierarchy)
✅ Alt text for images (add when you add real images)
✅ Mobile responsive
✅ Fast loading (minimal dependencies)
✅ Clean URLs (index.html, testimonials.html, booking.html)
✅ Internal linking between pages
✅ Contact information in footer (good for local SEO)

### 7. Additional SEO Improvements to Consider:

**Add a Blog Section:**
- "10 Tips for Spring Garden Maintenance"
- "How to Rescue an Overgrown Garden"
- "Best Plants for [Your City] Climate"
- Helps with keyword ranking and authority

**Add Real Images:**
- Before/after photos of gardens
- Photos of your team/equipment
- Compress images (use TinyPNG.com)
- Add descriptive alt text

**Get Customer Reviews:**
- Ask satisfied customers to review on Google
- Display reviews on testimonials page
- Reviews boost local SEO significantly

**Add FAQ Page:**
- "How much does garden restoration cost?"
- "How long does lawn care take?"
- Answers common questions, helps with voice search

### 8. Monitor Your SEO:

**Tools to use (all free):**
- Google Search Console - Track rankings, clicks, issues
- Google Analytics - Track visitors, behavior
- PageSpeed Insights - Check loading speed
- Mobile-Friendly Test - Verify mobile compatibility

### 9. Keywords to Target:

Based on your services, focus on:
- "garden restoration [your city]"
- "lawn care services [your city]"
- "landscaping [your city]"
- "overgrown garden cleanup [your city]"
- "pruning services near me"
- "garden maintenance [your city]"

### 10. Timeline Expectations:

- Week 1-2: Site gets indexed by Google
- Month 1-3: Start appearing in search results
- Month 3-6: Climbing in rankings (with ongoing SEO)
- Month 6+: Established presence in local search

**Remember:** SEO is a marathon, not a sprint. Consistent content, reviews, and local citations will boost you over time.

## Quick Wins for Immediate SEO Impact:

1. ✅ Create Google Business Profile (TODAY)
2. ✅ Submit sitemap to Google Search Console
3. ✅ Get 5-10 customer reviews on Google
4. ✅ Add your business to Yelp and local directories
5. ✅ Add real photos with descriptive filenames
6. ✅ Start posting garden tips on social media with links to site

## Questions?

Common issues:
- "Site not showing in Google" → Takes 1-2 weeks, submit sitemap
- "How to rank #1?" → Takes time, focus on reviews and content
- "Need more traffic?" → Google Ads can supplement while SEO builds

Good luck with Greg's Garden Rescue! 🌿
