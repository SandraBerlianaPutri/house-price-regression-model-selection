# House Price Regression and Model Selection

## About
This project explores regression models for house price analysis using R. Several approaches are compared to investigate predictor selection, response transformations, influential observations, and regression diagnostics.

## Project Analysis
- [View Full Analysis on RPubs](https://rpubs.com/sandraberlianaputri/house-price-regression)

## Dataset
- **Observations:** 1,015 property listings
- **Geographic coverage:** Bekasi, Indonesia, based on the location fields in the dataset
- **Response variable:** `Harga` — house price, recorded in billions of rupiah according to the source column name
- **Predictor variables:**
  - `Kamar Tidur`: Number of bedrooms
  - `Kamar Mandi`: Number of bathrooms
  - `Luas Tanah`: Land area (m²)
  - `Luas Bangunan`: Building area (m²)
  - `Garasi`: Garage indicator/count as recorded in the dataset
  - `Cicilan`: Monthly installment, in millions of rupiah
- **Additional variables:** `Jenis Bangunan`, `Kec`, and `Kab/Kota`

## Methods
- **Multiple Linear Regression:** Initial model using six predictors.
- **Regression Diagnostics:** Breusch–Pagan, Durbin–Watson, Shapiro–Wilk, and Kolmogorov–Smirnov tests, alongside VIF and influence measures.
- **Response Transformations:** Box–Cox, logarithmic, square-root, reciprocal, and squared-price transformations.
- **Influential Observation Analysis:** Leverage-based identification and model refitting.
- **Variable Selection:** Lasso regression with cross-validation.
- **Alternative Models:** Robust regression and median quantile regression.

## Author
**Sandra Berliana Putri** - Statistics and Data Science graduate from IPB University.
