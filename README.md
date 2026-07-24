# Vendor Performance Analysis Project

# Deutsch

**Überblick**

Ein effektives Bestands- und Verkaufsmanagement ist entscheidend für die Optimierung der Rentabilität im Einzel- und Großhandel. Diese Analyse konzentriert sich auf die Identifizierung leistungsschwacher Marken, die Bewertung der Lieferantenleistung sowie die Optimierung von Preis- und Lagerstrategien zur Steigerung von Effizienz und Rentabilität.

**Die Hauptziele dieser Analyse sind:**
- Identifizierung leistungsschwacher Marken, die Anpassungen bei Werbeaktionen oder Preisen erfordern.
- Ermittlung der wichtigsten Lieferanten, die maßgeblich zu Umsatz und Bruttogewinn beitragen.
- Analyse der Auswirkungen von Großeinkäufen auf die Stückkosten.
- Bewertung des Lagerumschlags zur Senkung der Lagerhaltungskosten und zur Verbesserung der operativen Effizienz.
- Untersuchung der Rentabilitätsunterschiede zwischen leistungsstarken und leistungsschwachen Lieferanten.

**Erkenntnisse aus der Datenexploration**

**Zusammenfassende Statistiken**

- Bruttogewinn: Ein Mindestwert von -52.002,78 deutet auf potenzielle Verluste durch hohe Kosten oder starke Preisnachlässe hin. 
- Gewinnspanne: Ein Minimum von -∞ weist auf Fälle hin, in denen der Umsatz null oder niedriger als die Kosten ist. 
- Absatzmenge & Umsatzwert: Einige Produkte weisen keine Verkäufe auf, was auf Ladenhüter oder veraltete Lagerbestände hindeutet.

**Ausreißer & Schwankungen**
- Einkaufs- & Ist-Preise: Die Höchstwerte liegen deutlich über dem Durchschnitt, was auf Premiumprodukte hinweist. 
- Frachtkosten: Die Spanne reicht von 0,09 bis 257.032,07, was auf logistische Ineffizienzen hindeutet. 
- Lagerumschlag: Werte zwischen 0 und 274,5 zeigen Unterschiede in der Verkaufsgeschwindigkeit der Produkte.

**Datenfilterung**

- Um die Zuverlässigkeit der Analyse zu gewährleisten, wurden Datenpunkte mit folgenden Kriterien ausgeschlossen:
- Bruttogewinn ≤ 0
- Gewinnspanne ≤ 0
- Gesamtabsatzmenge = 0

**Erkenntnisse zur Korrelation**
- Der Einkaufspreis weist eine schwache Korrelation mit dem Umsatzwert und dem Bruttogewinn auf. 
- Die Gesamteinkaufsmenge korreliert stark mit der Gesamtabsatzmenge (0,999), was einen effektiven Lagerumschlag bestätigt. 
- Die Gewinnspanne weist eine leichte negative Korrelation mit dem Gesamtverkaufspreis auf (-0,179). 
- Der Lagerumschlag zeigt eine schwache negative Korrelation mit Bruttogewinn und Gewinnspanne.

**Wichtigste Ergebnisse**

1. Marken für Anpassungen bei Werbeaktionen oder Preisen:
  - 198 Marken mit geringem Absatz, aber hoher Gewinnspanne könnten von gezielten Werbeaktionen oder Preisanpassungen profitieren. 2. Führende Lieferanten nach Umsatz- und Einkaufsanteil:
  - Die 10 wichtigsten Lieferanten machen 65,69 % des Gesamteinkaufsvolumens aus, was die Abhängigkeit von wenigen Lieferanten verdeutlicht.
3. Auswirkungen von Großeinkäufen:
  - Lieferanten, die große Mengen abnehmen, erzielen um 72 % niedrigere Stückkosten, was kosteneffiziente Preisstrategien begünstigt.
4. Lieferanten mit geringer Lagerumschlagshäufigkeit:
  - Der Wert des unverkauften Lagerbestands beläuft sich auf insgesamt 2,71 Mio. USD; dies deutet auf Ladenhüter und hohe Lagerhaltungskosten hin.
5. Vergleich der Gewinnspannen:
  - Lieferanten mit hohem Volumen weisen niedrigere Margen (~31 %) auf als leistungsschwächere Lieferanten (~41); dies deutet auf Ineffizienzen bei der Preisgestaltung oder der Marktreichweite hin.
6. Statistische Validierung:
  - Hypothesentests bestätigen einen signifikanten Unterschied bei den Gewinnspannen zwischen leistungsstarken und leistungsschwachen Lieferanten.

