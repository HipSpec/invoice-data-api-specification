# (Proposal) Invoice Data Api Specification


Goal: to provide customers access to basic data about their spend with a vendor in a simple, standardized format.

## Authentication:
Would be authenticated by oAuth2/ API token.

## Primary Endpoints:
* /api/invoices # Index of all historic invoices
* /api/invoices/upcoming.json # Pending/current period invoice
* /api/invoices/:id.json
* /api/invoices/:year/:month.json

## Seat based pricing: 
- Would describe number of seats, plan, sub totals, taxes, etc.
## Usage based pricing: 
- Would describe usage, rate, etc.
