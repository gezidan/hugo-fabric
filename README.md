# hugo-fabric
Hugo Fabric Theme, forked from https://github.com/wd/hexo-fabric. You can visit live demo at https://wdicc.com.

# Installation

First clone this repository in the `themes/` directory:

```
$ cd themes/
$ git clone https://github.com/wd/hugo-fabric
```

Second, specify `hugo-fabric` as your default theme in the config.toml file. Just add the line

```
theme = "hugo-fabric"
```

# Theme settings

Put settings below into your config.toml.

```
[params]
  author = "wd"
  [params.theme]
    subtitle = "happy every day"
    post_type = "page" # For archive
    archive_post_type = "archives"

    # According to https://discuss.gohugo.io/t/how-to-access-the-top-level-rsslink-from-a-post/2044, we have to set this ourself
    site_rsslink = "atom.xml"

    # social account
    github_user = "wd"
    twitter_user = "wd"
    disqus_shortname = "wdicc"

    # post sharing
    facebook_like = true
    twitter_tweet_button = true
    google_plus_one = true
    google_plus_one_size = "midum"
    addthis_profile_id = "wd"
```

# Archive support

Create a new file `hugo new archives.md`, and edit this file, add the following line in front matter.

```
type = "archives"
```

# Others

* https://github.com/wd/hexo2hugo
* https://discuss.gohugo.io/t/blog-archives-page/2577/17
