# Opportunity-Results

Published results of the [Opportunity Lab](https://netherlandsopportunitylab.nl) (Erasmus University Rotterdam).
This repository contains **output only**: aggregated, CBS-cleared tables. The code that produces them lives in the analysis repositories (Opportunity-Analysis-Intragenerational, -Gap, -Map, Opportunity-Preprocessing).

## Contents

| Folder               | Analysis                        | Used for                      |
|----------------------|---------------------------------|-------------------------------|
| `intragenerational/` | Intragenerational mobility      |                               |
| `gap/`               | Opportunity gap (kansenkloof)   | kansenkloof.nl, KCO dashboard |
| `map/`               | Opportunity map (kansenkaart)   | kansenkaart.nl                |
| `jgz/`               | Youth health care (JGZ)         |                               |

Inside each folder, results are grouped by region (e.g. `Amsterdam_metropolitan_area/`, `Netherlands/`).

## Releases and versions

Each delivery of results is a **GitHub Release**. The release notes list what was added or changed, and the same information goes in `CHANGELOG.md`.

- Tag format: `<analysis>-<stage>`, e.g. `intragenerational-S_2_1`. Stage codes use the `S_X_Y` notation from the naming conventions, as in the Opportunity Lab results tracker.
- A dataset keeps the same file path across versions. Older versions are available through earlier releases.
- Every release is archived on [Zenodo](https://zenodo.org) and gets a DOI.

To be notified of new results, use **Watch → Custom → Releases**.

## Data and disclosure

All results are based on non-public microdata from Statistics Netherlands (CBS). Only output that has passed CBS output checks is included. Cells with small numbers of observations have been suppressed. Files are provided as `.xlsx` and/or `.csv`.

## Citation and license

Please cite the Zenodo DOI of the release you used: `[DOI badge / citation]`.
License: `[e.g. CC BY 4.0, to be confirmed]`.

## Contact

Opportunity Lab, Erasmus University Rotterdam — `voorkamp@ese.eur.nl`
