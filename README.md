# Assignment#2：Meta-analysis-of-Ocean-Acidification-Effects-on-Behaviour
**The goal of this assignment is to conduct a meta-analysis on ocean acidification effects on behaviour**


# DATA files

### 1.OA_activitydat_20190302_BIOL3207.csv
#### Raw data form [Clark et al. (2020)](https://doi.org/10.1038/s41586-019-1903-y)
loc Location, and year, where the data were collected. AIMS = Australian Institute of Marine Science; LIRS = Lizard Island Research Station species Species name: acantho = Acanthochromis; Ambon = Pomacentrus amboinensis; Chromis = Chromis atripectoralis; Humbug = Dascyllus aruanus; Lemon = Pomacentrus moluccensis treatment Elevated CO2 [CO2] (850-1,050 µatm) or control [Control] (400 - 450 µatm) groups animal_id Fish identity sl Standard length of the fish in mm size Size grouping of the fish, separated at 15 mm standard length into 'big' or 'small' activity Number of seconds the fish was active per minute, averaged across the duration of the trial comment Comment with notes on the origin of the data
### 2.clark_paper_data.csv
#### Meta-analysis format description of raw data form [Clark et al. (2020)](https://doi.org/10.1038/s41586-019-1903-y)
### 3. ocean_meta_data.csv
#### Meta data from [Clements et al. (2022)](https://doi.org/10.1371/journal.pbio.3001511)

# SCRIPT files

### 1.Assignment2Meta-analysis.Rmd
Annotated R markdown document with meta-analysis of the above data.

### 2.Assignment2Meta-analysis.html
The final report after rendering from the above R markdown document.

# Meta-analysis workflow

## **Load the necessary R Packages**

## **Add the article by [Clark et al. (2020)](https://doi.org/10.1038/s41586-019-1903-y) to the Meta-analysis dataset**

##### 1. Analysis of [Clark et al. (2020)](https://doi.org/10.1038/s41586-019-1903-y) for each of the fish species’ `average activity` for each treatment.

##### 2. Merge the summary statistics generated from from [Clark et al. (2020)](https://doi.org/10.1038/s41586-019-1903-y) with the metadata

##### 3. Merge metadata from larger meta-analysis datase

## **Meta-analytical model for ocean acidification metadata sets**

##### 4. Calculate the log response ratio (lnRR) effect size for every row

##### 5. Meta-analytic model fitted to the data

##### 6. Results and discussion of the meta-analytical model

###### Uncertainty in the overall meta-analysis mean: 95% confidence interval:

###### Heterogeneity in effect size estimates across studies：

###### Forest plot to capture meta-analysis model results.

## **Publication biases in meta-analyses of ocean acidification metadata sets**

##### 7. Funnel plot for visually assessing the possibility of publication bias  

##### 8. Time-lag plot assessing how effect sizes may or may not have changed through time.

##### 9. Formal meta-regression model that includes year as a moderator (fixed effect) to test for time-lag bias

##### 10 Formal meta-regression model that includes inverse sampling variance (i.e., 1vlnRR) to test for file-drawer biases

##### 11 Discussion of the possibility of publication bias based on meta-regression results

##### 12 Discuss publication bias with reference to the study by [Clements et al. (2022)](https://doi.org/10.1371/journal.pbio.3001511) 




