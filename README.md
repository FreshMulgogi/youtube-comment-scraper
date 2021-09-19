# Parse Comments from Youtube Videos

This script will dump youtube video comments to a CSV from youtube video links. Video links can be placed inside a variable or list or CSV

The script is based on [youtube-comment-downloader](https://github.com/egbertbouman/youtube-comment-downloader)

It requires **pandas** and **requests** modules

To run :

`pip install -r requirements.txt`

`python ytb_comment_scraper.py`

By default, the script will download most recent 100 comments\

The comments will be dumped to a CSV file

You can set the parameter values as you wish - 

```
COMMENT_LIMIT : How many comments you want to download 

SORT_BY_POPULAR : filter comments by popularity (0 for True , 1 for false)

SORT_BY_RECENT : filter comments by recently posted (0 for True , 1 for false)
```