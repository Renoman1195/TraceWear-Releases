# TraceWear Cloud Seed API

This folder contains the first public static JSON endpoints for TraceWear cloud data.

- `vehicles/catalog.json`: discoverable vehicle catalog.
- `component-libraries/*.json`: full reference component libraries.
- `parts/fmtv/staging.json`: reviewed-staging workflow input for parts sync.
- `cost-models/default.json`: reference maintenance cost model.
- `diagnostics/j1939-map.json`: J1939 diagnostic-to-component mapping.

These files are public seed data. Source-backed operational data should move
through review before promotion into active component libraries.

Seeded HMMWV variants currently include the M998 base utility profile, the
M1151A1 up-armored profile, and an M1151A1 up-armored turret configuration.
