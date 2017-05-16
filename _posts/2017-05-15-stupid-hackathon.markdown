---
layout: post
title:  "Stupid Hackathon"
date:   2017-05-05 00:29:18 +0000
categories: blog post
---
# Stupid Sh*! and Terrible Ideas That No One Needs Hackathon

## Noisebridge pre-party with Godwaffle Noise pancakes

The hackathon started with a pre-party with music by Godwaffle Noise Pancakes, 
which is a noise band and waffles, er pancakes, er both, I am not really sure, 
I didn't check out the food. It was definitely loud! Renee, my collaborator on 
this project, and I used the time to brainstorm. 

## Awkward Silence Hotline is Born

We thought a lot about how technology has evolved and how 
communication really seems to flow so easily these days. With all of the options 
we have like texting, twittering, and snapchatting, just to name a few, it seems 
as though we can't stop communicating with other people. With all of that 
communication, don't you deserve a pause every now and then? Wouldn't be great if 
that pause went on just a little too long? We think you do, so we decided created 
Awkward Silence Hotline. Awkward Silence Hotline uses Twilio to allow  a user to 
call a number, pick from a list of customized options, and basque in the 
gloriousness of the artisianal awkward silence that follows.

## Hackathon Kickoff
    
Before we knew it, the concert was over and it was time for the hackathon to 
officially start. There were some stupid announcements, namely about spaces that
were available for hackers to use. For this hackathon Noisebridge and Double Union
teamed up to provide ample space for all of the terrible ideas to come to life.
There were also announcements concerning the materials and tools that were available
for us to use, as this hackathon was open to all kinds of ideas, not just technical
ones. 

People were then encouraged to share there ideas or request collaborators. This 
is always my favorite part of any hackathon. I love hearing all of the concepts
people have been dreaming up and are about to bring into the world. I think this
part is even better than the final presentations, because the possibilities at
this point are endless and even though the concept is born, it can still run in
so many different directions. This hackathon was particularly great because the
ideas were plentiful and awful. Many people encouraged other hackers to steal 
their ideas, which made the atmosphere all the more convivial.

## Starting Awkward Hotline

After everyone was done requesting collaborators and sharing ideas, it was time 
to officially set to work on our project. Renee and I set off in the fury of 
coding that is planning and breaking down the project into smaller pieces. We then
decided who was going to do what. 

It was very clear that we would need to get our site up and running fairly quickly
so that we could test out our app. We decided on Heroku for hosting, as it
is fairly straight-forward and simple to get things up and running. Setting up 
Heroku was my job and I did run into a little bug with pkg-resources early on 
which results from Ubuntu providing some incorrect metadata to pip. The fix for 
this is easy:

{% highlight bash %}
 pip freeze | grep -v "pkg-resources" > requirements.txt
{% endhighlight %}

While I haven't seemed to figure out entirely why this bug occurs, I do know 
that it is related to virtualenvs and will be researching further now that the
hackathon is over and I am not racing to complete a project.

We got our keys for Twilio, read the docs, played around a little bit to understand
exactly how things work. From there, it was not long before I got voice working. 
It was so great to the first time we heard the robo-voice on the phone reading 
back our script to us. We celebrated that small success, and I went to work creating
a menu of options for our callers. 

Once I got the menu working, I wanted to let callers record their own awkward silences,
so I set up voice recording. It was so fun to play around with this feature once
we got it up and running. 

While I was working with the voice features, Renee was setting up SMS capabilities.
She can tell you all about her process there. The end goal for her was to create 
a text bubble with the three dots to show that the person on the other end is typing.
We thought that this would be the equivalent of awkward silence for texting.

## Project Presentations

Before we knew it, it was time to head over to [Monument](http://www.monument.house/)
for the final presentations. We were blown away by all of the terrible ideas and
stupid sh@! that was created. There was a giant cover letter that would cover the 
desk of any recruiter, an app that would say grace and eulogize the meat that you 
eat, a group that moved piñatas into the future by gathering all the data about 
hits, artisanal therapeutic relaxation slime, upvote stickers for upvoting in real
life, and many, many other terrible ideas. The lucky winners were chosen at random
and received bricks as prizes. 
