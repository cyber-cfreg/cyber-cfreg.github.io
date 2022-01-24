## University of New Haven - cyber@cfreg Website

![University of New Haven CIT Banner Logo](images/unh_logo_banner.png)

cyber@cfreg Website URL: [https://hack.newhaven.edu/](https://hack.newhaven.edu/)

This website serves the purpose of creating a central location for information about cyber@cfreg, a student run organization at the University of New Haven which is often referred to as the hacking club. It also holds a record of the competition placements achieved hack@cfreg, the competitive hacking team for the University of New Haven.

This website was initially designed by [@CharlesBarone](https://github.com/CharlesBarone) and then ammended to a [Jekyll](https://jekyllrb.com/) template by [@samuelzurowski](https://github.com/samuelzurowski).

## Contribution Guidelines

Development is done in the `staging` branch, then merged into the `main` branch when it is ready to be published.

New pages should use the `other` page layout and be created as markdown files in the root directory of the repository.
#### Example New Page

[Jekyll](https://jekyllrb.com/) allows us to quickly and easily create pages using markdown language as seen below:

```markdown
---
layout: other
title: NewPage
---

# SubTitle 1

### SubSubTitle

- Bulleted
- List

1. Numbered
2. List

# SubTitle 2

Example new page text!
\
&nbsp;
\
&nbsp;
```

For more information about markdown formatting refer to [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

Whenever a commit is made to the `main` branch of this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the site, from the content in the markdown files.

## Test cyber@cfreg Website Locally

The following command will allow you to locally run the website on port 8000, assuming you have [Jekyll](https://jekyllrb.com/) installed. It will automatically rebuild the website every time a file is updated.

`jekyll serve --watch --port 8000`

### How to make a new announcement post

Posts on the Announcements page are managed by navigating to `/admin` on a local instance of the website. Once there, you can then navigate to `Posts` using the left sidebar navigation. New posts can be made using this tool and then published by pushing a commit to the git repository.


## Contact cyber@cfreg

Need to contact someone from cyber@cfreg? Feel free to join our [Discord](https://dsc.gg/cyberatcfreg) or visit the [contact page](https://hack.newhaven.edu/contact) for more information about how to reach us.
