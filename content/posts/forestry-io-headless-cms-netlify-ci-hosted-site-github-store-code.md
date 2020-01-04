---
date: 2020-01-04T14:04:49Z
hero_image: "/content/images/ren-ran-bBiuSdck8tU-unsplash.jpg"
title: forestry.io (headless cms) + netlify (CI, hosted site) + github (store code)
author: Robert Thoreau

---
forestry.io (headless cms) + netlify (CI, hosted site) + github (store code)

1\. 參考 [https://blog.jxtsai.info/post/forestry-io/](https://blog.jxtsai.info/post/forestry-io/ "https://blog.jxtsai.info/post/forestry-io/")

直接用內建的gatsby starter來生成blog

2\. 用netlify取代Forestry的CI, deploy

Forestry will stop building and deploying sites on January 1st, 2020.

We recommend to use a dedicated CI/CD platform like Netlify.

  [https://forestry.io/docs/hosting/github-pages/](https://forestry.io/docs/hosting/github-pages/ "https://forestry.io/docs/hosting/github-pages/")

3\. import github to netlify,

3\.1 import時，可限制權限只存取該repository

3\.2 import時，會自動填入

\---

Build command   gatsby build

Publish directory   public/

\---

而此處的public/跟github無關

4\. done. 從forestry加入新的內容到github時，netlify會自動CI

forestry only plain text and markdown

  [https://forestry.io/blog/discontinuing-wysiwyg-editor-new-focus-on-markdown/](https://forestry.io/blog/discontinuing-wysiwyg-editor-new-focus-on-markdown/ "https://forestry.io/blog/discontinuing-wysiwyg-editor-new-focus-on-markdown/")

ps. 內建的gatsby starter 內文一定要放head image, 不然build會失敗