<a href="https://titratelab.com/"><img src="https://raw.githubusercontent.com/TitrateLab/.github/main/profile/titratelab-icon.png" alt="TitrateLab" width="96"></a>

# TitrateLab

TitrateLab is an independent intelligence layer for the peptide market. It turns fragmented certificates of analysis, prices, stock observations and vendor identities into attributable, timestamped evidence, so that a researcher can check a claim before acting on it.

TitrateLab is not a vendor, a paid-review site or an influencer brand. It sells nothing but access to evidence.

## What is published here

- [peptide-coa-analysis](https://github.com/TitrateLab/peptide-coa-analysis): statistics from more than 100,000 published peptide lab reports, the largest open multi-lab dataset of public certificate-of-analysis evidence for research peptides that we have found (comparison measured 2026-10-12, in the repository README). Purity, quantity versus label and endotoxin testing by compound, laboratory and month, vendor-blind, released monthly with a manifest, a data dictionary, a datasheet and the method behind every number. Data under CC BY 4.0, code under MIT.

## Explore the October 12 release

The compound aggregates summarize **96,805 included report entries across 68 compounds and blends**. The source snapshot contains 116,363 published entries before the scope filters and small-cell exclusions. See the [dated manifest](https://github.com/TitrateLab/peptide-coa-analysis/blob/v2026-10-12/data/releases/2026-10-12/manifest.json) for the population, definitions and exclusions.

| What you want to do | Open resource |
| --- | --- |
| Search compounds and compare measurement availability | [Interactive coverage explorer](https://huggingface.co/spaces/TitrateLab/coa-coverage-explorer) |
| Download and analyze the aggregate tables | [Kaggle dataset](https://www.kaggle.com/datasets/titratelab/titratelab-peptide-coa-aggregates-2026-10-12) |
| Compare published report counts in a chart | [Tableau visualization](https://public.tableau.com/app/profile/titrate.lab/viz/TitrateLabPublishedCOAReportCounts2026-10-12/Publishedreportcounts) |
| Cite the preserved release | [Zenodo archive and DOI](https://doi.org/10.5281/zenodo.23551719) |

These resources describe collected reports, not market share or product safety. Testing and publication are selective; missing measurements are not failed tests. The [data catalog](https://titratelab.com/data) explains the available evidence and its limits.

## Where the evidence lives

- https://titratelab.com/coa searches every published lab report, with the laboratory, client and batch as printed on the public document.
- https://titratelab.com/labs profiles the laboratories that issue them.
- https://titratelab.com/data is the data catalog, with the four evidence layers kept separate on purpose.
- https://titratelab.com/developer?src=github is where to request access to the Data API for per-record, vendor-identified queries.

## How to read anything from TitrateLab

Every figure states what was measured, when, and what remains unknown. If a number here cannot be traced to a dated source, that is a bug. Open an issue.
