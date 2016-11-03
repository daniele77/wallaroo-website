# wallaroo-website
Website for the wallaroo C++ library

## Resources

  http://notes.hivetrix.com/tools/nanoc/

  http://www.yet.org/2012/11/nanoc/

## Dependencies
To get relative paths, use the filter "relativize_paths" in Rules.
You need the gem:

    gem install nokogiri 

To get syntax highlighting, you need the gem:

    gem install coderay

To generate sitemap xml, you need the gem:

    gem install builder

## Compile

    nanoc

## Deploy (staging)

    nanoc deploy --target staging

## Deploy (public)

    nanoc deploy --target public


