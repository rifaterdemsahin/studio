# 6_Semblance — Errors & Near-Misses

> Log problems, causes, fixes, and workarounds. The gap between simulation and reality.

---

## 📋 Error Log

| # | Date | Problem | Cause | Fix / Workaround | Status |
|---|------|---------|-------|-----------------|--------|
| 1 | TBD | _Add issues as they arise_ | | | |

---

## 📝 How to Log an Issue

1. Copy the row template above
2. Fill in: date, what went wrong, why it happened, how it was fixed
3. Update status: `Open` / `Fixed` / `Workaround`

---

## 🔍 Common Issues to Watch For

- **Lighting flicker** — check power frequency (50 Hz UK vs 60 Hz US) and camera shutter speed
- **Audio hum** — ground loop; use balanced cables or a DI box
- **Overheating camera** — mirrorless cameras can cut out after ~30 min; enable "clean HDMI" mode
- **OBS lag** — lower bitrate, use hardware encoder (NVENC/AMF) if available
- **Echo on audio** — add more acoustic panels or move mic closer to mouth
- **GitHub Pages not updating** — check Actions workflow status and branch settings
