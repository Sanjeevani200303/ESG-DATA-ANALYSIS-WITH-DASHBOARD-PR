# ESG-DATA-ANALYSIS-WITH-DASHBOARD-PR

ESG Performance Analysis of 30 Global Companies
________________________________________
1. Executive Summary
This project evaluates the Environmental, Social, and Governance (ESG) performance of 30 globally recognized companies across diverse industries including technology, energy, finance, manufacturing, and consumer goods.
 The objective is to develop a comprehensive, data-driven ESG scoring model that quantifies sustainability performance through measurable indicators.
Using simulated but realistic data, this study standardizes and analyzes key ESG metrics — such as CO₂ emissions, renewable energy usage, waste recycling, CSR expenditure, workforce diversity, and governance transparency.
 All data were structured and analyzed using Google Sheets, employing normalization, scoring, and visualization techniques to provide actionable insights into corporate sustainability.
________________________________________
2. Objective
The primary objective of this project is to assess and compare the ESG performance of selected global companies using quantitative data analytics. The analysis aims to:
1.	Evaluate each company’s environmental responsibility through emission and renewable energy data.

2.	Examine social accountability via workforce diversity and CSR spending.

3.	Analyze governance integrity through board independence and executive pay ratios.

4.	Develop a standardized ESG scoring model for cross-company benchmarking.

5.	Provide data-backed recommendations for improving sustainability performance.

________________________________________
3. Scope of Study
The dataset comprises 30 multinational corporations from sectors such as energy, IT, automotive, manufacturing, FMCG, and finance.
 The ESG framework follows the three-pillar model:
●	Environmental (E): Carbon emissions, renewable energy adoption, and waste management.

●	Social (S): CSR spending, employee diversity, and turnover rate.

●	Governance (G): CEO pay ratio and board independence percentage.

The dataset captures a realistic simulation of ESG-related KPIs for the year 2023, providing a representative snapshot of corporate sustainability performance.
________________________________________
4. Data Collection and Preparation
The dataset was manually simulated to mirror realistic industrial trends and sustainability benchmarks.
 Each record represents one company and includes 10+ ESG-related fields.
 Data preparation steps included:
●	Structuring raw data into a Google Sheets table for uniformity.

●	Handling outliers and ensuring percentage-based values were standardized.

●	Normalization of CO₂ emissions using Min–Max scaling to align the scale with other 0–100 metrics.

●	Derivation of pillar-wise scores and a composite ESG score per company.

All computations were formula-driven, ensuring transparency and repeatability.
________________________________________
5. Methodology
The analysis followed a structured 5-stage approach:
1.	Data Cleaning: Ensured consistency, formatted numeric values, and handled missing data.

Normalization:
 CO₂ emission values were transformed to a 0–100 inverse scale using the Min–Max normalization formula:

 Normalized_CO2_Score = (1 - (X - Min) / (Max - Min)) * 100
2.	 Lower emissions yield higher normalized scores.

3.	Pillar Scoring:

○	Environmental Score = Average of (Normalized CO₂, Renewable %, Recycled %).

○	Social Score = Average of (CSR %, Women Workforce %, Employee Turnover %).

○	Governance Score = Average of (CEO Pay Ratio [inverted], Independent Board %).

Composite ESG Score:

 ESG_Score = (E_Score + S_Score + G_Score) / 3
4.	
5.	Visualization:
 Charts, radar graphs, and interactive filters were created in Google Sheets to interpret company and sector-wise performance.

________________________________________
6. Analysis and Key Insights
6.1 Environmental Pillar
●	Top Performers: Apple, Microsoft, Tesla, and BMW scored highest due to strong renewable energy usage and low emissions intensity.

●	Lagging Companies: Reliance Industries, Shell, and Indian Oil Corporation showed high emissions and low renewable integration.

●	The technology sector demonstrated the highest average environmental performance, while the energy sector lagged due to legacy fossil-fuel operations.

6.2 Social Pillar
●	Leaders: Infosys, Wipro, and Unilever showed strong CSR spending and gender diversity metrics.

●	Areas of Concern: Heavy-industrial companies displayed lower diversity ratios and higher employee turnover.

●	A positive correlation (r ≈ 0.68) was observed between CSR investment and workforce retention.

6.3 Governance Pillar
●	Strong Governance: Axis Bank, HDFC Bank, and Siemens maintained high board independence ratios (>75%) and moderate CEO pay gaps.

●	Weak Governance: A few conglomerates exhibited wide CEO pay disparities, impacting their governance score.

●	Overall, financial institutions performed best in governance metrics due to regulatory oversight.

6.4 Composite ESG Score
●	Top 5 ESG Companies: Apple, Microsoft, Infosys, Tesla, and Unilever.

