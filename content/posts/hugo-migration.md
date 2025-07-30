---
title: "Hugo Migration and some Miscellaneous Updates"
date: 2025-07-11T18:01:54-04:00
draft: false
tags: ["updates", "web-dev", "technology"]
---

Hey all! It's been a hot minute, so I thought I'd send out a post to talk about a few updates to the site and some others.

## HUGO Migration

This site has officially been migrated to HUGO! If you have no idea what that is, all you need know is it makes managing this site 10x easier. For those unfamiliar, Hugo is what's called a static site generator. Essentially, it takes my content (now being written in Markdown) and my site's design templates, and then automatically builds all the individual HTML files for the entire site. This means I write less code and can focus more on the actual content (something this site deperately needs more of).

This is a massive improvement in my eyes compared to the old HTML & CSS solution as it no longer requires the manual repetitiveness for sections like blogs or God forbid the navbar needs an update. Previously, adding a new blog post meant manually linking it on the main blog page, homepage, and anywhere else it may need a link. In addition, any small tweak to the navigation bar required me to go through and edit *every single page* on the site. Hugo now handles all of that automatically; I update a template once, and it propagates everywhere. This frees up so much time!

I've tried to copy the theme from the old site as best I could, so most of the changes won't be seen on your end. That doesn't mean there are none though! For example, thanks to HUGO, this site now has a fully functioning [tag system](/tags) for the blog!

All this may seem a bit odd after I made [this post](/posts/why-i-dont-use-web-frameworks) about avoiding web frameworks (which, I find funny as it's essentially the topic of the viral [justfuckingusehtml.com](https://justfuckingusehtml.com/) but before it fully kicked off), and after this experience, I somewhat retract some of those points. My previous stance was primarily about avoiding bloated client-side JavaScript frameworks for simple sites. Hugo, as a static site generator, operates differently as it's a build tool that runs *before* the site is deployed, producing pure HTML, CSS, and JavaScript, rather than a full-on framework. I still think default HTML and CSS is the way to go if all you need is a basic landing page and stuff like that, but for a growing content site like this blog, leveraging a powerful tool like Hugo dramatically improves workflow without sacrificing performance or the 'static' nature of the site.

## Professional site

I'll try to keep this one brief as my goal isn't to just plug my work. I'm excited to announce the launch of my [professional site](https://pro.thecoup.xyz)! Here is where you can find my professional services such as web development, server setup, hardware support, whatever IT.

In another yet similar ironic twist, the site utilizes Nuxt.JS + TailwindCSS as it's stack (or what I've been calling NuxtWind). Yes, I know, it's another complete contradiction, but it employers dig it, so ¯\\\_(ツ)_/¯.

If you're ever in need of low-cost tech support, do check it out!

## I'm going to uni

I've been meaning to write a post about this for a long while, and I still plan to, I've just been extremely busy with a bunch of things. But, yes, I'll be attending Bridgewater State University as a Cybersecurity major starting in *very* early September (in fact, I move in the last day of August).

That's all I can say right now, when I do start I plan on writing a post with all the juicy details.

## End

That's all I have for y'all right now, I plan on making this site more complete as time goes on, but until then.

73

## See also
- [HUGO](https://gohugo.io)
- [Just Fucking Use HTML](https://justfuckingusehtml.com/)
- [Professional site](https://pro.thecoup.xyz)