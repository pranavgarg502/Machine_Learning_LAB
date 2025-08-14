
# Decision Log – Titanic Cleaning

1. Missing Age: Imputed with median (skewed distribution).
2. Missing Embarked: Imputed with mode ('S').
3. Cabin: Too sparse (>77% missing) → Dropped, created Cabin_known flag.
4. Fare Outliers: Capped at 512.3292 (IQR method).
5. Added missingness flags for Age, Embarked.
