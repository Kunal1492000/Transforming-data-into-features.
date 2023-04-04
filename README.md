# Transforming-data-into-features.
You are a data scientist at a clothing company and are working with a data set of customer reviews. This dataset is originally from Kaggle and has a lot of potential for various machine learning purposes. You are tasked with transforming some of these features to make the data more useful for analysis. To do this, you will have time to practice the following:

Transforming categorical data
Scaling your data
Working with date-time features
Let’s get started!






OUTCOMES .....

Index(['clothing_id', 'age', 'review_title', 'review_text', 'recommended',
       'division_name', 'department_name', 'review_date', 'rating'],
      dtype='object')
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 5000 entries, 0 to 4999
Data columns (total 9 columns):
clothing_id        5000 non-null int64
age                5000 non-null int64
review_title       4174 non-null object
review_text        4804 non-null object
recommended        5000 non-null bool
division_name      4996 non-null object
department_name    4996 non-null object
review_date        5000 non-null object
rating             5000 non-null object
dtypes: bool(1), int64(2), object(6)
memory usage: 317.5+ KB
None
True     4166
False     834
Name: recommended, dtype: int64
True     4166
False     834
Name: recommended, dtype: int64
Loved it     2798
Liked it     1141
Was okay      564
Not great     304
Hated it      193
Name: rating, dtype: int64
Series([], Name: rating, dtype: int64)
Tops        2196
Dresses     1322
Bottoms      848
Intimate     378
Jackets      224
Trend         28
Name: department_name, dtype: int64
Index(['clothing_id', 'age', 'review_title', 'review_text', 'recommended',
       'division_name', 'department_name', 'review_date', 'rating',
       'recommmended', 'Bottoms', 'Dresses', 'Intimate', 'Jackets', 'Tops',
       'Trend'],
      dtype='object')
