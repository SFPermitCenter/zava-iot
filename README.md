# Zava IoT Hub — with Device Pages

Static GitHub Pages site that *looks* like an Azure IoT Hub portal for demo purposes.

- Dashboard: `index.html` (links to per-device pages)
- Data endpoints:
  - `/data/devices.json`
  - `/data/kpis.json`
  - `/data/telemetry_latest.json`
  - `/data/personas.json`
  - `/data/work_orders.json`
  - `/data/alerts.json`
  - `/data/series/<DEVICE>_24h.json`
- Device pages: `/devices/<DEVICE>.html` (vibration & temperature charts + snapshot)

> For Copilot Studio: add the site root or `/data/` as a Public Website knowledge source.

## Publish
1) Create a repo (e.g., `fabrikam-iot-demo`), upload contents at repo root.
2) Settings → Pages → Deploy from a branch → `main` → `/(root)`.
3) Visit: `https://<user>.github.io/fabrikam-iot-demo/`.
