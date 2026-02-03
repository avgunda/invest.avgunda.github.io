---
layout: post
title: "E2E Networks Limited: Investment Analysis"
date: 2026-02-03
categories: [companies, investment]
---

_**Disclaimer: This analysis is for educational purposes only and does not constitute financial advice. Please conduct your own research or consult a financial advisor before making investment decisions. The facts presented herein are based on publicly available information and should be verified independently.**_

## 1. Summary

### 1.1 The Investment Thesis

E2E Networks Limited (NSE: E2E) stands at the precipice of a historic transformation, evolving from a niche domestic cloud provider into India's premier AI-focused hyperscaler. This transition is underpinned by a confluence of powerful secular tailwinds: the global explosion of Generative AI (GenAI), the Indian government's aggressive push for "Data Sovereignty" and "Atmanirbhar Bharat" in digital infrastructure, and a strategic recapitalization of the company following the entry of Larsen & Toubro (L\&T) as a strategic investor.

The investment case for E2E Networks is predicated on four pillars:

1. **First-Mover Advantage in Sovereign Compute:** As nations increasingly view data as a strategic asset, the demand for "Sovereign Cloud" infrastructure—where data, hardware, and legal jurisdiction remain within national borders—is skyrocketing. E2E Networks is the only listed pure-play entity in India offering an indigenous, GPU-centric public cloud that rivals global hyperscalers in performance while strictly adhering to Indian data localization mandates. 
2. **Strategic Validation via L\&T Partnership:** The acquisition of a 21% stake by engineering conglomerate Larsen & Toubro (L\&T) is a watershed moment. It fundamentally alters the company's risk profile by providing access to L\&T's vast enterprise client base, ensuring Tier-IV data center availability without heavy real-estate CAPEX, and fortifying the balance sheet with ₹1,407 Crore in fresh capital.This partnership de-risks the "execution" aspect of scaling.  
3. **Technological Leadership (The Blackwell Edge):** E2E is not merely following trends; it is setting the pace. The company has aggressively procured NVIDIA's latest Blackwell (B200) GPUs, positioning itself ahead of many competitors who are still deploying Hopper (H100) generations. With 1,024 B200 units slated for deployment in Q4 FY26, E2E possesses one of the densest AI compute clusters in the region.
4. **Financial Inflection Point:** While the company reported a net loss in Q3 FY26 due to accelerated depreciation and finance costs associated with capacity expansion, the underlying unit economics are robust. EBITDA margins have expanded to \~57%, and the Monthly Revenue Run-rate (MRR) is on track to hit ₹35-40 Crores by March 2026. This signals a classic "J-curve" trajectory where upfront investment suppresses short-term earnings but builds immense operating leverage for future years.

### 1.2 Key Risks & Sensitivities

Investors must weigh the high-growth potential against significant risks:

* **Technological Obsolescence:** The AI hardware cycle is brutally short (18-24 months). Rapid depreciation of H100/H200 assets as B200s become standard could compress margins.
* **Single Vendor Dependency:** The business model is heavily reliant on NVIDIA for GPU supply. Any supply chain disruption or pricing power exertion by NVIDIA poses a critical threat.
* **Execution Risk:** Managing a 10x expansion in infrastructure within 24 months creates operational fragility, evidenced by the recent Mumbai region outage.

### 1.3 Valuation Summary

Despite optics of high P/E multiples due to depreciation-led earnings suppression, E2E Networks trades at attractive forward multiples relative to its growth velocity. With revenue growing at ~70% YoY and EBITDA margins approaching 60%, the company effectively operates as a high-growth SaaS/Infrastructure play. We project the stock to outperform the broader Nifty IT index significantly over a 3-5 year horizon as the new capacity is monetized.


## 2. Industry Analysis: The AI Infrastructure Supercycle

### 2.1 The Macroeconomic Context: India's AI Ambition

India is currently undergoing a digital metamorphosis, transitioning from a service-exporting nation to a product and platform economy. The central government has identified Artificial Intelligence (AI) as a kinetic enabler for this transition, launching the **IndiaAI Mission** with an initial outlay of over ₹10,300 Crore. This mission aims to democratize computing access, a critical bottleneck for Indian startups and researchers.

