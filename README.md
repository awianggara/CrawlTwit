# CrawlTwit
twitter search 


### Running the script

1) Save the python file or download/clone the repository to your local machine.  Make sure you have the dependencies.

2) Open the `twitter_search.py` file and then find the `load_api()` function (at the top) and add your consumer key, consumer secret, access token, and access secret.  For example:
```
consumer_key = '189YcjF4IUzF156RGNGNucDD8'
consumer_secret = 'd7HY36s4pSh03HxjDg782HupUjmzdOOSDd98hd'
access_token = '2543812-cpaIuwndjvbdjaDDp5izzndhsD7figa9gb'
access_secret = '4hdyfnas7d988ddjf87sJdj3Dxn4d5CcNpwe'
```

3) Go to the `main()` function and edit the search criteria. Namely, you should enter a search phrase, the maximum time limit for the script to run, and the date range for the search (relative to today). For example:
```
search_phrase = '#makedonalddrumpfagain'
time_limit = 1.0 # runtime limit in hours
min_days_old, max_days_old = 1, 2 # search limits

# e.g. min_days_old, max_days_old = 7, 8
# gives the current weekday from last week,
# min_days_old=0 will search from right now
```

4) Open the terminal/command line to the file location and type: 
```
python twitter_search.py
```
The script will run until all tweets within your search criteria have been found.


#### Copyright (c) 2016 Alexander Galea 
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
