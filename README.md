# Data-prep-in-Pandas
For this assignment you will use the reg-30-spring-2018.csv dataset.

For this assignment, load and modify the data set.

Modify the dataset as follows:

    Drop the id column.
    Replace the missing values (NA's) in the width column with the median width. (obviously, do not use the NA's to calculate the median for this replacement)
    Replace the following columns with their z-score: landings, number, and pack.
    All other columns should be left unchanged.
    If is unlikely that you will get any submit warnings if you completed this assignment correctly.
    Your submitted dataframe will have these columns: distance, height, landings, number, pack, age, usage, region, weight, item, volume, width, max, power, size, target.

For this assignment you will use the reg-30-spring-2018.csv dataset.

For this assignment, load and modify the data set.
Modify the dataset as follows:

    Add a column named density that is weight divided by volume.
    Replace the region column with dummy variables.
    Replace the item column with an index encoding value (for example 0 for the first class, 1 for the next, etc. see function encode_text_index)
    Your submitted dataframe will have these columns: id, distance, height, landings, number, pack, age, usage, weight, item, volume, width, max, power, size, target, density, region-RE-0, region-RE-1, region-RE-10, region-RE-11, region-RE-2, region-RE-3, region-RE-4, region-RE-5, region-RE-6, region-RE-7, region-RE-8, region-RE-9, region-RE-A, region-RE-B, region-RE-C, region-RE-D, region-RE-E, region-RE-F.