**The "Sovereign Cloud" Imperative:** Historically, Indian enterprises relied on US-based hyperscalers (AWS, Azure, Google Cloud). However, geopolitical shifts and the Digital Personal Data Protection (DPDP) Act have created a "compliance moat." Critical sectors—Defense, BFSI (Banking, Financial Services, and Insurance), and PSU governance—now require data to reside physically in India, processed by entities subject to Indian jurisdiction. This creates a protected market for domestic players like E2E Networks.

### 2.2 Regulatory Tailwinds: Budget 2026 Implications

The Union Budget 2026 delivered a massive stimulus to the sector:

* **Tax Holidays:** A tax holiday until 2047 for foreign companies providing cloud services via Indian data centers. While this incentivizes global players to set up shop, it dramatically expands the total addressable market (TAM) for domestic infrastructure providers who can act as the "Indian reseller entity" required by law.
* **Infrastructure Status:** Data centers have been accorded infrastructure status, easing access to credit.  
* **Safe Harbour Norms:** New safe harbour provisions of 15% on cost for related entities provide clarity on transfer pricing, encouraging long-term capital deployment.

**Analysis of Impact on E2E:** These policies validate the sector's strategic importance. While global hyperscalers benefit, E2E's specific positioning as a "preferred partner" for sovereign workloads means it can capture the most sensitive (and often highest margin) slice of government and regulated enterprise business.

### 2.3 The Supply-Demand Mismatch in Compute

Global demand for AI compute far outstrips supply. The training of foundational Large Language Models (LLMs) requires clusters of thousands of GPUs running in parallel for weeks.

* **The Bottleneck:** It is not just about having GPUs; it is about *networking*. Standard cloud instances cannot handle LLM training because the latency between chips slows down the process.  
* **The Solution:** High-performance interconnects like **InfiniBand** (offering 3.2 Tbps throughput) are essential. E2E Networks is one of the few Indian providers deploying InfiniBand at scale, distinguishing it from commodity cloud providers who use standard Ethernet.


## 3. Business Analysis: The Sovereign AI Hyperscaler

### 3.1 Corporate Evolution

E2E Networks has successfully pivoted from a low-cost Linux cloud provider to a specialized AI infrastructure firm.

* **2009-2017:** Bootstrapped growth, focusing on SMEs and web hosting.  
* **2018:** IPO on NSE Emerge; capital raised for initial expansion.  
* **2022-2023:** Strategic pivot to GPU compute; launch of Cloud GPU instances.  
* **2024-Present:** L\&T Partnership, Blackwell procurement, and launch of TIR (AI PaaS).2

This evolution mirrors the trajectory of specialized US clouds like CoreWeave or Lambda Labs, which capitalized on the AI boom faster than generalist hyperscalers could pivot.

### 3.2 The "5As" Framework & Value Proposition

Management defines its competitive edge through the "5As": **Affordability, Assistance, Accessibility, Accommodativeness, and Atmanirbhar Bharat**.

* **Affordability:** By utilizing open-source software stacks (KVM, Linux) rather than expensive proprietary licenses (VMware, Windows), and by optimizing hardware density, E2E claims to offer **up to 70% cost savings** compared to AWS or Azure.
* **Accessibility:** Unlike hyperscalers that require long-term contracts for high-end GPUs, E2E offers hourly billing and instant provisioning (10-second deployment times), lowering the barrier to entry for startups.

### 3.3 Technology Stack: Deep Dive

The company's offering goes beyond "renting hardware." It has built a vertically integrated stack:

#### 3.3.1 Hardware Layer (The Engine)

* **GPU Inventory:** The portfolio includes the entire NVIDIA datacenter range: T4 (inference), A100 (training/inference), H100 (heavy training), and now H200 and B200 (Blackwell).
* **Blackwell Deployment:** The procurement of 1,024 B200 units is a game-changer. These chips offer 192GB of HBM3e memory and are essential for training trillion-parameter models. Deploying these in the Chennai DC (L\&T powered) creates a "Supercluster" capability previously unavailable in India.

