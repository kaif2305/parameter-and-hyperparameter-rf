## 🔧 Hyperparameters vs Parameters in Random Forest

### Hyperparameters
These are configurations **set before training** a model and guide the **learning process**. They are **not learned from data**.

**Examples:**
- `n_estimators`: Number of trees in the forest  
- `max_depth`: Maximum depth of each tree  
- `criterion`: Function to measure the quality of a split (e.g., `"gini"`, `"entropy"`)

### Parameters
These are values **learned from the data** during the training process. They define the **internal structure and decision rules** of the trained model.

**Examples in Random Forest (as exposed by scikit-learn):**
- `feature_importances_`: Importance scores for each feature  
- `estimators_`: List of individual decision trees built by the model
