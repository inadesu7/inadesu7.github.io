# INADESU Website

A modern, responsive Jekyll site for **Inclusive Action for Development and Sustainability (INADESU)**, a Cameroon-based non-profit organization working in health, education, advocacy, economic development, and project management.

🌐 **Live Site**: https://inadesu.com (when deployed to GitHub Pages)

## ✅ Status

**Complete and production-ready**. All pages, content, and functionality have been implemented. Ready for deployment to GitHub Pages.

### Recent Updates (Phase 2 - September 2026)
- ✨ **Projects page enhanced** – Separated into current and past project pages with dedicated layouts
- ✨ **Navigation dropdown** – Projects menu now includes "Current Projects" and "Past Projects" dropdown links
- ✨ **Responsive navbar** – Organization name displays on two lines on large screens, shows only "INADESU" on mobile
- ✨ **Homepage refresh** – Updated "Located In" section to "Where We Work" with expanded mission statement
- ✨ **News images** – Added unique images to stress/coping market traders article with proper positioning
- ✨ **Page banners** – Reduced height of green section headers by 50% for better visual balance
- 🔧 **Cleanup** – Removed unused navigation links ("Get Involved", "What We Do" pages)

---

## 📋 What's Included

### Pages (7)
- **Home** – Hero carousel, departments grid, featured projects, team preview, latest news
- **About Us** – Organization story, mission, vision, leadership, contact info
- **Projects** (Hub) – Project overview with featured current and past projects
  - **Current Projects** – 2 active initiatives with full images and team information
  - **Past Projects** – 9 completed projects (2016-2022) organized by year
- **Team** – 12 staff members with photos, names, roles, and departments
- **News** – Blog archive of 4 published articles with full content
- **Contact** – Contact form (Formspree), address, phone, email, social links
- **Donate** – Donation information and Donorbox integration

### Blog Posts (4)
Recovered from WordPress June 2026 backup with full original content:
1. **Gender-Based Violence Awareness** (June 2023) – Child sexual abuse prevention and survivor support
2. **Education Support Thank You** (Sept 2023) – Gratitude for international sponsorship
3. **Informal Market Mental Health** (Sept 2024) – Economic stressors and coping mechanisms for traders
4. **Playful Peer Tutoring in Crisis** (Dec 2024) – Educational response to Anglophone region conflict

### Content Data (5 files)
- `_data/organisation.yml` – INADESU contact, mission, vision, social links
- `_data/team.yml` – 12 team members with photos and roles
- `_data/departments.yml` – 5 operational departments with icons and descriptions
- `_data/projects.yml` – 2 current + 9 past projects with descriptions
- `_data/navigation.yml` – Main menu navigation structure

### Design & Assets
- **Layouts** (3) – Master template (default), page template, post template
- **Includes** (7) – Reusable components: header, navigation, footer, social icons, cards for projects/team/news
- **CSS** (4) – Bootstrap, Bootstrap Icons, Kind Heart Charity template, INADESU customizations
- **Fonts** – Metropolis font family (woff/woff2)
- **JavaScript** – Bootstrap minified
- **Images** (35+)
  - 12 team member portraits
  - 14 project activity photos
  - 5 news article feature images
  - 6 section background images
  - Logo and icons

### Integrations
- **Contact Form** – Formspree integration (form ID: meaodllp)
- **Donations** – Donorbox embedded fundraising platform
- **GitHub Actions** – Automated build and deploy workflow for GitHub Pages

---

## 🎨 Design

