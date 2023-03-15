# Hosting a Resume on GitHub Pages

## Purpose

This README is meant to explain how to host and format a resume on GitHub Pages. It will also explain key principles from the book Modern Technical Writing by Andrew Etter about lightweight markup languages, distributed version control, and static websites.

## Prerequisites

Before we start, there are a few things you'll want to prepare. The first is a Markdown editor to write your resume in, such as Visual Studio Code. You will also want a GitHub account, a working knowledge of Markdown syntax, and a static site generator such as Jekyll.

### Why Markdown?

Markdown is a lightweight markup language, which means it has *lightweight* syntax, aka clean and simple syntax. Markdown especially is the cleanest and one of the most widely used lightweight markup languages in the world.

Those traits make Markdown ideal because
- It's readable even when it isn't rendered
- It's easy to learn
- It doesn’t require specific tag knowledge like HTML
- It's easy to include links and pictures

In fact, you can view an example of Markdown's simple syntax by clicking on this file and then on the **Raw Text** option.
<!-- TO-DO: make this an image -->
### Why Visual Studio Code?

Visual Studio Code, or VSCode, is a versatile IDE that uses a Distributed Version Control system along with GitHub. A Distributed Version Control system is a system that allows users to download a local copy of the project onto their machine, then commit changes locally.

Distributed Version Control systems
- allow for better performance,
- give you the ability to work offline, and
- make it easy for multiple people to work on the same file.

### Static Websites

Finally, you will need a static site generator. A static site generator takes a Markdown file and a theme and generates a static website for you. Hosting your content on a site will let you fix and edit content near instantly and also allows for your content to stay in sync instead of having to send out new documents each time you make a change. Hosting your content on a *static* site will also allow you to work offline, which prevents you from losing your work if there are connectivity issues or browser crashes.

Reasons to choose static websites:
- speed, simplicity, portability, and security
- can be hosted anywhere
- no server-side application dependencies, databases, or installs needed
- you can test them locally

If you don't have these prerequisites prepared, you can go to [Resources](#resources) to find links and tutorials in order to get started.

## Instructions

The below instructions are for MacOS. If you are working on a different operating system, check [Resources](#resources) to find a link to instructions on how to install the various software.
<!-- TO-DO: complete this -->
1. Install Jekyll

Test

2. Create a repository

3. 

## Resources

- Learn Markdown [here](https://www.markdowntutorial.com/).

- Download Visual Studio Code [here](https://code.visualstudio.com/download).

- Buy Modern Technical Writing by Andrew Etter [here](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS).

- Install Jekyll for other systems [here](https://jekyllrb.com/docs/installation).

## Authors and Acknowledgements

Credit to the template author for the template used in this project.

Thank you to my group members Hamdi Elzard, Dirk Page, and Dane Wanke for their help and feedback in the creation of this page.

## FAQ

### **1. Why would I use Markdown over a WYSIWYG editor such as Google Docs?**

Some reasons to use Markdown over another text editor include:

- It can be used for anything
- It’s portable (you can move to any platform easily)
- It’s platform independent
- It’s future proof (even if your application stops working, you can still read Markdown)
- It’s used everywhere and many things support it
- It's easily exported to other file types such as PDF

These are also reasons why people use Markdown outside of code related projects, such as for note-taking and

### **2. Why are my changes not showing up after a commit?**

It can take up to 10 minutes for changes in your site to publish. If it takes longer than an hour, there may be something wrong. Check [About Jekyll build errors for GitHub Pages sites](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-jekyll-build-errors-for-github-pages-sites) for more information.