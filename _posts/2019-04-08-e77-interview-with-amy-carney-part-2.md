---
layout: podcast
title: "E77 - Interview with Amy Carney - Part 2"
type: podcast
summary: "Amy Carney tells us accessibility is not just a checklist of standards but that we really are building experience for people and allowing them to open up opportunities."

permalink: /podcast/e77-interview-with-amy-carney-part-2/
# Podcast Episode Metadata
episode_type: full
episode_number: 77

# Audio Information
audio_url: hhttps://a11yrules.ams3.digitaloceanspaces.com/podcast/episodes/E077-a11y-rules-amy-carney-part-2.mp3
audio_type: "audio/mpeg"

# Duration
duration: "PT16M15S"
duration_formatted: "16:15"

# Series
series: "A11y Rules Podcast"

# Episode Artwork


# Author/Host
author: "Nic Steenhout"

guests:
  - amy-carney
  

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
    

<p><strong>Nic</strong></p><p>Welcome to the Accessibility Rules Podcast. This is episode 77. I’m Nic Steenhout and I talk with people involved in one way or another with web accessibility. If you’re interested in accessibility, hey, this show’s for you.</p>
<p>To get today’s show notes or transcript, head out to <a href="https://a11yrules.com" style="text-decoration: underline;">https://a11yrules.com.</a> Thanks to Twilio for sponsoring the transcript for this episode. Twilio, connect the world with the leading platform for voice, SMS, and video at <a href="http://Twilio.com" style="text-decoration: underline;">Twilio.com</a>.</p>
<p>This week I’m continuing my conversation with Amy Carney, we had a great show last time talking about all kinds of things but also the wins that Amy has been able to be part of and trigger in accessibility in Alaska. So, that’s fantastic.</p>
<p>Amy, welcome back.</p>
<p><strong>Amy</strong></p><p>Thank you.</p>
<p><strong>Nic</strong></p><p>We finished last week on a high note talking about all the good stuff that’s happening in Alaska, accessibility wise. Let’s switch to something else. What would your greatest frustration be in terms of web accessibility?</p>
<p><strong>Amy</strong></p><p>You know, I think WebAIMprobably pointed those out in their WebAIM million report. The frustrations are probably the realization that people have simple choices to make a lot of the times, not all the time but a lot of times its simple choices and they just don’t quite understand quite how simple it is to make some fixes, and it isn’t really cost heavy and just a little extra time. And so, trying to explain to people that accessibility, for the most part, is easier than you think, and, also the frustrations of… I think I’ve seen this on Twitter, of having to go over HTML again with people. It comes down with some basic changes to your structure and …</p>
<p><strong>Nic</strong></p><p>Yeah</p>
<p><strong>Amy</strong></p><p>… element choices. So, yeah. I think it’s frustrating that people don’t see how easy it is sometimes and that it’s… it’s gained a lot of traction it feels like, in the past year for people talking about it but it’s still not as sexy as other things people are learning. Like, “Oh, you know about React and how to do this” and so many other trends that go on that people really spend a lot of time learning but then it’s kind of just a, “Oh, yeah, accessibility, I’ll think about that when I’m done with my project here”.</p>
<p><strong>Nic</strong></p><p>What do you think the one thing everyone knows about accessibility is?</p>
<p><strong>Amy</strong></p><p>The one thing that everybody knows… hmmm</p>
<p><strong>Nic</strong></p><p>Yeah</p>
<p><strong>Amy</strong></p><p>Well, I think the universal point is it has to do with people with disabilities. And, I feel like, you know, the image ALT attribute has been fairly common. I was even learning when I started dabbling in doing our library website and I remember our IT guy was like, “Well you have to have the ALT attribute or it’s not accessible.” There was no other discussion about accessibility but the ALT attribute had to be there and so I feel like I see that a lot even though that’s a common fail for places I feel like it’s also a win for a lot of places too. Even if the text inside isn’t always great. But the ALT attribute is there, so that’s fine. I feel like people have made a step forward.</p>
<p><strong>Nic</strong></p><p>Oh we’ve only been advocating for the ALT attribute for, since 1995 or so. It’s good that it’s finally starting to sink in a little bit.</p>
<p><strong>Amy</strong></p><p>I didn’t hear about it when I was doing Geocities.</p>
<p><strong>Nic</strong></p><p>Oooh you just dated yourself.</p>
<p><strong>Amy</strong></p><p>I did. That was my first flavor of web design.</p>
<p><strong>Nic</strong></p><p>Yeah, well that was mine as well. Geocities, yeah, I had a cooking website way back then.</p>
<p><strong>Amy</strong></p><p>Oh, cool. Mine was StarTrek fanfare.</p>
<p><strong>Nic</strong></p><p>StarTrek fan. Hmmm. May the force be with you, right?</p>
<p><strong>Amy</strong></p><p>What?! I can not believe you.</p>
<p><strong>Nic</strong></p><p>What do you think the number one reason is for most people to fail to succeed in implementing accessibility?</p>
<p><strong>Amy</strong></p><p>Hmmm. Well, I guess it depends on the site being built. You know, I see a lot of people when they’re working on their applications and their single page applications that the focus can be an issue of getting the focus in the right spot for somebody to understand where they’re at. But in just static webpages I feel like some people struggle with headings and heading levels. Maybe that’s just me but, you know, when you’re having to get back the same… you know, there’s CSS for that and you know, you’ve just created a section and that’s actually a heading for that section instead of a paragraph. I don’t think I run into too many Divs and Spans… as much but, well sometimes I do, but, yeah. I feel like it’s still on a basic level that I feel like I’ve mastered a long time ago and some people, they’re thinking ahead to a certain outcome in their mind and how to build it. They just take a different way of how to build it than I would’ve expected. That kind of goes back to the HTML thing.</p>
<p><strong>Nic</strong></p><p>How can we help them avoid these kinds of failures?</p>
<p><strong>Amy</strong></p><p>I’m still asking myself that question.</p>
<p><strong>Nic</strong></p><p>Fair enough</p>
<p><strong>Amy</strong></p><p>There’s uh… checklists are one thing that pops up in my mind but I don’t know when people are working on stuff if that’s really help or just an extra burden. Having people put stuff into their process, like, AXE or something like that that’s more automated to let people know or I know, [Hayden Macraine?06:48] has done some of that, here’s things in the CSS that could pop up right at you if you have that CSS file in development. And so, yeah I almost see an automated thing would be the easiest low hanging fruit.</p>
<p><strong>Nic</strong></p><p>Yeah</p>
<p><strong>Amy</strong></p><p>But just constant reminders maybe of regular education and reminders because I find that’s the only way I can keep on doing this too. Because my barriers are very low for accessing technology and so if I just remind myself other perspectives and this is real and real blocks for other people and just reading stuff, keeping myself educated keeps that in the forefront of my mind. So, I don’t know how you do that with other people. Some kind of reminder to keep it in the forefront of their mind. becomes more natural to develop it into a workflow.</p>
<p><strong>Nic</strong></p><p>Yeah, totally. What do you think the greatest challenge for our field, for accessibility, are to moving forward?</p>
<p><strong>Amy</strong></p><p>The greatest challenge to accessibility, well, probably going back to the last question keeping the awareness up. Keeping up the steam of advocacy and keep on repeating the same things over again…</p>
<p><strong>Nic</strong></p><p>Yeah</p>
<p><strong>Amy</strong></p><p>… I think that. People feeling like a broken record can be very exhausting and even I can understand that point. Like, I feel like people I work with at work, that I’m repeating myself and I’m like, “Didn’t I tell you this already?” But, it just… yeah, it’s just that keeping it to the forefront for people so… and understanding that they’re not thinking about this every day or they have other things that they’re dealing with in their day-to-day work. So…</p>
<p><strong>Nic</strong></p><p>Yeah</p>
<p><strong>Amy</strong></p><p>… yeah. I think it’s just the advocates and professionals and experts out there just keeping up the good fight. As they would say.</p>
<p><strong>Nic</strong></p><p>Yeah</p>
<p><strong>Amy</strong></p><p>And not growing tired of it.</p>
<p><strong>Nic</strong></p><p>I typically ask people what profession other than your own would you like to attempt. This is your second profession since you were a librarian before. Is there something else you’d like to get your hand onto if you were to do another career change?</p>
<p><strong>Amy</strong></p><p>I don’t know if I would. This was… this was a long time coming for me. As you see me when I was dealing with GeoCities back at the end of Highschool there. And, I really thought that’s what I wanted to do. Website stuff but it was still so new and I just didn’t know how I could even get into it and make it a profession, And I didn’t have enough encouragement or direction at that time. I started out trying to do a computer science degree and that first class after squeaking by trying to learn C++ was just, like, this isn’t really what I had in mind and the teacher wasn’t very supportive and it was a little awkward being the only girl in class and there’s just so many things. I was just, I don’t think this is where I’m supposed to be. So, I kind of floundered around a bit after that and did different things. But, yeah, after I had this opportunity to come on with the State of Alaska, with the Libraries, Archives, and Museums, ‘coz I actually really love that sector and so it was really great to be doing web stuff for that sector… combination of those sectors I should say because they each have their own specialties and mission… so this has been great to get into it and learn more and get paid to do it. So, I don’t know if when I hit 50 if I will be like, “Okay, that was fun, now let’s do something else maybe a little more physical with my hands” something that doesn’t require staring at a screen all day. But I don’t know what that would be because I haven’t really found that as a side hobby. I don’t really have a lot of hobbies on the side that would motivate me to go onto something else yet. But, that’s yet. That’s a little way down the road. Yeah, so, I keep it open to… you can definitely be more than one thing and I count on probably wanting to move on a couple of decades from now because I’ll have a different mindset and different interests.</p>
<p><strong>Nic</strong></p><p>And the technology will change.</p>
<p><strong>Amy</strong></p><p>And it will. Yeah. Imagine the opportunities there. Will I want to change with that technology? Or do I want to do something else?</p>
<p><strong>Nic</strong></p><p>Who inspires you, Amy?</p>
<p><strong>Amy</strong></p><p>Lot’s of people. From the undersung like my mom who put aside her own personal interests to take care of her family to people who are well known like Gandhi, Martin Luther King Jr… people who have spoken up for peoples rights and civil rights. To other women in tech. You have well-known names like Grace Hopper or you have other people that are just making their way now like Rachel Andrews and Jen Simmons… so, yeah, depending on what subject we’re talking about I could let you know…</p>
<p><strong>Nic</p><p>Fair enough</strong></p>
<p><strong>Amy</strong></p><p>.. who exactly inspires me. Mostly people who are… who haven’t been afraid to step forward and say, “ I want to try this and I’m going to do as much as I can, learn as much as I can” and not afraid to speak up about it and it takes courage to move forward and do what you really enjoy doing or want to do or feel like it’s going to make a difference. So… coz I still have a pretty small voice. I’ve never been someone that is loud or really spoken up for myself unless it really absolutely matters I guess and makes a life-changing difference of what options I get. But, it’s neat to see people who have really put it out there, on the line and the difference they’ve made.</p>
<p><strong>Nic</strong></p><p>I think you don’t give yourself enough credit. You may have a small voice but you were instrumental in affecting significant change in accessibility for the State of Alaska. I think that’s… you know, that’s a big accomplishment, You really should not reduce your achievements there.</p>
<p><strong>Amy</strong></p><p>Well, I hope it continues on. People after me can speak up.</p>
<p><strong>Nic</strong></p><p>Hmm. Yeah. Let’s wrap the show up with asking you, what is the one thing people should remember about accessibility?</p>
<p><strong>Amy</strong></p><p>That it comes down to the people. It’s not just a checklist of standards but that we really are building experience for people and allowing them to open up opportunities. Technology, computers is I think why I was drawn to it because it opened up opportunities for me and so I think we have to give that benefit an opportunity for other people no matter if they’re certain… Or use a computer the same way we do or don’t. It’s people.</p>
<p><strong>Nic</strong></p><p>It is people. Totally. And I think that perhaps that’s one of the pitfalls people fall into. That they think, well, we’re in a tech field, we have tech solutions so it’s a tech problem. But, it’s not. It’s not. It’s about people. It really is.</p>
<p><strong>Amy</strong></p><p>Yeah.</p>
<p><strong>Nic</strong></p><p>On that note, Amy Carney, thank you very much for being a guest on the show. It’s been a great chat and I look forward to connecting with you again on Twitter and maybe see you at a conference some time.</p>
<p><strong>Amy</strong></p><p>I hope so, someday. And, it was great being on your show. You’re very welcome and, thank you.</p>
<p><strong>Nic</strong></p><p>Thank you and have a good day!</p>
<p><strong>Amy</strong></p><p>You too!</p>
<p><strong>Nic</strong></p><p>Everyone out there, thank you for listening to the show. I hope you enjoyed it and if you do, please do tell your friends about it.You can get the transcript for this, and all other shows at <a href="https://a11yrules.com" style="text-decoration: underline;">https://a11yrules.com</a>.</p>
<p>Catch you next time!</p>

</details>

## Show Notes


