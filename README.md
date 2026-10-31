# Elmorshedy Group | Real Estate Sales Dashboard

A Power BI project that brings real estate sales, payment information, and project-level reporting into an interactive dashboard for Elmorshedy Group.

The report combines an executive overview with dedicated pages for **Degla Landmark** and **Zahra North Coast**, helping users explore property values, payments, and sales trends through visual summaries and filters.

![Elmorshedy Group dashboard overview](images/main_page.png)

## Business Objective

Real estate reporting needs to connect high-level performance with the details behind individual developments. This project organizes those views into a single report, supporting questions such as:

- What is the total value of the units represented in the report?
- How do paid and due amounts compare within each development?
- How do sales values vary across contract dates?
- How can users move quickly from an overview to a development-specific analysis?

## Dashboard Pages

| Page | Purpose | Features |
| --- | --- | --- |
| **Overview** | Present a high-level summary and an entry point to the report. | KPI cards, a project selector, advertised-unit totals, and navigation to development pages. |
| **Degla Landmark** | Explore sales and payment information for Degla Landmark. | Unit-value and installment measures, paid and due amounts, time-based charts, bank filters, and date controls. |
| **Zahra North Coast** | Explore sales and payment information for Zahra North Coast. | Project-specific unit values, payment summaries, sales trends, bank filters, and date controls. |

### Degla Landmark

![Degla Landmark sales dashboard](images/degla_page.png)

### Zahra North Coast

![Zahra North Coast sales dashboard](images/zahra_page.png)

## Analytical Focus

- **Sales value:** Summarize unit prices to show the value represented in the selected data.
- **Payments and installments:** Present paid amounts, due amounts, and installment-related measures.
- **Sales trends:** Explore unit values by sales-contract month and year.
- **Project context:** Include advertised total-unit information alongside detailed development reporting.
- **Interactive exploration:** Use project, bank, and date selections to focus the report on relevant records.

Advertised total units provide project context; they should not be interpreted as units sold. Unit prices, paid amounts, and due amounts also represent different business concepts and should be read separately.

## Tools and Skills Demonstrated

| Tool or skill | Application |
| --- | --- |
| **Power BI Desktop** | Building a multi-page, interactive business intelligence report. |
| **DAX measures** | Presenting calculated summaries for unit values and installment-related KPIs. |
| **Excel** | Providing advertised project-unit reference data. |
| **Sales analysis** | Organizing property values, payment information, and contract-date trends. |
| **Data visualization** | Using KPI cards, column charts, line charts, and donut charts to communicate performance. |
| **Dashboard design** | Combining consistent branding, visual hierarchy, page navigation, and filtering controls. |

## Getting Started

1. Download or clone this repository.
2. Open `morshedy_group.pbix` in Microsoft Power BI Desktop.
3. Start with the overview page and use the navigation controls to explore each development.
4. Adjust the available filters to explore sales and payment information.
5. To refresh the report, configure the data-source paths and credentials for source files you have access to. Existing paths may need to be updated for your environment.

The screenshots above provide a preview without requiring Power BI Desktop.

## Reporting Scope

This report supports descriptive analysis and interactive exploration. The screenshots show a saved report state; they do not establish live data freshness or measured business improvements.

## Author

**Dana Elshrbiny** · Data Analyst

[GitHub](https://github.com/danaelshrbiny10) · [LinkedIn](https://www.linkedin.com/in/danaelshrbiny/)
