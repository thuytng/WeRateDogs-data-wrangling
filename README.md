# WeRateDogs-data-wrangling

The purpose of this project is to assess and clean dirty data from the WeRateDogs twitter archive.

## View

To view the project, click wrangle-act.ipynb

## Data

The data for this project comes from 3 places.

1. Twitter archive data (twitter-archive-enhanced.csv)
2. [Twitter API](https://developer.twitter.com/en/docs)
3. [Image predictions from Udacity server](https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv): this link provides predictions for what dog breed is in the image of each tweet. This data is downloaded and stored in image-predictions.tsv 

All this data is then cleaned, merged, and stored into twitter-archive-master.csv