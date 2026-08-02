# ECU Checksum Correction API — SOFTECHPRO API

### 🔌 Automatic ECU checksum & CVN correction via a simple REST API — integrate it into your own tuning platform, app or workshop tool

**[👉 Get your API key at softechpro-solutions.com](https://softechpro-solutions.com)**

Part of the **[SOFTECHPRO API](https://github.com/softechpro-solutions/softechpro-api)** — send an ECU file, get it back processed in seconds. Brick-safe, native correctors (not a generic library). 740+ ECUs, 40+ brands, diesel and petrol — Bosch, Siemens, Continental, Delphi, Marelli, Denso.

- **Auth:** `X-API-Key` · one registered domain per key
- **Plans:** LITE €69/mo (€650/yr) — ~150 files/day, 60 req/min · higher tiers on request
- REST / JSON · responses in seconds

```bash
curl -X POST https://softechpro-solutions.com/api/checksum -H "X-API-Key: YOUR_KEY" -F "file=@modified.bin" -o corrected.bin
```

🌐 **[softechpro-solutions.com](https://softechpro-solutions.com)** — key, docs, pricing · full API: [softechpro-api](https://github.com/softechpro-solutions/softechpro-api)

---
*ECU Checksum Correction API: Automatic ECU checksum & CVN correction REST API for chiptuning software and ECU tuning platforms.*