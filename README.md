# FUJAX SOH Report — Invoicing

Interactive Connect Logistics report for reconciling FUJAX transport invoices and credit notes to the 2026 master stock report.

## Current study population

- 65 invoices and 5 credit notes received
- 1,814 supplied load-support rows
- 65,854.66 gross invoiced tonnes and 65,679.18 net tonnes after credits
- R36,083,938.41 gross invoiced ex VAT
- R114,978.26 credit notes ex VAT
- R35,968,960.15 net billed ex VAT
- 63 of 65 invoices reconcile to their supplied load schedules
- 1,780 exact two-ticket-and-weight master matches

## What the report provides

- Gross invoice, credit-note and net totals by order and route
- Credit-note allocation to original invoices, physical ticket pairs and surviving invoices
- Finance action register with expected result, actual result, cause, evidence and required action
- Invoice-level billed tonnage, selected weight basis, rate and totals
- Load-by-load invoice number and linked rate per ton
- Search and filtering by document, invoice, order, ticket and status
- Source-versus-master load detail
- CSV export and browser print/PDF output
- Reconciliation controls and source position

The current report confirms document arithmetic, credit-note allocation and the available load/master linkage. It identifies two invoices whose supplied workbooks do not substantiate the PDF tonnage. Charged rates are displayed but have not yet been compared with an approved tariff schedule.

The live site is deployed automatically from `main` using GitHub Pages.
