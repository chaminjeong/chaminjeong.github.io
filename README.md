# chaminjeong.github.io
chaminjeong.github.io
# Site
title:          차민정 개인 홈페이지
bio:            'Just a simple Jekyll theme'
description:    "경희대학교 대학원생 차민정 개인 홈페이지 입니다:)"
picture:        'assets/img/profile.png'
locale:         en_US
url:            https://github.com/chaminjeong/chaminjeong.github.io.git


# Jekyll
permalink:      /:title/
markdown:       kramdown
highlighter:    rouge
kramdown:
  auto_ids: true
  footnote_nr: 1
  entity_output: as_char
  toc_levels: 1..6
  enable_coderay: false
sass:
  sass_dir: _sass
  style: compressed

# Social
# if you don't have any of social below, comment the line.
#email:
twitter: username
facebook: 차차민정
#google:
  #plus: #username
  #analytics:
  #verify:
  #ad-client:
  #ad-slot:
#bing-verify:
github: chaminjeong
stackoverflow: #123456/username   from a "http://stackoverflow.com/users/123456/username" link
linkedin: username
#xing: username
instagram: username
lastfm: username
tumblr: username
#pinterest: username
#foursquare: username
steam: username
#dribbble: username
youtube: 차챠밍
#soundcloud: username
#weibo: username
#flickr: username
#codepen: username

# Paginate
# if you don't need pagination, comment the *paginate* configs below
# paginate: 5
# paginate_path: "blog/:num/"


# Comments
disqus_shortname: alperenbozkurt-net


# Gems
gems:
  - jekyll-mentions
  - jekyll-feed
  - jekyll-sitemap
  - jekyll-gist
  - jekyll-paginate

jekyll-mentions:
    base_url: https://github.com

# Exclude list
exclude: [README.md, Gemfile, Gemfile.lock, node_modules, gulpfile.js, package.json, _site, src, vendor, CNAME, LICENSE, Rakefile]
