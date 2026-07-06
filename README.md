# Language Learning Apps Archive

A comprehensive academic database and analysis dashboard for the systematic review of language learning applications, comparing commercial language learning tools with Mobile-Assisted Language Learning (MALL) apps for dominant and underserved languages.

## Project Overview

This project supports a systematic review examining how language learning technologies serve different language communities. The archive collects, codes, and analyses peer-reviewed literature from MALL research, HCI, NLP, linguistics, and language revitalisation studies to understand disparities in language technology development and accessibility.

## Research Focus

- **Commercial vs. underserved language apps**: Comparing features, pedagogical approaches, and sustainability
- **Language coverage**: Analysing which languages are supported by existing applications
- **Evaluation criteria**: Technical capability, pedagogical depth, community engagement, equity, and accessibility
- **First appearance timeline**: Tracking when apps enter academic literature over time

## Features

- **Interactive paper database**: Searchable, filterable table of all reviewed papers with composite scoring
- **Analysis dashboard**: Multiple visualizations including:
  - Papers by type and publication year
  - Average criterion scores (radar chart)
  - Language coverage distribution
  - Top apps mentioned in literature
  - First appearance timeline for apps
  - Composite score distribution
- **Data export**: Download paper database as JSON or CSV for further analysis
- **Firebase integration**: Real-time data synchronisation and cloud storage

## Technical Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Visualization**: Chart.js for interactive dashboards
- **Database**: Firebase Realtime Database
- **Deployment**: GitHub Pages / Jekyll

## Data Structure

Each paper entry includes:

- Metadata (DOI, title, authors, year, type)
- Language coverage (comma-separated list)
- Application mentions (comma-separated list)
- Criterion scores (0–3 scale):
  - Language Coverage
  - Pedagogical Depth
  - Technical Capability
  - Community & Sustainability
  - Equity & Access
- Composite total score

## Usage

### Viewing the Archive

1. Navigate to the main index page to browse all papers
2. Use the search and filter options to find specific studies
3. View the analysis dashboard for visual summaries

### Adding Papers

1. Use the paper submission form to add new entries
2. Ensure all criterion scores are on the 0–3 scale
3. Data automatically syncs to Firebase

### Exporting Data

- Click "Download JSON" or "Download CSV" to export the complete dataset
- Use exported data for statistical analysis or meta-analysis

## Methodology

This systematic review follows PRISMA-style screening protocols with standardised extraction and coding workflows. Papers are evaluated across five core dimensions reflecting established app-evaluation categories from MALL and language technology research.

## License

All paper data and analyses are openly available for academic use.

## Citation

If you use this database or dashboard in your research, please cite:

```text
Hannah M. Claus. (2026). Language Learning Apps Archive: A systematic review database [Data set]. GitHub. https://github.com/melkemaryam/Language-Learning-App-Comparison
```

## Contact

For questions about the dataset, methodology, or collaboration opportunities, please contact hmc78@cam.ac.uk.

## Acknowledgements

This work contributes to ongoing research in inclusive language technologies, decolonised AI perspectives, and language revitalisation for underserved communities.

