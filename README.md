# The City Is Flatter: Changing Patterns Of Job And Labor Access

## Contribution

This paper measures how automobile accessibility changed across Minneapolis–Saint Paul from 1995 to 2005 using travel times grounded in observed network performance. It finds broad accessibility gains and spatial convergence, with faster-growing suburbs gaining most, and decomposes those changes into land-use and transportation-network contributions.

Levinson, D., Marion, B., Owen, A., & Cui, M. (2017). The city is flatter: Changing patterns of job and labor access. Cities, 60(B), 124-138. https://doi.org/10.1016/j.cities.2016.08.002

## Package Status

This is a **ready public package** containing the paper, derived data workbooks, GIS shapefile layers, and metadata.

## Contents

- `paper/`: paper PDF.
- `data/derived/`: final revision accessibility workbooks.
- `data/gis/cif-shapes/`: GIS shapefile components for the paper outputs.
- `metadata/DATA_FILE_MANIFEST.csv`: data inventory.
- `metadata/GIS_DBF_FIELDS.csv`: DBF field names/types from staged GIS layers.
- `metadata/SOURCE_FILE_DECISIONS.csv`: source copy/exclusion decisions.

## Code

No final matrix-construction or decomposition script bundle was found in the checked folder. The package therefore preserves the derived workbooks/GIS outputs rather than claiming a standalone reproduction script.

Checked: 2026-05-17 22:10:53

## Rights And License

See `LICENSE` for the operative repository license and provenance boundary.
CC BY 4.0 applies only to author-created repository documentation, package
metadata, source-decision notes, data dictionaries, manifests, and
rights-cleared derived package metadata. It also covers author-created
derived accessibility tables, person-weighted accessibility summaries,
standard-deviational-ellipse change metrics, and map-ready
accessibility/decomposition outputs in the staged workbooks and GIS
attributes only to the extent they consist of author-created selection,
cleaning, integration, calculations, or analysis controlled by the paper
authors or repository maintainers.

The publication PDF, US Census, LEHD, CTPP, MnDOT, Metropolitan Council,
loop-detector, traffic-count, TAZ, highway, public-agency, source GIS, source
geometry, vendor/runtime/file-format structures, and other third-party
materials retain their original terms. The Metropolitan Council GIS
disclaimer in `data/gis/cif-shapes/notice.rtf` must remain with transmitted
GIS data or derivative portions when applicable.

<!-- package-hardening-status:start -->
## Package Hardening Status

Generated: 2026-07-02 11:48:13 AEST

- Pipeline: `UPLOADED`
- Sidecars added/updated: `LICENSE`, `PACKAGE_STATUS.md`, `PACKAGE_MANIFEST.csv`, `LICENSE_STATUS.md`.
- Paper reference copies are for local audit convenience and retain their publication terms.
- Final GitHub upload should use the manifest include statuses and the operative license boundary.
<!-- package-hardening-status:end -->
