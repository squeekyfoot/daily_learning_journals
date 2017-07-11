# Learning Journal - Code 301 - Day 1

Today was the first day in code 301 and we learned about VMC designing. This week focuses on the "view" which is essentially the presentation of your site and the way your information is displayed on screen.

We did our first pair programming today towards the end and we were given a list of TODO's within some sample code. We were able to complete four of five of the TODO items but the last one--the media query--was giving us some trouble.

In the end, we ended up submitting what we had at 6 oclock and since I was feeling a little under the weather, I decided just to sleep on it.

In the morning, I was able to bring up the code again and look more in-depth at the issues that were popping up in CSS. I was able to open up the dev tools in my browser and slowly look at inherited values in my CSS to see what was preventing me from displaying the nav items from my html file.

I found out that I was having a specifity issue with the media query rule. I was targeting li items to have them displayed as inline blocks, however, in another CSS file, there was a rule that was more specific and was overriding my rule. It was a .main-nav li selector that was causing my links to stay hidden.

It was a nice little problem to figure out because it helped improve my troubleshooting skills a little bit further.
