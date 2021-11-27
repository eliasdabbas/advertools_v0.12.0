

# `advertools` v0.12 New Features

A quick intro to some new features and how to use them: 

* A new function `logs_to_df` to parse and compress any log file
* Crawling has a new option to `skip_url_params`, which only follows links that don't contain any URL parameters
* Crawling extracts all `<img>` tag attributes ('alt', 'crossorigin', 'height', 'ismap', 'loading', 'longdesc', 'referrerpolicy', 'sizes', 'src', 'srcset', 'usemap', and 'width' )
* The `url_to_df` function  extracts a new column `last_dir` showing the last directory of the path part of each URL, typically the title of the page, or product name

Play with the new features now: 

[![Binder](https://mybinder.org/badge_logo.svg)](https://bit.ly/3HWW5y5)