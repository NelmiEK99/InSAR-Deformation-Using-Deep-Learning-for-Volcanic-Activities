# InSAR-Deep-Learning-Literature-Reviews

Literature reviews focused on **autonomous detection of volcanic and seismic hazards** using **InSAR (Interferometric Synthetic Aperture Radar)** and **deep learning**, with a strong emphasis on the **New Zealand (Aotearoa) context**. fileciteturn2file0L1-L30

## What this repo contains

This repository currently includes two PDF literature reviews:

- **Volcanic_Hazards_InSAR Deformation.pdf** — a full literature review (Assignment 02, Research Methods in Applied Technologies, Master of Applied Technologies, Auckland, 2025). fileciteturn2file0L1-L8  
- **AutonomousDetectionofVolcanicandSeismicHazardsAssociatedInSARDeformationUsingDeepLearning.pdf** — a shorter write-up/introduction version covering the same core topic area. fileciteturn2file1L1-L13  

## Scope and themes

Across the reviews, the work discusses:
- Why **InSAR** is useful for large-area, millimetre-scale deformation monitoring, and why operational use is hard (atmospheric effects, big data volume, expert interpretation). fileciteturn2file0L9-L17  
- How **AI / deep learning** can support automated pattern/anomaly detection for geophysical monitoring. fileciteturn2file0L14-L27  
- A taxonomy of reviewed literature, including:
  - traditional InSAR processing,
  - supervised + unsupervised deep learning,
  - synthetic dataset generation,
  - multi-temporal InSAR analyses,
  - multi-modal fusion (InSAR + seismic, GNSS, thermal, gas, etc.). fileciteturn2file0L18-L27  
- A methodology note describing a structured selection process (recent peer-reviewed papers, and inclusion/exclusion criteria). fileciteturn2file3L20-L37  

## Key takeaway (high level)

A recurring conclusion is the shift from purely supervised image classification toward **unsupervised / semi-supervised anomaly detection**, supported by large-scale (real + synthetic) datasets and multi-sensor fusion — which fits volcanology monitoring where true “events” are relatively rare. fileciteturn2file0L24-L27 fileciteturn2file5L27-L33

## Suggested repo structure (optional)

If you want to keep things tidy on GitHub, you can organize it like:

```
.
├── README.md
└── pdfs/
    ├── Volcanic_Hazards_InSAR Deformation.pdf
    └── AutonomousDetectionofVolcanicandSeismicHazardsAssociatedInSARDeformationUsingDeepLearning.pdf
```

## How to cite

If someone references this repo, a simple citation format is:

> Author, *InSAR Deep Learning Literature Reviews*, 2025. (PDFs in this repository)

You can also add a `CITATION.cff` later if you want GitHub to generate citations automatically.

## Notes

- These PDFs are literature-review documents intended for research/education use.
- If you plan to make the repo public, consider adding a `LICENSE` file (e.g., CC BY 4.0, MIT, etc.) depending on how you want others to reuse your writing.
