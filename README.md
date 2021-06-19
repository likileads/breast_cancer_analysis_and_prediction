# Breast cancer analysis and prediction

Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei.

### Attributes Used:
1. ID number
2. Diagnosis (<b>M</b> : malignant, <b>B</b> : benign)

Remaining:
[refer here (first row)](https://github.com/likileads/breast_cancer_analysis_and_prediction/blob/main/data/data.csv)

Ten real-valued features are computed for each cell nucleus:

a) radius (mean of distances from center to points on the perimeter)<br>
b) texture (standard deviation of gray-scale values)<br>
c) perimeter<br>
d) area<br>
e) smoothness (local variation in radius lengths)<br>
f) compactness (perimeter^2 / area - 1.0)<br>
g) concavity (severity of concave portions of the contour)<br>
h) concave points (number of concave portions of the contour)<br>
i) symmetry<br>
j) fractal dimension ("coastline approximation" - 1)<br>
