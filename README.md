# CES 2026 French Startups Directory

An interactive, searchable directory of **53 French startups** exhibiting at CES 2026 in Las Vegas.

Built for [French Tech Journal](https://frenchtechjournal.com).

![Preview](https://img.shields.io/badge/Startups-53-blue) ![Sectors](https://img.shields.io/badge/Sectors-16-green)

## Features

- 🔍 **Full-text search** across company names, descriptions, and products
- 🏷️ **Filter by sector** (16 categories including Health Tech, AI, Green Tech, Cybersecurity)
- 📱 **Mobile-responsive** dark theme design
- 🔗 **Direct links** to each startup's website
- 📖 **Expandable cards** showing product/innovation details
- ⚡ **Zero dependencies** — single HTML file, loads instantly

## Sectors Covered

| Sector | Count |
|--------|-------|
| Health Tech / Wellness | 11 |
| Robotics / AI | 6 |
| Cybersecurity | 6 |
| Consumer Tech / Lifestyle | 6 |
| Smart Home / Smart City | 4 |
| Industry 4.0 | 4 |
| Green Tech | 3 |
| Entertainment | 3 |
| AI Business Solution | 2 |
| Mobility | 2 |
| + 6 more sectors | |

## Deploy to Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/YOUR_USERNAME/ces-2026-french-startups)

Or connect this repo to Vercel:

1. Push this repo to GitHub
2. Go to [vercel.com/new](https://vercel.com/new)
3. Import your GitHub repository
4. Click **Deploy**

## Custom Domain

To use a custom domain like `ces.frenchtechjournal.com`:

1. In Vercel project settings → Domains
2. Add your subdomain
3. Add DNS record:
   - **Type:** CNAME
   - **Name:** ces
   - **Value:** cname.vercel-dns.com

## Updating the Data

Edit the `startups` array in `index.html` to add, remove, or update startups. Each startup object has:

```javascript
{
  name: "Company Name",
  website: "company.com",
  description: "Company description...",
  product: "Product/innovation description...",
  sector: "SECTOR NAME"
}
```

Valid sectors:
- `HEALTH TECH / WELLNESS`
- `ROBOTICS / AI`
- `GREEN TECH`
- `CYBERSECURITY`
- `CONSUMER TECH / LIFESTYLE`
- `SMART HOME / SMART CITY`
- `ENTERTAINMENT`
- `INDUSTRY 4.0`
- `MOBILITY`
- `FINTECH`
- `AI Business Solution`
- `EDTECH`
- `RETAIL TECH`
- `SPORT TECH`
- `TELECOM`
- `GAMING`

## Data Source

Startup data sourced from Business France's CES 2026 French Pavilion directory.

## License

© 2026 French Tech Journal. Data provided for informational purposes.
