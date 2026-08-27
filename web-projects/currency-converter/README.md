# Currency Converter

A live currency converter with a full calculator built in. One HTML file, no
dependencies, no build step. Open `index.html` in any browser.

## What it does

- Converts between 161 world currencies, every ISO 4217 code from AED to ZWG
- Live mid-market rates, refreshed every 20 seconds for the pair on screen and
  every 5 minutes for the full table
- 24 hour movement indicator and a 30 day trace for the current pair
- Falls back to a 5 minute table, then to stored reference rates, if a feed is
  unreachable. The status pill always says which one is in use
- Scientific calculator: trigonometry, logarithms, factorials, combinatorics,
  DEG and RAD, memory and a reusable tape
- Equation solver: exact worked steps for linear and quadratic equations,
  including complex roots, and numeric solving with a graph for anything else
- Money tools: loan repayments, compound growth, savings goals, debt payoff,
  return on investment, inflation, bill splitting and percentages
- Monochrome design with a day and night setting

## Rate sources

All free and unauthenticated, called directly from the browser:

1. fxapi.app for the full currency table
2. currencyexchangetool.com for a live quote and history on the current pair
3. open.er-api.com and jsDelivr as fallbacks

Rate limits apply per visitor IP, not per site, so traffic costs nothing.

## Notes

Rates are mid-market, so a bank will always quote worse. FX markets close over
the weekend, so the last quote holds until they reopen.
