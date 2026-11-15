<p align="center">
  <a href="https://www.fornax.ee">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="fornax-logo-on-dark.svg">
      <img src="fornax-logo-on-light.svg" alt="Fornax" height="80">
    </picture>
  </a>
</p>

<p align="center">
  <b>Industrial digitalisation and AI for woodworking manufacturers</b><br>
  doors · windows · furniture
</p>

---

Practical, field-tested building blocks for small and mid-size plants: machine data, CNC, quality control, traceability and local AI.
Written from a real factory, for people who have to keep production running while they change it.

## Open materials

| Repository | What it is |
|---|---|
| [**it-ot-boundary-kit**](https://github.com/fornax-ee/it-ot-boundary-kit) | Splitting responsibilities between corporate IT and production/OT: layered ownership, minimum baseline, change coordination, templates |
| [**cnc-program-history**](https://github.com/fornax-ee/cnc-program-history) | Read-only collection of CNC programs and machine files into Git, so every change has a history |
| [**local-llm-gateway-smb**](https://github.com/fornax-ee/local-llm-gateway-smb) | Local AI for ~50 users on one GPU server: vLLM behind an OpenAI-compatible gateway, model profiles instead of model names |
| [**machine-data-grafana**](https://github.com/fornax-ee/machine-data-grafana) | Logging production line data and analysing it in Grafana: collector → PostgreSQL → Grafana, without a full MES |
| [**rfid-on-production-lines**](https://github.com/fornax-ee/rfid-on-production-lines) | Field notes on RFID on conveyor and overhead lines: read range, zones, mounting, MQTT integration, buying checklist |

## Focus areas

- **Production data** — machines, lines and ERP in one view, live and historical
- **CNC & machinery** — program management, versioning and generation across machine brands
- **Quality control** — machine vision and measurements at the line
- **Marking & traceability** — RFID, QR and barcodes, inkjet marking and labels
- **Planning & reporting** — load forecasts and work-time standards built on real machine data
- **On-premise AI** — language and vision models on your own servers; factory data stays in-house

## How we build

- **Read-only first.** Observe machines before touching them.
- **Local where it matters.** Production keeps running when the internet link is down.
- **Boring technology.** Tools that a small team can run for years.
- **Same rules both ways.** IT and OT follow one baseline.

---

<p align="center">
  <a href="https://www.fornax.ee">fornax.ee</a> · <a href="mailto:info@fornax.ee">info@fornax.ee</a>
</p>
