# Eksperimen_SML_Sabillah_Nur

## Deskripsi
Project submission MSML:
- **Kriteria 1**: Data loading, EDA, dan preprocessing dataset Student Performance (UCI).
- **Kriteria 2 *: Training model Scikit-Learn dengan **MLflow Tracking lokal** menggunakan **MLflow autolog** + screenshot dashboard & artifacts.

## Struktur Folder
- `namadataset_raw/` : dataset mentah (raw)
- `preprocessing/` : notebook eksperimen
- `preprocessing/namadataset_preprocessing/` : dataset hasil preprocessing
- `membangun_model/` : training model + MLflow tracking + screenshot

## Output
### Kriteria 1
- Raw: `namadataset_raw/student_performance_raw.csv`
- Processed: `preprocessing/namadataset_preprocessing/student_performance_processed.csv`

### Kriteria 2
- Dataset untuk training: `membangun_model/namadataset_preprocessing/student_performance_processed.csv`
- Script training: `membangun_model/modelling.py`
- Dependencies: `membangun_model/requirements.txt`
- Screenshot:
  - `membangun_model/screenshoot_dashboard.jpg`
  - `membangun_model/screenshoot_artifak.jpg`
