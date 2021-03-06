Data_final is a dataframe of 67 variables and 180 observations.


30 subjects (“subject” variable) performed 6 activities (“activity” variable) and had different body accelerations and gravity recorded in 3 dimensions (x,y,z). I calculated the mean for all the gravity, acceleration measurements for each subject and each activity.


Variables: each variable represents the mean for that all measurements for each subject in that activity.
Units are radons/second

[1] "subject"                   "activity"                 
 [3] "tBodyAcc_mean_X"           "tBodyAcc_mean_Y"          
 [5] "tBodyAcc_mean_Z"           "tBodyAcc_std_X"           
 [7] "tBodyAcc_std_Y"            "tBodyAcc_std_Z"           
 [9] "tGravityAcc_mean_Y"        "tGravityAcc_mean_Z"       
[11] "tGravityAcc_std_X"         "tGravityAcc_std_Y"        
[13] "tGravityAcc_std_Z"         "tBodyAccJerk_mean_X"      
[15] "tBodyAccJerk_mean_Y"       "tBodyAccJerk_mean_Z"      
[17] "tBodyAccJerk_std_X"        "tBodyAccJerk_std_Y"       
[19] "tBodyAccJerk_std_Z"        "tBodyGyro_mean_X"         
[21] "tBodyGyro_mean_Y"          "tBodyGyro_mean_Z"         
[23] "tBodyGyro_std_X"           "tBodyGyro_std_Y"          
[25] "tBodyGyro_std_Z"           "tBodyGyroJerk_mean_X"     
[27] "tBodyGyroJerk_mean_Y\n"    "tBodyGyroJerk_mean_Z"     
[29] "tBodyGyroJerk_std_X"       "tBodyGyroJerk_std_Y"      
[31] "tBodyGyroJerk_std_Z"       "tBodyAccMag_mean"         
[33] "tBodyAccMag_std"           "tGravityAccMag_mean"      
[35] "tGravityAccMag_std"        "tBodyAccJerkMag_mean"     
[37] "tBodyAccJerkMag_std"       "tBodyGyroMag_mean"        
[39] "tBodyGyroMag_std"          "tBodyGyroJerkMag_mean"    
[41] "tBodyGyroJerkMag_std"      "fBodyAcc_mean_X"          
[43] "fBodyAcc_mean_Y"           "fBodyAcc_mean_Z"          
[45] "fBodyAcc_std_X"            "fBodyAcc_std_Y"           
[47] "fBodyAcc_std_Z"            "fBodyAccJerk_mean_X"      
[49] "fBodyAccJerk_mean_Y"       "fBodyAccJerk_mean_Z"      
[51] "fBodyAccJerk_std_X"        "fBodyAccJerk_std_Y"       
[53] "fBodyAccJerk_std_Z"        "fBodyGyro_mean_X"         
[55] "fBodyGyro_mean_Y"          "fBodyGyro_mean_Z"         
[57] "fBodyGyro_std_X"           "fBodyGyro_std_Y"          
[59] "fBodyGyro_std_Z"           "fBodyAccMag_mean"         
[61] "fBodyAccMag_std"           "fBodyBodyAccJerkMag_mean" 
[63] "fBodyBodyAccJerkMag_std"   "fBodyBodyGyroMag_mean"    
[65] "fBodyBodyGyroMag_std"      "fBodyBodyGyroJerkMag_mean"
[67] "fBodyBodyGyroJerkMag_std"


1.  subject                  : integer, range 1-30 
 2. activity                 : character:  "laying" "sitting" "standing" "walking" “walking_upstairs” “walking_downstairs”
 3. tBodyAcc_mean_X          : numeric,  range: -0.040513953 -0.001308288
 4. tBodyAcc_mean_Y          : numeric, range -0.15251390 -0.07537847
 5. tBodyAcc_mean_Z          : numeric, range: -0.9960686  0.6269171
 6. tBodyAcc_std_X           : numeric, range -0.9902409  0.6169370
 7. tBodyAcc_std_Y           : numeric, range -0.9876587  0.6090179
 8. tBodyAcc_std_Z           : numeric, range -0.9966864  0.6091768
 9. tGravityAcc_mean_Y       : numeric, range -0.4950887  0.9578730
 10. tGravityAcc_mean_Z       : numeric, range -0.9967642 -0.8295549
