---
title: "Hosting the Sigasi documentation in your secure and closed network"
pager: true
date: 2016-04-01
lastmod: 2019-07-17
tags: 
  - howto
comments: true
bannerad: true
---


Some development teams are completely disconnected from the public internet, for security reasons. Engineers in these teams can still access the documentation on [Sigasi Insights](/), using one of the procedures below.

Some things will not work if you view this website offline:

 * Video's are hosted separately, and will not be available
 * External links will be broken
 * The comments sections use an external service and will not be available

# Local build with Hugo

You can also generate the Sigasi insights page locally:

1. Download the source code of the Sigasi Insights website from GitHub: <https://github.com/sigasi/sigasi_insights>
2. Make sure you have [Hugo] installed
3. Generate the site
    *  Run the site locally with `hugo server`
    *  Or generate the html code using `hugo` and copy the *public* folder to your internal server
4. Visit <http://localhost:1313> to see the documentation

[Hugo]: https://gohugo.io/
