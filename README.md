# Nonlinear PM₂.₅–Hypertension Relationships in Michigan: The Intersection of Pollution and Poverty

**Author:** Nelson Anyim Bronya  
**Affiliation:** Central Michigan University  
**Repository:** [Nelbro/Research](https://github.com/Nelbro/Research)  
**Last Updated:** [Insert Date]

---

## 🔍 Research Overview

This study investigates the complex relationship between fine particulate matter (PM₂.₅) exposure and hypertension prevalence across 83 Michigan counties, revealing how socioeconomic factors mediate environmental health risks. Using advanced spatial and statistical modeling, we demonstrate:

- **Nonlinear toxicity thresholds** for PM₂.₅ exposure
- **Socioeconomic mediation** of pollution impacts
- **Geospatial clustering** of high-risk populations
- **Cost-effective intervention** strategies

---

## 📊 Key Findings

### 1. Nonlinear Exposure Response (Fig 1)
- **U-shaped relationship**: PM₂.₅ shows threshold effects on hypertension
  - Below 9-10 µg/m³: Socioeconomic buffers reduce risk
  - Above threshold: +3.20-4.11% hypertension increase per µg/m³ (p < 0.01)

### 2. Socioeconomic Mediation (Fig 2)
- **86.4% of PM₂.₅ effects** mediated through:
  - Income inequality (58.1%)
  - Poverty rates (28.3%)
- **Rural disparity**: 40.15% vs urban 35.64% hypertension (p < 0.001)

### 3. Spatial Risk Clusters (Fig 3)
| Cluster                | Characteristics          | Example Counties     |
|------------------------|--------------------------|----------------------|
| Low PM₂.₅, High Income | Urban SE Michigan        | Oakland, Washtenaw   |
| Transitional           | Mixed urban-rural        | Kent, Ingham         |
| High PM₂.₅, Low Income | Rural Upper Peninsula    | Marquette, Alger     |

### 4. Intervention Potential
10% PM₂.₅ reduction could:
- Prevent **15,000 hypertension cases** annually
- Save **$25 million** in healthcare costs

---

## 🛠️ Repository Structure
Research/
├── data/
│ └── final_data_clean.csv # Analyzed dataset (PM₂.₅, HPT, socioeconomic variables)
├── analysis/
│ ├── analysis_script.R # Complete reproducible analysis pipeline
│ └── urban_rural_fix.R # Error-corrected visualization code
├── figures/ # Generated visualizations
│ ├── GAM_curve.png # U-shaped exposure-response (Fig 1)
│ ├── Mediation_sankey.png # Socioeconomic pathways (Fig 2)
│ ├── 3D_clusters.html # Interactive spatial analysis (Fig 3)
│ └── UrbanRural_comparison.jpg # Health disparities (Fig 4)
├── docs/
│ └── references.pdf # Complete reference list
└── README.md # Project overview


---

## 🚀 Getting Started

### Requirements
```r
required_packages <- c(
  "tidyverse", "mgcv", "ggalluvial", "plotly", "sf",
  "viridis", "scales", "knitr", "webshot2"
)
Installation

Clone repository:
bash
git clone https://github.com/Nelbro/Research.git
cd Research
Install dependencies:
r
source("analysis/install_packages.R")  # Auto-installs missing packages
Configure paths in analysis_script.R:
r
base_dir <- "~/path/to/Research"  # Set your project root
📈 Recreating Analyses

r
# Run full analysis pipeline
source("analysis/analysis_script.R")

# Generate specific figures
source("analysis/generate_figures.R")  # Options: 1-4
🏛️ Policy Implications

Environmental Standards
Adopt PM₂.₅ threshold <9 µg/m³
Implement community air monitoring networks
Health Equity Measures
Expand rural telehealth infrastructure
Target Medicaid expansion in hotspot counties
Economic Interventions
Fund green space development in urban cores
Create pollution reduction tax incentives
📚 References & Support

[QR Code Placeholder]
Scan for full references and supplementary materials

Contact: phadanelson@gmail.com
License: MIT (see LICENSE)
