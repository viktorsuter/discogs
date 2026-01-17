# Discogs Vinyl Analysis

Finding the hottest records on Discogs.

## Data

**Source**: Discogs monthly data dump (January 2026)  
**Total releases**: 18,797,505

| Sample | Size | Link |
|--------|------|------|
| 50k random | 12.5 MB | [Download CSV](https://www.dropbox.com/scl/fi/k4d8e47q9ky8hhd5hwwkn/releases_50k_random_sample.csv?rlkey=xnicb09k8ouji0qd6yqdc7xag&dl=1) |
| 1M random | 251.5 MB | [Download CSV](https://www.dropbox.com/scl/fi/q34ib5hytg963bhzt9x9b/releases_1m_random_sample.csv?rlkey=8mlgfifj2gu0qfavojskjet03&dl=1) |

**Variables**: 'id', 'title', 'country', 'released', 'notes', 'data_quality', 'master_id', 'artists', 'label', 'format', 'format_qty', 'format_desc', 'genres', 'styles', 'track_count'

## Setup

1. Get a Discogs API token: https://www.discogs.com/settings/developers
2. Create `.env` file with: `DISCOGS_TOKEN=your_token_here`
3. `pip install -r requirements.txt`

## Structure
```
discogs/
├── notebooks/       <- Analysis notebooks
├── README.md
└── requirements.txt
```
## Author

Viktor Suter
