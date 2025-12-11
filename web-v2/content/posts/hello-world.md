+++
title = "Hello World"
date = 2025-12-11T20:09:09+01:00
+++

When I first created my personal website, I challenged myself to code everything from scratch to fully understand web design with Figma, HTML, and CSS. I really enjoyed the process, and I remember those summer days when I kept stumbling over how to turn the design I created into HTML and CSS.

Over time, I realized that my ~~noobish~~ homemade system wasn't very efficient and, around the same time, I kept hearing about Hugo on YouTube (*I even watched [this helpful video](https://www.youtube.com/watch?v=ZFL09qhKi5I) by Luke Smith*). Since it's an open-source static site generator written in Go, I decided to rebuild my site using this technology as a learning opportunity.  

With my old setup, updates were really tedious: I had to create a new file for each blog post and manually add links to the blog section (*it feels embarrassing to write this down hahaha*). Now, content organization with Markdown is easier (*I can even create posts directly from the command line*). Plus, if I ever want to switch from the Poison theme, I can do so effortlessly without worrying too much.  

Setting up Hugo wasn't complicated at all:  
1. Installed [Go](https://go.dev/) and [Hugo](https://gohugo.io/).  
2. Cloned the Poison template into the `themes` folder.  
3. Configured `config.toml` to customize the sidebar and added images + a favicon to the `/static` folder.  
4. Tested the site locally with `hugo server`.  
5. Created this blog post with `hugo new posts/hello-world.md`.  
6. Created the static site with `hugo` (*by default, Hugo outputs the static site to the public/ folder*).

While I've read that Hugo can have a steep learning curve, I’ve found it to be very accessible (*at least at this level*). I can now focus on writing and sharing projects instead of rewriting styles and pages manually.  

In case you weren't able to see it, here is a comparison (before & after): [^1]

![Before redesign](/images/before.jpeg)

![After redesign](/images/after.png)

[^1]: I'm honestly quite proud of the original design, but I prefer simplicity in functionality over aesthetics. I might redo it as an Hugo template if I keep learning more.

Anyway, if you’re thinking about moving to a static site generator, I highly recommend giving Hugo a try to create your portfolio or personal blog. See ya! ♡