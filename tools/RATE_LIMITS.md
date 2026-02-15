# API Rate Limits & Budget

## Rate Limits
- **5 seconds minimum** between API calls
- **10 seconds minimum** between web searches
- **Max 5 searches per batch**, then 2-minute break
- **Batch similar work** (1 request for 10 leads, not 10 separate requests)
- **If 429 error:** STOP → wait 5 minutes → retry

## Budget
- **Daily:** $5 (warning at $3.75 / 75%)
- **Monthly:** $100 (warning at $75 / 75%)

## Guidelines
- Respect rate limits strictly
- Batch requests to minimize calls
- Monitor spending carefully
- Warn on budget thresholds