#### 3.3.2 TIR Platform (The OS for AI)

Launched in 2024, **TIR** (Training, Inference, Research) is a Platform-as-a-Service (PaaS) layer sitting on top of the hardware.

* **Functionality:** It abstracts the complexity of cluster management. Data scientists can launch "Notebooks," manage "Vector Databases" (Qdrant), and deploy "Inference Endpoints" without managing the underlying Linux kernel or networking drivers.  
* **Strategic Value:** TIR increases customer stickiness. Once a team builds their MLOps workflow on TIR, migrating to another cloud becomes difficult due to the integration of proprietary tools and data pipelines. It also commands higher margins than raw infrastructure rental.

#### 3.3.3 AI Labs as a Service (AILaaS)

Targeting the academic sector, AILaaS allows universities to slice a single physical GPU into multiple virtual instances (vGPUs), enabling 15+ students to share one card.

* **Insight:** This is a customer acquisition funnel. By training the next generation of engineers on E2E's platform, the company ensures that future decision-makers are familiar with its ecosystem.

### 3.4 Strategic Partnerships & Acquisitions

#### 3.4.1 Larsen & Toubro (L\&T)

L\&T's ₹1,407 Crore investment for a 21% stake is not passive.

* **Infrastructure:** L\&T is building massive data centers. E2E fills these centers with high-value compute.  
* **Sales Channel:** L\&T has deep relationships with the government, defense, and heavy industry. E2E effectively becomes the "Cloud Division" for L\&T's digital transformation projects. The ₹8.49 Crore order in Jan 2026 is the first sign of this channel activation.

#### 3.4.2 Jarvis Labs Acquisition

In Dec 2025, E2E acquired Jarvis Labs.

* **Strategic Rationale:** Jarvis Labs had a strong UI/UX focused on global developers ("one-click" deployments). E2E acquires this "frictionless" frontend technology and a global customer base, positioning it to export compute services to markets like the US and Europe where GPU availability is tight.


## 4. Financial Analysis & Forensic Review

### 4.1 Profit & Loss (P\&L) Trajectory

The P\&L statement reveals a company in hyper-growth mode, currently absorbing the costs of scaling.

Historical Performance (FY22 \- FY25):

* **Revenue:** Scaled from ₹51.87 Cr (FY22) to ₹163.96 Cr (FY25). **3-Year CAGR: 46.7%**.  
* **EBITDA:** Grew from ₹22.94 Cr (FY22) to ₹96.66 Cr (FY25). **3-Year CAGR: 61.5%**.  
* **PAT:** Exploded from ₹6.45 Cr (FY22) to ₹47.49 Cr (FY25). **3-Year CAGR: 94.5%**.

Q3 FY26 Snapshot (The Investment Phase):

* **Revenue:** ₹70.0 Cr (+68.3% YoY). The acceleration in revenue growth (vs. historical CAGR) confirms robust demand for the new capacity.  
* **EBITDA Margin:** 56.6%. Despite aggressive hiring and expansion, core margins remain elite, far superior to traditional IT services companies (typically 20-25%).  
* **Net Loss (PAT):** \-₹5.7 Cr.  
  * *Forensic Note:* This loss is driven by **Depreciation** (+₹47.6 Cr) and **Finance Costs**. In infrastructure businesses, depreciation is a non-cash charge. The company is cash-flow positive on an operating basis. The loss indicates heavy CAPEX deployment (installing GPUs) before full revenue realization (utilization ramp-up).

### 4.2 Balance Sheet Analysis

The balance sheet has undergone a radical transformation due to the L\&T recapitalization.

**Debt-to-Equity (D/E) Ratio Trends:**

* **FY24:** 2.03 (High Leverage Risk). The company borrowed heavily to buy H100s.  
* **FY25:** **0.046** (Fortress Balance Sheet). The equity infusion wiped out net debt relative to equity.  
* **Implication:** E2E now has one of the cleanest balance sheets in the infrastructure sector. It has the capacity to raise significant debt in the future to fund further expansion without diluting shareholders further.

