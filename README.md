# setcha.github.io
Made for CSCI 3715, HCI
Seth Chatterton


Usage

Website:
https://setcha.github.io

With source code and files:
1. cd to the folder that the site is in. (The first directory with index.html)
2. Type "bundle exec jekyll serve" on command line.
3. Go to http://127.0.0.1:4000/ in your web browser.


Design Decisions
On the front page, I tried to give the site a Z-pattern to guide the eyes of the user around. The user will probably look at the bold header first, then right over to the navigation bar, look at the large picture, and finally down to the blog posts. This front page format also matches the eye's natural F-pattern. I put the most interesting things at the top, so that the user can see them immediately, but the user can also quickly identify the blog posts coming out from the left side of the screen in their bold boxes.

I decided to go with the font Menlo, because I've always liked the way that code looks, and I think it matches the neat, precise doodles displayed in the blog posts. I chose a light gray as the background because it matches my perception of what "tidyness", "precision", or "machinery" should look like. Around the pictures and blog posts, I put bold highlighting boxes to make each element distinct. I think the bold boxes go well with the Menlo font, but I wonder if I made the boxes a little too bold.

Technical Note: While I never used the "minima" theme, I didn't manage to get rid of the places where it is called from, because many unhelpful errors appear after I attempt to remove all traces of "minima". So, I left the original gemfile in, even though I don't use the minima theme.


Challenge

First of all, I found it very difficult to do graphical design when I was working with the text instead of the graphics. For me, it was a lot of trial and error to get things looking ok. 

I followed the Jekyll tutorial for most of the first few hours, and from there I had a very basic working website with Jekyll. The longest step of the whole process was when I was stuck for an hour and a half because I did not realize that post markdown files have to have a date in front of them.

I had never really used CSS before, so it was interesting to learn what I could do with it. I don't think I used it nearly to its full potential though. It took me a long time to get the black borders around everything I wanted to, along with centering pictures horizontally.


This was also the first time I have used Github Pages, but setting it up was fairly easy. One glitch, however, that I couldn't fix is that on the posts, the black boxes around pictures do not appear, only when viewd on Github Pages. It works on my local computer, but maybe Github pages doesn't support the same kind of styling that I was using for the boxes.'


Credits

https://jekyllrb.com/docs/step-by-step/

https://www.w3schools.com/howto/howto_css_topnav_right.asp

https://www.w3schools.com/tags/tryit.asp?filename=tryhtml_img_border_css

All of my photos and artwork are original. (Seth Chatterton, 2019)

