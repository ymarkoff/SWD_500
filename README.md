# SWD_500
The project follows the presentation website of Alter World Simula, a Platform side-scroller video game developed in JavaScript.

The website’s purpose is to serve as a portal for the game, containing both the game in a landing page, as well as to provide promotional material, guides and even a recruitment form for people who want to join the development of the project.

# Installation
Running this website is as easy as hosting it and opening the index.html page. But if modifications are to be made, the following scripts needs to be executed in the top-level directory:

`npm install`
`node-sass --watch sass/main.css css/main.css`

# Repository
The active repository of the project can be found here:
https://github.com/ymarkoff/swd_500

# Website
The hosted version of the website can be found here:
[http://alterworld-rpg.com/website/](http://alterworld-rpg.com/website/)

# Screenshots
A list of screenshots taken from some pages of the project(in both Desktop and Mobile versions):
`![Index(Desktop)](http://alterworld-rpg.com/website/screenshots/index_desktop.png)


![Index Mobile](http://alterworld-rpg.com/website/screenshots/index_mobile.png)

![Development Desktop](http://alterworld-rpg.com/website/screenshots/development_desktop_1.png)

![Development Desktop](http://alterworld-rpg.com/website/screenshots/development_desktop_2.png)

![Development Mobile](http://alterworld-rpg.com/website/screenshots/development_mobile_1.png)

![Development Mobile](http://alterworld-rpg.com/website/screenshots/development_mobile_2.png)

`![Shop Desktop](http://alterworld-rpg.com/website/screenshots/shop_desktop_1.png)

![Shop Desktop](http://alterworld-rpg.com/website/screenshots/shop_desktop_2.png)

![Shop Mobile](http://alterworld-rpg.com/website/screenshots/shop_mobile_1.png)
`![Shop Mobile](http://alterworld-rpg.com/website/screenshots/shop_mobile_2.png)



# Reflection

## Introduction
Having worked on Web Development for years in the past, I was still proven by the project that this subset of Computer Science is ever-evolving and that there are new things to learn in it every day you get up from bed... yes, maybe even after just a nap.

## RWD Grid
I have done responsive development before, but in ways different than the RWD Grid. After spending some time knocking my head at it, I learned than in the end it's not really different than anything else in CSS - it doesn't seem to make much sense at the start, but once you get your hands dirty for long enough, it becomes a second nature of your coding. I'm not even exaggerating when I say that by the end of the project I was making the needed calculations (*% - px style*) without even understanding consciously why the values I typed work in a scenario. That being said, I didn't become a complete guru even by that point - in the end I couldn't make a perfect square calculation for the shop grid items in the desktop viewport, and the mistake didn't seem easy to fix, like a missing 10px margin.
In conclusion, I think that the RWD grid is one of the best tools front-end designers have their hands on today - not because it's perfect, but because it's simplistic and that allows for better control than most others.

## Sass
In the process of this project's development I came learn and start using Sass's as a new way to "do CSS". I went through the trouble of learning it because I wanted to bring in some fresh experience in the sometimes monotonous CSS typing that's par for the course with every new web project. And by the end of my first few hours with it, it was already the way I was thinking "CSS" in. I have nothing but deep appreciation for this style's existence, although I have to mention that the preprocessor itself did give me trouble for more than a day. The pure time conservation that comes with typing in SCSS aside, what I appreciate the most is the nested class structure that came naturally with Sass.

## Development Process
At the time of posting this, I still have two pages from the planned site structure left to finish. More than anything else though, the reason lies within the late decision to do some serious remodelling of the planned design. Namely, not being happy with how the RWD development was going, I decided to switch from 12-column design with no rightmost and leftmost margins to one with such margins included. The redesign(in Figma) process made experiment and play around with new ideas of the visual design, like change of colors, introduction of a new font and even complete redesign of some pages(including removal of previously planned site pages and putting up new ones in their place). The main takeaway from this process of rapid re-development is that sometimes doing all designs separate from any (at least experimental) development is not always the best course of action. I can only imagine how much more redesign work would come with a project bigger than this one.

##  Future Plans
Except for completing the missing two pages from the website structure, I plan to continuously update this website in terms of both design and content, especially as the game that it's supposed to wrap around comes closer to release. Some of the plans I have at the point of writing this is doing some more complex design work, like creating better backgrounds and finding better color combinations. Last but not least, I would like to restructure the SCSS code, most of which is now based in a single _gridd.css file, before the codebase grows too large.