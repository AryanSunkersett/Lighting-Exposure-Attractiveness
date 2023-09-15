# EDA of Percieved Attractiveness From Different Lightings/Exposures

### Description of the Data:
The data comes from two separate experiments in which a number of participants were photographed in identical conditions barring changes in only lightings and exposures respectively. The photos of these participants were then rated on a subjective scale from 1-10 by volunteers.

### Methodology
1. Data Cleaning:
    1. Converted missing values (0's) to NaN
    1. Calculated and converted outliers to NaN as well
    1. Count total NaN's to verify not too many datapoints were removed
1. Basic Stats:
    1. Calculate means and standard deviations for every type of lighting and exposure
    1. Create and overlaid bar graph of the distribution of lighting scores over the same subject to see if there is an apparent difference between them
1. ANOVA (Analysis of Variance) Tests:
    1. Calculate the ANOVA scores for the two trials to check significance of any differences
1. P-Value Heatmap:
    1. Display a heatmap of p-values between individual lighting/exposure conditions

### Conclusions:
1. Lighting has a significant effect on percieved attractiveness
    1. Overhead lighting is the worst, while a single 45 degree box light was the best
1. Exposure does not have a significant effect on percieved attractiveness
    1. Even if you cherry-pick the averages of the highest and lowest exposures, there is still no significant difference