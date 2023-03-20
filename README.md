# Predicting-Turbine-Energy-Yeild-TEY-

## Dataset Description:-
- The dataset contains 36733 instances of 11 sensor measures aggregated over one hour (by means of average or sum) from a gas turbine.
- The Dataset includes gas turbine parameters (such as Turbine Inlet Temperature and Compressor Discharge pressure) in addition to the ambient variables.

## Problem statement:-
- predicting turbine energy yield (TEY) using ambient variables as features.

## Attribute Information:-
- The explanations of sensor measurements and their brief statistics are given below.

| Variable (Abbr.)           | Unit     | Min     | Max     | Mean    |
|----------------------------|----------|---------|---------|---------|
| Ambient temperature (AT)   | C        | -6.23   | 37.10   | 17.71   |
| Ambient pressure (AP)      | mbar     | 985.85  | 1036.56 | 1013.07 |
| Ambient humidity (AH)      | (%)      | 24.08   | 100.20  | 77.87   |
| Air filter difference pressure (AFDP) | mbar     | 2.09    | 7.61    | 3.93    |
| Gas turbine exhaust pressure (GTEP) | mbar     | 17.70   | 40.72   | 25.56   |
| Turbine inlet temperature (TIT) | C        | 1000.85 | 1100.89 | 1081.43 |
| Turbine after temperature (TAT) | C        | 511.04  | 550.61  | 546.16  |
| Compressor discharge pressure (CDP) | mbar | 9.85    | 15.16   | 12.06   |
| Turbine energy yield (TEY) | MWH     | 100.02  | 179.50  | 133.51  |
| Carbon monoxide (CO)       | mg/m3    | 0.00    | 44.10   | 2.37    |
| Nitrogen oxides (NOx)      | mg/m3    | 25.90   | 119.91  | 65.29   |

## Accuracy of Models:-

| Regression | Simple Linear | Multiple | Decision tree | Random Forest | KNN | SVM | Bagging | Adaboost | Gradient Boosting | xgboost Regressor |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Training r2_score | 0.9778 | 0.9958 | 0.9357 | 0.9982 | 0.9825 | 0.9950 | 0.9964 | 0.9851 | 0.9964 | 0.9977 |
| Testing r2_score | 0.9771 | 0.9957 | 0.9317 | 0.9973 | 0.9814 | 0.9894 | 0.9949 | 0.9835 | 0.9962 | 0.9971 |

## Observations:
- We got pretty good results for all model but it that Random forest is the best model.
- Train and test errors are also quiet similar, which means our model is not overfitted or underfitted.
