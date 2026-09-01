## Bagas — Industrial Engineering @ UC Berkeley

I build models that make an operating decision cheaper to get right: where inventory
should sit, what a production line is actually capable of, how many people to staff and
when. Currently a **Summer Analyst at EY** (Strategy & Transactions — Valuation, Modeling
& Economics), and I run two small businesses that give me real systems to point the
methods at.

Indonesian, based in Berkeley during term and Jakarta over breaks.

---

### Portfolio

Each repo is a full analysis — real code, a runnable pipeline, a quantified result, and a
section on what is wrong with the model. `python run_analysis.py` reproduces every number
in every README from a clean clone.

| Project | The question | Result |
|---|---|---|
| **[Multi-echelon inventory optimization](https://github.com/bagas17-a11y/supply-chain-optimization)** | How much of each SKU should sit at each of three Indonesian DCs? | **Cost to serve −32%**, worst-served lane from 73% → 99.8% fill. The answer was to hold *more* inventory, not less. |
| **[Assembly line simulation](https://github.com/bagas17-a11y/assembly-line-simulation)** | An optimally balanced footwear line still misses target by 19%. Where does the capacity go, and what should we buy? | Preventive maintenance beats a second operator 3.6× per rupiah. Reducing task-time variability **loses money**. |
| **[Service operations design](https://github.com/bagas17-a11y/service-operations-design)** | My own barbershop: how many chairs, how many barbers, which hours, and is the booking system worth Rp 449k/month? | The shop loses **Rp 9.95m/month** to walk-outs the till never records. The booking subscription does not pay — chairs and appointment books are substitutes. |
| **[Aksara Buana](https://github.com/bagas17-a11y/aksara-buana)** | Dispatchers cannot see where the delivery fleet is. | Offline-first PWA for live driver tracking, digital checklists and proof of delivery. Next.js · Supabase · Leaflet. |

**Methods across the four:** discrete-event simulation (SimPy) · mixed-integer programming
(PuLP/CBC) · queueing theory (Erlang C, M/G/c) · demand forecasting (gradient boosting,
WAPE) · newsvendor and (R, S) inventory policy · line balancing (SALBP-1/2) · statistical
process control (X̄/R, Cp/Cpk) · Monte Carlo and block bootstrap · simulation-based
optimization

---

### Beyond the repos

**EY — Strategy & Transactions (VME).** Industry research and financial modeling. Indonesia
macro work (energy shocks, fuel subsidy policy, trade) and a used-car market study for an
Astra-focused engagement; multi-year audited financials rebuilt into working models.

**Timor Trims** — a two-chair barbershop I am opening in Jakarta Timur. SOPs, POS
selection, staff incentive design, unit economics. The service-operations repo above is
this shop, modelled properly.

**[Bagascuts](https://github.com/bagas17-a11y)** — a student barbershop I started at
Berkeley and grew to 150+ clients. It funded Timor Trims.

**Toyota** — Operations Management & Development Division (Jakarta, Dec 2025–Jan 2026).
Exposed to Toyota Production System and lean manufacturing practice on the shop floor.

**Shopee** — Product & Business Intelligence Intern on ShopeeFood (Jakarta, May–Aug 2025).
Designed a local-merchant bundling program that doubled average basket size across 35+ merchants
and grew buyer volume 20%. Diagnosed funnel and fulfillment gaps across 50M+ transaction records
via SQL, surfacing 8 insights adopted into ShopeeFood's regional planning cycle. Coordinated package tracking & logistics operations for SPX Express across Jakarta’s high-volume distribution network, identifying shipment discrepancies and escalating delays to uphold last-mile delivery SLA targets. Optimized last-mile delivery route planning for SPX Express Jakarta, restructuring courier assignments across delivery
zones to reduce route overlap and improve stops-per-hour efficiency within high-density urban corridors.

**Engvolve** — an IELTS prep and university-admissions platform for Indonesian students.
Product, content and partnerships.

**Mangroovy** — youth-led mangrove conservation in Jakarta. $35K+ initiative, 91 volunteers,
300+ trees planted, 3 national publications.

---

### Toolkit

`Python` (pandas, NumPy, SciPy, scikit-learn, SimPy, PuLP, matplotlib) ·
`SQL` · `Excel / financial modeling` · `TypeScript / Next.js` · `Supabase / PostgreSQL`

---

📫 bagas17@berkeley.edu · open to Summer 2027 internships in supply chain, operations
analytics, manufacturing and strategy
