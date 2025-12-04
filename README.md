
# Francesco Foresta — Online CV

Welcome to the professional online CV of **Francesco Foresta**, Principal Architect specializing in Cloud-Native Telecom, Edge, and 5G RAN/Core solutions. This site showcases my career, skills, certifications, publications, and more.

## About Me

- **Role:** Principal Architect at JMA Wireless
- **Expertise:** Cloud-Native Telecom, 5G RAN/Core, Kubernetes, eBPF, Open Source, System Architecture
- **Patents:** 4+
- **Location:** Bologna, Italy
- **Languages:** Italian (Native), English (Professional)
- **Contact:** fr [dot] foresta [at] gmail [dot] com
- **LinkedIn:** [frforesta](https://www.linkedin.com/in/frforesta)
- **GitHub:** [unusualfor](https://github.com/unusualfor)

## Site Features

- Career profile, education, and work experience
- Certifications and skills
- Publications and patents
- Interests and contact information

All content is managed in `_data/data.yml` for easy updates.

## Local Development

To preview or edit the site locally:

```bash
# Clone the repository
git clone https://github.com/unusualfor/online-cv.git

# Install dependencies
bundle install

# Serve locally
bundle exec jekyll serve

# Open http://localhost:4000 in your browser
```

Or use Docker:

```bash
docker-compose up
```

## Deployment

This site is built with Jekyll and can be deployed on Cloudflare Pages or GitHub Pages.

**Cloudflare Pages settings:**
- **Build command:** `bundle exec jekyll build`
- **Output directory:** `_site`

## Customization

You can personalize the site by editing `_data/data.yml` (profile, skills, experience, etc.) and choosing a color scheme from the available skins in `_sass/skins/`.

## License & Credits

Theme by [Xiaoying Riley](http://themes.3rdwavemedia.com/).
Site design and content © Francesco Foresta.