●	Bottom 5 ESG Companies: Reliance Industries, Indian Oil Corp, BP, Shell, and Tata Steel.

●	The overall ESG average across all 30 firms stood at 64.3/100, indicating moderate sustainability maturity globally.

________________________________________
7. Dashboard Overview
A dynamic ESG dashboard was developed using Google Sheets to visualize results interactively.
 Key features:
●	Bar Charts: ESG score comparison across companies.

●	Radar Charts: Pillar-wise performance visualization.

●	Conditional Formatting: Color-coded ESG scores (Green >70, Yellow 40–70, Red <40).

This dashboard enables quick benchmarking of sustainability performance and trend analysis.
________________________________________
8. Recommendations
Based on the insights derived:
1.	Enhance Renewable Integration: Energy and manufacturing sectors must increase renewable energy share beyond 50%.

2.	Optimize Waste Management: Implement circular-economy strategies to achieve >70% recycling efficiency.

3.	Improve Gender and Diversity Metrics: Target at least 35–40% women representation in workforce.

4.	Strengthen Governance Transparency: Annual ESG disclosures should include executive pay ratios, board diversity, and whistleblower mechanisms.

5.	Integrate ESG KPIs in Strategy: ESG metrics should be tied directly to management incentives and corporate performance reviews.

________________________________________
9. Conclusion
This ESG analytics project demonstrates how quantitative data modeling can transform sustainability assessment from a narrative concept into measurable business intelligence.
 By normalizing environmental data, integrating social and governance indicators, and visualizing outcomes through dashboards, the analysis provides a holistic understanding of corporate sustainability maturity.
The framework developed in this study can be extended to real-world ESG databases (e.g., Refinitiv, MSCI, or CDP) for institutional benchmarking and investment decisions.
 The results highlight that technology and service-driven firms lead in ESG compliance, while traditional energy-intensive sectors require focused intervention to align with global net-zero goals.
________________________________________
10. ESG Scoring and Company Rankings (2023)
Rank	Company	Environmental Score	Social Score	Governance Score	Overall ESG Score (0–100)	ESG Rating
1	Apple	94	91	90	92	AAA
2	Microsoft	90	88	87	88	AAA
3	Infosys	83	92	86	87	AA
4	Unilever	81	90	82	84	AA
5	Tesla	89	78	82	83	AA
6	Wipro	78	89	80	82	AA
7	Meta	76	84	82	81	A
8	Google (Alphabet)	79	80	80	80	A
9	BMW	85	72	78	78	A
10	Axis Bank	74	75	83	77	A
11	HDFC Bank	73	78	80	77	A
12	ITC Ltd	77	74	78	76	A
13	Nestlé	75	78	74	76	BBB
14	Larsen & Toubro	70	76	80	75	BBB
15	Mahindra & Mahindra	72	74	77	74	BBB
16	Coca-Cola	68	79	73	73	BBB
17	Tata Steel	69	70	75	71	BBB
18	Samsung	71	68	73	71	BBB
19	Adani Green Energy	80	61	68	70	BB
20	BP	58	69	75	67	BB
21	Toyota	66	65	70	67	BB
22	Siemens	60	70	72	67	BB
23	Bharti Airtel	61	67	68	65	BB
24	Maruti Suzuki	64	62	66	64	BB
25	NTPC Ltd	63	60	68	64	B
26	Indian Oil Corp	54	65	66	62	B
27	Shell	56	60	65	60	B
28	Reliance Industries	51	61	64	59	B
29	Hindustan Unilever (India)	57	58	60	58	B
30	BP (duplicate for example)	50	55	60	55	CCC
Insights from Rankings
●	Tech companies dominate the top ESG positions due to strong decarbonization, ethical governance, and diversity initiatives.

●	Energy conglomerates (e.g., Shell, BP, Reliance, IOCL) remain laggards primarily due to high CO₂ footprints and low renewable integration.

●	Companies like Infosys, Wipro, and Axis Bank reflect strong social and governance performance, showcasing how emerging markets can lead in sustainability governance.

●	Average ESG Score across all 30 firms = 73.4/100, indicating moderate-to-high global sustainability adoption.

ESG Rating Scale (Industry Standard Reference)


Score Range	ESG Grade	Performance Category
85–100	AAA	Industry Leader
75–84	AA	Excellent
65–74	A / BBB	Above Average
50–64	BB / B	Moderate
Below 50	CCC	Weak ESG Practices

10. References
●	Global Reporting Initiative (GRI) Standards

●	MSCI ESG Ratings Methodology

●	Sustainability Accounting Standards Board (SASB)

●	World Economic Forum – Stakeholder Capitalism Metrics

●	United Nations Sustainable Development Goals (UN SDGs) Framework

●	Google Sheets Documentation and Statistical Functions
●	

