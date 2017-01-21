# [Start Bootstrap](http://startbootstrap.com/) - [Clean Blog](http://startbootstrap.com/template-overviews/clean-blog/)

[![Greenkeeper badge](https://badges.greenkeeper.io/ergo-cms/theme-clean-blog.svg)](https://greenkeeper.io/)

This is the ergo-cms compatible edition of [Clean Blog](http://startbootstrap.com/template-overviews/clean-blog/): a stylish, responsive blog theme for [Bootstrap](http://getbootstrap.com/) created by [Start Bootstrap](http://startbootstrap.com/). This theme features a blog homepage, about page, contact page, and an example post page along with a working PHP contact form.

## Notes

This theme provides the following layout files, which are commonly available for most standard 'blog' style installations:

* homepage.html. Use this layout by making sure the following line is in the header area of your home page (typically @/index.tex@):

bc. layout = homepage.html

* page.html. This is the 'default' page for all pages that aren't part of a blog. They are your standard pages (like, about.html, etc).
* post.html. This is the page that is used in blog posts. It has features such an author, date and provides a Disqus comments area.
* list.html. This page is used for building pages that have 'lists of things', such as a list of blog posts. The [default ergo skeleton package](https://ergo-cms/ergo-skel) uses this page in @/blog/index.tex@, by setting the following fields in it's header area:

bc. layout = list.html
list_type = blog

There are two partial files that are included, that may be overridden easily:

* footer_text.html. This controls the text that appears in the footer area.
* menu.tex. This controls the menus in the top navigation area.


## The easy installation

```
ergo theme install sbs_clean_blog
```

This will download and install the theme into the _themes folder and set it is as the current one. You can then rebuild your site with (a 'clean' is always recommended when switching themes):

```
ergo build --clean
```

## The long winded installation

If you prefer to do things manually to install a theme, then follow these instructions.

Download and extract this theme into your `_themes` folder as 'sbs_clean_blog' and then edit your `config.ergo.js` file and change the setting theme to:

```
	theme = 'sbs_clean_blog',
```

Note that you may choose whatever folder name you like.

Then, rebuild your website using:

```
ergo build --clean
```



## Creator

Start Bootstrap was created by and is maintained by **[David Miller](http://davidmiller.io/)**, Owner of [Blackrock Digital](http://blackrockdigital.io/).

* https://twitter.com/davidmillerskt
* https://github.com/davidtmiller

Start Bootstrap is based on the [Bootstrap](http://getbootstrap.com/) framework created by [Mark Otto](https://twitter.com/mdo) and [Jacob Thorton](https://twitter.com/fat).

## Copyright and License

Copyright 2013-2016 Blackrock Digital LLC. Code released under the [MIT](https://github.com/BlackrockDigital/startbootstrap-clean-blog/blob/gh-pages/LICENSE) license.