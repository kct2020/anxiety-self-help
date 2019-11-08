---
title: Install Shrewdies Site Starter
categories:
- General
feature_image: "https://picsum.photos/2560/600?image=872"
---

Deploy Shrewdies Site Starter to Netlify and configure the basics.

<!-- more -->

##  Install Shrewdies Site Starter
When I first deployed this from https://github.com/daviddarnes/alembic the build failed because there are no build instructions in that repository. However, this was easy to fix by copying ```netlify.toml``` from https://github.com/daviddarnes/alembic-kit. But you don't need to do that because I've changed the original Alembic theme repository into a Netlify starter kit for Jekyll website creation.

So all you need to do is edit ```_config.yml```. Then you can edit the contents of ```index.md```, ```\about\```, and ```\_posts\```. Or delete the contents of those files and add your own.

I will assume you are going to edit the contents. So you should follow the notes that I've presented in these example blog posts.

##  Configure Shrewdies Site Starter
Your first step is to change my details in ```_config.yml``` to your own. As I believe this is straightforward, I do not include detailed notes here. However, if you need me to add more explanations, please ask using my <span style="color:orange">Feedback Form</span> below.

Similarly, edit your home page in ```index.md``` to match how you want to introduce your website.

##  Your Jekyll Site Starter
Now you should have a working website. But you must delete or replace my About Shrewdies pages before you publish your website to the public. So delete the contents of ```/about/``` now. Or see my next post to learn how to edit your own About pages.

While you're waiting for the next step, it's a good idea to subscribe to my update service. That way, you'll be the first to know when I publish new information on this website. Note that I explain how you include your own notification and feedback services as part of amending the About Shrewdies pages.

#### Feedback for Install Shrewdies Site Starter
- Oct 29 2019 - *Resolved* Next/Prev navigation missing from news blog entries. See premium page map for solution regarding edits to posts layout and css files.
- Oct 29 2019 - *Issue* Annoying but not serious affect on performance from font files.
- Oct 30 2019 - **ToDo** Configure Google Analytics (GA). Probably need to change Netlify site name before registering with GA. 
- Nov 08 2019 - **ToDo** Configure favicons. NB - there seems to be lack of agreement about which icons are necessary. Especially since the top result for ```what favicon sizes do i need``` search omits 512x512 needed for manifest and omits 16x16 despite lots of explanation about it. However, that's a much-revised post so more research is needed if this is important. For now, I've gone with 4 sizes: ```# 8. Site favicons & manifest icons
favicons: # Favicons are also used in the manifest file. Syntax is 'size: path'
  16: '/assets/logos/logo@16px.png'
  32: '/assets/logos/logo@32px.png'
  180: '/assets/logos/logo@180px.png'
  512: '/assets/logos/logo@512px.png'
```
