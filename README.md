# In Search Of Lost Trams: Comparing 1925 And 2020 Transit Isochrones In Sydney

Paper ID: `paper-2022-03`

## Bibliographic Information

- Authors: Lahoorpoor, Levinson
- Venue: Findings, March 2022
- DOI: https://doi.org/10.32866/001c.33040
- Citation: Lahoorpoor, Levinson. (2022). In Search Of Lost Trams: Comparing 1925 And 2020 Transit Isochrones In Sydney. Findings. 10.32866/001c.33040

## Archive Status

- Pipeline target: `READY-TO-UPLOAD/PUBLIC`
- Upload action: `derived_only_candidate`
- Rights status: `likely_clear_with_provenance`
- Controlled access status: `none`
- Human subjects status: `no`
- Audit timestamp: 2026-05-19 19:41:06

## Contents

- `paper/33040-in-search-of-lost-trams-comparing-1925-and-2020-transit-isochrones-in-sydney.pdf` - published paper reference copy.
- `data/scenario_gtfs/` - curated GTFS scenario bundles for S1-S6, with byte-identical duplicates represented by pointer files.
- `data/derived_results/All_PWA.csv` - scenario PWA/access result table used for the paper figure/table checks.
- `metadata/SCENARIO_GTFS_MANIFEST.csv` - scenario file manifest, checksums, GTFS table presence, and row counts.
- `metadata/DATA_DICTIONARY.csv` - data dictionary for `All_PWA.csv`.
- `metadata/PUBLIC_SOURCE_LINKS.csv` - public source and DOI pointers.
- `metadata/SOURCE_FILE_DECISIONS.csv` - inclusion/exclusion decisions.
- `metadata/CHECKSUMS_SHA256.csv` - checksums for package files.
- `metadata/UPLOAD_NOTES.md` - GitHub large-file note.

## Public Shared Source

The baseline historical Sydney GTFS source is already publicly archived and should be cited rather than duplicated wholesale:

- https://hdl.handle.net/2123/34748
- https://doi.org/10.25910/07z3-bn41

## Release Boundary

This package includes the paper-specific scenario GTFS bundles and derived PWA result table now available locally. It does not include generated OTP travel-time matrices, full 2016 Census source tables, or a runnable OTP script bundle. Those are not treated as blockers because the paper describes the method, the GTFS inputs are staged or publicly archived, and the compact derived result table is included.

## Upload Mechanics

The package is public-ready. The 2020 GTFS zip is about 198 MB and is tracked with Git LFS for GitHub upload. Local `paper/*.pdf` reference copies are retained on disk for audit convenience but ignored from the public GitHub tree unless redistribution rights are separately cleared.

<!-- package-hardening-status:start -->
## Package Hardening Status

Generated: 2026-05-20 15:32:54 AEST

- Pipeline: `READY-TO-UPLOAD/PUBLIC`
- Sidecars added/updated: `PACKAGE_STATUS.md`, `PACKAGE_MANIFEST.csv`, `LICENSE_STATUS.md`.
- Paper reference copies are for local audit convenience and are not public-upload assets without rights review.
- Final GitHub upload should use the manifest include statuses and the license-status note.
<!-- package-hardening-status:end -->
