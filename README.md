# Data-Wrangling
This project is part of the data wrangling curriculum of the Data Analyst Nano degree
program of Udacity.
 <br />Using Python and different libraries I gathered data from a variety of sources and in
a variety of formats, assessed its quality and tidiness and cleaned it. This process is
called data wrangling. The data that was wrangled was the archive of Twitter user
@dog_rates, also known as WeRateDogs(twitter account that rates people’s dogs
with a humorous comment about the dog.
 <br />Libraries
 <br />The following packages(libraries) need to be installed.We can install these packages
via conda or pip.
 <br />● pandas
 <br />● NumPy
 <br />● requests
 <br />● tweepy
 <br />● json
 
 <br />__Project Details__
 <br />__The following tasks have been done:__
 <br />Data wrangling, which consists of:
          <br />●Gathering data: The 3 files twitter_archive , image_predictions and
Twitter API has been gathered using different techniques.1st file was
gathered using read_csv, for the 2nd file the image_predictions was
downloaded pragmatically using the Requests library and the 3rd file
was extracted discretely from Twitter using Twitter API.
          <br />●Assessing data- For Assessing data visual assessing and
programmatic assessing have been used. 8 Quality issues and 2 tiding
issues have been observed in the python book and
          <br /> ●Cleaning data – in this section the copies of the data sets have been
created, the data has been cleaned and the 3 copies were merged into
one clean file.
 <br />● Storing, analyzing, and visualizing your wrangled data
 <br />● Reporting data wrangling efforts data analyses and visualizations
<br />__Data__
<br />The WeRateDogs Twitter provides their archive twitter_archive_enhanced.csv for the
use of this project. The archive contains basic tweet data for all 5000+ of their
tweets, but not everything. The file contains columns that need to be assessed and
cleaned.
<br />The Twitter API has been queried for each tweet’s JSON data using Python’s
Tweepy library. After querying each tweet ID, the JSON data has been written to the
required tweet_json.txt file with each tweet's JSON data on its own line. then the file
was read, line by line, to create a pandas DataFrame that has been assessed and
cleaned.
<br />The tweet image predictions, i.e., what breed of dog (or other object, animal, etc.) is
present in each tweet according to a neural network. This file (image_predictions.tsv)
is hosted on Udacity's servers and should be downloaded programmatically using
the ‘Requests’ library.
