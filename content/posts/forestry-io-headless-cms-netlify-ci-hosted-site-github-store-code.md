---
date: 2020-01-04T14:04:49Z
hero_image: "/content/images/ren-ran-bBiuSdck8tU-unsplash.jpg"
title: forestry.io (headless cms) + netlify (CI, hosted site) + github (store code)
author: Robert Thoreau

---
0\. forestry.io (headless cms) + netlify (CI, hosted site) + github (store code)

1\. 參考 [https://blog.jxtsai.info/post/forestry-io/](https://blog.jxtsai.info/post/forestry-io/ "https://blog.jxtsai.info/post/forestry-io/")

2\. 

Forestry will stop building and deploying sites on January 1st, 2020.

We recommend to use a dedicated CI/CD platform like Netlify.

  [https://forestry.io/docs/hosting/github-pages/](https://forestry.io/docs/hosting/github-pages/ "https://forestry.io/docs/hosting/github-pages/")

3\. import github to  netlify,

import時，可限制權限只存取該repository，

會自動填入

\---

Build command   gatsby build

Publish directory   public/

\---

而此處的public/跟github無關