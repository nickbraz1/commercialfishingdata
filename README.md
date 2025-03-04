# Commercial Fishing Incident Database (CFID) Analysis

This repository contains data obtained by the [Data Liberation Project](https://www.data-liberation-project.org/), via a [Freedom of Information Act request](https://www.data-liberation-project.org/) to the Centers for Disease Control and Prevention (CDC) — NIOSH’s parent agency — and pre-processed by the Data Liberation Project.

## FOIA Records

The  provided by the CDC and NIOSH via the Data Liberation Project contain information on **fatalities and vessel disasters** in the U.S. commercial fishing industry. These records enable analysis of industry hazards and help answer questions like:
- Where are the most hazardous fisheries?
- What are the most common causes of fatalities?
- What prevention efforts would be most effective?

## Code

This repository contains data and analysis files related to the CFID dataset:

- [`comfish-analysis.malloy`](comfish-analysis.malloy), sources all the data tables for the analysis portion of this repository.
- [`comfish-analysis.malloynb`](comfish-analysis.malloynb), performs the data analysis using Malloy.
- [`analysis.py`](analysis.py), contains Python code for additional statistical analysis and visualization.

## Summary of Findings

The key insights from the analysis include:
- **Most hazardous fisheries** are concentrated in specific geographic regions.
- **Drowning and vessel instability** are the most common causes of fatalities.
- The majority of vessel disasters involve **wood and fiberglass hull materials**.
- Seasonal variations significantly impact incident rates.

## Licensing

The files provided directly via FOIA (see listing above) are, as government documents, now in the public domain. All other data files have been generated for academic research and are available under Creative Commons’ [CC BY-SA 4.0 license terms](https://creativecommons.org/licenses/by-sa/4.0/). This repository’s code is available under the [MIT License terms](https://opensource.org/license/mit/).  

## Future Work

- Enhance geographic analysis with **GIS mapping**.
- Investigate **correlations between weather conditions and incidents**.
- Develop **interactive dashboards** for better data visualization.

## Acknowledgments

Special thanks to **NIOSH, CDC, and the Data Liberation Project** for making this dataset available for public research.

---

For any questions or collaborations, feel free to contact **[your.email@example.com]** or submit a pull request!
