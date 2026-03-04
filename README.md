# InvoiceGen — Free Online Invoice Generator

A clean, fast, and fully open-source invoice generator. No signup required. Works entirely in the browser.

**Live demo:** https://zafarshaikh1992.github.io/invoice/

---

## Features

- **Real-time live preview** — see your invoice update as you type
- **PDF download** — one-click "Download PDF" via browser print-to-PDF
- **Logo upload** — drag & drop your company logo
- **22 currencies** — USD, EUR, GBP, INR, JPY, and more
- **8 accent colors** — customize the invoice style
- **Line items** — add/remove rows with auto-calculated amounts
- **Discount** — percentage or flat amount
- **Tax** — configurable tax rate
- **Shipping** — add shipping costs
- **Amount paid** — track partial payments, shows balance due
- **Ship To** — optional separate shipping address
- **Payment terms** — Net 7/15/30/60/90 with auto due date
- **Notes & Terms** — add custom messages and conditions
- **No backend** — 100% client-side, no data ever leaves your browser
- **Mobile friendly** — responsive layout

## Usage

### Option 1: Use online
Visit https://zafarshaikh1992.github.io/invoice/

### Option 2: Self-host
1. Clone the repo: `git clone https://github.com/zafarshaikh1992/invoice.git`
2. Open `index.html` in any web browser — no server needed!

### Option 3: Deploy your own
Fork this repo, enable GitHub Pages from **Settings → Pages → Source: GitHub Actions**, and your copy will be live.

## Tech Stack

- Pure **HTML + CSS + JavaScript** — zero dependencies, zero build step
- **Google Fonts** (Inter) for typography
- **Browser Print API** for PDF generation
- **FileReader API** for logo upload
- **Intl.NumberFormat** for accurate currency formatting

## Contributing

Pull requests are welcome! Please open an issue first to discuss major changes.

## License

[MIT](LICENSE) — free to use, modify, and distribute.
