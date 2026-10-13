# 🌐 Baran Office — Unified Smart Workspace (MIT)

Word + Excel + PowerPoint in ONE fluid document. UI in EN/TR/AR.
Static single file + README. By Baran Avisat.

## Unified canvas (modular blocks)

- **📝 Text, 📊 Sheet (8×20 + formulas), 📈 Chart (live), 📽️ Slide** —
  add/move/delete, per-block adaptive toolbar.
- **⚡ Live sync:** `{{Sheet1!B4}}` placeholders resolve live in text;
  charts re-render on every edit. Verified by tests.
- **🤖 AI co-pilot:** table-from-text (number extraction), slides-from-doc,
  extractive summary, report-from-sheet, chart-from-sheet — EN/TR/AR commands.
- **▶ Present mode**, multi-doc library, templates (report/budget/pitch),
  undo, `.baran.json` + HTML + print export.

## Formula engine (tested)

Arithmetic, comparisons, %, 20 functions (SUM/AVERAGE/MIN/MAX/COUNT/
COUNTA/SUMIF/COUNTIF/AVERAGEIF/IF lazy/AND/OR/NOT/CONCAT/UPPER/LOWER/LEN/
TRIM/ABS/INT/ROUND/SQRT/POWER/MOD/TODAY/NOW/TRUE/FALSE), ranges,
Excel-compatible errors incl. `#CIRC!`.

## Money & contact

- `CONFIG.ads` footer slot. Donate: BTC + USDT-TRC20 + IBANs.
- 📧 baranavisat@gmail.com · 📞 +90 531 326 37 22 · WhatsApp

## Run

```bash
cd baranoffice
python3 -m http.server 8080
```

## License

MIT.
