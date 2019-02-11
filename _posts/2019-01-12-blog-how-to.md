---
layout: post
title: "How to make a blog like this one"
---

## What exactly?

This blog is a static website hosted on _[GitHub Pages][1]_, it's built with _[Jekyll][2]_ using the _[jekyll-minimal-theme][3]_ to style the site, I write my blog posts using _[Markdown][4]_ on a _text editor_ and I push my new blog posts to the Internet using _[git][5]_.

[1]: https://pages.github.com/
[2]: https://jekyllrb.com/docs/
[3]: https://github.com/henrythemes/jekyll-minimal-theme
[4]: https://www.markdowntutorial.com/
[5]: https://guides.github.com/introduction/git-handbook/#basic-git

## What if I want my blog to look different?

Its more important that you begin writing your blog, you can change the look of it later down the line.

## What do you get?

* A blog with a (somewhat) custom url.
* A mobile friendly blog.
* The ability to preview changes on your blog before publishing to the web.
* A Home page.
* An about me page.
* An RSS feed, meaning readers can "subscribe" to your blog and get notifications.
* A menu for selecting what post to read.
* An easy way for your readers to download all your posts. 



## At what cost?

About 10 to 15 minutes to set up the site, no money involved whatsoever.

To replicate this blog on your own you need a few things:

1. A computer with an Internet connection, Windows, Mac & Linux are sported, the setup process can only be done on a computer, although writing posts can be done on a mobile device, to add a new blog entry you need a computer too.
1. A GitHub account to set up your GitHub Pages Blog, your user name will be the url of your blog followed by the suffix `.github.io`, if your user name is `a-polar-bear` your blog url will be `a-polar-bear.github.io`, you can only make one blog with "custom" url per account, meaning if `a-polar-bear` wants to start a second blog called `honey` the blog will be created on `a-polar-bear.github.io/honey`.
1. **[Optional]** A Text editor your comfortable with, on it you will write all your posts, note that the text editor you choose must allow you to save your documents with any suffix you want, for example your text editor should be able to produce a document titled `doc.abc`, If your text editor forces you to use a specific format like `.pdf`, `.docx` or `.pages` you must search for another text editor that supports arbitrary suffixes.
1. **[Optional]** Installing a program on your computer called _Jekyll_, this program helps you to preview your blog before uploading it to the Internet, if you don't need to preview your site you can ignore this step, Jekyll is the program that creates the blog but GitGub Pages already comes with it pre-installed.
1. **[Optional]** To upload your changes to the web you need a program that interacts with GitHub, there are two main options, you can install _GitHub Desktop_ (easy to understand and work with for beginners) or you can install the _git command line tool_ (it does essentially the same as the desktop version but it only works by using the command line, recommended for enthusiasts and programmers).

## This seems very technical, why not use tool X to build a blog?

A few days ago I started my blog, so naturally I looked up videos on how to start a blog and I came across a video by The Minimalists, I consider myself a minimalist so I gave it a go and it was horrible. The video was beautifully produced but the content seemed anything but minimalist, Joshua Fields Millburn said strait up that you need to keep your credit card close by and then proceeded to buy a 125 dollar minimalist theme, that's 125 dollars for a website with black text with white background, then he instructed the viewer to install wordpress and on top of that you need google analytics, the jetpack wordpress SEO plugin, consider mailchimp (an extra 10 dollars a month for sending emails), sort out comments from another third party service and consider buying stock photos for populating your site. That advice wont get you a minimalist site but a bloated and expensive one.

And as far as I can tell all site or blog building tools are bloat on top of bloat with horrible interfaces and unreasonable prices. The Minimalists video pitches the idea that making a blog used to be a web designer's game or a programmer's game but that changed because X platform makes it easy! and then they just happen to give you a discount. Making a blog manually is not hard like The Minimalists suggest on their video, because their video is an advertisement, not a tutorial. You won't need to program anything, I set everything up for you, you just need to setup the preset I made and add your blog name.



## Instructions - how to get your blog up and running (for dummies)

> If you don't feel like reading all the instructions below I have a shorter version of the instructions further down below.

I made things easy for you, first you need to decide on the url of your blog. 

