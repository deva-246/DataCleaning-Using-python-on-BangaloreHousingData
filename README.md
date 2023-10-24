# DataCleaning-Using-python

## Missing / Null values in a dataset
1. When we say a value is missing or is null, we do not mean that the value is an empty string, such as ' ', or a zero value, such as 0 or 0.0. Missing or null means there is no value present at all. 
2. For the survey data we are looking at now, it means the person taking the survey provided no answer. When we are representing our data with a series or a dataframe, we can't simply skip missing values, they must be encoded in some way. 
3. A series with a missing value at the fifth index can't just be one value shorter. It throws off everything. Instead, we need to plug in a special value that represents a missing value so that when we perform operations on the series, nothing goes awry. 
4. For example, if we ask for the mean value of a series of values that contains some missing values, we would not want to sum all the values and then divide them by the length of the series. The length would include the missing values and throw off the mean value.
