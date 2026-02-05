---
layout: podcast
title: "E69 - Interview with Ire Aderinokun - Part 2"
type: podcast
summary: "In which Ire tells us that she thinks convincing framework developers to implement accessibility will have more impact than trying to change individual developers' minds."

permalink: /podcast/e69-interview-with-ire-aderinokun-part-2/
# Podcast Episode Metadata
episode_type: full
episode_number: 69

# Audio Information
audio_url: https://a11yrules.ams3.digitaloceanspaces.com/podcast/episodes/E069-a11y-rules-ire-aderinokun-part-2.mp3
audio_type: "audio/mpeg"

# Duration
duration: "PT26M06S"
duration_formatted: "26:06"

# Series
series: "A11y Rules Podcast"

# Episode Artwork


# Author/Host
author: "Nic Steenhout"

guests:
  - ire-aderinokun
  

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
  
<p><strong>Nic</strong></p><p>Welcome to the a11y Rules podcast. This is episode 69. I am Nic Steenhout, and I talk with people involved in one way or another with web accessibility.</p>
<p>If you are in interested in accessibility, hey, this show is for you. To get today’s show notes, or transcript, head out to <a href="http://a11yrules.com" style="text-decoration: underline;">a11yrules.com</a>.</p>
<p>In this episode, I am continuing my conversation with Ire Aderinokun. Last show was really great. We spoke about all kind of things, but some concept that I found really important was the idea that automated tools are a great way to get started with understanding and starting thinking about accessibility. &nbsp;And, the other things was that Ire pointed out accessibility will not take you ten times more effort if you only use HTML properly. So, those were great.</p>
<p>Welcome back Ire. Thanks for joining me again.</p>
<p><strong>Ire</strong></p><p>Great to be back.</p>
<p><strong>Nic</strong></p><p>So, we finished last week with your greatest achievement in terms of web accessibility which was a nexus ability cheat sheet you wrote that has been really popular.</p>
<p>A flip side to that would be, what’s your greatest frustration in terms of web accessibility?</p>
<p><strong>Ire</strong></p><p>Okay, greatest frustration. Well, I don’t know if this is a frustration with web accessibility, but is more with the frameworks and tools that we’re using. So, one thing that’s frustrating me a lot right now, is that, for my job, BuyCoins that I mentioned, we are building a cryptocurrency exchange. I do a lot of work with the Ionic framework, and we had to use this particular framework because I primarily use angular and front end code and we needed to have mobile applications. But, the problem with Ionic is that it is really not all that accessible and it’s kind of been very frustrating because I have had to use this particular framework, which has ended up in the resulting products not being the way that I would like them to be.</p>
<p>And, of course, –</p>
<p><strong>Nic</strong></p><p>Yeah.</p>
<p><strong>Ire</strong></p><p>… I can try and contribute to the Ionic source as much as possible, which I am trying to do slowly, but trying to do. But, it’s really frustrating when the makers of these tools, and I know they are only humans, and they also have limited time, so they obviously can’t do everything, but it is just really frustrating when I feel like I am forced to use a particular tool or a particular framework and I have to deal with the fact that it is not very accessible.</p>
<p><strong>Nic</strong></p><p>This idea that when we want to work and we depend on frameworks that have not done the work to do accessibility can be quite limiting and frustrating. You said you were contributing to the framework. How have you found the reaction of what you are contributing? Are people receptive, or do they seem to just not really care one way or another?</p>
<p><strong>Ire</strong></p><p>No, I think they care a lot and this is something that’s relatively new to me. We’ve only just begun really digging in and using the framework. So far, I have started with helping raise issues and wherever I see something that I feel like I can try and solve, I try and do that as well. Generally, I think they are very receptive, and they’re open to it. And, that’s kind of why I said that I know that they have limited time and resources themselves, so it is not like they didn’t do this because they just didn’t want to do it. It’s more like they, I guess, they didn’t prioritize it, which is also part of the problem, that it’s considered okay to release something that is not accessible.</p>
<p>It’s also part of what is frustrating about, I guess the community, is that it would never be accessible to launch a framework or launch any kind of library or sort of projects and it’s been incredibly on performance, but it’s okay to do it if it is really inaccessible.</p>
<p>So, yeah, that’s kind of one of the problems at the moment, I guess.</p>
<p><strong>Nic</strong></p><p>I often talk about this tripod of three different aspects of web development that really should be considered in same kind of level of importance. The first one is performance, as you said. The other one is security. And, the third one is accessibility. And, we should no more build sites or apps or anything that isn’t secure or isn’t performant, but by the same token, we shouldn’t build things that are not accessible.</p>
<p><strong>Ire</strong></p><p>Yeah, exactly, if there was some security flaw in … I mean, we have even seen this in the past whenever there is a security flaw in Angular it gets resolved within 24 hours, they have released a new patch, everything is cool. But, there could be an issue about this accessibility flaw for months and it never gets fixed. It is just not really considered a high priority at the moment.</p>
<p><strong>Nic</strong></p><p>Do you think there is something that everybody knows about web accessibility?</p>
<p><strong>Ire</strong></p><p>I don’t think everybody actually knows about web accessibility, because whenever I write about something or I just even in an article that isn’t focused on web accessibility, if I mention something to do with accessibility, I always get a comment from at least one person saying, “Oh, I really didn’t know about that.” or “I didn’t really consider that.”. So, I think, even though for me, maybe because I follow a lot of these people and I am very interested in the topic, I feel like everybody is always talking about it. But, it seems like there’s a lot of people who still actually maybe have not even really thought about it. And, I am sure some of it is new people entering the industry, but I still feel a lot of people who have been writing websites for years and years, probably still don’t know a lot about accessibility.</p>
<p>I think there is still room for a lot of content and people trying to spread the knowledge more.</p>
<p><strong>Nic</strong></p><p>How do we make that happen? You mentioned people that are new to coding and people that have been doing it for a long time. So, it seems like there is two targets. What would you think is the best way to reach either of these target?</p>
<p><strong>Ire</strong></p><p>Well, there are two ways we could go about it. One would be to outwardly just to have more content that’s focused on accessibility. So, in conferences, there should be more talks where the actual primary focus of the talk is accessibility. But, I think maybe a more impactful thing would be to just make it part of everything. So, whenever there is a talk about flex box, for example, there is always going to be an accessibility part to any topic.</p>
<p>So, I feel like it should just be part of everything and, even like I mentioned in the previous episode about whenever I had code samples, trying to make sure that it’s written in a way that’s accessible code. I am not putting out code samples that are using the wrong elements or anything. I think it goes a long way for people to just see accessibility being in part of everything.</p>
<p>So, like I mentioned, a talk about flex box, for example, you could also mention that, “Oh, make sure that you don’t completely reorder the order of the elements in the document and back.”, that’s accessibility related topic. You are still talking about flex box, but you are just bringing along the accessibility concerns, like you would with performance for example.</p>
<p>Usually, if somebody is talking about some new framework or something that is not directly related to performance, there is usually some mention of performance or something that’s tangential to it as well.</p>
<p><strong>Nic</strong></p><p>Yeah.</p>
<p><strong>Ire</strong></p><p>So, I think it should just be brought along with everything because really it’s just about writing code that is valid and writing it in the way that makes sense. I think in addition to it being more out there in terms of topics specifically about accessibility, it should just be part of everything and people should, as much as possible, put out accessible code in whatever they are doing.</p>
<p><strong>Nic</strong></p><p>I like that. I like this idea that we should talk about accessibility with every aspect of things we’re presenting at conferences. I have been talking about accessibility specifically at a lot of conferences. I do think that if more people, even if you have a don’t know, a 45 minute talk slot, even if you spend 5 minutes covering accessibility in that, you are right, it would increase awareness tremendously.</p>
<p><strong>Ire</strong></p><p>Yeah, and one thing about the conference talks is that the people who are going to attend the topic on accessibility are probably more likely to be people who already … it’s in the back of their mind even if they don’t consciously work with it every day or it is something that they are already interested in. That’s why I feel like it needs to creep into everything else. So, people who aren’t really thinking about it, that kind of force to confront it because they have to realize that it’s not just a topic on its own, it’s related and has impact to everything else.</p>
<p><strong>Nic</strong></p><p>You are giving me so many good thoughts. Thank you Ire. That’s really good stuff.</p>
<p><strong>Ire</strong></p><p>I’m glad.</p>
<p><strong>Nic</strong></p><p>Really good stuff.</p>
<p>Yeah. I think my listeners are going to be enjoying this conversation quite a bit.</p>
<p><strong>Ire</strong></p><p>I hope so.</p>
<p><strong>Nic</strong></p><p>Yeah. What do you think the number one reason is for most people to fail to succeed in implementing accessibility?</p>
<p><strong>Ire</strong></p><p>I think maybe it forces people to think about how they are writing particularly HTML in a different way. So, if you are not really thinking about accessibility, or I guess just like writing HTML in the way that it is supposed to be written, then you kind of write HTML very differently. You kind of just structure things in whatever way. It is kind of like div vomit, and you just put anything –</p>
<p><strong>Nic</strong></p><p>Yeah.</p>
<p><strong>Ire</strong></p><p>… anywhere and you just kind of like, “Oh, as long as it shows up on the page, then that’s fine.”, right. But, I think when you start to think about accessibility, it kind of forces you to really think about the way you structure your documents in a totally different way. And, that is probably something that I realized was more of a shift when I started thinking about it more because I realized that I started to think more about, “Okay, so which element should I actually use here?”, and, especially, when all these new HTML five elements came out. We had a header element, a main element, and aside and a footer, and it just made me think, “Okay, I can use this element in this way and I structure it in this way.”, and it’s kind of just a different way of thinking about how you write HTML. That might be something that you need to overcome if you are just getting started and you are used to looking at what is the result of your HTML, instead of also looking at the HTML itself and making sure it makes sense on its own.</p>
<p><strong>Nic</strong></p><p>How can we make sure people take the steps and click to that fact?</p>
<p><strong>Ire</strong></p><p>Well, I found it’s almost easier actually to do it this way. Especially, when you learn about the, like I mentioned, HTML five elements, it just makes more sense and the HTML that you write actually comes out … it is more maintainable because you are not just putting divs everywhere. It makes more sense when you are looking at just the HTML. So, I am not sure how you can over-comment, but I guess maybe if you see what a properly structured document looks like you might be convinced that this actually just makes more sense, especially in terms of the developer experience and how you are going to continue maintaining this document in the future.</p>
<p>So, maybe it is just like you see how much better it is and hopefully that convinces you to try and learn how to do it this way.</p>
<p><strong>Nic</strong></p><p>What do you think the greatest challenge is for the field of accessibility is going forward?</p>
<p><strong>Ire</strong></p><p>Well, I think one of the challenges are the way we are starting to write our applications nowadays. So, a lot of stuff is completely powered by JavaScript where a lot of people are doing less, just writing HTML and relying more on frameworks and things like that. Even the example I gave, my problems with working with Ionic, a lot of people are learning frameworks rather than just learning maybe HTML, CSS and JavaScript, and so, it’s going to be a problem if these frameworks don’t really prioritize and put a lot of importance on making it accessible. Because I don’t know what percentage of the web is powered by these frameworks, but I am sure it’s quite a significant percentage and, I am just going to throw out a random number, but if 50% of the web is like React, it is important for React to make sure that they are making their framework really accessible.</p>
<p>So, I think conveying the importance and making sure that these platforms and these frameworks that people are building their own sites upon, making sure that they are considering the accessibility is important. That is really important going forward.</p>
<p><strong>Nic</strong></p><p>It’s mission critical from frameworks to do that. I was involved a long time ago with the Joomla CMS and it was important for Joomla to be able to provide accessible output, but also an accessible interface for people to be able to manage their content. And, it’s the same thing with WordPress. I think they’re saying it’s 35% of all website are powered by WordPress today.</p>
<p>And, yet, WordPress is going to release with a new editor that is not accessible. So, when we are thinking about that I think you are right. If we only could manage to convince the frameworks to do something that gives the bare bones of accessibility that gives best practices for developers to able actually understand that it needs to happen. That might actually make a massive impact on the overall health of web accessibility in the future.</p>
<p><strong>Ire</strong></p><p>Yeah, exactly. I think if we are thinking about what is going to make the biggest impact, probably going after the frameworks is going to be more important than convincing each individual developer that they should think about accessibility. Because like you said, WordPress, 35% of the internet, that’s a huge amount, and in one upgrade they could drastically change the accessibility of their editor.</p>
<p><strong>Nic</strong></p><p>Yeah.</p>
<p><strong>Ire</strong></p><p>Yeah, it’s quite significant, and quite important.</p>
<p><strong>Nic</strong></p><p>What profession other than your own would you like to attempt? So, if you weren’t a web developer, a front-end developer, what would you like to do?</p>
<p><strong>Ire</strong></p><p>Okay, this is a good question.</p>
<p>Well, I would start with what is more likely. At university I actually have two separate degrees. I first studied psychology, then I studied law. So, realistically, if I wasn’t doing web development, I would probably be a lawyer or go into psychology. But, unrealistically, I used to want to be a dancer and I am quite good at dancing, but I also wanted to be a musician. I really have the worst voice ever. I am glad that dream sort of died. So, I think starting in terms of what is more likely, maybe a lawyer, then a psychologist, then a dancer, then a musician.</p>
<p><strong>Nic</strong></p><p>How does one go from studying psychology and law to become a web developer?</p>
<p><strong>Ire</strong></p><p>That is a good question that I get asked very often. I started doing web development as a hobby since I was teenager, but, at the time, I didn’t know it was a career. And, I didn’t even know that computer science was something that I could study at school. I didn’t get that much information about career options when I was choosing –</p>
<p><strong>Nic</strong></p><p>Right.</p>
<p><strong>Ire</strong></p><p>… what to do in university. So, I just kind of picked my favorite subject at the time, just psychology. And, it wasn’t until I was doing my masters that I actually realized that web development was a thing that I could do. So, once I graduated I decided I needed to give this a try, because this was something I’ve been really interested in for as long as I can remember and so I started doing some freelance and I basically did some self-teaching through looking at other websites and just reading people’s blogs and some things like Codecademy was really useful. It is like a short course to learn new topics. So, that is kind of how I transitioned.</p>
<p><strong>Nic</strong></p><p>That’s fascinating. I’m interested because my background is … I’ve had basically, this is my third career in a way. I started as a chef when I was young and foolish. I was a professional cook. And then, when I had to use a wheelchair full time, I switched away from professional cooking. I did a lot of work with non-profits and working with and for people with disabilities. And, as part of that work, I was developing websites for fun and taught myself about accessibility and that was 20, 25, 26 years ago, and over those 20-odd years, I actually became a web accessibility specialist and that is what I do full time now. So, –</p>
<p><strong>Ire</strong></p><p>Wow.</p>
<p><strong>Nic</strong></p><p>… I am always interested in the way people come to accessibility. I think your journey is quite interesting.</p>
<p><strong>Ire</strong></p><p>Yeah, yours is really interesting as well. A chef, that’s amazing.</p>
<p><strong>Nic</strong></p><p>Who inspires you?</p>
<p><strong>Ire</strong></p><p>I always find this a difficult question to answer, because a lot of people inspire me. Maybe I have a problem with the word inspiration, but I think that a lot people are doing some really amazing things and I follow a lot of people on Twitter and I am also very inspired and interested by what that people do.</p>
<p>In terms of specifically accessibility work, a few people that I can mention are Heydon, Léonie … I don’t know how to say people’s names … Léonie Watson, I think.</p>
<p><strong>Nic</strong></p><p>Yeah, that’s okay.</p>
<p><strong>Ire</strong></p><p>Yeah. And, Rob Dodson, those are three people that I’ve been following for a while and they always put out really interesting content and they have also inspired me to research a lot more. They are always putting out interesting things that always sends me down a research rabbit hole and learning like, “Oh, I really didn’t know about this thing.”, and then I spend ages just researching this particular topic.</p>
<p><strong>Nic</strong></p><p>Yeah.</p>
<p><strong>Ire</strong></p><p>Yeah. I am sure that there are so many people doing amazing things but those are three people I can probably mention that I have been following for a while.</p>
<p><strong>Nic</strong></p><p>Rob, Léonie and Heydon are really dynamite and they are rock stars in the field of accessibility. It is not surprising that you find value in what they share. I find value in what they share, too.</p>
<p><strong>Ire</strong></p><p>Yeah.</p>
<p><strong>Nic</strong></p><p>So, it’s good stuff.</p>
<p>To wrap things up, I would like to ask if there was one thing you would like people to remember about accessibility, what would it be? What would be the one message you think people must have in their minds about accessibility?</p>
<p><strong>Ire</strong></p><p>Okay, this is something that Léonie said I think in one of her talks, but it is probably the thing that stuck with me the most and I don’t know if I would say inspired, but it definitely rings in my ear every time I think that maybe what I am doing is not enough; is that accessibility doesn’t have to be perfect, it just needs to be a bit better than, I think yesterday is what she said. So, people can tend to look at maybe the list of errors on their sites and feel like, “Oh, this is so much. There is no point in even starting.”, or “There is no point in trying to get all of these stuff done because it’s a long list of things that need to be fixed.”.</p>
<p>But, I think it’s okay to just start with fixing one thing if you only go and change one button on your sites. If you change it from a span to a button. If you only go home today and do that one thing, I think you can still feel good about that. And, you can still feel like you are making an impact and making progress.</p>
<p>Because that is still progress and maybe that’s the one button that somebody really needed to access to be able to submit that form, for example. And, that actually made a difference to the person. So, I just think, there are so many things to think about when it comes to accessibility and just in general it can start to feel like a lot, but the thing that you should realize is that you could just start with one thing. You don’t have to make it perfect to feel like okay you are starting to do work with accessibility. You just need to start.</p>
<p><strong>Nic</strong></p><p>Yeah, I like that. Don’t focus on doing everything all at the same time, just make it a little bit better every day.</p>
<p><strong>Ire</strong></p><p>Yeah, exactly.</p>
<p><strong>Nic</strong></p><p>It’s a good approach.</p>
<p>Ire, thank you so much for your time, your candor and your wonderful thoughts. I really enjoyed this conversation and I think the listeners out there will as well.</p>
<p><strong>Ire</strong></p><p>Thank you so much for having me. It’s been really great and I hope people do enjoy it.</p>
<p><strong>Nic</strong></p><p>Alright, thank you and catch you on the web.</p>
<p><strong>Ire</strong></p><p>You too.</p>
<p><strong>Nic</strong></p><p>Everyone out there, thank you for listening to the show. I hope you enjoyed it and if you do, please do tell your friends about it.</p>
<p>You can get the transcript for this and all of the shows at <a href="http://a11yrules.com" style="text-decoration: underline;">a11yrules.com</a>. And, a quick reminder, you can get yourself some neat A11y Rules branded swag at <a href="http://a11y.store" style="text-decoration: underline;">a11y.store</a>.</p>
<p>Catch you next time.</p>
  


</details>

## Show Notes


