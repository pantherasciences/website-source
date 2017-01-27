# Source of pantherasciences.com
Welcome to the comprehensive source code for the Panthera Sciences website. Here you can find an exhaustive breakdown of how this website was made, and what tools were used in the process, so you too can make your own awesome static website and Octopress-powered blog.

# [Jekyll 3.1.2](https://github.com/jekyll/jekyll)
>Jekyll is a simple, blog-aware, static site generator perfect for personal, project, or organization sites. Think of it like a file-based CMS, without all the complexity. Jekyll takes your content, renders Markdown and Liquid templates, and spits out a complete, static website ready to be served by Apache, Nginx or another web server. Jekyll is the engine behind [GitHub Pages](https://pages.github.com/), which you can use to host sites right from your GitHub repositories.

We have used Jekyll to manage the [blog aspect of the website](https://pantherasciences.com/blog). The simplicity of Jekyll's site generation is great. It allows us to write our blog posts in simple Markdown, which is then interpreted and translated into HTML when published. The site that Jekyll generates is static, meaning it is super simple and can be hosted pretty much anywhere. This allows us to host using GitHub Pages rather than our old, evil, overlord, Squarespace.

# [Octopress 3.0.11](https://github.com/octopress/octopress)
Octopress, as of version 3, is an awesome toolkit built for Jekyll. It adds commands and features for us as site authors that allow for much easier ways to make new blog posts or new pages. Octopress also provides a single command (`octopress deploy`) method for publishing the site. Octopress adds a ton of awesome features to Jekyll. In addition to the many features added by Octopress, we can also add Octopress plugins, which can give us even more blogging capabilities.

### `_config.yml`
In Octopress's built-in configuration file, many site-wide variables and settings are declared. These settings and variables can be accessed in files, and when the site is built by Jekyll, the variable is replaced with its value. This is also where some URL settings are made, such as the path to blog posts: `:categories/:title`, which Jekyll will build into something like [http://pantherasciences.com/blog/balloons/lunarhab-launch-and-recovery](http://pantherasciences.com/blog/balloons/lunarhab-launch-and-recovery).

# [HTML5 UP](http://html5up.net)
HTML5 UP is an excellent website that hosts tons of free to use website templates. We use one such template to power [the non-blog pages of the website](https://pantherasciences.com). After a careful selection process, we eventually decided to use the Spectral template. Using the included template pages, we were able to develop project pages, a home page, a project index, and more.

# Symbiosis
In order to have a seamless user experience, Octopress and the HTML5 UP template were merged.

This process involved editing existing and creating new Octopress layouts (found in `_layouts`) for use with different pages. By doing this, we were able to drastically reduce the amount of code required per page, because any code that is repeated for multiple pages can instead be generated and added in by Jekyll. Harnessing this tool was critical to this website's development. 

The next aspect of this merge was filling the `_includes` files. In some cases, such as `_includes/head.html`, this code was mostly written from scratch. In the `head.html` file, we added optimization for Facebook, Twitter, and Google Chrome on Android. Other files, such as `header.html` and `footer.html` are almost exact ports of code from the Spectral template, because these code segments simply needed to be repeated for multiple pages. Instead of writing the full HTML code for the header into every page's HTML file, we can simply write `{{ page.header }}`, and Jekyll will include the contents of `header.html` when building the site.

CSS, Sass, and JavaScript was imported directly from the Spectral theme, and placed in an `assets` folder in the root directory. The file `main.css` provides the styles for the website.
