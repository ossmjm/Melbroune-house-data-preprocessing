# Melbroune-house-data-preprocessing
To preprocess data with missing values and outliers, employ various techniques:

### Handling Missing Values:
1. **Forward Fill (FFill):**
   - Propagate the last observed non-missing value forward.

2. **Backward Fill (BFill):**
   - Propagate the next observed non-missing value backward.

3. **Fill by Median:**
   - Replace missing values with the median of the respective column.

4. **KNN Imputer:**
   - Utilize K-nearest neighbors to impute missing values based on similar observations.

### Outlier Treatment:
1. **Quantile-Based Method:**
   - Identify and replace values beyond a certain quantile range as outliers.

2. **Winsorization:**
   - Cap extreme values at a specified percentile to mitigate the impact of outliers.

These methods collectively address missing values and outliers, enhancing the robustness of the dataset for further analysis.
