# About
Here will be where I write my thoughts and plans each time I open this document. 
The latest entry will be at the top and everything else will be pushed to the bottom (only applies to new day entry).
I will be following a format as follows:

##Date
Plan:

###time
Entry

### Note to self
All DevLog changes done on **"main" branch.**
When experimenting with new stuff **_create a new branch_**!

## 080424
### 1520
I managed to get the sliding animation for the welcome to work. But I still need to **make a loading screen**. The font just doesn't load in time before the animation plays. It's going to be damn janky. :/ 
Some isssues I'm currently facing is that I don't actually know what is considered as fully loaded versus paritally loaded. Or if I can even just check if certain fonts are loaded yet.
If I can check only certain parts can just load those first it will be great. 
It could also be that it was a mistake using obscure, but good looking, webfonts

## 070424
### 1135
So, after some thinking, I probably will be **using flask** for this particular project. Through it I plan to learn the basics. Then I'll **pick up sql** for databasing stuff. Up till now I"ve mostly just been hardcoding some of the permanent stuff like the intro page and nav bar into the html and css. I don't even know if that's what I should be doing, cuz idk what flask needs me to do in the front-end side of things. Hopefully nothing too much needs to change. I haven't even included a js beacuse I wasn't sure if it will interfere with the python code.


## 030424
Plans:
just mess around more with css. At least get the Intro section looking pretty legit

### 1340
Trying to add the background that looks just right (but honestly I need to add more stuff to see how it works). 
I noticed how the welcome text takes a while to load when entering. It should be fine cuz I'm planning to make animations on it, but... It concerns me
thus I **should make a loading screen**. just another thing to consider. 
I also need to read thru this doc again to see what I missed so far. 
I'm thinking of making the **"welcome" background** turn from **whatever colour to white from left to right**. 
That should be it for today I guess. 

## 020424
plans:
figure out RWD
commit into new branch.

### 2140
I was playing around with the animations. thought of this pretty cool thing. 
Also I think, the last line will just **suddenly pop out of nowhere** just before the person scroll or when they are in the **midst of scrolling**.
 

### 0840
so basically I'm planning for the intro section to fill up the whole screen, then I need to make 2 versions. One for com, one for phone. I'm not sure how the phone one should look like so I'll do computer first. I'm guessing that if I'm going to use this as portfolio, they will probably try on their com first. Then during the explanation section, I'll allude to the fact that it has RWD (not a very impressive feat, but still something i suppose). honestly, RWD is not totally needed. 

### 1250
I've been playing around with how to make my website more responsive first before actually adding designs and whatnot. 
Anyway, I'm thinking of also changing the website to check for network connectivity, **If it's poor, then just load everything, no animations (or minimal)**. 
Otherwise, just do all the animations and what not. 
This is assuming that playing the animations require good network 
(the thought is that the end-user has to download all the media into a cache or smth then need to load it.)


## 010424
### 1530
I decided to add some stuff to the html and css because, where I am now, I cannot do much. Thus, I just decided that I should at the very least figure out something for the website. There are some ideas I have, which I've written as comments in the html. but to summarise the more important stuff here: I am now planning to do even bigger things. For example, I need to **program a small website game** (maybe even make it 2 player) and then have an **adventure style game** (which I have 0 idea what it should be based on). Not to forget, I haven't even started actually learning to do the backend of the site yet. Plus, I still need to refigure out some stuff about javascript. So yeah... I might be biting off more than I can chew here. I suppose the best option now is just to take things one step at a time. 

## 240324
Plans: 
- Start learning django (or at least installing it)

I don't have a lot of time today so that's about it
### 1000
I started the django tutorial but am now figuring out how virtual environment works lol
### 1030
making a venv. Just realised I'm in the main branch oops
### 1100
Just merged everything into the stuff. 
Turns out installing files into the active branch is a very unwise thing to do. Especially after making commits lol... 
Next time whenever I am not sure what in the world I'm doing I'll do them in another branch. Though I'm not sure how that would work exactly. 

## 230324
Finally starting with the website. At least I'm writing something in this doc. There are many things I have to do. For now the plan is to
Get everything set up properly in github
- such as the main and other branches
figure out the general flow of how to make a website that uses python...
- as of now I figured out that I'll probably be **using django** *(which I have 0 idea how it works)*
- I will need to make a **html and css backbone** *(not sure how JS will fit into everything)*

### around 10pm?
What I've done:
I've set linked VSC to github
started this doc
learned about django's existence

### 2300
So, I've set up the barebones of the website. Everything's gonna be placed into the unlaunched branch for now.
I've also redownloaded python onto the computer. Trying to download django now... but for some reason even though I downloaded python from the python.org site, it's not recognised on the computer. I think I need to restart my computer. 
Thus, I'll be restarting the computer and stopping for the day. I may or may not continue tomorrow. Still need to prep to get back to camp.
Also there are going to be pull req problems when it comes to DevLogs LOL.
I also forgot to mention that I've learned about classes in python. Pretty cool stuff.
