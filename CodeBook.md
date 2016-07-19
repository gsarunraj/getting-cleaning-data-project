The original dataset was made of two main datasets, called test group and training group. In the new dataset, both test group and training group datasets were merged into a new dataset, denominated the whole dataset, which contains data from both original groups. The step-by-step procedure of the project that resulted in the whole dataset is stated in the README.md file.

Regarding the nature of each variable, some sensible changes were made in order to make the whole dataset easier to read and understand:

* In the original datasets, the measured activity was stated through it's index (1-6). In the whole dataset, the measured activity is stated by through it's own name (LAYING, STANDING, SITTING, WALKING_DOWNSTAIRS, WALKING_UPSTAIRS, WALKING). Also, the activity variable was renamed as "Activity";

* In the original datasets, the variables were depicted through a very specific code (^t, ^f, Acc, Gyro, Mag and ()). The code was broken down in the whole dataset, as follows:
  - The "^t" was changed for "time";
  - The "^f" was changed for "frequency";
  - The "Acc" was changed for "Acceleration";
  - The "Mag" was changed for "Magnitude";
  - The "Gyro" was changed for "Gyroscope";
  
* In the original datasets, there were 10299 observations in total. The whole dataset contains only the variables regarding the average of each variable for each Activity and each Subject, to a total of 180 observations.

* In the original datasets, there were 561 variables. The whole dataset only contains the variables regarding the mean or standart deviation for each measurement, to a total of 68 variables. They are:
 -  "Subject", set of subjects of the experiment, range from 1 to 30                                        
 -  "Activity", set of six activities performed by the subjects: LAYING, STANDING, SITTING, WALKING_DOWNSTAIRS, WALKING_UPSTAIRS, WALKING                                 
 -  "timeBodyAcceleration_Mean-X"                    
 -  "timeBodyAcceleration_Mean-Y"                    
 -  "timeBodyAcceleration_Mean-Z"                    
 -  "timeBodyAcceleration_Std-X"                     
 -  "timeBodyAcceleration_Std-Y"                     
 -  "timeBodyAcceleration_Std-Z"                     
 -  "timeGravityAcceleration_Mean-X"                 
 -  "timeGravityAcceleration_Mean-Y"                 
 -  "timeGravityAcceleration_Mean-Z"                 
 -  "timeGravityAcceleration_Std-X"                  
 -  "timeGravityAcceleration_Std-Y"                  
 -  "timeGravityAcceleration_Std-Z"                  
 -  "timeBodyAccelerationJerk_Mean-X"                
 -  "timeBodyAccelerationJerk_Mean-Y"                
 -  "timeBodyAccelerationJerk_Mean-Z"                
 -  "timeBodyAccelerationJerk_Std-X"                 
 -  "timeBodyAccelerationJerk_Std-Y"                 
 -  "timeBodyAccelerationJerk_Std-Z"                 
 -  "timeBodyGyroscope_Mean-X"                       
 -  "timeBodyGyroscope_Mean-Y"                       
 -  "timeBodyGyroscope_Mean-Z"                       
 -  "timeBodyGyroscope_Std-X"                        
 -  "timeBodyGyroscope_Std-Y"                        
 -  "timeBodyGyroscope_Std-Z"                        
 -  "timeBodyGyroscopeJerk_Mean-X"                   
 -  "timeBodyGyroscopeJerk_Mean-Y"                   
 -  "timeBodyGyroscopeJerk_Mean-Z"                   
 -  "timeBodyGyroscopeJerk_Std-X"                    
 -  "timeBodyGyroscopeJerk_Std-Y"                    
 -  "timeBodyGyroscopeJerk_Std-Z"                    
 -  "timeBodyAccelerationMagnitude_Mean"             
 -  "timeBodyAccelerationMagnitude_Std"              
 -  "timeGravityAccelerationMagnitude_Mean"          
 -  "timeGravityAccelerationMagnitude_Std"           
 -  "timeBodyAccelerationJerkMagnitude_Mean"         
 -  "timeBodyAccelerationJerkMagnitude_Std"          
 -  "timeBodyGyroscopeMagnitude_Mean"                
 -  "timeBodyGyroscopeMagnitude_Std"                 
 -  "timeBodyGyroscopeJerkMagnitude_Mean"            
 -  "timeBodyGyroscopeJerkMagnitude_Std"             
 -  "frequenceBodyAcceleration_Mean-X"               
 -  "frequenceBodyAcceleration_Mean-Y"               
 -  "frequenceBodyAcceleration_Mean-Z"               
 -  "frequenceBodyAcceleration_Std-X"                
 -  "frequenceBodyAcceleration_Std-Y"                
 -  "frequenceBodyAcceleration_Std-Z"                
 -  "frequenceBodyAccelerationJerk_Mean-X"           
 -  "frequenceBodyAccelerationJerk_Mean-Y"           
 -  "frequenceBodyAccelerationJerk_Mean-Z"           
 -  "frequenceBodyAccelerationJerk_Std-X"            
 -  "frequenceBodyAccelerationJerk_Std-Y"            
 -  "frequenceBodyAccelerationJerk_Std-Z"            
 -  "frequenceBodyGyroscope_Mean-X"                  
 -  "frequenceBodyGyroscope_Mean-Y"                  
 -  "frequenceBodyGyroscope_Mean-Z"                  
 -  "frequenceBodyGyroscope_Std-X"                   
 -  "frequenceBodyGyroscope_Std-Y"                   
 -  "frequenceBodyGyroscope_Std-Z"                   
 -  "frequenceBodyAccelerationMagnitude_Mean"        
 -  "frequenceBodyAccelerationMagnitude_Std"         
 -  "frequenceBodyBodyAccelerationJerkMagnitude_Mean"
 -  "frequenceBodyBodyAccelerationJerkMagnitude_Std" 
 -  "frequenceBodyBodyGyroscopeMagnitude_Mean"       
 -  "frequenceBodyBodyGyroscopeMagnitude_Std"        
 -  "frequenceBodyBodyGyroscopeJerkMagnitude_Mean"   
 -  "frequenceBodyBodyGyroscopeJerkMagnitude_Std"
