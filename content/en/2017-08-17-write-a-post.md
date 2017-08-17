---
title: write a post
author: ~
date: '2017-08-17'
slug: write-a-post
categories: []
tags: [create]
---

- Download the folder 'shuaiweb' from github
- In RStudio console, run the command: **blogdown::new_post(title = 'write a post', subdir = 'en')**, where title; subdir: could be 'en' for English blogs and 'cn' for Chinese blogs
- fill in the categories, tags, contents, etc.
- Go to github, shuaiweb/content/en[or cn]/, click the button 'Upload files', and drag the created blog file in local folder

Prerequired steps:

- **if (!requireNamespace("devtools")) install.packages("devtools")**
- **devtools::install_github("rstudio/blogdown")**
- **blogdown::install_hugo()**