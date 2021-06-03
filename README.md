# (WIP) Massively - Jekyll Theme

A Jekyll version of the "Massively" theme by [HTML5 UP](https://html5up.net/).

![Massively Theme](assets/images/massively.jpg "Massively Theme")

# How to Use.

For those unfamiliar with how Jekyll works, check out [jekyllrb.com](https://jekyllrb.com/) for all the details,
or read up on just the basics of [front matter](https://jekyllrb.com/docs/frontmatter/), [writing posts](https://jekyllrb.com/docs/posts/),
and [creating pages](https://jekyllrb.com/docs/pages/).


# How to run the build file:

If you want to run the a local version of the website execute this command in your Terminal app when you are in your erik-bleich.github.io folder:

```
	bundle exec jekyll serve
```

Open up a browser and go to http://localhost:4000/ and voila! You have a running Local version

> Note that none of your changes on the local version will change the actual deployment version. You have to use github to add your local changes to the master repo. Consult your local software developer if you do not know how to do this

# How to add a new page:

* If you want to add a page on the website and have it display it in the navbar.

Create a markdown file in the root directory named i.e:
	PAGENAME.md

Inside the PAGENAME.md you should add the contents like so:

```
---
layout: page
title: [NAVBAR TITLE]
---
<section class="post">
		<p>
			CONTENTS
		<p>
</section>
```

> The markdown file will create a new PAGENAME.html file in your sites directory

# How to add a new blog post:

* Check the technical do if you want to create a new post for the website


# Added Features

* **[Formspree.io](https://formspree.io/) contact form integration** - just add your email to the `_config.yml` and it works!
* Add your **social profiles** easily in `_config.yml`. Only social profiles buttons you enter in `config.yml` show up on the site footer!
* Set **featured images** in front matter.


# Credits

Original README from HTML5 UP:

```
Massively by HTML5 UP
html5up.net | @ajlkn
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)


This is Massively, a text-heavy, article-oriented design built around a huge background
image (with a new parallax implementation I'm testing) and scroll effects (powered by
Scrollex). A *slight* departure from all the one-pagers I've been doing lately, but one
that fulfills a few user requests and makes use of some new techniques I've been wanting
to try out. Enjoy it :)

Demo images* courtesy of Unsplash, a radtastic collection of CC0 (public domain) images
you can use for pretty much whatever.

(* = not included)

AJ
aj@lkn.io | @ajlkn


Credits:

	Demo Images:
		Unsplash (unsplash.com)

	Icons:
		Font Awesome (fortawesome.github.com/Font-Awesome)

	Other:
		jQuery (jquery.com)
		Misc. Sass functions (@HugoGiraudel)
		Skel (skel.io)
		Scrollex (github.com/ajlkn/jquery.scrollex)
```
