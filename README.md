# School_District_Analysis

### Overview of the school district analysis: Explain the purpose of this analysis.

A school district asked for help to create informative charts using different methods to show differnet outcomes of the school district. The main analysis focused on the performance of math and reading scores in different ways for use in a board meeting to help make critical decisions. However, after the school board reviewed the data, it was determined that the data there was some inconsistency with the data and it was determined we would remove the data from the original source and re-run the outcombs to pinpoint the discrepancy. 

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.

## How is the district summary affected?

In the original analysis, Thomas High School started with a 91% overall passing rate, which was a concern to the school board as being too high. 

After calculating the total number of 10th - 12th grade students as the new denominator, the rest of the testing data was adjusted accordingly.

*Original

<img width="973" alt="original" src="https://user-images.githubusercontent.com/105955544/178926225-b08f203e-6d02-4388-87c9-9e9df5ce6e02.png">

*Adjusted

<img width="939" alt="Adjusted" src="https://user-images.githubusercontent.com/105955544/178926922-a059d1bd-c1c3-4593-9ce5-33db31261caf.png">

## How is the school summary affected?

In the original analysis, Thomas High School started with a 91% overall passing rate, which was a concern to the school board as being too high. 

After calculating the total number of 10th - 12th grade students as the new denominator, the rest of the testing data was adjusted accordingly.

![image](https://user-images.githubusercontent.com/105955544/178925243-1270ff26-5ec3-4caf-9776-88fa9e719ef5.png)

## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

In the original analysis, Thomas High School ranked 2nd in the district raising red flags with the school board.

After adjusting the 9th grade data, Thomas High School ranked in the exact middle of 15 campuses at 8th from the bottom.


## How does replacing the ninth-grade scores affect the following:


##  Math and reading scores by grade

The original analysis, Thomas High School had 83.6 math average and 83.7 reading average for the 9th grade tests. Now the scores have been 

replaced with null values and shows up in Python programming as NaN in the following charts.

<img width="313" alt="math" src="https://user-images.githubusercontent.com/105955544/178928245-e4018187-878d-43ac-9c20-aa679c6ed254.png">

<img width="500" alt="Screen Shot 2022-07-14 at 12 36 28 AM" src="https://user-images.githubusercontent.com/105955544/178928260-4d7f1296-fe92-465a-884a-fff37ceaf160.png">


## Scores by school spending

Thomas High School falls in the $630-$644/student spending range. However, the hundredths place was needed to see the nominal changes

<img width="674" alt="Scoresbyspending" src="https://user-images.githubusercontent.com/105955544/178924550-552905c2-5ab0-4f52-b475-4626c1be6221.png">

## Scores by school size

Thomas High School is defined as a medium sized school. The hundredths place was needed to see the nominal changes.

<img width="973" alt="Scoresbyschoolsize" src="https://user-images.githubusercontent.com/105955544/178925017-b65d12e3-61d8-4e10-9f84-7ed0000896ad.png">



### Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

* The overall passing rate for Thomas High School changed dramatically from 91% to 65%.

*Thomas High School's ranking dropped from 2nd to 8th in the district of 15 campuses.

* Data at the grade level will now show as "NaN" in reports for the 9th grade students at Thomas High School

* In addition to the overall passing rate, the campus math and reading averages and passing percentages all saw shifts.



