---
layout: page
title: "Contributing"
---

You can use the [editor on GitHub](https://github.com/computational-musicology/computational-musicology.github.io/edit/master/index.md) to maintain and preview website content in Markdown files.

Pages are rebuilt automatically on committing to the repository,
but you will have to wait a minute or so until the changes become visible.
You can see the deploy history [here](https://github.com/computational-musicology/computational-musicology.github.io/deployments).

Pages are styled using Markdown, a lightweight and easy-to-use syntax.
For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

This site uses the [minima](https://github.com/jekyll/minima) Jekyll template.
Follow the link for more information about this template.

Page properties, specifically page type, author, and title,
are specified using code at the top of each page.
A page can be specified as follows:

```
---
layout: page
title: "Contributing"
author: "Peter Harrison"
---
```

A post can be specified as follows:

```
---
layout: date
title: "Contributing"
author: "Peter Harrison"
date: "2nd May 2019"
---
```

Note that author and date fields are optional.

Pages are used for displaying general information, 
and are not typically associated with a date.
Their Markdown files are located in the main directory,
at the same level as `index.md`.
To include a page in the site's navigation area,
you should edit the `header_pages` section of `_config.yml`,
and add the Markdown file corresponding to your new page.

Posts are typically associated with a date, 
and take on more of a 'news' functionality. 
Their Markdown files should be situated in a directory called `_posts`,
located at the top level of the repository.

Edits can be submitted through the GitHub interface in the form of pull requests,
which can then be approved by the site's moderators.
