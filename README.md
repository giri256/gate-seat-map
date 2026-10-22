# GATE Seat Map

**Live:** https://giri256.github.io/gate-seat-map/

Enter your B.Tech branch, GATE paper, score and category. It shows every CCMT programme (NITs, IIITs, other CFTIs) your degree is eligible for, with opening and closing GATE scores for every round of 2023–2026, including the special and national spot rounds. Programmes your score cleared come first.

- **Near-degree hints:** if a programme lists a close variant of your degree (e.g. EEE when you have EE) but not yours, it's shown in amber with a note.
- **IIT tab:** each IIT's own published figures (COAP closing scores, shortlisting cutoffs, minimum scores to apply) for 18 IITs, with links to the official PDFs.
- Dark by default, light theme toggle. A static page, no tracking, no backend.

## Data
- CCMT 2026 seat matrix, programme eligibility mapping (qualifying degree × GATE paper × group), and round-wise opening/closing GATE scores 2023–2026 from ccmt.admissions.nic.in.
- IIT figures from each IIT's admissions pages. They differ in kind (closing score vs. shortlisting cutoff vs. minimum to apply); every card says which.

Past cutoffs are a guide, not a promise. Always confirm eligibility with the institute.

## Run locally
Open `index.html`, or `python3 -m http.server` in this folder.
