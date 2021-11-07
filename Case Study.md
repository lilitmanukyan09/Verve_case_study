# Verve case study

![Data_science](http://recoverydecisionscience.com/wp-content/uploads/2016/03/RDSDataProductsWebHeader.jpg)

## The following are potential problems that may arise with the dataset while building the Machine Learning algorithm
  * **device_name:** 1.	Device name could be a good predictor of the gender if we have a list of all names in the world/target countries with their corresponding genders. However, the field of device name has 60% of the values missing, which makes it difficult to fill the missing data, as it is not numeric and couldn’t be filled with statistical techniques like median, mean, mode etc.
  * **app_category and ad_category:** Around 1.8% of the app_category and ad_category fields is NAN. As it is a small percentage, it can be excluded from the dataset
  * **app_category and ad_category:** These features are represented as strings, while they should be converted to categories. One hot encoding technique will enable encoding it to numbers before we can fit and evaluate a model.
