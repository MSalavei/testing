# CodeBook for FinalData.txt

## Data Description

The dataset contains measurements from the accelerometers of the Samsung Galaxy S smartphone.

## Variables

- `subject`: Identifier for the subject who carried out the experiment.
- `activity`: Activity performed by the subject.
- Measurements: Mean and standard deviation for each measurement, appropriately labeled.

## Transformations

1. Merged the training and test sets to create one dataset.
2. Extracted only the measurements on the mean and standard deviation for each measurement.
3. Used descriptive activity names to name the activities in the dataset.
4. Labeled the dataset with descriptive variable names.
5. Created a second, independent tidy dataset with the average of each variable for each activity and each subject.

## Notes

- The dataset is sorted by `subject` and `activity`.
- Variable names are descriptive and follow the conventions for tidy data.