# IT Service Desk Dashboard

A Power BI dashboard built to give IT support leadership a clear, end-to-end view of help desk performance — from overall ticket volume down to individual technician metrics.

## Overview

This report consolidates IT service desk ticket data into a set of interactive pages so managers can monitor workload trends, service quality, and team performance without digging through raw ticket exports. It is designed for quick daily/weekly check-ins as well as deeper performance reviews.

## Report Pages

- **Executive Overview** — high-level KPIs and trends for leadership at a glance.
- **Ticket Volume & Trends** — ticket intake over time, volume by category/priority, and trend analysis.
- **Technician Performance** — comparative view of how each technician is performing.
- **SLA & Quality Deep Dive** — SLA compliance rates and customer satisfaction (CSAT) analysis.
- **Technician Drillthrough** — per-technician detail view, including Total Tickets, Average Resolution Hours, SLA Compliance %, Average CSAT, and Reopen Rate %.

## Key Metrics Tracked

- Ticket volume and trends over time
- Average resolution time
- SLA compliance percentage
- Customer satisfaction (CSAT) scores
- Ticket reopen rate
- Technician-level performance breakdowns

## Tech Stack

- **Power BI** (report + semantic model)
- File: `IT Service Desk Dashboard.pbix`

## Getting Started

1. Download the `.pbix` file from this repository.
2. Open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Connect it to your own IT service desk data source, or explore the report using the sample data included.

## Data

Data is refreshed periodically; the report displays a "Data updated" timestamp on load. Update the underlying data source and refresh in Power BI Desktop (or publish to the Power BI service) to bring in the latest tickets.

