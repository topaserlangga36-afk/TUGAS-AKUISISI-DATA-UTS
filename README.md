# Proyek Akuisisi Data Pariwisata Bali

Proyek ini mengintegrasikan data pariwisata bulanan dari BPS Bali, data historis cuaca dari Open-Meteo API, dan data wilayah hasil scraping Wikipedia.

## Struktur Direktori
- `data/raw/` : Menyimpan file mentah (Excel BPS, JSON cuaca, HTML Wikipedia)
- `data/processed/` : Menyimpan data hasil pembersihan (long format CSV, gabungan data)
- `metadata/` : Menyimpan dokumen kepatuhan etika data, provenance, dan merge metadata.
