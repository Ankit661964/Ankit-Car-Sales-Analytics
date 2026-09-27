# Used Car Sales & Pricing Analytics
### AICTE | IBM SkillsBuild Data Analytics with AI Internship 2026

## Project overview
This project analyzes used-car listings to understand pricing patterns, vehicle age, mileage, fuel type, seller type, transmission and ownership.

## Dataset
**Primary source:** Kaggle — Vehicle dataset from CarDekho  
https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho

The Kaggle dataset describes eight fields: `name`, `year`, `selling_price`, `km_driven`, `fuel`, `seller_type`, `transmission`, and `owner`.

**Optional public mirror:**  
https://github.com/bagassenop/cardekho

> For the cleanest provenance, download the CSV from Kaggle and place it beside the notebook as `CAR DETAILS FROM CAR DEKHO.csv`.

## Files in this submission
1. `Ankit_Car_Sales_Analytics.ipynb` — complete Python/Jupyter analysis.
2. `requirements.txt` — Python libraries needed to run the notebook.
3. `Ankit_Car_Sales_Analytics_ProjectReport.docx` — project documentation/report.
4. `README.md` — project overview, dataset link and run instructions.

## Tools and technologies
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Analysis performed
- Data loading and inspection
- Missing-value and duplicate checks
- Data cleaning
- Brand extraction
- Vehicle-age feature creation
- Descriptive statistics
- Price distribution
- Fuel/transmission/seller analysis
- Brand frequency analysis
- Mileage vs price
- Vehicle age vs price
- Ownership vs price
- Correlation analysis
- Baseline linear regression
- Actual vs predicted price visualization
- Automatic key-finding summary

## How to run
1. Download the dataset from the Kaggle link above.
2. Extract the CSV.
3. Put `CAR DETAILS FROM CAR DEKHO.csv` in the same folder as the `.ipynb` file.
4. Install dependencies:
   `pip install -r requirements.txt`
5. Open Jupyter Notebook:
   `jupyter notebook`
6. Open `Ankit_Car_Sales_Analytics.ipynb`.
7. Use **Kernel → Restart & Run All**.
8. Save the notebook after all cells finish.

## Academic note
This is an educational analytics project. The dataset represents used-car listings and should not be interpreted as a complete census of the used-car market. Correlation and regression results describe the dataset and do not prove causation.

## Suggested submission checklist
- [ ] `.ipynb` opens and all cells run
- [ ] `requirements.txt` included
- [ ] `.docx` report included
- [ ] `README.md` included
- [ ] Dataset link works
- [ ] Your full name/student details are added where required
- [ ] No placeholder personal details remain in the final report
