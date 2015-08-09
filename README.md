# Casper - Disqus

This theme is a copy of the [default theme for Ghost](https://github.com/TryGhost/Casper) and adds [Disqus comments](https://www.disqus.com) to it. To be specific this theme adds

  1. comments to the end of each article page and
  2. a link to the article comments of each article that includes the number of comments to the index page.

## Download

To download, visit the [releases](https://github.com/baschtl/ghost-casper_disqus/releases) page. The release versions of this theme map to the ones of the original Casper theme.

## Usage

Look for the line `var disqus_shortname  = 'YOUR_DISQUS_SHORTNAME';` in `partials/comment.hbs` and `partials/comment_count.hbs` and replace `YOUR_DISQUS_SHORTNAME` with your actual Disqus shortname.
