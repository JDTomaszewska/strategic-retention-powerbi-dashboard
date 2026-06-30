Markdown

# StreamFlow: Strategic Retention & Churn Analytics Dashboard

## Business Context & Objective / Cel i kontekst biznesowy
**[EN]** In subscription-based business models (SaaS), customer retention and Monthly Recurring Revenue (MRR) stability are critical growth drivers. This Power BI dashboard delivers actionable insights into subscription health by identifying global churn trends, segmenting revenue risk, and diagnosing underperforming acquisition channels.

**[PL]** W modelach biznesowych opartych o subskrypcję (SaaS), retencja klientów oraz stabilność miesięcznych przychodów powtarzalnych (MRR) to kluczowe czynniki wzrostu. Dashboard w Power BI dostarcza operacyjnych wniosków dotyczących kondycji subskrypcji poprzez identyfikację globalnych trendów odpływu (churn), segmentację ryzyka przychodów oraz diagnozę kanałów pozyskiwania klientów o niskiej efektywności.

---

## Tech Stack & Features / Wykorzystane technologie i funkcje
* **Tool:** Power BI Desktop
* **Data Transformation (ETL):** Power Query (data cleaning, column unpivoting, type enforcement)
* **Data Modeling:** Star Schema (1:N relationships, dedicated Calendar Dimension)
* **Analytical Calculations:** Advanced DAX (Time Intelligence, conditional filtering via CALCULATE)
* **UX/UI Design:** Custom container grid, integrated Call-To-Action navigation buttons

---

## Dashboard Architecture & Views (English Version)

### Page 1: Strategic Retention Overview
The main screen focuses on high-level executive KPIs and immediate diagnostic entry points:
* **Core KPIs:** Top-level metrics tracking Global Churn Rate vs. Target (5%), Net Subscriber Growth, Total MRR, and Monthly MRR change.
* **Executive Summary:** An integrated notification banner presenting the primary business insight directly to stakeholders.

![Strategic Retention Overview](dashboard_page1.png)

* **Interactive Navigation:** Includes an intuitive "Call to Action" navigation element below the segmentation chart. Clicking this element leverages internal report actions to seamlessly transition the user to Page 2 for deep-dive exploratory analysis.

### Page 2: Detailed Trend Analysis (Exploratory View)
* A dedicated drill-down view containing an expanded, high-resolution line chart that analyzes the long-term historical trajectory of the churn rate, allowing managers to isolate seasonal variances and macroeconomic impacts. Includes a date-range timeline slicer for advanced filtering.

![Detailed Churn Trend Analysis](dashboard_page2.png)

---

## Architektura raportu i widoki (Wersja Polska)

### Strona 1: Strategiczny Przegląd Retencji
Główny ekran koncentruje się na kluczowych wskaźnikach efektywności (KPI) dla kadry zarządzającej oraz punktach natychmiastowej diagnozy:
* **Główne Wskaźniki KPI:** Najważniejsze metryki śledzące globalny wskaźnik churnu w odniesieniu do celu (5%), przyrost netto subskrybentów, całkowity MRR oraz miesięczną zmianę wartości MRR.
* **Podsumowanie Menedżerskie:** Zintegrowany baner powiadomień prezentujący najważniejszy wniosek biznesowy bezpośrednio dla interesariuszy.

### Strona 2: Szczegółowa Analiza Trendu (Widok Eksploracyjny)
* Dedykowany widok szczegółowy zawierający rozbudowany wykres liniowy w wysokiej rozdzielczości, analizujący historyczną trajektorię wskaźnika odpływu w długim okresie, wzbogacony o suwak osi czasu dla zaawansowanego filtrowania okresów.

---

##  Key Business Takeaways / Kluczowe Wnioski Biznesowe
* **[EN]** While referral and organic channels exhibit strong retention (71% and 66% respectively), Paid Search and Social Ads underperform significantly. This reveals an optimization opportunity to reallocate marketing spend toward higher-lifetime-value (LTV) channels.
* **[PL]** Podczas gdy kanały poleceń i ruchu organicznego wykazują silną retencję (odpowiednio 71% i 66% ), płatne wyszukiwanie oraz reklamy w mediach społecznościowych osiągają znacznie gorsze wyniki. Wskazuje to na potrzebę optymalizacji i realokacji budżetów marketingowych w stronę kanałów generujących wyższą wartość życiową klienta (LTV).

---
*Project implemented as part of a Business Intelligence portfolio demonstrating production-ready data architecture and human-centric dashboard design.*
