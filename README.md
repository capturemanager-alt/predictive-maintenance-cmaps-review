# Predictive Maintenance: Turbofan Engine RUL Prediction (NASA CMAPSS)

End-to-end LSTM deep learning project for predicting Remaining Useful Life (RUL) of turbofan engines.

## Key Results
- Test MAE: 36.26 cycles  
- Test RMSE: 41.16 cycles  
- Evaluated on 93 valid test engines (standard CMAPSS protocol)

## Features Demonstrated
- Data loading & exploration (sensor trends, RUL trajectories)
- Preprocessing (normalization, sliding windows)
- LSTM model with stability fixes (low LR, gradient clipping, L2 reg)
- Training history visualization
- Test evaluation & metrics
- Business ROI simulation

## How to Run
1. Clone repo: `git clone https://github.com/capturemanager-alt/predictive-maintenance-cmaps-review.git`
2. Install dependencies: `conda env create -f environment.yml` (if you export one) or `pip install -r requirements.txt`
3. Run notebook: `jupyter notebook Predictive_Maintenance_CMAPSS.ipynb`

## Interactive View
View/run online: [nbviewer link here – paste your nbviewer URL]

Built as a portfolio project for tailored AI/ML solutions in manufacturing and defense.  
Questions? Contact: capturemanager@fitzinit.com
