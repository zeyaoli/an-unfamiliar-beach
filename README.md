# An Unfamiliar Beach

An unfamiliar beach is a pure HTML and CSS website that visualizes Bei Dao's poem "An Unfamiliar Beach 陌生的海滩". This is the first assignment of Dynamic Web Development, Spring 2020

## About

An unfamiliar beach is a website that visualizes Bei Dao's poem "An Unfamiliar Beach 陌生的海滩". It only uses HTML and CSS to make. The website is made for the first assignment of Dynamic Web Development, Spring 2020 @ NYU ITP

## Set Up

Part of the point of working on the first assignment is to develop a website like a pro! Since I've developing some websites for a while, I don't feel any strange about these steps.

First step, we create a folder in our local drive, then open terminal (I switched to iTerm and started using oh-my-zsh, it changed my life tbh!) to type `cd` and the path to the driver so we can be inside the folder we are coding in. I also use `mkdir` to create folders in terminal now. After entering the folder, we got into our next step.

Type `git init` to initialize the git in the folder and then type `git add .` to add any changes (if there are any files) to the git, then type `git commit -m "some comments go here"` to finish the commit. 

Now switch to the browser. Go to github and create a new repository and copy the git address to the clipboard. Back to terminal type `git remote add origin address` to add the origin to the repo and then `git push -u origin master` to push it up to the internet. 

After that, we are pretty much done with setup. Just every time we want to make a change go repeat the add commit and push and we are good!! 

## Build
I build my page with VSCode and Github, then deploy to Glitch at the end

## Process
I felt like finding what did I want to do for this assignment was such a struggle! I kinda started with the idea of scrolling and making things transform from one place to another place. LiKE how emojis can make a combination and mean something, however, this kind of technique requires JavaScript to do and that's beyond the requirement. Thus I have to do something else.

I still kinda wanted to do something with emojis but when I placed a bunch of emojis in Figma, a tool for web design, I was not really feeling it. So I looked up on the Internet and found [SQRRL](http://www.john-russell.org/sqrrl.html), an hypertext website for a storytelling! I liked the idea of using a pure HTML and CSS page to tell a story or to visualize something. 

![Title picture of the SQRRL website](http://www.john-russell.org/SQRRL/SQRRL_ANIM_ANGEL_cyborg.gif)

Then I searched one of my favorite poet, Bei Dao's poem. Bei Dao is a contemporary Chinese poet. I found a poem that I like ["An Unfamiliar Beach"](http://wenxue.chnart.com/index.php?m=content&c=index&a=show&catid=182&id=5148) that has English translation so I decided to build on top of it.

I LOVE the idea of having pages taking the whole screen size (actually my portfolio page has the same technique that I used here). The website is currently divided into three "pages" yet all these are in the same page. Users don't have click anywhere to get to another link. The first page is the super minimal title page. Then I designed two pages for two sections of the poem (which I do want to keep expending for a bit). Each section I designed based on the text and tried to visualize the phenomenon that I interpret.

### Some techniques that I use for the page: 

[Gradient Animation](https://www.gradient-animator.com/)

Radical / Linear Gradient -> I use Figma to generate it and paste the code

Hover and expand the textbox: Use transition to change the height once hover and set overflow to hidden. Also be careful with the width. 

Animation: move the left position with keyframe animation

## Next Step

When I deployed to glitch I realize the embed audio didn't work well. It automatically downloaded my music instead of a player on the website. I need to fix that.

Also I want to make one or two more pages and then add a navigation on the title page. 