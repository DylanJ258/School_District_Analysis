# School_District_Analysis

## Project Overview
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.
## Resources
* Data Source: students_complete.csv
* Software: Python 3.7.6, Jupyter Notebook

## Results
* How is the district summary affected?
    * The average math score went from 79.0 to 78.9
    * The average reading score stayed at 81.9
    * The passing math % went from 75% to 74.8%
    * The passing reading % went from 86% to 85.7%
    * The overall passing % went from 65% to 64.9%
    * <img width="568" alt="Screen Shot 2022-05-23 at 12 59 49 AM" src="https://user-images.githubusercontent.com/104036750/169753597-cf8c03fb-1f38-4f28-bb76-69e1b96bb4a3.png">
    * <img width="366" alt="Screen Shot 2022-05-23 at 12 59 35 AM" src="https://user-images.githubusercontent.com/104036750/169753625-79ca1b5d-8b9c-493e-a4e3-6aadbb3baae2.png">

* How is the school summary affected?
  * The average math score went from 83.42 to 83.35
  * The average reading score went from 83.85 to 83.89
  * The passing math % went from 93.27% to 66.9%
  * The passing reading % from 97.3% to 69.7%.
  * The overall passing % went from 90.9% to 65.1%.
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  * THS isnt a top 5 school after the scores are adjusted.
* How does replacing the ninth-grade scores affect the following:
    *Math and reading scores by grade
      * It changes the score to nan
    *Scores by school spending
    
     <img width="1019" alt="Screen Shot 2022-05-23 at 2 40 01 AM" src="https://user-images.githubusercontent.com/104036750/169768455-a4989165-6195-4f97-8c14-687dafc14e2e.png">
      
     <img width="1011" alt="Screen Shot 2022-05-23 at 2 40 32 AM" src="https://user-images.githubusercontent.com/104036750/169768551-bfe00fa6-d723-4faa-bdfe-52bb8e4b506f.png">

    *Scores by school size
    
    <img width="1006" alt="Screen Shot 2022-05-23 at 2 42 38 AM" src="https://user-images.githubusercontent.com/104036750/169768917-aab63665-4a0b-41bd-a8fa-09367b9b5621.png">
    
    <img width="1007" alt="Screen Shot 2022-05-23 at 2 43 21 AM" src="https://user-images.githubusercontent.com/104036750/169768965-76860e62-319e-4254-bd06-343042ea36b6.png">

    *Scores by school type
    
     <img width="756" alt="Screen Shot 2022-05-23 at 2 44 22 AM" src="https://user-images.githubusercontent.com/104036750/169769209-a9728106-83ac-4e9b-b5f6-d2c2597d6688.png">
      
     <img width="743" alt="Screen Shot 2022-05-23 at 2 44 59 AM" src="https://user-images.githubusercontent.com/104036750/169769242-e7e6117d-a1ff-416f-b457-8e2418b98798.png">

## Summary
* After review it seems as if there was some form of academic dishonesty
