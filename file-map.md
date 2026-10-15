# Which file holds what

| Pack | File | One row is | Region, product or week? |
|---|---|---|---|
| thilisupply | `weekly_sales_all.csv` | A product in a week (Monday start) | National. Product and week. **No region** |
| thilisupply | `shipments.csv` | A shipment | Origin DC and destination region. No product |
| thilisupply | `events_calendar.csv` | A festival or offer | Dates |
| thilifinance | `invoices_payments.csv` | An invoice | Distributor, invoice, due and payment dates. No product |
| thilifinance | `distributors.csv` | A distributor | Region and channel |
| thilifinance | `budget_vs_actual_weekly.csv` | A product in a week | Budget and actual units and prices |
| thilimarketing | `reviews.csv` | A customer review | Region and date. Product appears in the text |
| thilimarketing | `outlet_sales_weekly.csv` | An outlet in a week | Outlet and region |
| thilipeople | `employees.csv` | An employee | Location (not region), hire and exit dates |
| thilipeople | `overtime_monthly.csv` | An employee in a month | Monthly only |

Kochi DC ships to Malabar, Central Kerala and South Kerala. Coimbatore DC ships to Coimbatore-Palakkad, Bengaluru and
Chennai.
