# Thai Tax Calculator 🧾

[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE) [![Live Demo](https://img.shields.io/badge/demo-live-blue.svg)](https://iindrajeet4.github.io/thai-tax-calculator/) [![Dependencies](https://img.shields.io/badge/dependencies-none-brightgreen.svg)](#)

**Thai Personal Income Tax (PIT) calculator for tax year 2568 (2025)** — all 8 income categories under Section 40, dividend tax-credit comparison, the complete allowance set, and a live tax-planning mode. Single HTML file, 100% client-side, bilingual **ไทย/English** (Thai-first).

คำนวณภาษีเงินได้บุคคลธรรมดา ปีภาษี 2568 — รองรับเงินได้ทั้ง 8 ประเภทตามมาตรา 40, เปรียบเทียบเครดิตภาษีเงินปันผล, ค่าลดหย่อนครบชุด และโหมดวางแผนลดหย่อน ไฟล์เดียว ไม่ส่งข้อมูลออกจากเครื่อง

**[🔗 Live Demo / ลองใช้เลย](https://iindrajeet4.github.io/thai-tax-calculator/)**

## ✨ Features

- **All 8 income categories (มาตรา 40)** — add multiple income rows with a type selector; correct expense deduction per type:
  - 40(1) salary + 40(2) service/freelance — 50% standard expense, **combined** cap ฿100,000
  - 40(3) royalties/goodwill — 50% cap ฿100,000, or actual expenses
  - 40(4) interest — no expense deduction
  - 40(4) dividends — no expense; see dividend credit below
  - 40(5) rent — by asset type: buildings 30%, agricultural land 20%, other land 15%, vehicles 30%, other 10%, or actual
  - 40(6) liberal professions — medical 60%, law/accounting/engineering/architecture/fine arts 30%, or actual
  - 40(7) contract work with materials — 60% or actual
  - 40(8) business/other — 60% or actual
- **Dividend tax credit (เครดิตภาษีเงินปันผล, มาตรา 47 ทวิ)** — 20/80 gross-up for the 20% corporate rate; the app computes both routes (include in return + credit vs. 10% final withholding) side by side, recommends the cheaper one, and lets you override
- **Complete allowances**, grouped in collapsible sections: personal ฿60,000, spouse ฿60,000, children ฿30,000 (+฿30,000 extra for 2nd+ children born 2018/2561 onward → ฿60,000), parents ฿30,000 each (max 4), disabled dependents ฿60,000, social security ≤฿9,000, life insurance ≤฿100,000, own health insurance ≤฿25,000 (life+health combined ≤฿100,000), parents' health insurance ≤฿15,000, PVD/GPF ≤15%, NSF ≤฿30,000, RMF ≤30%, pension insurance ≤15% & ฿200,000 — **retirement group combined cap ฿500,000 applied automatically** — ThaiESG ≤30% & ฿300,000, ThaiESGX new money (May–Jun 2025) ≤30% & ฿300,000, ThaiESGX LTF-switch (year-1 portion ≤฿300,000 of the ฿500,000 spread), home-loan interest ≤฿100,000, Easy E-Receipt 2.0 ≤฿50,000, political party donation ≤฿10,000, education/sports/public-hospital donations counted 2× (≤10%), general donations ≤10% — donation caps applied in the correct order
- **Transparent results**: bracket-by-bracket table (0%→35%), effective + marginal rate, gross → expenses → allowances → net breakdown, minimum-tax check under Section 48(2) (0.5% of gross when non-salary income ≥ ฿120,000), and a clear **ภาษีที่ต้องชำระเพิ่ม / ขอคืน** line once you enter tax already withheld
- **Planning mode**: drag RMF/ThaiESG sliders and instantly see tax saved vs. a no-investment baseline
- EN/TH toggle, dark/light theme, thousands separators, responsive — all persisted locally, no data leaves your machine

## 🔄 Update policy / นโยบายการอัปเดตข้อมูล

This is a **static app — tax rules are embedded in the file**, not fetched live. Check the version label in the header: **"ข้อมูลปีภาษี 2568 · อัปเดตล่าสุด <date>"**. Rules are re-verified against the Revenue Department and reputable tax summaries whenever the app is updated; yearly measures (Easy E-Receipt, ThaiESGX) change with each government announcement and are updated here after they are official.

แอปนี้เป็นไฟล์ static — กฎภาษีฝังอยู่ในไฟล์ ไม่ได้ดึงสดจากอินเทอร์เน็ต โปรดดูป้ายเวอร์ชันที่หัวเว็บว่าข้อมูลเป็นของปีภาษีใดและอัปเดตล่าสุดเมื่อไร

## 📚 Sources / แหล่งอ้างอิง

- [กรมสรรพากร (Revenue Department)](https://www.rd.go.th) — progressive rate schedule, Sections 40, 42 ter, 47, 47 bis, 48(2) of the Revenue Code
- [PwC Worldwide Tax Summaries — Thailand, Individual deductions](https://taxsummaries.pwc.com/thailand/individual/deductions)
- [SEC Q&A on LTF → Thai ESGX tax measures (PDF)](https://www.sec.or.th/TH/Documents/Thai%20ESGX/QA-LTF-to-Thai%20ESGX-010468.pdf)
- [SET Investnow — 2568 fund deduction options (ThaiESG/ThaiESGX)](https://www.setinvestnow.com/th/knowledge/article/664-rinjai-investment-options-with-tax-ltf-thaiesgx-deduction-benefits-in-2025)

## 🚀 Usage

Use it right away at **https://iindrajeet4.github.io/thai-tax-calculator/**, or open `index.html` in any browser. No build, no server, no data leaves your machine.

## ⚠️ Disclaimer

**Estimates only — not tax or investment advice.** Figures follow the tax year 2568 (2025) structure. Deduction caps (especially ThaiESG/ThaiESGX and yearly stimulus measures like Easy E-Receipt) change with government announcements — always verify against [rd.go.th](https://www.rd.go.th) or a tax professional before filing.

เป็นการประมาณการเบื้องต้นเท่านั้น ไม่ใช่คำแนะนำทางภาษีหรือการลงทุน การคำนวณอิงโครงสร้างภาษีปีภาษี 2568 เพดานลดหย่อนบางรายการเปลี่ยนตามประกาศแต่ละปี โปรดตรวจสอบกับกรมสรรพากรก่อนยื่นจริง

## 📄 License

MIT — see [LICENSE](LICENSE)

---

## 💼 Services & custom work

I take on freelance and contract work around this project — custom implementation,
new features, and integration with your stack.

**Contact:** [GitHub @iindrajeet4](https://github.com/iindrajeet4) (opening an issue on this repo works too) · [DubeGames](https://dubegames.indrajeetdubeyy.workers.dev/)
