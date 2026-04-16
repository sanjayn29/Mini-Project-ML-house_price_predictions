# Mini-Project-ML-house_price_predictions

## **Project Overview**
- Built a predictive model using the **House Price Dataset**.
- Focused on key features: 
  - `GrLivArea` (above-ground living area in square feet)
  - `TotalBsmtSF` (total basement square footage)
  - `BedroomAbvGr` (number of bedrooms)
  - `FullBath` (number of full bathrooms)
- The target variable is `SalePrice`, representing the house price.

## **Key Highlights**
- **Data Preprocessing**:
  - Handled missing values by filling them with the median.
  - Selected and processed features for optimal performance.
- **Model Training**:
  - Implemented a **Linear Regression Model** using Python's `sklearn` library.
  - Achieved a Root Mean Squared Error (RMSE) of **46,664** on the validation dataset.
- **Prediction**:
  - Generated house price predictions for the test dataset.
  - Exported the results to a CSV file.

## **Technologies Used**
- **Python**: Data processing and model development.
- Libraries: `pandas`, `numpy`, `sklearn`.

## **Future Enhancements**
- Experiment with advanced models like **XGBoost** or **Random Forest**.
- Perform additional feature engineering to improve accuracy.
- Fine-tune the model using hyperparameter optimization techniques.

## **How to Run the Project**
1. Clone the repository:
   ```bash
   git clone <repository-link>
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the script to train the model and generate predictions:
   ```bash
   python house_price_prediction.py
   ```

## **Output**
The predictions for the test dataset are saved in a CSV file: `house_price_predictions.csv`.

## 👨‍💻 Developer

**Sanjay N** 🚀 Freelancer

🌐 Portfolio: https://sanjayn.me  
💼 LinkedIn: https://linkedin.com/in/sanjayn29  
🐙 GitHub: https://github.com/sanjayn29  

---

## ⭐ Support

If you like this project, consider giving it a **star ⭐ on GitHub** to support the development.