Built on the **Kind Heart Charity** Bootstrap 5 template with INADESU branding:
- **Primary Color**: Green (#2f8548)
- **Secondary Color**: Dark Gray (#3d5144)
- **Accent Color**: Orange (#e77f2f)
- **Fully responsive** – Mobile, tablet, desktop optimized
- **Accessibility** – Semantic HTML, alt text for all images, keyboard navigation

---

## 🚀 Deployment

### GitHub Pages (Recommended)

1. Push to GitHub repository:
```bash
git remote add origin https://github.com/YOUR_ORG/inadesu.github.io.git
git branch -M main
git push -u origin main
```

2. Enable GitHub Pages:
   - Go to repository Settings → Pages
   - Set source to "Deploy from a branch"
   - Select `main` branch, root folder
   - Save

3. Site builds automatically on every push
4. Access at: `https://YOUR_ORG.github.io` or custom domain

### Local Testing (Optional)

If Ruby and Bundler are available:

```bash
bundle install
bundle exec jekyll serve
# Visit http://localhost:4000
```

---

## 📝 Updating Content

### Add a Blog Post

Create `_posts/YYYY-MM-DD-slug.md`:

```yaml
---
layout: post
title: Article Title
date: YYYY-MM-DD HH:MM:SS +0000
categories: [Category1, Category2]
image: /assets/images/news/image-filename.jpg
image_alt: Brief image description
---

Article content in Markdown...
```

### Edit Organization Info

Update `_data/organisation.yml` for:
- Contact information
- Mission and vision statements
- Social media links
- Donation details

### Update Team

Edit `_data/team.yml` to add/update team members.

### Create a New Page

Create `_pages/page-name.md`:

```yaml
---
layout: page
title: Page Title
permalink: /page-name/
---

Page content in Markdown...
```

Then add to navigation in `_data/navigation.yml`.

---

## 📁 Project Structure

```
inadesu-jekyll/
├── _config.yml                 # Jekyll configuration
├── _data/                      # Data files (YAML)
│   ├── organisation.yml
│   ├── team.yml
│   ├── departments.yml
│   ├── projects.yml
│   └── navigation.yml
├── _includes/                  # Reusable components
│   ├── header.html
│   ├── navigation.html
│   ├── footer.html
│   ├── project-card.html
│   ├── team-card.html
│   ├── news-card.html
│   └── social-links.html
├── _layouts/                   # Page templates
│   ├── default.html           # Master layout
│   ├── page.html              # Standard pages
│   └── post.html              # Blog posts
├── _pages/                     # Content pages (Markdown)
├── _posts/                     # Blog posts
├── assets/
│   ├── css/                   # Stylesheets
│   ├── fonts/                 # Metropolis font
│   ├── images/                # INADESU images
│   └── js/                    # JavaScript
├── .github/workflows/         # GitHub Actions
├── .gitignore
├── Gemfile
├── index.html                 # Homepage
└── MIGRATION_NOTES.md         # Migration documentation
```

---

## 🔐 No Sensitive Files

This repository contains **only public-facing website content**. No hosting configuration, credentials, certificates, private keys, email data, access logs, or system files from the original archive were included.

---

## 🔗 Links & Resources

- **INADESU**: info@inadesu.com | +237 6 52 64 90 23
- **Location**: Baptist Junction, Bokwoango, Buea, Cameroon
- **GitHub Actions**: Automatic deployment on push to main branch
- **Jekyll Docs**: https://jekyllrb.com/docs/

---

## 📄 License

This website content is © INADESU. The Kind Heart Charity template is available under MIT License.

---

## 🛠️ Troubleshooting

**Site not building?**
- Check `_config.yml` syntax (YAML format)
- Verify image paths are correct (use relative_url filter)
- Ensure all Markdown front matter is valid YAML

**Links not working?**
- Use `{{ '/path/' | relative_url }}` for Jekyll links
- Use absolute paths for external links

**Images not showing?**
- Verify image files exist in `/assets/images/`
- Check file names match exactly (case-sensitive on GitHub Pages)
- Use proper Jekyll path: `{{ '/assets/images/file.jpg' | relative_url }}`

**Form not submitting?**
- Verify Formspree form ID in contact.md
- Check email notifications in Formspree account

---

**Questions or issues?** Open an issue on GitHub or contact info@inadesu.com
