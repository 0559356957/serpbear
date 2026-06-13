# FoneZone SerpBear Setup Guide
## Self-Hosted Keyword Rank Tracker — Free

---

## OPTION A — Run Locally (Test on your Mac/PC first)

1. Install Docker Desktop: https://www.docker.com/products/docker-desktop/
2. Copy docker-compose.yml and .env.fonezone to a folder, rename .env.fonezone to .env
3. Edit .env — change PASSWORD and SECRET
4. Run: docker compose up -d
5. Open: http://localhost:3000

---

## OPTION B — Run on VPS (Recommended)

Best cheap VPS:
- Hetzner: €4.51/mo — https://www.hetzner.com/cloud
- DigitalOcean: $6/mo — https://digitalocean.com

Steps:
```bash
ssh root@YOUR_VPS_IP
curl -fsSL https://get.docker.com | sh
mkdir /opt/fonezone-serpbear
cd /opt/fonezone-serpbear
# Upload files then:
docker compose up -d
```

---

## ADDING DOMAINS

- fonezone.ae — Google UAE (at) English
- fonezone.me — Google KSA (sa) English + Arabic
- fastlinkinc.com — Google UAE (at) English
- fone44.com — Google UAE (at) English

---

## SCRAPER API Setup

Sign up free: https://www.scrapingbee.com (1000 free credits/mo)
In SerpBear → Settings ui Scraper → Select ScrapingBee → Paste Key

---

## COST

| Component | Cost |
|-----------|-----|
| VPS (Hetzner CX22) | €4.51/mo |
| ScrapingBee (1000 free) | $0/mo to start |
| **Total** | **~+5/mo** |

vs Semrush Position Tracking = $99+/mo
**Saves ~$90-€1/mo**
