# LightningRiskMX

<p align="center">
  <img src="assets/logo.png" alt="LightningRiskMX logo" width="280">
</p>

**Mapping lightning-related fatality risk in Mexico**  
*Natural hazard, social vulnerability, and municipal-level risk*

[**Read the peer-reviewed article**](https://doi.org/10.1175/WCAS-D-23-0151.1)

## About this repository

**LightningRiskMX** is a companion repository to the published study *Mapping Lightning Risk in Mexico: Integrating Natural Hazard and Social Vulnerability* (Jaramillo and Dominguez, 2024), published in *Weather, Climate, and Society*.

The study examines the geographical distribution of lightning-related fatalities in Mexico and develops a municipal-level risk map that combines **lightning hazard** with **social vulnerability**. This repository provides a place to share and preserve selected maps and associated geospatial products from the completed research.

The central message of the paper is that **lightning risk cannot be understood from lightning occurrence alone**: the social conditions of exposed populations are also essential.

## Key findings

- **2,573 lightning-related deaths** were reported in Mexico between **1998 and 2021**, according to official mortality records.
- **Fatality incidents are geographically uneven.** The State of Mexico reported the largest number of cases, followed by Oaxaca and Michoacán. At the municipal level, concentrations occur along the Sierra Madre Occidental, in central Mexico, and in parts of southern Veracruz and Tabasco.
- **Social vulnerability matters.** Men accounted for **81.4%** of reported lightning deaths, and rural populations engaged in outdoor work were particularly affected.
- **High-risk areas extend across multiple regions**, including the Sierra Madre Occidental, the Pacific coast, central and southeastern Mexico, and the Yucatán Peninsula. These patterns reflect the combined influence of lightning activity and social vulnerability.
- **82.1% of recorded fatality incidents occurred in municipalities classified as high or very high risk**: **25.6%** in high-risk municipalities and **56.5%** in very-high-risk municipalities. This agreement supports the relevance of the combined risk assessment.
- **Lightning-related mortality has declined over time.** The study places the 1998–2021 records in a longer historical context, showing a decline from approximately **5.6 deaths per million people in the early 1980s** to **0.3 per million in 2021**.

## Maps

The following maps correspond to results presented in the published article. The image placeholders below will be replaced as the map files are added to this repository.

### 1. Lightning-related fatality incidents by state

> **[INSERT FIGURE HERE — STATE-LEVEL INCIDENTS MAP]**  
> Suggested file: `assets/incidents_by_state.png`

<!-- When the image is ready, replace the placeholder with:
![Lightning-related fatality incidents by state in Mexico, 1998–2021](assets/incidents_by_state.png)
-->

*Figure 2a of Jaramillo and Dominguez (2024).* Accumulated lightning-related fatality incidents across Mexican states during 1998–2021. The map highlights differences in the geographical distribution of reported incidents at the state level.

### 2. Lightning-related fatality incidents by municipality

> **[INSERT FIGURE HERE — MUNICIPAL-LEVEL INCIDENTS MAP]**  
> Suggested file: `assets/incidents_by_municipality.png`

<!-- When the image is ready, replace the placeholder with:
![Lightning-related fatality incidents by municipality in Mexico, 1998–2021](assets/incidents_by_municipality.png)
-->

*Figure 2b of Jaramillo and Dominguez (2024).* Accumulated lightning-related fatality incidents at the municipal level during 1998–2021. The finer spatial resolution reveals localized patterns that may be obscured by state-level aggregation.

### 3. Lightning-related fatality risk in Mexico

> **[INSERT FIGURE HERE — MUNICIPAL RISK MAP]**  
> Suggested file: `assets/lightning_risk_map.png`

<!-- When the image is ready, replace the placeholder with:
![Municipal-level lightning-related fatality risk in Mexico](assets/lightning_risk_map.png)
-->

*Figure 6 of Jaramillo and Dominguez (2024).* Municipal-level lightning-related fatality risk, integrating lightning hazard and social vulnerability. Five risk categories are shown in the published map: **very low, low, middle, high, and very high**.

## Methodological overview

The published risk assessment combines two complementary components:

1. **Natural hazard:** the mean annual number of days with lightning activity, calculated using the WWLLN Global Lightning Climatology (WGLC) for **2010–2021**.
2. **Social vulnerability:** an index derived from the **2020 normalized marginalization index** for Mexican localities, incorporating social and socioeconomic disadvantages.

Locality-level risk is calculated from the normalized product of hazard and vulnerability. The risk values are classified into five categories using the **Dalenius–Hodges method**. Each municipality is assigned the **highest risk among its constituent localities**, providing a conservative representation of its risk conditions.

The resulting municipal classification is evaluated against officially reported lightning-related fatality incidents for **1998–2021**.

**Scope and limitations:** The assessment focuses on **fatality risk**, not the full range of lightning impacts or nonfatal injuries. Reported deaths may be underestimated, especially in rural regions, and lightning observations are subject to detection limitations. For methodological details, assumptions, and interpretation, consult the published article.

## Data availability

The original paper provides a **municipality-level supplementary table** containing municipality identifiers, coordinates, normalized risk and risk categories, vulnerability information, and accumulated reported fatality incidents. Consult the [article and its supplementary material](https://doi.org/10.1175/WCAS-D-23-0151.1) for the original research outputs.

Map images and any additional geospatial files can be incorporated into this repository as they are prepared for public distribution. Their availability here should not be assumed until they have been uploaded.

## Citation

If you use the results or maps presented in this repository, please cite the original peer-reviewed publication:

> Jaramillo, A., and C. Dominguez, 2024: Mapping lightning risk in Mexico: Integrating natural hazard and social vulnerability. *Weather, Climate, and Society*, **16**(3), 563–574. https://doi.org/10.1175/WCAS-D-23-0151.1

## Authors

**Alejandro Jaramillo** and **Christian Dominguez**  
Instituto de Ciencias de la Atmósfera y Cambio Climático, Universidad Nacional Autónoma de México (UNAM)

---

*LightningRiskMX documents results from a completed, peer-reviewed research study. The journal publication is the authoritative source for scientific methods and conclusions.*
