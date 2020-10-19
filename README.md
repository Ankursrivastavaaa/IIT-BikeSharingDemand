# IIT-BikeSharingDemand
Forecast use of a city bikeshare system

You are provided hourly rental data spanning two years (Data (training and test) available here). The training set is
comprised of the first 19 days of each month, while the test set is the 20th to the end of the month. You must predict
the total count of bikes rented during each hour covered by the test set, using only information available prior to the
rental period. Fit a Poisson regression model to the count data (output). Treat year, month, weekday, hour, holiday,
weather, atemp, humidity, windspeed etc. as input features that are combined linearly to determine the rate
parameter of the Poisson distribution. Create a 80-20 split of the train data into training, and validation.
1) Explain maximum likelihood estimation in poisson regression and derive the loss function which is
used to estimate the parameters.
2) Find statistics of the dataset like mean count per year, month etc.
3) Plot count against any 5 features.
4) Apply L1 and L2 norm regularization over weight vectors, and find the best hyper-parameter
settings for the mentioned problem using validation data and report the accuracy on test data for
no regularization, L1 norm regularization and L2 norm regularization.
5) Determine most important features determining count of bikes rented.
