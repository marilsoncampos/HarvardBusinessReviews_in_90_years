
# History of the United States through the lens of Harvard Business Review Articles (1922 - 2012) 

[![HBR 90 years visualization](/term_map_clean2.png "HBR 90 years visualization")](/term_map_clean2.png)

-> [Open the the high def picture](/term_map_clean2.png)  

A text mining project for [HBR articles in 90 years](https://www.kaggle.com/c/harvard-business-review-vision-statement-prospect/).

In this project, I use a multivariate technique called [Correspondence Analysis (CA)](https://en.wikipedia.org/wiki/Correspondence_analysis). Given a term-year matrix that describe how many times a term j have been mentioned in year (or group of years) j, CA produces a set of orthognal components (just like Principal Component Analysis PCA) that capture the "driving forces" of variance in a dataset.

How to read the plot ?

The plot shows a representative subset of words across all years. You can imagine a spring between each word and all the years. The strenth of the spring is weighted by the number of times a word has been mentioned in that year. This way, words associated with 30's will pull those years while words associated with recent years will pull in a different direction. The plot approximates this sort of image.

More technical describtions can be found in Wikipedia:

- https://en.wikipedia.org/wiki/Correspondence_analysis
