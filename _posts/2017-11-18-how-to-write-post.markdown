---
layout: post
title: How to write post on blog
date: 2017-11-18 01:40:00 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img:IMG_0764.jpg # Add image post (optional)
tags: [Cat, Description]
---
블로그에 글을 적는법에 대하여
- 신종환이 Git Commit권한을 수여한 사람들에 한하여 가능함
 1) id / email setting
    git config user.id
    git config user.email
 2) git pull or copy https://github.com/lab402/lab402.github.io
 3) jekyll 을사용하여 제작 하였으며 _config.yml을 통하여 기본 정보를 수정
 4) 개시글은 Post folder에 작성
 5) Img 등록 방법은 아래와 같음
   "({{site.baseurl}}/assets/img/IMG_0764.jgg)"
({{site.baseurl}}/assets/img/IMG_0764.jpg)
 6) git add --all or -a
 7) git commit --all or -a
 8) git origin master

 - 끝 ! -
