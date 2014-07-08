Maintaining the Kwiat group website with Jekyll
==================

Introduction
------------------

The Kwiat group website is maintained using Jekyll and files hosted on GitHub. This guide contains an overview of how Jekyll generates the site, and instructions for specific tasks like adding news posts or editing the navbar. It does not explain every detail of how Jekyll works, or every possible feature you might want to use. For more about what Jekyll can do, read the Jekyll documentation here: http://jekyllrb.com/docs/home/

###But first, wait! Don't edit those HTML files on the server!

Seriously, don't do it. All will be explained! But basically, the way this works is that if you want to change something on the website, you're going to do the following:

1. Edit a file in this GitHub repository
2. Run Jekyll
3. Copy the files generated by Jekyll to the server that hosts the website

If you edit the HTML files (or any files) that are already on the server, your changes will not be visible to Jekyll or committed to the GitHub repository, and they will be lost the next time someone runs Jekyll and updates the website.

And whatever you're trying to change, there's probably an easier way to do it using Jekyll. For example, you can edit most of the text on the website without ever looking at an HTML file. You can add a link to the navbar without editing five separate pages. You can add a news item that will automatically show up as an excerpt on the front page and in a longer form on the News page. So resist the urge to edit that HTML file, and read on.

###What is Jekyll?
Jekyll is a tool that takes pieces of content like text files and HTML layouts and builds a website, taking care of tedious things you might otherwise have to do manually (like updating the navbar on each page if you want to add a new link). Another common way to accomplish this is by building a dynamic site using PHP or other server-side languages. The advantages of using Jekyll are primarily that you don't need to learn a server-side language, and the site can be hosted anywhere without worrying about whether the host server supports your dynamic content.

The whole process of building the website happens on your computer, and the result is a static website that can be uploaded to a server. So while using Jekyll might seem intimidating, it's a great way to build a complex website without knowing much more than basic HTML and CSS. Many tasks won't even require more than editing plain old text. You can do it!

Installation and Setup
------------------

You must complete a few steps before you can maintain the website with Jekyll from your own computer. 

###Clone this GitHub repository
