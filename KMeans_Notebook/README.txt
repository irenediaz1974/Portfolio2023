This is my taks for the course "Foundations of Data Science: K-means Clustering in Python"
This course has been extremely motivating and interesting for me, I recommend it!!!!

Analyzing Banknote_authentication dataset

In the scatter, despite the fact that there is dispersion, I can observe 3 regions in which the data can be organized. I think it is possible to apply kmeans.
 I actually spent more than 1.5 hr for analysis, found the outliers count a bit confusing ( using count_values on the dataset for x,y  <  than 2 times standard deviation), results are 15 for V1 and 17 fo V2, but visually I can't substantiate these numbers  .
I sorted a dataset, normalized with the max-min method, plotted a Boxplot , and tried to find otliers.  I really found the dataset describe function useful dataset.describe(), these are the values for normed data:

                       V1                          V2

count      1372.000000       1372.000000

mean      0.539114                 0.587301

std          0.205003                  0.219611

min        0.000000                 0.000000

25%      0.379977                  0.451451

50%      0.543617                 0.602168

75%      0.711304                 0.770363

max       1.000000               1.000000  