Return on Capital Employed (ROCE) Dynamics 2:

* **FY23:** 24.8% (Peak efficiency).  
* **FY25:** 4.56%.  
* **Analysis:** The crash in ROCE is a **denominator effect**. The capital base (Equity \+ Reserves) exploded from \~₹50 Cr to \~₹1,600 Cr due to the L\&T deal. This capital is currently sitting as "Cash" or "Capital Work in Progress" (CWIP). As the B200 clusters go live (Q4 FY26) and start generating revenue, ROCE will mathematically rebound. We expect ROCE to normalize back to 20%+ levels by FY27/28 as the asset base matures.

### 4.3 Cash Flow Analysis

The "Cash & Bank" balance stood at a massive ₹1,356.94 Cr in Mar 2025. This "dry powder" is the company's biggest asset. It allows E2E to:

1. Pre-pay for NVIDIA hardware (securing priority allocation).  
2. Acquire smaller players (like Jarvis Labs).  
3. Weather any short-term demand fluctuations without distress.

### 4.4 Major Investments & Stock Deals

* **CAPEX:** Significant increase in Fixed Assets and CWIP, driven by the ₹1,407 Cr commitment for expansion.  
* **Bulk Deals:** Notable exits by early investors like Blume Ventures (taking profits) and entry of institutional capital (Airavat Capital, L\&T).13 The shift from VC to Strategic/Institutional ownership improves the stability of the shareholder base.


## 5. Competitive Landscape & Benchmarking

E2E Networks faces competition from three distinct vectors.

### 5.1 vs. Global Hyperscalers (AWS, Azure, GCP)

* **Price:** E2E is \~60-70% cheaper. Hyperscalers have high overheads and cross-subsidize other divisions. E2E runs lean.11  
* **Performance:** Customer testimonials (e.g., Crownit, myCBSEguide) cite better raw performance per dollar on E2E's bare-metal instances compared to virtualized instances on AWS.  
* **Data Sovereignty:** AWS/Azure are subject to US CLOUD Act, allowing US agencies theoretical access to data. E2E is purely under Indian jurisdiction, a non-negotiable for Indian Defense/Govt workloads.

### 5.2 vs. Domestic Telco Clouds (Tata Communications, Jio)

* **Focus:** Tata and Jio are conglomerates where cloud is one of many verticals. For E2E, it is the *only* vertical. This "singular focus" allows for faster integration of new tech (e.g., being first with H200s).  
* **Bundling:** Competitors can bundle internet bandwidth with cloud. E2E counters this with superior "Assistive" support and specialized AI tools (TIR).

### 5.3 vs. Hardware Builders (Netweb Technologies)