**Konkrete Handlungsempfehlungen**
- Optimierung der Preisgestaltung: Überprüfung der Preise für Marken mit geringem Absatz, aber hoher Marge, um das Volumen zu steigern, ohne die Rentabilität zu gefährden.
- Diversifizierung der Lieferantenbasis: Verringerung der Abhängigkeit von wenigen Lieferanten zur Minderung von Risiken in der Lieferkette.
- Nutzung von Großeinkaufsvorteilen: Beibehaltung wettbewerbsfähiger Preise bei gleichzeitiger Optimierung der Lagerkosten.
- Management von Ladenhütern: Anpassung der Einkaufsmengen, Durchführung von Abverkaufsaktionen oder Überarbeitung der Lagerstrategien.
- Verbesserung von Marketing und Vertrieb: Steigerung der Sichtbarkeit und des Absatzes für leistungsschwache Lieferanten.

**Fazit**

Durch die Umsetzung dieser Empfehlungen können Einzel- und Großhandelsunternehmen eine nachhaltige Rentabilität erzielen, betriebliche Risiken minimieren sowie die Effizienz im Lager- und Lieferantenmanagement steigern.

# English

**Overview**

Effective inventory and sales management are crucial for optimizing profitability in the retail and wholesale industry. This analysis focuses on identifying underperforming brands, evaluating vendor performance, and optimizing pricing and inventory strategies to improve efficiency and profitability.

**The main objectives of this analysis are:**
Identify underperforming brands requiring promotional or pricing adjustments.
Determine top vendors contributing to sales and gross profit.
Analyze the impact of bulk purchasing on unit costs.
Assess inventory turnover to reduce holding costs and improve operational efficiency.
Investigate profitability variance between high-performing and low-performing vendors.

**Data Exploration Insights**

**Summary Statistics**

  - Gross Profit: Minimum value of -52,002.78 indicates potential losses due to high costs or heavy discounts.
  - Profit Margin: Minimum of -∞, showing cases where revenue is zero or lower than costs.
  - Sales Quantity & Sales Dollars: Some products show zero sales, suggesting slow-moving or obsolete inventory.

**Outliers & Variations**
  - Purchase & Actual Prices: Maximum values are significantly higher than the mean, indicating premium products.
  - Freight Costs: Range from 0.09 to 257,032.07, highlighting logistical inefficiencies.
  - Stock Turnover: Ranges from 0 to 274.5, indicating variability in product sales velocity.

**Data Filtering**

- To ensure analysis reliability, data points were filtered to exclude:
- Gross Profit ≤ 0
- Profit Margin ≤ 0
- Total Sales Quantity = 0

**Correlation Insights**
  - Purchase price has a weak correlation with sales dollars and gross profit.
  - Total purchase quantity correlates strongly with total sales quantity (0.999), confirming effective inventory turnover.
  - Profit margin has a slight negative correlation with total sales price (-0.179).
  - Stock turnover shows weak negative correlation with gross profit and profit margin.

**Key Findings**

1. Brands for Promotional or Pricing Adjustments:
    - 198 brands with low sales but high profit margins could benefit from targeted promotions or price adjustments.
2. Top Vendors by Sales & Purchase Contribution:
    - Top 10 vendors contribute 65.69% of total purchases, highlighting dependency on a few suppliers.
3. Impact of Bulk Purchasing:
    - Vendors buying in bulk achieve 72% lower unit costs, supporting cost-effective pricing strategies.
4. Vendors with Low Inventory Turnover:
    - Unsold inventory capital totals $2.71M, indicating slow-moving stock and high holding costs.
5. Profit Margin Comparison:
    - High-volume vendors have lower margins (~31%) compared to low-performing vendors (~41%), suggesting pricing or market reach inefficiencies.
6. Statistical Validation:
    - Hypothesis testing confirms a significant difference in profit margins between top-performing and low-performing vendors.

**Actionable Recommendations**
- Pricing Optimization: Re-evaluate pricing for low-sales, high-margin brands to increase volume without sacrificing profitability.
- Vendor Diversification: Reduce reliance on a few vendors to mitigate supply chain risks.
- Leverage Bulk Purchasing: Maintain competitive pricing while optimizing inventory costs.
- Manage Slow-Moving Inventory: Adjust purchase quantities, launch clearance sales, or revise storage strategies.
- Enhance Marketing & Distribution: Improve visibility and sales for low-performing vendors.

**Conclusion**

By implementing these recommendations, retail and wholesale businesses can achieve sustainable profitability, reduce operational risks, and improve inventory and vendor management efficiency.