11. tGravityAcc_std_X        : numeric, range -0.9942476 -0.6435784
12. tGravityAcc_std_Y        : numeric, range -0.9909572 -0.6101612
 13. tGravityAcc_std_Z        : numeric, range -0.9968035 -0.8323221
 14. tBodyAccJerk_mean_X      : numeric, range -0.03868721  0.05681859
 15. tBodyAccJerk_mean_Y      : numeric, range -0.06745839  0.03805336
 16. tBodyAccJerk_mean_Z      : numeric, range -0.9946045  0.5442730
 17. tBodyAccJerk_std_X       : numeric, range -0.9895136  0.3553067
 18. tBodyAccJerk_std_Y       : numeric, range -0.99328831  0.03101571
 19. tBodyAccJerk_std_Z       : numeric, range -0.9952548  0.5499092
 20. tBodyGyro_mean_X         : numeric, range -0.20420536  0.02747076
 21. tBodyGyro_mean_Y         : numeric, range -0.0724546  0.1791021
 22. tBodyGyro_mean_Z         : numeric, range -0.9942766  0.2676572
 23. tBodyGyro_std_X          : numeric, range -0.9942105  0.4765187
 24. tBodyGyro_std_Y          : numeric, range -0.9855384  0.5648758
 25. tBodyGyro_std_Z          : numeric, range -0.9944308  0.2611970
 26. tBodyGyroJerk_mean_X     : numeric, range -0.07680899 -0.01320228
 27. tBodyGyroJerk_mean_Y: numeric, range -0.092499853 -0.006940664
 28. tBodyGyroJerk_mean_Z     : numeric, range -0.9965425  0.1791486
 29. tBodyGyroJerk_std_X     : numeric, range -0.9970816  0.2959459
 30. tBodyGyroJerk_std_Y      : numeric, range -0.9953808  0.1932065
 31. tBodyGyroJerk_std_Z      : numeric, range -0.9965631  0.2144223
 32. tBodyAccMag_mean         : numeric, range -0.9864645  0.4284059
 33. tBodyAccMag_std          : numeric, range -0.9881353  0.2745010
 34. tGravityAccMag_mean      : numeric, range -0.9864645  0.4284059
 35. tGravityAccMag_std       : numeric, range -0.9881353  0.2745010
 36. tBodyAccJerkMag_mean     : numeric, range -0.9946469  0.4506121
 37. tBodyAccJerkMag_std      : numeric, range -0.9948159  0.4049489
 38. tBodyGyroMag_mean        : numeric, range -0.9813727  0.2999760
 39. tBodyGyroMag_std         : numeric, range -0.9787018  0.3779637
 40. tBodyGyroJerkMag_mean    : numeric, range -0.9976661  0.2501732
 41. tBodyGyroJerkMag_std     : numeric, range -0.9978948  0.1146086
 42. fBodyAcc_mean_X          : numeric, range -0.9890343  0.5241877
 43. fBodyAcc_mean_Y          : numeric, range -0.9894739  0.2807360
 44. fBodyAcc_mean_Z          : numeric, range -0.9966046  0.6585065
 45. fBodyAcc_std_X           : numeric, range -0.9906804  0.5601913
 46. fBodyAcc_std_Y           : numeric, range -0.9872248  0.6871242
 47. fBodyAcc_std_Z           : numeric, range -0.9957068  0.6337999
 48. fBodyAccJerk_mean_X      : numeric, range -0.9893988  0.2767169
 49. fBodyAccJerk_mean_Y      : numeric, range -0.9920184  0.1577757
 50. fBodyAccJerk_mean_Z      : numeric, range -0.9950738  0.4768039
 51. fBodyAccJerk_std_X       : numeric, range -0.9904681  0.3497713
 52. fBodyAccJerk_std_Y       : numeric, range -0.993107760 -0.006236475
 53. fBodyAccJerk_std_Z       : numeric, range -0.9933974  0.6642578
 54. fBodyGyro_mean_X         : numeric, range -0.9940255  0.3288170
 55. fBodyGyro_mean_Y         : numeric, range -0.9859578  0.4924144
 56. fBodyGyro_mean_Z         : numeric, range -0.9946522  0.1966133
 57. fBodyGyro_std_X          : numeric, range -0.9943531  0.6462336
 58. fBodyGyro_std_Y          : numeric, range -0.9867253  0.5224542
 59. fBodyGyro_std_Z          : numeric, range -0.9943107  0.3811366
 60. fBodyAccMag_mean         : numeric, range -0.9876485  0.1786846
 61. fBodyAccMag_std          : numeric, range -0.9859826  0.4887390
 62. fBodyBodyAccJerkMag_mean : numeric, range -0.9943667  0.3163464
 63. fBodyBodyAccJerkMag_std  : numeric, range -0.9925551  0.4788837
 64. fBodyBodyGyroMag_mean    : numeric, range -0.9814688  0.2366597
 65. fBodyBodyGyroMag_std     : numeric, range -0.9836433  0.3622492
 66. fBodyBodyGyroJerkMag_mean: numeric, range -0.9975852  0.2878346
 67. fBodyBodyGyroJerkMag_std : numeric, range -0.9973610  0.3513626


Study design:
I did not participate in the study design. I analyzed some of the data given in the project. 

Data analysis
Please see README.txt for all details. 
Initially all test files were put together using cbind (x_test, y_test, tsubject_test). Same for train files. The test and train data were brought together using rbind. The first 3 columns were named “subject”, “activity” and “measurement”. I only extracted the variables that included “mean()” or “std()” in their name.

Activities were assigned to walking, walking_upstairs, walking_downstairs, sitting, standing or laying as per the code found in activity_labels.txt.

Then I melted the extracted data keeping “subject” and “activity” as id variables and having the other variable as measure variables (“measurement” variable was dropped). Using dcast , I obtained the final dataframe – “subject” and “activity” were kept and means for all other variables were calculated.
