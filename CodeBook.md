## Code Book

For the provided UCI HAR Dataset the following vars are set from run_analysis.R.  See the [README](README.md) for additional details.

### Tidy Mean

A data.table named `tidy.mean` is set with the following columns.  All units are maintained from the original data set. A file named tidy.mean.txt is written from run_analysis.R.

| column       | description                                              | type    |
| ------------ | -------------------------------------------------------- | ------- |
| Subject      | Identifier of the subject                                | integer |
| Activity     | Label of the activity                                    | factor  |


### Tidy

A data.table named `tidy` is set with the following columns.  All units are maintained from the original data set. A file named tidy.txt is written from run_analysis.R.

| Column                       | Original Name               |
| ---------------------------- | --------------------------- |
| Activity                     |                             |
| Subject                      |                             |
| timeBodyAccelerometer-mean()-X          | tBodyAcc-mean()-X           |
| timeBodyAccelerometer-mean()-Y          | tBodyAcc-mean()-Y           |
| timeBodyAccelerometer-mean()-Z          | tBodyAcc-mean()-Z           |
| timeBodyAccelerometer-std()-X           | tBodyAcc-std()-X            |
| timeBodyAccelerometer-std()-Y           | tBodyAcc-std()-Y            |
| timeBodyAccelerometer-std()-Z           | tBodyAcc-std()-Z            |
| timeGravityAccelerometer-mean()-X       | tGravity-mean()-X        |
| timeGravityAccelerometer-mean()-Y       | tGravity-mean()-Y        |
| timeGravityAccelerometer-mean()-Z       | tGravity-mean()-Z        |
| timeGravityAccelerometer-std()-X        | tGravityAccr-std()-X         |
| timeGravityAccelerometer-std()-Y        | tGravityAcc-std()-Y         |
| timeGravityAccelerometer-std()-Z        | tGravityAcc-std()-Z         |
| timeBodyAccelerometerJerk-mean()-X      | tBodyAccJerk-mean()-X       |
| timeBodyAccelerometerJerk-mean()-Y      | tBodyAccrJerk-mean()-Y       |
| timeBodyAccelerometerJerk-mean()-Z      | tBodyAccJerk-mean()-Z       |
| timeBodyAccelerometerJerk-std()-X       | tBodyAccJerk-std()-X        |
| timeBodyAccelerometerJerk-std()-Y       | tBodyAccJerk-std()-Y        |
| timeBodyAccelerometerJerk-std()-Z       | tBodyAccJerk-std()-Z        |
| timeBodyGyroscope-mean()-X         | tBodyGyro-mean()-X          |
| timeBodyGyroscope-mean()-Y         | tBodyGyro-mean()-Y          |
| timeBodyGyroscope-mean()-Z         | tBodyGyro-mean()-Z          |
| timeBodyGyroscope-std()-X          | tBodyGyro-std()-X           |
| timeBodyGyroscope-std()-Y          | tBodyGyro-std()-Y           |
| timeBodyGyroscope-std()-Z          | tBodyGyro-std()-Z           |
| timeBodyGyroscopeJerk-mean()-X     | tBodyGyroJerk-mean()-X      |
| timeBodyGyroscopeJerk-mean()-Y     | tBodyGyroJerk-mean()-Y      |
| timeBodyGyroscopeJerk-mean()-Z     | tBodyGyroJerk-mean()-Z      |
| timeBodyGyroscopeJerk-std()-X      | tBodyGyroJerk-std()-X       |
| timeBodyGyroscopeJerk-std()-Y      | tBodyGyroJerk-std()-Y       |
| timeBodyGyroscopeJerk-std()-Z      | tBodyGyroJerk-std()-Z       |
| timeBodyAccelerometerMagnitude.Mean         | tBodyAccelerometerMage-mean()          |
| timeBodyAccelerometerMagnitude.Std          | tBodyAccelerometerMage-std()           |
| timeGravityAccelerometerMagnitude.Mean      | tGravityAccelerometerMag-mean()       |
| timeGravityAccelerometerMagnitude.Std       | tGravityAccelerometerMag-std()        |
| timeBodyAccelerometerJerkMagnitude.Mean     | tBodyAccelerometerJerkMag-mean()      |
| timeBodyAccelerometerJerkMagnitude.Std      | tBodyAccelerometerJerkMag-std()       |
| timeBodyGyroscopeMagnitude.Mean        | tBodyGyroMag-mean()         |
| timeBodyGyroscopeMagnitude.Std         | tBodyGyroMag-std()          |
| timeBodyGyroscopeJerkMagnitude.Mean    | tBodyGyroJerkMag-mean()     |
| timeBodyGyroscopeJerkMagnitude.Std     | tBodyGyroJerkMag-std()      |
| frecuencyBodyAccelerometer-mean()-X           | fBodyAcc-mean()-X           |
| frecuencyBodyAccelerometer-mean()-Y           | fBodyAcc-mean()-Y           |
| frecuencyBodyAccelerometer-mean()-Z           | fBodyAcc-mean()-Z           |
| frecuencyBodyAccelerometer-std()-X            | fBodyAcc-std()-X            |
| frecuencyBodyAccelerometer-std()-Y            | fBodyAcc-std()-Y            |
| frecuencyBodyAccelerometer-std()-Z            | fBodyAcc-std()-Z            |
| frecuencyBodyAccelerometerJerk-mean()-X       | fBodyAccJerk-mean()-X       |
| frecuencyBodyAccelerometerJerk-mean()-Y       | fBodyAccJerk-mean()-Y       |
| frecuencyBodyAccelerometerJerk-mean()-Z       | fBodyAccJerk-mean()-Z       |
| frecuencyBodyAccelerometerJerk-std()-X        | fBodyAccJerk-std()-X        |
| frecuencyBodyAccelerometerJerk-std()-Y        | fBodyAccJerk-std()-Y        |
| frecuencyBodyAccelerometerJerk-std()-Z        | fBodyAccJerk-std()-Z        |
| frecuencyBodyGyroscope-mean()-X          | fBodyGyro-mean()-X          |
| frecuencyBodyGyroscope-mean()-Y          | fBodyGyro-mean()-Y          |
| frecuencyBodyGyroscope-mean()-Z          | fBodyGyro-mean()-Z          |
| frecuencyBodyGyroscope-std()-X           | fBodyGyro-std()-X           |
| frecuencyBodyGyroscope-std()-Y           | fBodyGyro-std()-Y           |
| frecuencyBodyGyroscope-std()-Z           | fBodyGyro-std()-Z           |
| frecuencyBodyAccelerometerMagnitude.Mean          | fBodyAccMag-mean()          |
| frecuencyBodyAccelerometerMagnitude.Std           | fBodyAcceMag-std()           |
| frecuencyBodyAccelerometerJerkMagnitude.Mean  | fBodyBodyAccJerkMag-mean()  |
| frecuencyBodyAccelerometerJerkMagnitude.Std   | fBodyBodyAccJerkMag-std()   |
| frecuencyBodyGyroscopeMagnitude.Mean     | fBodyBodyGyroMag-mean()     |
| frecuencyBodyGyroscopeMagnitude.Std      | fBodyBodyGyroMagnitude-std()      |
| frecuencyBodyGyroscopeJerkMagnitude.Mean | fBodyBodyGyroJerkMag-mean() |
| frecuencyBodyGyroscopeJerkMagnitude.Std  | fBodyBodyGyroJerkMag-std()  |

