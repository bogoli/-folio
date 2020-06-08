# *folio
A simple theme for showcasing your work, emphasis on whitespace, transparency, and helvetica. 


<a href="http://bogoli.github.io/-folio/">Live Demo</a>

<hr/>


## Features

### Collections
This Jekyll theme implements collections to let you break up your work into categories. The example is divided into poetry and portfolio, but easily revamp this into recipes, apps, short stories, limmericks, whatever your creative work is. 
> To do this, edit the collections in the config file, create a corresponding folder, and update the portfolio and poetry source files. 

Three different layouts are included—the poetry layout, for a simple list of entries, the blog layout (index.html), for more detailed descriptive list of entries, and the portfolio layout. The portfolio layout overlays a descriptive hoverover on a background image. If no image is provided, the square is auto-filled with the chosen theme color. Thumbnail sizing is not necessary, as the grid crops images perfectly. 

### Portfolio Specifics
You can easily add full pages for each of the projects in your portfolio. If you want one to link to an external website, create a file for it in _portfolio, and  fil in the YAML front matter as you would for another, but with a redirect, like so: 

	---
	layout: post
	title: Project
	description: a project that redirects to another website
	img:
	redirect: https://otherpage.com
	--- 

### Theming
Six beautiful theme colors have been selected to choose from. The default is red, but quickly change it by editing the _base.scss file in line 40. The color variable are listed there, as well. 

### Photos
Photo formatting is made simple using rows of a 3-column system. Make photos 1/3, 2/3, or full width. Easily create beautiful grids within your blog posts and projects pages. 

### Code Highlighting
This theme implements Jekyll's built in code syntax highlighting with Pygments. Just use a liquid tag to delineate your code: 
{% highlight python %}
	code code code
{% endhighlight %}


<hr/>
The MIT License (MIT)
Copyright (c) 2015 Lia Bogoev

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

