---
layout: post
title: Meet Utterances
categories:
- Web
feature_text: |
  Adding comments to your blog
---

Well, I was going to write a big long post about adding comments to my site and how long it took for a newbie like myself, until that is I heard about <a href="https://utteranc.es/">Utterances</a> by <a href="https://github.com/jdanyow">Jeremy Danyow</a>. 

It does what it says and takes only a few minutes to setup. Install the <a href="https://github.com/apps/utterances">Utterances app</a> on your repo and then add this script to the page you want the comments to appear. 

```html
  <script src="https://utteranc.es/client.js"
        repo="OWNER/NAME" 
        issue-term="pathname"
        theme="github-light"
        label="comment"
        crossorigin="anonymous"
        async>
</script> 
``` 

Nothing more to say, it just works, people just have to log into GitHub to comment and you even get emailed when comments come in. 


<script src="https://utteranc.es/client.js"
        repo="neil344/neil344.github.io" 
        issue-term="pathname"
        theme="github-light"
        label="comment"
        crossorigin="anonymous"
        async>
</script>  
