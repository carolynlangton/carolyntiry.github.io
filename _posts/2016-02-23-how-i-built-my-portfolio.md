---
layout: post
title: How I built my portfolio
---

An online portfolio/blog/resume catch-all site has been on my to-do list for a while. I kept putting it off because I didn't want the baggage and bloat of a CMS like Wordpress, and I felt too busy with work, classes and homework to start completely from scratch. So when I read about [Github Pages](https://pages.github.com/) and [Jekyll](https://jekyllrb.com/), I figured I'd found a near-perfect solution.

I like that my site is all static files &mdash; it's super simple, easy to create new posts, a snap to back up, and I get an automatic version history because I'm already using Github for the repository. I can write my posts in Markdown or HTML. Github hosts the site for free (!). And I can still connect the site to a custom domain, if I so choose.

I found a great [semi-tutorial](http://joshualande.com/jekyll-github-pages-poole/) from Joshua Lande and got started right away. I used flavor of Poole (the Jekyll butler) called [Hyde](http://hyde.getpoole.com/). All I had to do was download the Hyde repository, push it to my repository on Github, and presto! carolyntiry.github.io was ready.

### Customizations

I added a [resume]({{ site.url }}/resume) page by adding a resume.md file and filling out the content with my professional qualifications. This is a perfect setup for me &mdash; the layout is simple and easy to read, but I can still link to development projects that I've worked on for potential employers to peruse.

I added an [archive]({{ site.url }}/archive) page by adding an archive.md file and, in it, looping through all the posts in my sites files to create a link for each one.

I used [Font Awesome](https://fortawesome.github.io/Font-Awesome/) to add some social media links at the bottom of the sidebar and added a simple CSS transition to make the hover state of the links pop a bit more.

I then used Joshua's guide to add Google analytics.

### Repository

You can find the [repository for this site on Github](https://github.com/carolyntiry/carolyntiry.github.io). Check it out, give me feedback on Github or [Twitter](https://twitter.com/carolyntiry), or use these resources to get started on your own free Jekyll site. Happy coding!
