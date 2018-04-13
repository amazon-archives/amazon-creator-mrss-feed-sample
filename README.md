# Readme

This is a simple [Jekyll](https://jekyllrb.com/) website with an MRSS feed that designed for creating an Amazon Fire TV app with [Amazon Creator](https://creator.amazon.com). You can view the documentation for Amazon Creator [here](https://creator.amazon.com/documentation/ac/overview.html).

You build this project using the [standard build process for Jekyll](https://jekyllrb.com/docs/quickstart/):

Assuming you already have RubyGems installed, just run the following from the command line:

```
gem install jekyll bundler
bundle exec jekyll serve
```

## Setup

Create posts in the \_posts folder following standard Jekyll post formats. Each post should have frontmatter and content similar to the sample posts.

This information, along with some values from the \_config.yml file, gets passed into the feed_firetv.xml file. You can view the feed_firetv.xml file here: http://sample-firetv-web-app.s3-website-us-west-2.amazonaws.com/feed_firetv.xml.

This feed contains media properties that validate against the MRSS specification. Amazon Creator can consume this MRSS feed and create a Fire TV app.

Note that the project also contains a feed_roku.xml file in case you're also submitting your feed into Roku's Direct Publisher.
