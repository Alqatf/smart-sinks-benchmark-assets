# SMART-SINKS synthetic benchmark assets

This repository publishes the version 2 public HTTP source fixtures for the SMART-SINKS Agent–MCP research benchmark. It contains **125 distinct synthetic JSON assets**: 40 catalogue seed assets and 85 scenario publication assets. Each file identifies its asset ID and provider DID and contains six deterministic, dimensionless generated indices.

These files are **synthetic benchmark inputs**. They are not field observations, calibrated measurements, or scientific estimates. They are publicly downloadable. EDC contracts govern transactions performed through EDC but cannot restrict a direct download from these public URLs.

Published files are in [`docs/v2/`](docs/v2/). The URL of each asset is:

`https://alqatf.github.io/smart-sinks-benchmark-assets/v2/<provider-key>/<asset-id>.json`

The corresponding execution suite, scoring oracle, fixture generator, and hash lock remain in the SMART-SINKS research project. The version 2 files are a separate evaluation condition; earlier results from the original benchmark must not be relabeled as version 2 results.
