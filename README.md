# Thai Tax Calculator 🧾

[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE) [![Live Demo](https://img.shields.io/badge/demo-live-blue.svg)](https://iindrajeet4.github.io/thai-tax-calculator/) [![Dependencies](https://img.shields.io/badge/dependencies-none-brightgreen.svg)](#)

**Thai Personal Income Tax (PIT) calculator with a live tax-planning mode** — drag RMF/ThaiESG sliders and instantly see how much tax you save. Single HTML file, 100% client-side, bilingual **English/ไทย**.

คำนวณภาษีเงินได้บุคคลธรรมดา พร้อม**โหมดวางแผนลดหย่อน** — เลื่อน slider RMF/ThaiESG แล้วเห็นภาษีที่ประหยัดได้ทันที ไฟล์เดียว ไม่ส่งข้อมูลออกจากเครื่อง

**[🔗 Live Demo / ลองใช้เลย](https://iindrajeet4.github.io/thai-tax-calculator/)**

## ✨ Features

- **Progressive bracket engine** per the Thai Revenue Department schedule (0% → 35%, 8 brackets) with a live bracket-by-bracket table highlighting where your income lands
- **Transparent breakdown**: gross income → standard expense (50%, max ฿100,000) → total allowances → net taxable income, all with thousands separators
- **Full deduction set**: personal, spouse, children, parents, disabled dependents, social security, life/health insurance, parents' health insurance, PVD/GPF, RMF, ThaiESG, annuity, home-loan interest, donations (education counted 2×, 10% caps applied in correct order), Easy E-Receipt (capped ฿50,000)
- **Retirement-group cap** (RMF + PVD + annuity ≤ ฿500,000 combined) and per-item caps applied automatically
- **Planning mode**: shows tax saved vs. a no-investment baseline and the instant "% return" your deduction gives you, plus average tax per month
- Effective rate vs marginal rate, EN/TH toggle, dark/light theme — all persisted locally

## 🚀 Usage

Use it right away at **https://iindrajeet4.github.io/thai-tax-calculator/**, or open `index.html` in any browser. No build, no server, no data leaves your machine.

## ⚠️ Disclaimer

Estimates follow the **tax year 2568 (2025)** structure. Deduction caps (especially ThaiESG and yearly stimulus measures like Easy E-Receipt) change with government announcements — always verify against [rd.go.th](https://www.rd.go.th) or a tax professional before filing. **Not tax or investment advice.**

การคำนวณอิงโครงสร้างภาษีปี 2568 เพดานลดหย่อนบางรายการเปลี่ยนตามประกาศแต่ละปี โปรดตรวจสอบกับกรมสรรพากรก่อนยื่นจริง — ไม่ใช่คำแนะนำทางภาษีหรือการลงทุน

## 📄 License

MIT — see [LICENSE](LICENSE)
