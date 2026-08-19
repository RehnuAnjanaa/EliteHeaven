# EliteHeaven
Project for travel flight analysis.
Flight price analysis (static plots)
-----------------------------------

Files:
- analysis.py: main script to create static PNG plots and compute feature importances.
- requirements.txt: Python dependencies.

How to run:
1. Create a virtualenv (recommended)
   python -m venv venv
   source venv/bin/activate

2. Install requirements:
   pip install -r requirements.txt

3. Run the analysis script:
   python analysis.py --input flight_pricing_dataset.csv

   - If you run the script from the repo root and the CSV is at repo root, that path will work.
   - If you omit --input, the script will download the default CSV from the repository raw URL.

Outputs:
- plots/*.png
- feature_importances.csv
