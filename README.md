# In Search Of Lost Trams: Comparing 1925 And 2020 Transit Isochrones In Sydney

Paper ID: `paper-2022-03`

## Bibliographic Information

- Authors: Lahoorpoor, Levinson
- Venue: Findings, March 2022
- DOI: https://doi.org/10.32866/001c.33040
- Citation: Lahoorpoor, Levinson. (2022). In Search Of Lost Trams: Comparing 1925 And 2020 Transit Isochrones In Sydney. Findings. 10.32866/001c.33040

## Archive Status

- Pipeline target: `UPLOADED`
- Upload action: `derived_only_candidate`
- Rights status: `likely_clear_with_provenance`
- Controlled access status: `none`
- Human subjects status: `no`
- Audit timestamp: 2026-05-19 19:41:06

## Contents

- `paper/33040-in-search-of-lost-trams-comparing-1925-and-2020-transit-isochrones-in-sydney.pdf` - published open-access paper PDF, included under CC BY-SA 4.0 as stated in the PDF.
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

The package is uploaded to GitHub at https://github.com/dlevinson/paper-2022-03-in-search-of-lost-trams-comparing-1925-and-2020-transit-isochrones-in-sydney. The 2020 GTFS zip is about 198 MB and is tracked with Git LFS. The published Findings PDF is included because the PDF states that it is distributed under CC BY-SA 4.0.

<!-- package-hardening-status:start -->
## Package Hardening Status

Generated: 2026-05-20 15:32:54 AEST

- Pipeline: `UPLOADED`
- Sidecars added/updated: `PACKAGE_STATUS.md`, `PACKAGE_MANIFEST.csv`, `LICENSE_STATUS.md`.
- The published paper PDF is included because open-access redistribution rights were checked; other paper reference copies remain review-only unless separately cleared.
- GitHub upload completed with LFS for the >100 MiB GTFS zip.
<!-- package-hardening-status:end -->
