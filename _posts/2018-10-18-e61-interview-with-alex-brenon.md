---
layout: podcast
title: "E61 – Interview with Alex Brenon"
type: podcast
summary: "Alex is a developer who has experienced the difference between baking in accessibility from the start compared to trying to retrofit accessibility into an existing project – which leads to a lot of trial and error and wasted time."

permalink: /podcast/e61-interview-with-alex-brenon/
# Podcast Episode Metadata
episode_type: full
episode_number: 61

# Audio Information
audio_url: # 5. podcast URL from WP page
audio_type: "audio/mpeg"

# Duration
duration: "PT20M02S"
duration_formatted: "20:02"

# Series
series: "A11y Rules Podcast" 

# Episode Artwork


# Author/Host
author: "Nic Steenhout"

guests:
  - alex-brenon
  

# Content Rating
explicit: false

# Categories/Tags
categories: original
tags: 
---


<div class="audio-container">

<h2>Listen to the episode</h2>
<audio id="audio1" data-able-player preload="auto" data-heading-level="2" data-speed-icons="animals" data-root-path="/podcast-dev/assets/ableplayer/">
  <source type="audio/mpeg" src="{{ page.audio_url }}"/>
</audio>

</div>


<details>
    <summary><h2>Transcript</h2></summary>
    <p><strong>Nic</strong>: Welcome to the Accessibility Rules Podcast. This is episode 61. I’m Nic Steenhout and I talk with people involved in one way or another with web accessibility. If you’re interested in accessibility, hey, this show’s for you.</p>