[To create your account click here](https://github.com/join)

> **IMPORTANT:** Once you create your user name you cannot change it.

Name your user name how you want your blog to be named, if you want your blog url to be `coolblogs.github.io` your user name must be `coolblogs`, if the user name is not available try again with another name.

Once you have your account you need to duplicate my blog, to do so go to [this link](https://github.com/alex-esc/post-clone).

Then click on the `Fork` button.

![](https://help.github.com/assets/images/help/repository/fork_button.jpg)

Wait a second...

Once it finished loading you should see your user name followed by `/post-clone` written in blue text.

![](https://help.github.com/assets/images/help/repository/repo-actions-settings.png)

> in this example picture it shows _octo-org/octo-repo_, yours will say _yourusername/post-clone_.

Click on settings



![](https://help.github.com/assets/images/help/repository/repository-name-change.png)

> in this example picture it shows _html-proofer_, yours will say _post-clone_.

Change `post-clone` for your user name, it must be written exactly as your user name.

After you wrote your user name add `.github.io` and click on rename, you can rename as many times as you need.

> Example: if your user name is`coolblogs`, you must rename your site to `coolblogs.github.io`.


You are almost done! now you need to configure the site to make it yours.

Scroll to the top of the page and click on _<> code_, its a few buttons to the left of the settings menu you just clicked.

There you will see a list of files that make up your website, the list consists of:

	_layouts
	_posts
	css
	gitignore
	LICENSE.md
	_config.yml
	archive.md
	feed.xml
	index.md
	


Click on _config.yml and then click the edit button (pencil).

![](https://guides.github.com/features/pages/edit-file.png)

Then you will see this text:

	title:   'YOUR BLOG TITLE GOES HERE'
	author:
	  name:  'YOUR BLOG TITLE GOES HERE'
	description:  A DESCRIPTION FOR YOUR BLOG GOES HERE
	path: ''
	url:  'https://YOUR USERNAME GOES HERE.github.io/'
	
Replace "YOUR ___ GOES HERE" with your information.

For example:

	title:   'Cool Blogs'
	author:
	  name:  'mr. blog man'
	description:  Only the coolest of blogs
	path: ''
	url:  'https://coolblogs.github.io/'
	
Then scroll down, write a name for your change and click the green button that says _Commit chnages_, if you do not write a description the button will be un-clickable.

The blog is now configured, next we will turn on the blog, to do so go back to the settings menu.

![](https://help.github.com/assets/images/help/pages/none-source-setting.png)

Scroll down the page and look for _GitHub Pages_, then click on the button that says _none_, then choose the option that says _master branch_ and then hit _save_.

Now the site is ready, now you only need to write blogs on it!

> To see your blog in action go to https://_**YourUsername**_.github.io/, if you get a 404 page you need to wait a few minutes for your site to build on the background.

## The instructions are too long, cant you just get to the point!

1. Make a GitHub Account, [click here](https://github.com/join).
1. Name it like your blog.
1. Go to my preset by [clicking here](https://github.com/alex-esc/post-clone) and click _Fork_.
1. Change the name of your site from _post-clone_ to _YOUR USERNAME GOES HERE.github.io_.
1. Go to the code and open _config.yml.
1. Edit in your settings (name, description, etc), commit your changes.
1. Go to settings, on the GitHub Pages section select the master branch as source, save.
1. Done!




## How to use your new blog

### What does each file does?


| File or folder | What it does |
|---|---|
| _layouts | In this folder you will find the `default` and `post` layout, meaning it tells the site what elements to place where and in what order, `default` tells the site to write the name of the blog and the rest of the content below and the `post` layout tells the site to write the name of the post, the date and the post itself. |
| _posts | Here you will place all your blog posts. |
| css | Contains the stylesheets, it's what gives the site it's look. |
| gitignore | This is a necessary file used by _git_. |
| LICENSE.md | Contains the license of the theme "jekyll-minimal-theme". |
| _config.yml | Here you can change the main settings of the site, settings like name of the blog, author and description. |
| archive.md | This is the archive page, is the same on the top bar. |
| feed.xml | This file generates the RSS feed, learn more about RSS [here][rssyt]. |
| index.md | This is the homepage of the site, meaning the first page you visit when opening your blog. |

[rssyt]: https://www.youtube.com/watch?v=0klgLsSxGsU

### How to blog.

1. Make a new Markdown file inside the `_posts` folder.
1. Name the file `YEAR-MONTH-DATE-TITLE.md`.
1. Add the block of configuration at the top (also called YAML block).
1. Write your post using Markdown
1. Save and push to the live site.


### How to write posts?


#### Blog post structure.

All Blog post entires belong inside the `_posts` folder.

On it you will see a file named with a date and a post title: by default you will see a file called `2019-01-07-test.md`, _2019-01-07_ is the date, _test_ is the title and _md_ is the format of the file.

> **IMPORTANT:** all post files names must have "-" for spaces, for example an incorrect file name is `2025-08-21 the best day of my life.md`, and a correct version would be `2025-08-21-the-best-day-of-my-life.md`.

Every blog post entry must be placed inside the `_posts` folder and must be named `YEAR-MONTH-DATE-TITLE.md`, no two files must share the same name.

All post entries must have a _block of configuration at the top_, this configures the post to share the look of the rest of the site, the configuration block looks like this:

	---
	layout: post
	title: "How to make a blog like this one"
	---


> The block of configuration's technical name is `YAML block`.

Copy paste this configuration (or YAML)  block at the beginning of every post and replace _How to make a blog like this one_ with your own title (keep the parenthesis).

After that you can begin typing your blog content, just type, then save.

> By default the only blog post is `2019-01-07-test.md` which you can delete and add your own entry.

**Structure example:**

File is named YEAR-MONTH-DATE-TITLE.md and its placed inside the `_posts` folder.

	---
	layout: post
	title: "TITLE GOES HERE"
	---
	
	Text goes here.



### How to format the text inside a post.

All text formating is done via a light markup language called _Markdown_, it's super simple you can learn it in 10 extra minutes by playing [this interactive tutorial game](https://www.markdowntutorial.com/) on your computer.

All files ending in `.md` means that file uses Markdown to format the text.

### How to make and push the changes to the Internet.

Your bloging workflow will depend on the tools you use, you have 2 main options at your disposal, you can:

* Work entirely inside the web browser, this is the easier workflow but by only using the website to make your changes you will **miss out on the ability to** _preview your changes before you publish_ and every time you save your work it will be immediately published, meaning _you must write all your post in one go_ (for more info read _Push using the GutHub website_).

or you can

* Make your changes and write your blogs on your computer and use a program called _git_ to publish them to the web, git works by downloading a copy of your blog to your computer, you will make all the changes you need and until you click publish git will upload your local changes to the Internet, meaning you can experiment as mush as you want with the site without messing with the actual blog, this is the method I use (for more info read _Push using Git_.).

#### Push using the GutHub website.

1. Visit [`https://github.com/`][ghwb] and log in with your username.
1. Click on your website's name, it's placed inside your _repositories_.
1. Make your changes here, click on a file to view and click the pencil to edit or click the _create a new file_ button.
1. After your changes are done scroll down and under the _Commit changes_ section you should name your commit and click the green button to commit the changes.


[ghwb]: https://github.com/

#### Push using Git.

To use git you must install it first, but there are many ways to interact with git, you can use git via the command line or by using GitHub desktop.

> Before you decide what program to use you must first understand the basics of git, [here][gitpoets] you can find a video tutorial aimed for non-programmers.

**git through the command line**

	$ git add *.c
	$ git add LICENSE
	$ git commit -m 'initial project version'

> This program doesn't use the mouse or has any buttons or menus, it has no interface at all, it works via the command line like computers used to work before the 1990's, above is an example of how git looks like.

| [Download git][dwgit] | [Read the manual][gitmanual] |

**GitHub desktop**

![](https://desktop.github.com/images/github-desktop-screenshot-windows.png)

> This desktop client has a graphical interface, it uses the mouse, in other words is just a normal program, downside is that it lacks most of git's advanced features, but for this use it will do the job, it's the method I use.

| [Download GitHub desktop][dwghd] | [Read the manual][gitdesman] |

[gitpoets]: https://www.youtube.com/playlist?list=PLRqwX-V7Uu6ZF9C0YMKuns9sLDzK6zoiV
[gitmanual]: https://git-scm.com/doc
[gitdesman]: https://help.github.com/desktop/guides/
[dwgit]: https://git-scm.com/downloads
[dwghd]: https://desktop.github.com/


### Going beyond this tutorial.

More advanced questions like:

* How can I preview the changes before publishing?
* How can I change the look of the blog?

The answer to both have too do with using Jekyll: The program responsible for building the site, to learn more about Jekyll take a look at these resources:


* [Read the Jekyll manual](https://jekyllrb.com/docs/)
* [Watch a video tutorial on the basics of Jekyll](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB)


**Download Jekyll:**

| [windows][jwin] | [mac][jmac] | [ubuntu][jubuntu] | [other linux distribuitions][jlinux] |


[jwin]: https://jekyllrb.com/docs/installation/windows/
[jmac]: https://jekyllrb.com/docs/installation/macos/
[jubuntu]: https://jekyllrb.com/docs/installation/ubuntu/
[jlinux]: https://jekyllrb.com/docs/installation/other-linux/

> If you need a reference, you can take a look at the source code of my blog [here][bsource].

[bsource]: https://github.com/alex-esc/posts

## Conclusion.

Starting a blog is not hard, GitHub Pages provides free hosting, Jekyll is free of charge too. The only thing standing between you and your future blog is your determination for sitting down and writing your blog posts. Spend 10-15 minutes following my setup tutorial, do the Markdown tutorial and start your blog today!