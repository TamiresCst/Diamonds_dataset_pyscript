# **Project - Diamonds dataset**

## BASE
The dataset of this project is https://ggplot2.tidyverse.org/reference/diamonds.html
There are ten attributes of almost 54,000 round cut diamonds. The variables are as follows:

- **price:** price in US dollars ($326--$18,823)
- **carat:** weight of the diamond (0.2--5.01)
- **cut:** quality of the cut (Fair, Good, Very Good, Premium, Ideal)
- **color:** diamond colour, from D (best) to J (worst)
- **clarity:** a measurement of how clear the diamond is (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best))
- **x:** length in mm (0--10.74)
- **y:** width in mm (0--58.9)
- **z:** depth in mm (0--31.8)
- **depth:** total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43--79)
- **table:** width of top of diamond relative to widest point (43--95)

## DATA ANALYSIS

The main idea was to use statistical libraries (matplotlib, seaborn and scikit-learn) to train a decision tree machine learning model and verify its accuracy. In addition, the PyScrit framework was used to run Python programs directly in the browser. Two types of graphs were made to visualize the behavior of cut diamonds in relation to their quality.

The result showed that the Decision Tree Model was not satisfactory for these data, since its accuracy reached 65%.





