<!-- title: JAMstack-->
<!-- author: Le singe vert -->
## idea title Medium article
JAMstack-stick
How JAMstack save me from my tutorial fatigue
Why beginner web-developper self-learner should try JAMstack?
As a self-learning web-developper I've tried JAMstack and found it great

### My road to find a "simple" tool.

First, I have tried a Content Management System or CMS. It is the most convenient if you want to build a web site. [Here](https://wedevs.com/160609/best-cms-platforms-comparison/) is a CMS comparison. [Webflow](https://webflow.com/discover/popular#recent) was advised in the UX/UI bootcamp I did. 

However, [Wordpress](https://wordpress.com/) is the most popular CMS. There's a lot of tutorials. It is free to start. If you invest your learning in it which means to be able to customize your web-site using plug-ins and some code (wordpress is build on PHP), it is a very marketable skill.

It is a very comprehensive and powerfull tool. However, I felt like using a word-processing software where you press "publish" and tadaaam. Simple but, at the end, it would fulfill only one of my goal: building a blog. I want to practice my brand new coding skill, as well.

I read some articles about [JAMstack](https://jamstack.org/). It seems the new, cool thing about building simple websites. I have to admit something: I am a fashion victim.

### pre-requisite

Compared to a Content Management System ([A CMS outlook](https://wedevs.com/160609/best-cms-platforms-comparison/)), JAMstack need some programming knowledge. 

The pre-requisite are: use some terminal commands and manage a Git/Github repository. In order to customize your site, you need to know some HTML, CSS and Javascript. You don't need to be an expert in any of those, a beginner level is enough. All the basics of those skills can be acquired in a few weeks.

You have to pick up some tools: a "SSG" and a "CDN". And you have to know how to write a [markdown](https://www.markdownguide.org/)file. Most of markdown can be learned [in 15 minutes](https://www.markdowntutorial.com/). In a nutshell, A content delivery network (CDN) is a group of servers which will deploy your site: some HTML, CSS, Javascript files with images and videos and a Static Site Generator (SSG) will turn some markdown files into a site (HTML, CSS, etc).

So here are the 3 steps of how to build a JAMstack:
1. write some markdown files
2. convert automatically those markdown files into a website files (HTML, CSS, JS, etc) with a Static Site Generator (SSG)
3. deploy this site with a Content Delivery Network

About the design, most of the SSG give you pre-defined themes and the possibility to design your own. 

On a user-friendly perspective, you can use a [headless CMS](https://jamstack.org/headless-cms/) for users you would just produce the content, instead of writing raw markdown files. At the end, you get the confort of a traditional CMS.

There is a lot of Static Site Generator (SSG). Which one to choose? They are a lot of [choices] (https://jamstack.org/generators/).

There is two filters that can help narrowing the choice: languages and purpose. 

I see three categories of SSG considering the purpose:
- to design a beautiful profesional site. Those generators have their site with a "showcases": ie, [Next.js](https://nextjs.org/showcase), [Gatsby.js](https://www.gatsbyjs.com/use-cases/), [Hugo](https://gohugo.io/showcase/), [Jekyll](https://jekyllrb.com/showcase/)
- to document a project. Those generators help to built very fonctional sites mainly linked with github repositories and deplyed with github pages: ie, [slate](https://slatedocs.github.io/slate/#introduction),[gitbook](https://www.gitbook.com/), [docsify](https://docsify.js.org/#/)[mkdoc](https://www.mkdocs.org/)
- to DIY. To be honest, this is a catch-all-what-remain category. There are generators "simple and lightweight", like ... which 

Considering language, there are a lot of generators built on javascript and their famous frameworks (NextJs, Gatsby, GridSome), Jekyll and Ruby, it is interesting to note Hugo as a very popular generator built on Golang which is a promising but quite young coding language,  

First filter: Python and Ruby are the coding language I have some knowledge of. So [Pelican](https://blog.getpelican.com/) and [Jekyll](https://jekyllrb.com/) might be cool to try first.

They are easy to use and well documented, with tutorials very beginners friendly. Jekyll is very impressive. [Here](https://www.wearecollins.com/) is an example of web site build with Jekyll. Amazing, isn't it? And there are [plenty of them](https://jekyllrb.com/showcase/).

With Pelican, I followed this [step-by-step](https://bitstudio.dev/make-a-netlify-website-with-pelican/) and I was able to display a real website in 1 hour. 

They are great tools however too elaborated for my purpose: building my blog and using my three months programming knowledge to customize them.

I found this humble [makesite.py](https://jamstack.org/generators/makesite/) based on Python and I found immediately in love:
- I was able to make a first website in less than 1 hour,
- I am able to open the hood and play with the code and start customizing my site.

## attention aux versions de Python
commonmark.py is tested against the CommonMark spec with Python versions 2.7, 3.4, 3.5, 3.6, and 3.7

