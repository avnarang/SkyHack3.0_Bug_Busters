# SKYHACK – Flight Difficulty Score

## Setup
python -m venv venv
# macOS/Linux: source venv/bin/activate
# Windows (PS): .\venv\Scripts\Activate.ps1
pip install -r requirements.txt
python -m ipykernel install --user --name skyhack

## Data
Place CSVs in `data/`. Notebooks assume they run from `code/` and use paths like `../data/*.csv`.

## Run (VS Code)
Open `SKYHACK` in VS Code → select the `venv`/`skyhack` kernel → open `code/*.ipynb` → **Run All**.

## Order
1) `code/eda_analysis.ipynb`
2) `code/flight_difficulty_score.ipynb`
3) `code/post_analysis_and_operational_insigths.ipynb`

## Outputs
Written to `outputs/`.