<p>To get today’s show notes or transcript, head out to <a href="https://a11yrules.com">https://a11yrules.com</a>.</p>
<p>This week I’m speaking with Alex Brenon. Thanks for joining me to this conversation around web accessibility Alex. How are you?</p>
<p><strong>Alex</strong>: I’m good, how are you?</p>
<p><strong>Nic</strong>: I’m doing very good. Ah, look Alex. I like to let guests introduce themselves so in a brief elevator style introduction. Who’s Alex Brenon?</p>
<p><strong>Alex</strong>: Okay. Yeah, so I’m a relatively recent graduate of Smith College. And since then I’ve been working in blended learning and digital humanities. Which is basically just the intersection between technology and learning and teaching and research. And last year I was given some time and resources to explore whatever facets of technology or career development I was interested in and I chose accessibility and that’s how I got started.</p>
<p><strong>Nic</strong>: Right. How did you come to pick accessibility? What was the impetus on selecting that particular topic?</p>
<p><strong>Alex</strong>: I think I’ve always been interested in accessibility. I’m also interested in education and through that making knowledge accessible. In more in the sense of open access so it had been something that I didn’t know anything really at all about but had always kind of thought about.</p>
<p><strong>Nic</strong>: Right. So how do you weave that into your job day in, day out? What … how do you implement accessibility? What’s your tasks with that?</p>
<p><strong>Alex</strong>: Well, it’s really interesting for me because last year I was designing new parts of a Drupal website and got to kind of just bake accessibility into that. Whereas this year I am also designing a new WordPress site but also working with existing ones and so this year it’s much more about trying to figure out how to get accessibility retrofitted or see how we can change things to kind of focus on that.</p>
<p><strong>Nic</strong>: How do you go about that retrofitting accessibility into an existing site?</p>
<p><strong>Alex</strong>: It definitely helps that I have done development from scratch before and I’m given all the leeway I want to kind of run with it. But basically, it’s just a lot of trial and error. Honestly just trying to see how to change things that won’t break everything else…</p>
<p><strong>Nic</strong>: Yeah</p>
<p><strong>Alex</strong>: …but make certain parts more accessible.</p>
<p><strong>Nic</strong>: So you say you’ve been given leeway… how is leadership in the organization you work at supporting you in… specifically giving you leeway? You know, are they saying, “Just go to it” or are they giving specific supports or… What kind of shape and color does that take in your specific job?</p>
<p><strong>Alex</strong>: So, my department is just my supervisor and I.</p>
<p><strong>Nic</strong>: Okay</p>
<p><strong>Alex</strong>: But he’s very supportive of both giving me time and being very open to when I say “we can’t really move forward with this because it’s not going to be accessible” and saying alright,” let’s step back. How can we make this better? “. So, he’s showing.. My supervisor is showing that he’s also committed and interested in making things accessible.</p>
<p><strong>Nic</strong>: Alex, tell me something that most people would not know about you.</p>
<p><strong>Alex</strong>: Hmmm… I guess I have done a lot of acting in musicals. Both throughout all of Highschool and then into College. So that’s been a pretty big part of my life. Like, outside of work.</p>
<p><strong>Nic</strong>: Cool. Do you see some similarities between doing musicals and working in development and specifically working with accessibility?</p>
<p><strong>Alex</strong>: Um… I will say learning to think on my feet has kind of been something that’s come from all sides of my experience. Both development and acting. And so that’s kind of feed off each other of trying to work little pieces of things into different ways and make them better.</p>
<p><strong>Nic</strong>: Yeah. Yeah, I think it all ties in at some point to… to be able to… you know, pick experiences in one area and apply them to others. So, you say you are a recent graduate you’ve been diving into accessibility for about a year. What kind of barriers are you finding on your way to learn more about accessibility and develop your skills and develop your skills and make sure things are more accessible on the web? Are you finding barriers? Or…?</p>
<p><strong>Alex</strong>: Overall I’ve actually had a relatively easy time I would say, compared to… I think, some other peoples experiences. Partially because at my… at the job I was working at last year, we were in the process of finding a new accessibility guide, I guess, for people who worked both in my department and beyond and so I got to take… try out a lot of different courses.</p>
<p><strong>Nic</strong>: Right</p>
<p><strong>Alex</strong>: So, that worked out really great because I… at that point I knew quite a bit about accessibility but those courses allowed me to really… kind of, delve deeper. But outside of that, I’d say the only main barrier is it’s…there’s not a tonne of things for people who aren’t developers. So, I am but some of the things I’m working with are much more design-oriented when I look toward accessibility it’s things in design, sometimes, less than development. And so when I ‘m looking at those there’s not always as much on the devel… on the design side.</p>
<p><strong>Nic</strong>: What resources would you like to see on the web specifically towards design? You know, what kind of issues have you come across that you can’t find the answers about?</p>
<p><strong>Alex</strong>: Well, one thing I really like is there’s a couple of accessibility pattern libraries and I think making more of those or actually just adding more documentation is…would be very helpful and just kind of documentation in general aimed at beginners that’s not behind some kind of paywall but your organization has to give you access to.</p>
<p><strong>Nic</strong>: Yeah. Those pattern libraries are quite fantastic and, yeah, we probably… we as a community should look at growing those. So you’ve been on this journey for about a year… a year and a half more or less. What was the biggest surprise you had when you learned more about accessibility?</p>
<p><strong>Alex</strong>: I think… I guess there’ve kind of been a couple of things and one is… I guess is… it’s interesting to remember how many people need accessible technologies because that… certain parts of that haven’t been part of my experience or part of the experience of people who I ‘m close friends with. And so being exposed to user stories has been fantastic. And helps me remember why I’m doing… Like why I’m fighting for these things. But also I would just say the fact that making things more accessible makes it easier for everyone. Which I knew definitely in content and I had kind of worked a little bit with that since College but really implementing that and seeing how incredible much easier accessible websites are to access for everyone else as well as just general accessibility things.</p>
<p><strong>Nic</strong>: Yeah, I think that’s… that’s an aspect a lot of people don’t really think about until they start thinking about it. Is that accessibility does benefit everyone and it… I think it’s a selling feature of accessibility that, you know when you’re trying to convince leadership… obviously, you don’t have that issue in your current employment but often when we’re trying to sell accessibility, finding this “It benefits everyone” seems to have a great impact. Unfortunately, it’s not enough to say, “Hey, you know what… there’s maybe 20% maybe 25% of people with disabilities out there that really need this” and it’s amusing that leadership will worry about that 3% of people that are using IE11 still but they’re not worried about the 20% of people that can’t get to the site because they have a disability. So… yeah.</p>
<p><strong>Alex</strong>: Oh I know, when I was developing last year we were going back to IE9 for some things to make sure that everything worked.</p>
<p><strong>Nic</strong>: Yeah</p>
<p><strong>Alex</strong>: So, yeah definitely… I guess, allowances are made for a lot of different things but not always accessibility.</p>
<p><strong>Nic</strong>: You’re a new kid on the block so your perspective is fresh… What do you think the biggest problem the field of accessibility has right now?</p>
<p><strong>Alex</strong>: I think… I would say probably buy-in from upper levels. I think it’s still being seen as… like you said, just this really small amount of people who… why does it matter? But I hope that that will start changing and I think that as it becomes easier to make things accessible that will change a little bit so it’s not… you’re not asking for, you know, a huge part of the project to go towards… specifically accessibility it’s just making everything in general accessible.</p>
<p><strong>Nic</strong>: Yeah. Build it as, you know, it’s not an afterthought. It’s part and parcel of what you do.</p>
<p><strong>Alex</strong>: Exactly.</p>
<p><strong>Nic</strong>: Is that where you’d like the field of accessibility to be in five years? Or in ten years? Or is there something else that you’re having hopes for, for our field?</p>
<p><strong>Alex</strong>: I would really just hope that it becomes more mainstream. And that people who are even outside of tech are aware of accessibility and in their daily lives kind of can notice when things are accessible because it’s… if we as a society can get there then life would be much easier for… well, everyone.</p>
<p><strong>Nic</strong>: Yeah, yeah…yeah. Hey Alex, I know you have not been doing this for very long but is there something you’ve achieved accessibility related that makes you really proud?</p>
<p><strong>Alex</strong>: I would say… I can’t think of anything specific but I am proud of the fact that although this is relatively new to me I’ve been really pushing hard to make sure that things we are making are accessible. And I’m definitely reminded of it now when I’m retrofitting that I am very glad that when we were designing the first site that it was… I was kind of baking that in as it started as opposed to making someone come by a couple of years later and realize they have to change things.</p>
<p><strong>Nic</strong>: Yeah. So, you mentioned earlier you’ve been using Drupal and now you’re working with some WordPress sites… What’s your experience with making these two platform.. Sites on these two platforms accessible? Are you finding one is better than the other? Or they’re pretty much equal with different idiosyncracies or … tell us a little bit more about that experience.</p>
<p><strong>Alex</strong>: I would definitely… I think it’s a bit hard for me to compare them since I have only been doing WordPress for a relatively short amount of time compared to Drupal. But overall I would say they’re… they each have their own idiosyncrasies. In my basic searches, I found Drupal themes are more likely to have accessibility-ready features whereas WordPress there’s just less options which has just been this past week I’ve been searching for themes for our new site. And a lot of WordPress themes, if they’re not tagged with accessibility-ready they often just haven’t thought about it at all.</p>
<p><strong>Nic</strong>: Yeah</p>
<p><strong>Alex</strong>: Which kind of makes it harder to start with. So yeah, both of them… they’re both heading in better directions, for sure. And…</p>
<p><strong>Nic</strong>: What’s the one thing you’d like people to remember about accessibility?</p>
<p><strong>Alex</strong>: I guess hoe relatively easy it is to make some really small changes that make everything better. So there are some really basic accessibility things that when you change them the overall user experience is so much better and it’s not just… it’s not some huge thing that it’s all or nothing. Your site is either completely accessible or it’s not at all but making those little changes is how you get started to making it better,</p>
<p><strong>Nic</strong>: Yeah, I like that. Give us a couple of examples of small changes that developers can implement, like, today to make it accessible.</p>
<p><strong>Alex</strong>: So a couple of things are just like, adding skip links so in your navigation you’re going to be able to get around better. Also… so, my top two pet peeves are… One: links that only say click here or something similar because that’s just really unhelpful. So adding more link text so saying something about “read more about our programmes” or something like that. And then also images that don’t have alt text are really… it’s so easy to just add some type of alt text and you can really get great alt text going and that’s when things really kick up to the next level of accessibility. But just adding some type of alt text to let users know what they.. What they would be… what’s going on and that page which also benefits if people are using, lets, say outdated Internet Explorer or a device that has really low internet capabilities then they will also be able to learn about the image that is appearing there if you have the alt text.</p>
<p><strong>Nic</strong>: Yeah. Yeah, I think these are great examples. I’d also like to refine the idea of alt text that it’s super important for informative images but perhaps decorative images are better served with empty alt attribute I think.</p>
<p><strong>Alex</strong>: Yeah. Well, that and also right giving it an empty alt text will help if the rest of the site is correctly described then it’s obvious those images are not giving any meaning.</p>
<p><strong>Nic</strong>: Yeah context is everything. Alex, thank you for your time Thanks for being a willing participant of the accessibility rules podcast and I… I really wish you well in your journey into accessibility because you sound like you have passion and it’s great. Maybe you’ll get to a point where… you know, you’re the new guard coming behind us. So thank you for that.</p>
<p><strong>Alex</strong>: Thank you.</p>
<p><strong>Nic</strong>: Everyone out there, thank you for listening to the show. I hope you enjoyed it and if you do, please do tell your friends about it.You can get the transcript for this, and all other shows at <a href="https://a11yrules.com">https://a11yrules.com</a> and a quick reminder, you can get yourselves some neat accessibility rules branded swag at <a href="https://a11y.store">https://a11y.store</a></p>
<p>Catch you next time!</p>
</details>

## Show Notes
<!-- leave blank -->

