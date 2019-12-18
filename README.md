# Instructions

## Building locally

To build the website and display it locally on your computer, open a command prompt (cmd) and type
```
bundle exec jekyll serve
```
`bundle exec` just makes sure you're using the correct library versions.  `jekyll serve` builds and serves the
website using the jekyll website engine.

The command prompt will then say something like
```
      Generating...
       Jekyll Feed: Generating feed for posts
                    done in 5.438 seconds.
 Auto-regeneration: enabled for '/Users/Gerry/GIT_REPOS/virginia.com'
    Server address: http://127.0.0.1:4000//
  Server running... press ctrl-c to stop.
```

And you can navigate to ***`127.0.0.1:4000`*** in Google Chrome to view the website.  Most changes you make
will be automatically updated without needing to rerun jekyll serve, but if you make a change in the
`_config.yml` file or some other more central files, then you will have to kill jekyll with Ctrl-C
and then restart it by rerunning `bundle exec jekyll serve`.

## Publishing
Just push to github and in a minute or two your updates should appear at [https://virginiapan.github.io/](https://virginiapan.github.io/)