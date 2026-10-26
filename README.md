# SMART-SINKS synthetic benchmark assets

This repository publishes versioned public HTTP source fixtures for the SMART-SINKS Agent–MCP research benchmark. Each version contains **125 distinct JSON assets**: 40 catalogue seed assets and 85 scenario publication assets. These are synthetic benchmark inputs, not field observations, calibrated measurements, or scientific estimates.

## Versions

- **Version 3 — aligned measurement-like fixtures:** each asset has six records across three synthetic site labels and two synthetic dates. Each record includes the variables named in its metadata, with explicit units or categories. Public base URL: `https://alqatf.github.io/smart-sinks-benchmark-assets/v3`.
- **Version 2 — original workflow-only fixtures:** each asset has six dimensionless synthetic indices. Its files remain unchanged for reproducibility. Public base URL: `https://alqatf.github.io/smart-sinks-benchmark-assets/v2`.

Each version has a `source_index.json` containing all asset URLs, provider DIDs, and SHA-256 hashes. The corresponding execution suite, scoring oracle, generators, and hash locks remain in the SMART-SINKS research project. Version 3 is a new benchmark condition; results from version 2 or the original benchmark must not be relabeled as version 3 results.

All raw JSON URLs are publicly downloadable. EDC contracts govern transactions performed through EDC but cannot restrict direct downloads from this public repository. The numeric ranges in version 3 are illustrative and deterministic; they are not an ecological simulation or evidence of observed peatland conditions.
