# Restore Opportunity Dashboard

Internal performance dashboard for Restore Hyper Wellness's Meta ad accounts.

Live URL: https://mrahmey-dd.github.io/restore-opportunity-dashboard/

## What's here

`index.html` — single-file dashboard showing:
- Opportunity scores (pulled from Meta's Marketing API) for 6 Restore ad accounts
- Meta-recommended actions grouped by remediation type
- Path-to-100 score breakdowns per account
- Budget allocation (Lead vs Schedule optimization)
- CPL and Cost-per-Appointment metrics
- Per-action projected impact on the relevant metric
- Compound impact waterfalls (per-account and portfolio level)
- Toggles to exclude CAPI and HQ Brand Fund from projections

## Data source

All numbers are pulled from Meta's Marketing API via a custom MCP server. The dashboard is a static snapshot — to refresh, re-run the pipeline from the Cowork session that produced it.

## Maintained by

Disruptive Digital · [disruptivedigital.agency](https://disruptivedigital.agency)
