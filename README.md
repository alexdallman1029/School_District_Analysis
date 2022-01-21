# School District Analysis
Using Python, Pandas, and Jupyter Notebook to analyze test scores in a school district
## Overview
The purpose of this analysis was to remove dishonest school data reported from a dataset containing a multitude of information, and then run a detailed analysis on the data once it has been cleaned. The DataFrame below is a summary representing the District after replacing the ninth graders' scores with NaN.This report will be presented to the school board to inform future decision-making and funding for schools in that district.


## Results
### Process
The analysis was written in python using numpy and pandas in jupyter notebook. You can see the code [here](https://github.com/alexdallman1029/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb). Data used came from the following data sets: [school_data_complete.csv](https://github.com/alexdallman1029/School_District_Analysis/blob/main/Resources/schools_complete.csv) and [students_data_complete.csv](https://github.com/alexdallman1029/School_District_Analysis/blob/main/Resources/students_complete.csv).

### Results 

Thomas High School's ninth grade had their scores replaced with NaN, which affected the district results, school results, comparative results with other schools, including math and reading Math and reading scores by grade, scores by school spending, scores by school size, and scores by school type.

#### Effect on District Summary
The overall passing percentage for the entire district fell to 64.9% from 65%.
The math passing percentage for the entire distrcit fell to 74.8%	from 75%.
The reading passing percentage for the entire distrcit fell	to 85.7% from 86%.
#### Effect on School Summary
The overall passing percentage for Thomas High School fell to 65%.
The math passing percentage for the school fell to %.
The reading passing percentage for the school fell to %. 
#### Thomas High School’s Performance Relative to Other Schools
Thomas High School fell to the bottom-five schools, whereas it was previously in the top-five schools by overall passing percentage.
#### Math and Reading Scores by Grade

#### Scores by School Spending

#### Scores by School Size

#### Scores by School Type

## Summary

While the omission of Thomas High School's ninth-grade scores was not ideal, it was the best option to exclude the dishonest data. The distinction between dishonest and honest data could not be made; therefore, all of the ninth-grade data for Thomas High School was removed. Relacing Thomas High School's ninth-grade student scores with NaN caused the school's overall passing percentages to significantly decrease. The entire district's overall passing percentage, as well as average math and reading scores decreased. Thomas High School was no longer in the top five for the district. 
