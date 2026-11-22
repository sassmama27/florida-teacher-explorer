# Florida Teacher Discipline Explorer — Version 4.1 public prototype

Static GitHub Pages website based on the original Version 4 prototype. Upload the contents of this directory to the repository root and enable Pages from the main branch / root.

## Data
- `discipline_data.json`: original Version 4 dataset, 16,043 rows (unchanged).
- `review_data_v4_1.json`: preliminary incident review data linked by case number, with evidence candidates and processing statuses.
- Three CSV files: original Version 4.1 review exports, preserved for transparency.

**Important:** All 100 supplied incident reviews are marked `Pending`, with no populated verified school or verified incident type. Candidate labels and extracted passages are **not verified findings**. The site displays them separately in case details, without overwriting the original statewide records.

This is an independent prototype, not an official Florida Department of Education website. Refer to source final orders for authoritative records. GitHub Pages is static hosting; no Python server is required.

## PDF source links
Each record includes a View PDF link to its original source final order URL. Links open externally; their availability depends on the source website.

PDF link fix: PDF links use a separate pdf-link class so the details-toggle click handler no longer intercepts them; HTTP links are upgraded to HTTPS.
