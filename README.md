
# House Price Prediction Using Random Forest and Spatial Models

## 🏡 **Project Description**
This project uses **Random Forest** and **Spatial Random Forest** models to predict house prices based on property features and geographic location. The analysis incorporates datasets of property attributes and spatial coordinates within the Nairobi metropolitan area.

## 📁 **Folder Structure**
- **data/**: Contains input datasets, including property details and shapefiles.
- **scripts/**: Includes R scripts for data preprocessing, model training, and prediction.
- **results/**: Stores prediction outputs and performance metrics.
- **README.md**: Project overview and setup instructions.

## 💾 **Getting Started**
### Prerequisites
- R 4.0 or higher
- Required libraries: `tidyverse`, `spatialRF`, `randomForest`, `sf`, and `ggplot2`

### Installation
1. Clone the repository:
```bash
git clone https://github.com/fmirriam/housing-price-prediction.git
```
2. Open the project in **RStudio**.
3. Install dependencies:
```r
install.packages(c("tidyverse", "sf", "spatialRF", "randomForest", "ggplot2"))
```

## 📊 **Key Steps in the Analysis**
1. **Data Preprocessing:**
    - Cleaning and encoding categorical variables
    - Handling missing values and outliers
    - Spatial coordinate correction

2. **Exploratory Data Analysis (EDA):**
    - Visualizing feature distributions
    - Mapping property locations with shapefiles

3. **Model Training:**
    - Random Forest for baseline predictions
    - Spatial Random Forest to incorporate spatial effects

4. **Prediction and Evaluation:**
    - Predict house prices on test data
    - Evaluate performance using RMSE and R²

## 📈 **Model Performance**
- **Random Forest:** 71.16% variance explained
- **Spatial Random Forest:** Improved prediction with spatial factors

## 💡 **How to Reproduce the Analysis**
1. Load datasets in `/data`
2. Execute scripts in `/scripts`
3. View predictions in `/results`

## ✅ **Authors**
- **Faith Osoro**  
- GitHub: [fmirriam](https://github.com/fmirriam)

For questions or contributions, please open an **issue** or submit a **pull request**. 😊
