# AI-for-Crop-Yield-Optimization-in-Illinois
Graduate-level project focused on predicting corn yield across Illinois counties using historical agricultural, weather, and soil data. The project applies both classical machine learning and deep learning methods to explore performance, limitations, and generalization in a real-world setting.

## View Notebooks (if GitHub doesn’t render)
- ML notebook (nbviewer): https://nbviewer.org/github/Abiokpo27/AI-for-Crop-Yield-Optimization-in-Illinois/blob/main/BSE5124_FinalProject_Batubo_ML.ipynb
- DL notebook (nbviewer): https://nbviewer.org/github/Abiokpo27/AI-for-Crop-Yield-Optimization-in-Illinois/blob/main/BSE5124_FinalProject_Batubo_DL.ipynb

## Project Overview
Corn is a major staple crop in Illinois, and accurate yield prediction is crucial for supporting food security, economic planning, and climate adaptation. This project models yield across 90 counties using multiple public datasets.

## Modeling Approach
I implemented two modeling approaches within the same project:
- **Classical Machine Learning models:** Random Forest and Gradient Boosting
- **Deep Learning model:** LSTM

Both approaches were used to explore model behavior, performance, and generalization on a complex, real-world agricultural dataset.

## Data
Features include yield (bushels/acre), weather variables (precipitation, temperature, solar radiation, vapor pressure), soil characteristics (pH, texture, water capacity), and management indicators (percent planted).

## Results Summary (high-level)
Tree-based ML models achieved lower validation error after tuning, while the LSTM showed limitations in generalization under the available data. This reinforced the importance of careful validation and reliability checks before real-world deployment.

## Files
- `BSE5124_FinalProject_Batubo_ML.ipynb` - ML implementation and evaluation
- `BSE5124_FinalProject_Batubo_DL.ipynb` - LSTM implementation and evaluation

## Notes
This work reflects my individual coursework and learning process.
