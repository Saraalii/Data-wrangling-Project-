# Data-wrangling-Project-

Twitter_Wrangling

First dataset which is the twitter archive enhanced, I assessed it and I found the following quality problems:

• Tweet_id types are int and they should be a string

• Removing tweets that are not original ( the retweets )

• Changing the timestamp data type from string to date time type

• Create a column for dogs

• Fixing the missing values in the expanded_urls

# For the second dataset we have which is image predictions.tsv and after assessing it, I found the following problems:

• Duplicated URLS in the jpg_url columns

• Tweet_id data type isn’t correct and it should be string

• Notice some useless underscores in the p1,p2 and p3 columns instead of spaces

• Fixing the capital letters, and replacing them with small letters

For the third dataset which is the tweets json file and what I did with the data is:

• Renaming the Id column so we can merge it later

• Dropping the unwanted columns

• Fixing the tweet_id

# For tidiness problems :

• Create one column for dogs, and drop the old dogs columns

• And combining and merging the 3 datasets because they havethe same tweet id. After assessing the datasets that I have, moved on to the last step which is

cleaning the data sets:

I created a copy of each data frame and renamed them

Also checked the data type information and started to deal with duplicates

Fixed all the quality problems using : pd.to_datetime, drop, astype(‘str’),replace, rename,

And lastly after cleaning and fixing the quality problems and the tidiness problems, we merge the 3 datasets together and we will store it to a csv file with the name df_main
