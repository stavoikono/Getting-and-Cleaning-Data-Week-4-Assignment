# Tidy data set description

### The variables in the tidy data
Tidy data contains 180 rows and 68 columns. Each row has averaged variables for each subject and each activity.

### Only all the variables estimated from mean and standard deviation in the tidy set were kept.

* mean(): Mean value
* std(): Standard deviation

### The data were averaged based on subject and activity group.

Subject column is numbered sequentially from 1 to 30.
Activity column has 6 types as listed below.
1. WALKING
2. WALKING_UPSTAIRS
3. WALKING_DOWNSTAIRS
4. SITTING
5. STANDING
6. LAYING

### The tidy data contains 6 rows (averaged based on activity) and 69 columns (66 variables and activity labels).
1. "activitylabel"
2. "subject"
3. "activity"
4. "tBodyAcc-mean()-X"          
5. "tBodyAcc-mean()-Y"
6. "tBodyAcc-mean()-Z"
7. "tBodyAcc-std()-X"           
8. "tBodyAcc-std()-Y" 
9. "tBodyAcc-std()-Z"
10. "tGravityAcc-mean()-X"
11. "tGravityAcc-mean()-Y"
12. "tGravityAcc-mean()-Z"
13. "tGravityAcc-std()-X"        
14. "tGravityAcc-std()-Y"
15. "tGravityAcc-std()-Z"
16. "tBodyAccJerk-mean()-X"      
17. "tBodyAccJerk-mean()-Y"
18. "tBodyAccJerk-mean()-Z"
19. "tBodyAccJerk-std()-X"       
20. "tBodyAccJerk-std()-Y"
21. "tBodyAccJerk-std()-Z"
22. "tBodyGyro-mean()-X"         
23. "tBodyGyro-mean()-Y"
24. "tBodyGyro-mean()-Z"
25. "tBodyGyro-std()-X"          
26. "tBodyGyro-std()-Y" 
27. "tBodyGyro-std()-Z" 
28. "tBodyGyroJerk-mean()-X"     
29. "tBodyGyroJerk-mean()-Y"
30. "tBodyGyroJerk-mean()-Z"
31. "tBodyGyroJerk-std()-X"      
32. "tBodyGyroJerk-std()-Y"
33. "tBodyGyroJerk-std()-Z"
34. "tBodyAccMag-mean()"         
35. "tBodyAccMag-std()"
36. "tGravityAccMag-mean()"
37. "tGravityAccMag-std()"       
38. "tBodyAccJerkMag-mean()"
39. "tBodyAccJerkMag-std()"
40. "tBodyGyroMag-mean()"        
41. "tBodyGyroMag-std()"
42. "tBodyGyroJerkMag-mean()"
43. "tBodyGyroJerkMag-std()"     
44. "fBodyAcc-mean()-X"
45. "fBodyAcc-mean()-Y"
46. "fBodyAcc-mean()-Z"          
47. "fBodyAcc-std()-X"
48. "fBodyAcc-std()-Y"
49. "fBodyAcc-std()-Z"           
50. "fBodyAccJerk-mean()-X"
51. "fBodyAccJerk-mean()-Y"
52. "fBodyAccJerk-mean()-Z"      
53. "fBodyAccJerk-std()-X"
54. "fBodyAccJerk-std()-Y"
55. "fBodyAccJerk-std()-Z"       
56. "fBodyGyro-mean()-X"  
57. "fBodyGyro-mean()-Y"
58. "fBodyGyro-mean()-Z"         
59. "fBodyGyro-std()-X"
60. "fBodyGyro-std()-Y"   
61. "fBodyGyro-std()-Z"          
62. "fBodyAccMag-mean()"
63. "fBodyAccMag-std()"   
64. "fBodyBodyAccJerkMag-mean()" 
65. "fBodyBodyAccJerkMag-std()"
66. "fBodyBodyGyroMag-mean()" 
67. "fBodyBodyGyroMag-std()"     
68. "fBodyBodyGyroJerkMag-mean()" 
69. "fBodyBodyGyroJerkMag-std()"

### variable units
Activity variable is factor type.
Subject variable is integer type.
All the other variables are numeric type.