* **Business Model:** Netweb sells the "shovels" (servers) for a one-time fee. E2E rents them for recurring revenue.  
* **Economics:** Netweb has lower CAPEX but lower lifetime value per customer. E2E has high CAPEX but high recurring revenue and higher long-term margins (55-60% EBITDA vs. Netweb's \~15-20% manufacturing margins).

### 5.4 Comparison Matrix

| Feature | E2E Networks | Netweb Technologies | AWS / Azure |
| :---- | :---- | :---- | :---- |
| **Primary Revenue** | Recurring (Cloud Rental) | One-time (Hardware Sales) | Recurring (Cloud Rental) |
| **EBITDA Margin** | **\~56-59%** | \~15-18% | \~30-40% |
| **Data Sovereignty** | **High (Indian)** | N/A (Hardware Vendor) | Medium (US Domiciled) |
| **AI Focus** | **Pure-Play AI/GPU** | HPC/Supercomputing | General Purpose Cloud |
| **Pricing** | **Value Leader** | Premium Hardware | Premium Pricing |


## 6. Strategic Developments & Corporate Actions

### 6.1 IndiaAI Mission Wins

Securing ₹265 Cr in contracts (Gnani.ai & GAN AI) under the IndiaAI Mission is a massive validation.

* **Implication:** E2E is now effectively a "quasi-sovereign" entity, trusted by the state to handle national AI infrastructure. This opens doors to further government contracts (Digital India, defense simulations).  
* **Execution:** Phased deployment began in Dec 2025\. This ensures revenue visibility for FY27.

### 6.2 Management Guidance & Targets

* **MRR Target:** Management is targeting an MRR of ₹35-40 Cr by March 2026\. As of Dec 2025, they were at ₹28 Cr.
* **Confidence:** Management stated they are "70-80% there," implying high confidence in meeting the target.  
* **Blackwell Timeline:** Live deployment expected before end of Q4 FY26, with revenue realization starting Q1 FY27.


## 7. Risks & Governance

### 7.1 Governance Analysis

* **Risk Committee:** Chaired by Srishti Baweja, overseeing vendor and tech risks.
* **Board Composition:** The entry of L\&T nominees will professionalize the board, adding layers of oversight typical of large-cap companies. This reduces the "key man risk" associated with founder-led small caps.

### 7.2 Critical Risks

1. **Vendor Concentration:** E2E is effectively a reseller of NVIDIA compute. If NVIDIA decides to become a cloud provider directly (competing with its customers) or throttles supply to India, E2E suffers. *Mitigation:* The L\&T partnership adds geopolitical weight to procurement negotiations.  
2. **Tech Obsolescence:** If E2E buys B200s and NVIDIA releases a "C200" in 12 months that is 10x faster, the B200 inventory depreciates instantly. *Mitigation:* E2E cascades older GPUs to lower-tier tasks (inference/education), extending their economic life.
3. **Pricing Pressure:** As GPU supply eases globally (post-2027), hourly rates for compute may crash. E2E must move up the value chain (TIR platform software revenue) to protect margins.


## 8. Valuation & Price Targets

**Current Metrics:**

* P/E Ratio: High/Negative (distorted by depreciation).  
* EV/EBITDA: The most relevant metric for infrastructure companies.  
  * Current Annualized EBITDA (based on Q3): ₹40 Cr \* 4 \= ₹160 Cr.  
  * FY27 Projected EBITDA (assuming ₹40 Cr MRR): ₹480 Cr Revenue \* 55% Margin \= \~₹264 Cr.

### Revenue Growth Drivers

* **IndiaAI Mission Execution (₹265 Cr Order Book)**
    * Contribution: Significant revenue recognition starts Q4 FY26/Q1 FY27.
    * Evidence: Management confirmed ₹265 Cr contracts (Gnani.ai & GAN AI) have initiated phased deployment in Dec 2025. Payment cycles shifted to monthly, improving cash flow velocity.

* **The "L&T Channel" Activation**
    * Contribution: High-ticket enterprise deals (longer contracts, lower churn).
    * Evidence: First conversion visible with ₹8.49 Cr order in Jan 2026. L&T's 21% stake aligns E2E as the preferred cloud partner for L&T’s vast client base (Defence, EPC, PSU).

* **Blackwell (B200) Pricing Power**
    * Contribution: 1,024 B200 GPUs going live Q4 FY26. B200s command 2x-3x pricing per hour vs H100s ($3-$4/hr globally).
    * Evidence: Deployment of 1,024 units confirmed at Chennai DC. Management targets 80-90% utilization in FY27.

* **Monthly Revenue Run-rate (MRR) Expansion**
    * Contribution: Recurring SaaS-like revenue model.
    * Evidence: Management guidance targets ₹35-40 Cr MRR by March 2026 (Annualized Run Rate of ~₹480 Cr entering FY27).

| Metric | FY25 (A) | FY26 (E) | FY27 (E) | FY28 (E) | FY29 (E) |
| :---- | ----: | ----: | ----: | ----: | ----: |
| Total Revenue (INR Cr) | 164 | 260 | 600 | 900 | 1,300 |
| YoY Growth | 74% | 58% | 130% | 50% | 44% |

### Margin Growth Drivers

* **Operating Leverage (The "J-Curve")**
    * Driver: Fixed costs (Data Center floor space, cooling) remain relatively stable while revenue per rack explodes with B200 density.
    * Evidence: Q3 FY26 EBITDA margin held at 56.6% despite massive expansion, proving the business model scales efficiently.

* **TIR Platform (Software Margin)**
    * Driver: Shifting from raw "Infrastructure as a Service" (IaaS) to "Platform as a Service" (PaaS) via TIR (training/inference platform).
    * Evidence: Software revenue has near-zero marginal cost compared to hardware rental. Management focus on "sovereign AI software" layer.

* **L&T Cost Synergies**
    * Driver: Lower CAPEX for Data Center shell; E2E pays for compute, L&T handles real estate/power efficiencies.
    * Evidence: Strategic partnership explicitly mentions utilizing L&T's data center infrastructure, reducing E2E’s real-estate CAPEX burden.

| Metric | FY25 (A) | FY26 (E) | FY27 (E) | FY28 (E) | FY29 (E) |
| :---- | ----: | ----: | ----: | ----: | ----: |
| EBITDA Margin | 59% | 50% | 50% | 55% | 60% |


### Profits & EPS Projections

| Metric | FY25 (A) | FY26 (E) | FY27 (E) | FY28 (E) | FY29 (E) |
| :---- | ----: | ----: | ----: | ----: | ----: |
| Revenue | 164 | 260 | 600 | 900 | 1,300 |
| EBITDA | 97 | 130 | 300 | 495 | 780 |
| PAT | 47 | 10 | 100 | 160 | 380 |
| EPS | 24 | 5 | 50 | 80 | 190 |

#### Stock Price Scenarios (3-4 Yr Outlook)

| Scenario | P/E | Target Price (INR) | Upside from CMP | Logic |
| :---- | :---- | :---- | :---- | :---- |
| Bearish | 40x | 7,600 | ~190% | Competition from Hyperscalers increases; utilization drops to <70%. |
| Base | 60x | 11,400 | ~340% | Successfully deploys B200s; L&T channel stabilizes; maintains 55% EBITDA. |
| Bullish | 80x | 15,200 | ~480% | Becomes de-facto Sovereign Cloud for Govt/Defense; TIR software revenue expands margins >60%. |


## 9. Conclusion

E2E Networks is a "picks and shovels" play on the Indian AI gold rush. It has successfully graduated from the fragile startup phase to a robust, strategically backed infrastructure player.

The combination of **L\&T's balance sheet**, **IndiaAI's sovereign mandate**, and **NVIDIA's Blackwell performance** creates a powerful moat. While short-term earnings will look volatile due to accounting depreciation, the cash-generating engine is accelerating.

For investors willing to look past optical P/E ratios and focus on EV/EBITDA and growth velocity, E2E Networks presents one of the most compelling compounding opportunities in the Indian market today.

---

#### **Works cited**

1. E2E Networks Ltd share price \- Screener, accessed February 3, 2026, [https://www.screener.in/company/E2E/](https://www.screener.in/company/E2E/)  
2. Company's Annual Reports, Quarterly Earnings Releases, and Investor Presentations
3. L\&T's Staggering ₹1,400 Cr Investment Hit: E2E Networks Stake Value CRASHES – What Investors MUST Know\! | Whalesbook, accessed February 3, 2026, [https://www.whalesbook.com/news/English/tech/LandTs-Staggering-indian-rupee1400-Cr-Investment-Hit-E2E-Networks-Stake-Value-CRASHES-What-Investors-MUST-Know/6930f41c65a9badb9b771881](https://www.whalesbook.com/news/English/tech/LandTs-Staggering-indian-rupee1400-Cr-Investment-Hit-E2E-Networks-Stake-Value-CRASHES-What-Investors-MUST-Know/6930f41c65a9badb9b771881)  
4. L\&T Acquires 15% Stake in E2E Networks via Preferential Allotment \- Angel One, accessed February 3, 2026, [https://www.angelone.in/news/share-market/l-and-t-acquires-fifteen-percent-stake-in-e-two-e-networks-via-preferential-allotment](https://www.angelone.in/news/share-market/l-and-t-acquires-fifteen-percent-stake-in-e-two-e-networks-via-preferential-allotment)  
5. IndiaAI Mission: Democratizing Access to AI Compute \- IBEF, accessed February 3, 2026, [https://www.ibef.org/blogs/indiaai-mission-democratizing-access-to-ai-compute](https://www.ibef.org/blogs/indiaai-mission-democratizing-access-to-ai-compute)  
6. Union Budget 2026 bets big on AI as IndiaAI Mission gets Rs 1,000 crore push, accessed February 3, 2026, [https://www.businesstoday.in/union-budget/news/story/union-budget-2026-bets-big-on-ai-as-indiaai-mission-gets-rs-1000-crore-push-514018-2026-02-01](https://www.businesstoday.in/union-budget/news/story/union-budget-2026-bets-big-on-ai-as-indiaai-mission-gets-rs-1000-crore-push-514018-2026-02-01)  
7. Budget 2026 Explainer: Tax Clarity and Incentives for Cloud, Data Centers & AI Players, accessed February 3, 2026, [https://www.india-briefing.com/news/india-union-budget-2026-cloud-data-centers-tax-incentives-42311.html/](https://www.india-briefing.com/news/india-union-budget-2026-cloud-data-centers-tax-incentives-42311.html/)  
8. E2E Networks, Anant Raj surge up to 10% on tax holiday for cloud services, accessed February 3, 2026, [https://www.business-standard.com/markets/news/data-centre-stocks-e2e-networks-anant-raj-netweb-surge-up-to-10-on-tax-holiday-for-cloud-services-126020200234\_1.html](https://www.business-standard.com/markets/news/data-centre-stocks-e2e-networks-anant-raj-netweb-surge-up-to-10-on-tax-holiday-for-cloud-services-126020200234_1.html)  
9. India sets the stage to become a Global Cloud and AI Hub with its Tax holiday policy till 2047 – Budget 2026, accessed February 3, 2026, [https://indiatechnologynews.in/india-sets-the-stage-to-become-a-global-cloud-and-ai-hub-with-its-tax-holiday-policy-till-2047-budget-2026/](https://indiatechnologynews.in/india-sets-the-stage-to-become-a-global-cloud-and-ai-hub-with-its-tax-holiday-policy-till-2047-budget-2026/)  
10. Budget bets big on data centres, offers tax holiday till 2047 to foreign cloud firms, accessed February 3, 2026, [https://www.onmanorama.com/news/business/2026/02/01/india-ai-hub-tax-holiday-cloud-services-data-centers-india-budget.html](https://www.onmanorama.com/news/business/2026/02/01/india-ai-hub-tax-holiday-cloud-services-data-centers-india-budget.html)  
11. Top 10 E2E Cloud Alternatives & Competitors in 2026 \- G2, accessed February 3, 2026, [https://www.g2.com/products/e2e-cloud/competitors/alternatives](https://www.g2.com/products/e2e-cloud/competitors/alternatives)  
12. Transcript \- E2E Networks Limited, accessed February 3, 2026, [https://e2e-mainsite-ui.objectstore.e2enetworks.net/Investor\_Resources/Investor\_Presentations/Transcript\_for\_Earnings\_Meet\_Con\_Call\_held\_on\_11\_11\_2025.pdf](https://e2e-mainsite-ui.objectstore.e2enetworks.net/Investor_Resources/Investor_Presentations/Transcript_for_Earnings_Meet_Con_Call_held_on_11_11_2025.pdf)  
13. E2E Networks Share Price Today \- Stocks \- ICICI Direct, accessed February 3, 2026, [https://www.icicidirect.com/stocks/e2e-networks-ltd-share-price](https://www.icicidirect.com/stocks/e2e-networks-ltd-share-price)  
14. Bulk and Block deals for E2E Networks on NSE and BSE \- Trendlyne.com, accessed February 3, 2026, [https://trendlyne.com/equity/bulk-block-deals/E2E/97147/e2e-networks-ltd/](https://trendlyne.com/equity/bulk-block-deals/E2E/97147/e2e-networks-ltd/)