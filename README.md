# 50 years Werner

You can use the [editor on GitHub](https://github.com/C2DH/repair/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

## Add a post
Date
in the front matter:

## Add a category
Currently there are two categories, `diy` and `repair`. To add a new category:

1. in [_data/navigation.yaml](https://github.com/C2DH/repair/blob/master/_data/navigation.yaml) add an identifier (`a-z` chars only)
2. add one markdown file per language in [pages](https://github.com/C2DH/repair/blob/master/pages) folder named after this identifier in the form `<identifier>.<language>.md`, e.g. `repair.fr.md`. The language specified in `default_lang` in `config.yml` can be omitted.
3. add front matter specifying `lang`, `layout`, `permalink`, `title` and the identifier in the `ref`. We use `ref` to get all the available languages for the same page. Note that the permalink starts with slash and should be different for every language.
```
---
lang: fr
layout: category
ref: repair
permalink: /reparer
title: Reparer
---

Abstract to be displayed on top of the page
<!-- more -->

A longer text, will be displayed at the bottom of the page
```
4. add a first post having that ref in category and check the result.

## Add a language


## Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/C2DH/repair/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
