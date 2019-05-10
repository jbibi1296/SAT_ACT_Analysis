# Problem Statement
#### _**Through analyzing the 2017 & 2018 SAT/ACT data, we would like to increase the SAT Participation percentage in 1 specific state.**_
# Executive Summary
- Framing the problem
  - After creating this problem statement I crafted my Starter Hypothesis which was **_"The more a state participates in a test, the lower its average test score will be. "_**
- Data Collection
  - I started to collect the data from multiple sources. 2017 data was given to us from GA and the 2018 data was given to us from Thomas Ludlow. 
- Data Analyze
  - I analyzed the data and identified some incorrect values, incorrect data types, unnecessary rows, and misspelled strings.
- Data Cleaning
  - I fixed all of the imperfections that I found in the 'Data Analyze' phase.
(I would repeat these 2 stages until I finally acceoted my data as being "clean")
- Exploratory Data Analysis
  - I Started creating tables:
    - To view the top 5/ bottom 5 states in each category
    - Found some interesting insights about many states and the relationship between their participation rates and their average test scores
  - Heatmap
    - This Heatmap gave me a quick overall picture of all of the correlations and how strong/weak they are and also in which direction the correlations are
    - I was able to see how strong of a negative correlation there was between a test's participation rate and it's overall average grade by state.
  - Histograms & Distribution Plots
    - These charts were created to see if the sitributions are normal and a safe representation of the total population
    - All of these charts were far from normal and most of them were bimodal
      - This shows how there are 2 different populations that are split based on an outside factor
        - This factor was that most states either focus on the SAT or ACT and not both
  - Correlation & Regression Tables
    - There charts were able to show me what the heatmap was saying but in a more detailed and focused visual.
  - Box Plots
    - There were to demonstrate central tendency and spread in variables
    - Similar to histograms but better able to identify if there are  clear outliers or differences in IQR...


# Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|column name|int/float/object|ACT/SAT|This is an example| 
|State|object|ACT/SAT|The state that the tests were taken in|
|2017_ACT_Participation|float|ACT|The percentage of the state's eligible population's participation in taking the ACT for 2017|
|2017_ACT_English|float|ACT|The state's average grade on the English section of the ACT for 2017 (Between 1-36)|
|2017_ACT_Math|float|ACT|The state's average grade on the Math section of the ACT for 2017 (Between 1-36)|
|2017_ACT_Reading|float|ACT|The state's average grade on the Reading section of the ACT for 2017 (Between 1-36)|
|2017_ACT_Science|float|ACT|The state's average grade on the Science section of the ACT for 2017 (Between 1-36)|
|2017_ACT_Composite|float|ACT|The state's average composite ACT score for 2017. (Add all 4 sections and divide by 4. Between 1-36)|
|2017_SAT_Participation|float|SAT|The percentage of the state's eligible population's participation in taking the SA for 2017T|
|2017_SAT_Math|int|SAT|The state's average grade on the Math section of the SAT for 2017 (Between 200-800)|
|2017_SAT_Reading|int|SAT|The state's average grade on the Evidence-Based Reading and Writing section of the SAT for 2017 (Between 200-800)|
|2017_SAT_Total|int|SAT|The state's average total grade on the SAT for 2017. (Add the 2 sections to get final grade. Between 400-1600)|
|2018_ACT_Participation|float|ACT|The percentage of the state's eligible population's participation in taking the ACT for 2018|
|2018_ACT_Composite|float|ACT|The state's average composite ACT score for 2018. (Add all 4 sections and divide by 4. Between 1-36)|
|2018_SAT_Participation|float|SAT|The percentage of the state's eligible population's participation in taking the SAT for 2018|
|2018_SAT_Math|int|SAT|The state's average grade on the Math section of the SAT for 2018 (Between 200-800)|
|2018_SAT_Reading|int|SAT|The state's average grade on the Evidence-Based Reading and Writing section of the SAT for 2018 (Between 200-800)|
|2018_SAT_Total|int|SAT|The state's average total grade on the SAT for 2018. (Add the 2 sections to get final grade. Between 400-1600)|

# Detailed conclusion and recommendations
- 3 states stuck out to me because of their participation rates
  - Colorado
    - Colorado signed a contract to move the state's requirement from the ACT to the SAT 
      - Colorado went from 100% ACT participation and 30% SAT participation in 2017 to 11% ACT participation and 100% SAT participation in 2018
  - Minnesota
    - Minnesota has 100% ACT participation and 3% SAT participation in 2017 and  99% ACT participation and 4% SAT participation in 2018
    - The highest SAT scores in 2017 AND 2018
  - Nebraska
    - Nebraska has a contract with the ACT that requires all students to take the ACT in order to graduate.
    - This contract gives Nebrask a discount on the SAT of around 15% 
      - Nebraska also offers free tests to students from lower-income families
- I focused on one state that I felt is the best opportunity for the College Board
  - Minnestoa has an extremely low SAT participation rate and tha SAT has an extremely large opportunity to grow in this state.
  - Minnesota has 100% participation on the ACT but without any state contracts tying the state to this test.
  - The College Board can approach this states Educational Board and offer a contract to require the SAT or at leats puch it and offer a minimal discount.
  - This discount is really a game-changer to students and will definitely raise the SAT participation rate.
  - Additionally, Minnesota currently has the top SAT average score out of all states so this can give the extra motivation for students to feel confident in taking the SAT in this state.
  
#### Data Sources
https://www.edweek.org/ew/section/multimedia/states-require-students-take-sat-or-act.html
https://www.cde.state.co.us/assessment/coloradosat