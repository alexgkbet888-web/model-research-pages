# Model Research Console — GitHub Pages

Free, client-side backtesting console. All computation runs in browser Web Workers; verified Binance spot 5-minute archives and public REST are the only market sources. Reports and caches are stored in each browser IndexedDB, not uploaded to GitHub. Keep the page open while running and export reports for backup.

Nine original models, shared capital, fixed first order, average-cost add-on logic, trailing take profit, insufficient-funds freezes and open-position valuation use the existing engine. Intrabar order remains a simulation assumption, not real executed trades.

This repository contains only publishable static assets, no account credentials, private reports or server configuration. See about.html for limitations and build.json for engine source hashes.

