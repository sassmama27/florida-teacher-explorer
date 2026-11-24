# Florida Teacher Discipline Explorer — Version 4.1 Public Prototype

[Open the Florida Teacher Discipline Explorer](https://sassmama27.github.io/florida-teacher-explorer/)

The Florida Teacher Discipline Explorer is an independent, searchable database of Florida educator discipline records. Use it to search by educator name or case number, filter by county, order year, action, violation type, or certificate outcome, and open the linked final order when available. Can contain errors, check source PDF in order to double check. 

## Data

- [`discipline_data.json`](discipline_data.json) contains 16,043 statewide records and includes the latest case updates from review Batches 12, 13, and 18. These batches updated 178 existing records.
- [`review_data_v4_1.json`](review_data_v4_1.json) contains preliminary incident review entries, candidate evidence, and processing statuses linked by case number.
- The original Version 4.1 review exports are available in [`incident_review_v4_1.csv`](incident_review_v4_1.csv), [`evidence_candidates_v4_1.csv`](evidence_candidates_v4_1.csv), and [`processing_status_v4_1.csv`](processing_status_v4_1.csv).

**Important** — Review status can differ between the disposition and the violation. Open **View details** to see the available review statuses and any provisional labels. Entries marked **Pending OCR**, **Needs review**, or **Source unavailable** indicate that the relevant part of the review remains unresolved. Treat candidate labels and extracted passages as preliminary and consult the official final order for the Education Practices Commission’s disposition and the record it adopted.

## PDF source links
Each record includes a View PDF link to its original source final order URL. Links open externally; their availability depends on the source website.

PDF link fix: PDF links use a separate pdf-link class so the details-toggle click handler no longer intercepts them; HTTP links are upgraded to HTTPS.
