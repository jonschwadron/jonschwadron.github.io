---
layout: post
title:  "Tutorial: Build a static website through Github Pages"
date:   2022-02-23 08:48:05 -0700
categories: github pages tutorial
---
Documentation: [Github Pages documentation][gh-pages-documentation]

Github Pages is one way you can display static webpages for free. This is a fantastic start for those who are looking to build their portfolio. Let's walk through this guide and get your first webpage running via Github Pages.

1. Create a GitHub account: [Getting started with your GitHub account][gh-account-documentation]
2. Create a new repository
3. Set repository name to: yourusername.github.io
4. Open up a new tab and navigate to your GitHub Pages url: https://yourusername.github.io

At the moment Github Pages will display the content of the readme.md file by default.

You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[gh-account-documentation]: https://docs.github.com/en/get-started/onboarding/getting-started-with-your-github-account
[gh-pages-documentation]: https://docs.github.com/en/pages
[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
