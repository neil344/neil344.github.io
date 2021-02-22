---
title: Customising Cayman theme
categories:
- Web
feature_image: "https://picsum.photos/2560/600?image=872"
---

In our main page we setup a static website using Github pages and we installed Cayman Theme to give us a starting point to build a blog but we need to tweak a few settings first.

<!-- more -->


Go to our repository and click "add file" and name it index.md and then click "commit to file" ![figure 19.jpg](/assets/images/figure 19.jpg){:class="img-responsive"}  


Now click on index.md and click pencil edit icon ![figure 23.jpg](/assets/images/figure 23.jpg){:class="img-responsive"}  

Index.md will be the first page of our site and we need to create the title of our story first and the story itself second and click commit changes ![figure 24.jpg](/assets/images/figure 24.jpg){:class="img-responsive"}  

and now we have this ![figure 26.jpg](/assets/images/figure 26.jpg){:class="img-responsive"} 

So far so good but what if we want to add images. Lets go to our repository and click create file ![figure 27.jpg](/assets/images/figure 27.jpg){:class="img-responsive"}  

Now type in uploads/blank.md (notice how the uploads has turned into a folder) now click commit to file ![figure 29.jpg](/assets/images/figure 29.jpg){:class="img-responsive"}   

Now let's go back to our main repository and click uploads ![figure 30.jpg](/assets/images/figure 30.jpg){:class="img-responsive"}     

Click add file followed by upload file ![figure 31.jpg](/assets/images/figure 31.jpg){:class="img-responsive"} 

We can now drag or upload our pictures and click commit changes ![figure 32.jpg](/assets/images/figure 32.jpg){:class="img-responsive"} 

the format for inserting pictures is with location and name of picture between brackets  ![figure 33.jpg](/assets/images/figure 33.jpg){:class="img-responsive"} 

So let's open index.md and add our text for picture ![figure 34.jpg](/assets/images/figure 34.jpg){:class="img-responsive"} 

And here is our picture ![figure 35.jpg](/assets/images/figure 35.jpg){:class="img-responsive"} 

Now it's time to remove that "View on Github" button and change banner name  ![figure 36.jpg](/assets/images/figure 36.jpg){:class="img-responsive"} 

let's make a folder called _layouts and a file called default.html within it. Let's go to our main repository and click add file and create new file ![figure 40.jpg](/assets/images/figure 40.jpg){:class="img-responsive"}  

Name this _layouts/default.html and then commit new file ![figure 50.jpg](/assets/images/figure 50.jpg){:class="img-responsive"} 


we now need to go to <a href="https://github.com/pages-themes/cayman/blob/master/_layouts/default.html">https://github.com/pages-themes/cayman/blob/master/_layouts/default.html</a>
  and copy the contents of file and then go back to our _layouts/default.html and paste the contents into it and click commit to file. 

now lets go into _layouts/default.html and look for "</head>" delete everything below it and replace with 

![figure 42.jpg](/assets/images/figure 42.jpg){:class="img-responsive"}  


Now click commit to file 
 

And hey presto  ![figure 44.jpg](/assets/images/figure 44.jpg){:class="img-responsive"}  







      <script src="https://utteranc.es/client.js"
        repo=[neil344 /
neil344.github.io]
        issue-term="pathname"
        theme="github-light"
        crossorigin="anonymous"
        async>
</script>










