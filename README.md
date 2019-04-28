## Summary

Sometimes I want to read heavy web pages on a slow internet connection.
This lets me run Mozilla's Readability on a remote server, and download
just the text. 

Reading a typical guardian.com article through this uses ~10KB of bandwidth,
versus ~1MB to download the article directly (including all images and scripts).

Implementation heavily inspired by [this blog post](https://adambard.com/blog/self-hosted-readability-on-heroku-with-nodejs/).

## Deploying
Just clone the repo and push it on a new Heroku app (or any other host). 
Or just use my running instance: http://loadfast.herokuapp.com/

