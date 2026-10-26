# Hotword Radar (prototype)

A daily "new-word radar" for indie web-tool builders. It watches public launch/dev/news sources, clusters the same concept across sources, checks whether an exact-match domain is still available via RDAP, and validates demand with Google Trends.

## Why
New-word sites win on speed: find a term before search volume peaks, register the domain, ship a small tool in 48 hours. The hard part is separating signal from noise.

## How it works
- Discovery: Hacker News, GitHub, Product Hunt, Hugging Face, Google News, Lobsters, DEV, Google Suggest.
- Entity resolution: normalize modifiers, cluster by head noun, require ≥2 independent source families for a high-confidence daily pick.
- Validation: Google Trends time series (moving averages / stage), RDAP domain availability, buildability score.

## Status
Local prototype, not a public service yet. Data is aggregated; raw source content is not redistributed.

## Contact
## Contact
tracyyan30@gmail.com
