# Texas Demographics, Diversity & Population Pyramids Explorer

An interactive, high-precision geospatial demographic laboratory for Texas Geography (**GEOG 331**) at **Texas Southern University (TSU)**, authored by **Dr. Moulay Anwar Sounny-Slitine**.

Live Application: https://sounny.github.io/tx-pop-pyramids/

---

## Educational Purpose & Spatial Inquiry

This interactive application empowers students to explore the human geography of Texas through the lens of official **U.S. Census Bureau American Community Survey (ACS) 5-Year Data (Tables B01001 & B03002)**:

1. **Dual Population Pyramids:** Compare age-sex cohort structures across all 254 Texas counties (e.g. suburban rapid-growth communities vs. micro-rural oil extraction vs. aging Trans-Pecos counties).
2. **The "New Texas Mosaic":** Visualize racial and ethnic composition, analyzing the transition to majority-minority and "No-Majority" demographics using the **Simpson Diversity Index**.
3. **Regional Dependency & Infrastructure:** Evaluate Youth Dependency, Old-Age Dependency, Total Dependency, and Sex Ratios to understand public education burdens, healthcare accessibility, and workforce dynamics.
4. **Publication-Grade PNG Export:** Direct HTML5 Canvas sub-pixel rendering engine for student submission to Canvas LMS.

---

## Key Features

* **254 Texas Counties Choropleth (Leaflet.js):**
  * Dynamic metric layers: Median Age, Total Population, Simpson Diversity Index, Hispanic/Latino %, Non-Hispanic White %, Non-Hispanic Black %, Asian Alone %, Dependency Ratios.
  * Multi-basemap support (CartoDB Dark Matter, Positron Light, ESRI World Satellite, OpenStreetMap).
  * Overlays for Texas Anchor Cities and the Texas Urban Triangle Megaregion.
* **Dual Population Pyramids:**
  * 18 standardized 5-year cohorts (0-4 through 85+).
  * Males (left) vs. Females (right) with cohort hover inspection.
  * Toggles between Percentage (%) Scale and Absolute Headcounts.
* **Racial & Ethnic Diversity Mosaic:**
  * 100% stacked horizontal bar comparison.
  * Real-time Simpson Diversity Index calculation.
* **Pre-Configured Pedagogical Presets:**
  * **Fort Bend (Suburban Diversity Powerhouse) vs. Loving County (Micro-Rural Permian Basin)**
  * **Fort Bend vs. Brewster County (Trans-Pecos Big Bend / Aging Frontier)**
  * **Fort Bend vs. Presidio County (Rio Grande Borderland Majority-Hispanic)**
  * **Fort Bend vs. Jeff Davis County (Davis Mountains / High Median Age)**
  * **Harris County (Houston Megacity) vs. Starr County (Rio Grande Valley / Youthful)**
  * **Travis County (Silicon Hills Austin) vs. Terry County (South Plains Cotton)**
  * **Dallas County vs. Hudspeth County (Trans-Pecos Salt Flat Desert)**
* **Student Spatial Synthesis Studio:**
  * Integrated drafting notepad with word-count tracker and guided analytical prompts.
  * One-click clipboard copy formatted with quantitative summary tables for Canvas Text Entry.
* **High-Resolution Canvas Export:**
  * 1600x1200 composite PNG download containing student metadata, dual pyramids, diversity bars, and quantitative metrics.

---

## Data Sources & Technical Stack

* **U.S. Census Bureau ACS 5-Year Detailed Tables (2022 Vintage):**
  * `B01001`: Sex by Age (49 variables across 23 male/female age cohorts)
  * `B03002`: Hispanic or Latino Origin by Race
  * `B01002`: Median Age by Sex
* **Mapping:** Leaflet 1.9.4 & WGS84 GeoJSON
* **Visual Identity:** Official Texas Southern University Brand Colors (TSU Maroon `#7C183E`, TSU Dark Maroon `#4E121B`, Tiger Gold `#D97706`, Slate `#0F172A`)
* **Zero Dependencies:** Single self-contained HTML file running 100% client-side with offline resilience.

---

## License & Attribution

Designed and developed by **Dr. Moulay Anwar Sounny-Slitine** for Texas Southern University (TSU) Department of History, Geography & General Studies.
