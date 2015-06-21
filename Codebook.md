

Processing  Script                                                                                              
The run_analysis.R sript performs the 5 steps described in the course project's definition.
- Raw data is read in 
- Similar data is combined before the data is rbind to create a full subject_data.
- Mean and standard deviation columns are extracted.                                                                      
- Activities names are matched to the respective activities ids.
- A final set of tidy data is created by taking the average measurs.


Variables
- x_train, y_train, x_test, y_test, subject_train and subject_test basically reads the data from the downloaded files.   
- x_data, y_data are intermediate processing data
- subject_data combines all the raw dataset
- features and activities are given by the data inputs as definition files
- mean_and_std_features are selected columns from the raw data                                                          
- all_data combines the 4 steps to give a processed dataset                                                             
- averages_data is obtained by taking column means of all_data, except for activity and subject                         



