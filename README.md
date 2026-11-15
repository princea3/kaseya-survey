# Kaseya VSA Survey: Evidence Repository

Evidence for the survey paper *Kaseya VSA Ransomware Attack: A Review of Problems and Targeted Defences*
(IILM University, Gurugram, School of Computer Science and Engineering, Foundation of Cyber Security, CSE 25305, Group 1).

## Files

| File | What it holds |
|---|---|
| `literature_matrix.csv` | One row per reviewed work (34): citation, year, category, type, URL, evidence grade (A to D), how it was found, who read it, and reading notes |
| `search_log.csv` | The 15 search strings, the date of each search (13 Nov 2026) and the number of hits |
| `search_results.csv` | All 248 results listed by the searches |
| `references.bib` | BibTeX export of the 34 references in the paper |

## How the review was done

- 15 web searches on 13 Nov 2026 listed 248 results. After removing 19 repeats, 229 unique pages remained.
- 45 pages were chosen for full reading. Of these, 12 could not be opened and 3 were excluded after reading, which left 30 works.
- 4 more works were added by hand after the team compared drafts: refs 31 to 34 (marked "Added by hand" in the matrix).
- IEEE Xplore, ACM Digital Library and Google Scholar were not searched directly. This is a stated limit of the review.

## Evidence grades

- A: primary record or official advisory
- B: technical write-up by the party that investigated
- C: peer-reviewed work, standards and institutional reports
- D: news and industry reports

A grade names the type of evidence, not whether it is true.

## Use of AI tools

An AI assistant (Claude, by Anthropic) was used to run the web searches, open and summarise sources, draw the figures and draft the paper. Every member must re-read their assigned sources and record this in the matrix column "Read by (member name)" before submission.
