---
layout: podcast
title: "E68 - Interview with Ire Aderinokun - Part 1"
type: podcast
summary: "In the first part of my interview, Ire Aderinokun tells us that accessibility will not take you a massive effort if you're using HTML correctly."

permalink: /podcast/e68-interview-with-ire-aderinokun-part-1/
# Podcast Episode Metadata
episode_type: full
episode_number: 68

# Audio Information
audio_url: https://a11yrules.ams3.cdn.digitaloceanspaces.com/podcast/episodes/E068-a11y-rules-ire-aderinokun-part-1.mp3
audio_type: "audio/mpeg"

# Duration
duration: "PT27M38S"
duration_formatted: "27:38"

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
    
<p><strong>Nic</strong></p><p>Welcome to the A11y Rules podcast. This is episode 68. I’m Nic Steenhout, and I talk with people involved in one way or another with web accessibility. If you’re interested in accessibility, hey, this show is for you. To get today’s show notes or transcript, head out to <a href="https://a11yrules.com" style="text-decoration: underline;">https://a11yrules.com.</a> This week, I’m speaking with Ire Aderinokun. Thanks for joining me for this conversation around web accessibility, Ire. How are you?</p>
<p><strong>Ire</strong></p><p>I’m great. Thanks for having me.</p>
<p><strong>Nic</strong></p><p>Thank you. So I like to let guests introduce themselves. In a brief introduction, who is Ire Aderinokun?</p>
<p><strong>Ire</strong></p><p>Okay, so I’m a front-end developer and user interface designer. I live and work in Lagos, Nigeria. I’m currently working on a startup called BuyCoins, and we’re building a cryptocurrency exchange that’s targeted at Africans, and Nigerians for now, Africa soon. I also write a blog. It’s called bitsofcode where I write a lot about front-end development. So, HTML, CSS, JavaScript. I’m actually currently trying to write almost every day, so I’m trying to do an article every weekday for the next about 30 days/30 articles. There’s a lot of content going on there right now, so that’s what I focus on.</p>
<p><strong>Nic</strong></p><p>Right, so that would keep you busy. So to get going a little bit, tell us something that most people would not know about yourself.</p>
<p><strong>Ire</strong></p><p>Interesting. I guess people would not know that I’m really scared of flying, because I’m flying a lot because I travel for things like conferences. I’m traveling at least maybe every month, every two months or something, so people might not be aware that I’m actually really, really scared of flying despite the fact that I do it a lot.</p>
<p><strong>Nic</strong></p><p>Yeah, that would be problematic. From Nigeria, it’s a bit difficult to get anywhere really unless you’re doing a lot of African continent conferences. But I think you’re coming over to the States and to Europe quite a bit, aren’t you?</p>
<p><strong>Ire</strong></p><p>Yeah, so recently in the past, maybe a year, I’ve been going particularly to California a bit mainly because the startup I was working on, or I am working on, we got into Y Combinator, so we’re there for most of the summer. Also, a few conferences I go for are usually in California, but I also go to Europe quite a bit. Yeah, every conference I go to is at minimum six hours away, so it’s kind of a struggle.</p>
<p><strong>Nic</strong></p><p>Yeah, I can imagine that. I can imagine that. So the podcast is about web accessibility, and there seems to be as many variations of the definition of web accessibility as there’s people I speak to on the podcast. How would you define web accessibility?</p>
<p><strong>Ire</strong></p><p>That’s a good question actually. Well, I just think of web accessibility basically like any form of accessibility, and it’s just about access to the platform. In this case, the web to as many people as possible. People tend to focus on specifically people that have disabilities. So how does somebody who is, for example, blind use the web? That’s one of the major things people might think about. But it’s just about making the web or whatever platform we’re talking about, making it easy to access for as many people as possible, including people who might have a disability.</p>
<p>But I always say that accessibility is not only about targeting the people who have a disability. It’s just about increasing access in general, and that might also mean that people who don’t have disability will be able to access the content in a better way or in an easier way as well.</p>
<p><strong>Nic</strong></p><p>Right, so in other word, accessibility benefits everyone?</p>
<p><strong>Ire</strong></p><p>Yes, exactly.</p>
<p><strong>Nic</strong></p><p>I’m curious about where your role falls within web accessibility. You were telling us you do a lot of writing and you’re working with a startup about cryptocurrency. How do you weave web accessibility into that?</p>
<p><strong>Ire</strong></p><p>Yes, so I think web accessibility is a really big part of the job of the front=end developer. It is part of everybody’s job in some way or the other, but I think it might be the most important for the front-end developer because most of the time their decisions either make or break whether a website is accessible or not. So how they decide to build links if these sites are used, like the correct elements for the correct things. Those are a lot of the things that really impacts whether a site is accessible or not probably more so than how the content is written maybe.</p>
<p>So a content developer’s job and probably also the designer. I think in how I decide to build the websites, that’s really important, and accessibility comes a lot into that. Like I mentioned, doing a lot of speaking and writing a lot, I try as much as possible to think about accessibility in whatever I’m writing and even in topics that are not necessarily directly related to accessibility, I try and be as conscious about it as possible. So even in things as simple as code examples, making sure that I’m not giving an example that’s a poor example for accessibility because that really affects a lot of people I’ve found.</p>
<p>So if I have a simple HTML document, for example, making sure that there is a language attribute on the HTML elements, that goes a long way because a lot of people who are beginners might not necessarily have started thinking about things like accessibility. They’re more likely to just copy and paste what you do, and I have to think and make sure that I’m not assuming that they know that this is not the most optimal way to write this. I have to try and be as conscious as possible in things that I write and examples that I give.</p>
<p><strong>Nic</strong></p><p>I must thank you for that because it’s one of my pet peeves that so many tutorials and code samples up there actually are not focused on accessibility or even just properly formed HTML. It’s a pleasure to hear that you’re doing that, so newbies in particular, but also experienced coders actually see this is how you do it. So, thanks for that.</p>
<p><strong>Ire</strong></p><p>You’re welcome. I mean, I try. I’m sure it’s not perfect, but I definitely try.</p>
<p><strong>Nic</strong></p><p>How did you become aware of web accessibility and how important it is?</p>
<p><strong>Ire</strong></p><p>That’s a good question. I haven’t really thought about it. I think it probably started as part of my blog. So when I first started writing, I had initially challenged myself that I needed to write every single week, and I actually did that for the first two years or so. So every time I needed to find something to write about, it really forced me to do a lot of research and try and understand things a lot more. So I think it probably started from me digging deep into HTML and understanding what each element does, what it’s for, what everything means, and I think having a greater understanding of HTML made me understand … made me better at accessibility because I truly understood the difference between a button and a link for example.</p>
<p>I could understand why it’s important that you should use the correct element for each thing and also because of writing and forcing myself to research things more. I’m sure I just across the web content accessibility guidelines. That’s one of the things I even wrote about in the first year of my blog, and I actually read as much of it as possible. I didn’t actually read everything, but I skimmed as much of it as possible rather. Reading that really gave me a much better understanding of why it’s important, and I guess it kick-started me into thinking a lot more about it and consciously trying to make the effort to find content that talks about it or follow people that are talking about it so I can be exposed to as much of that kind of information as possible.</p>
<p><strong>Nic</strong></p><p>Has your view of accessibility changed since you became aware and then started digging into it?</p>
<p><strong>Ire</strong></p><p>I would definitely say that what I think about accessibility and just generally about it has changed from the beginning to where I am now, because I think when I first heard of it or even first begun researching it, I was still very much of the mindset of, “Okay, this is only really important for people who are blind for example, and because I am maybe not building a site that a blind person might use.” So even though I’m aware that accessibility is a thing, I still had that very closed-minded view of why it was important. But I think as I’ve grown more and starting to research more about it and just learning more in general, it’s like I said at the beginning that I just tend to think that’s it’s better for everyone, and it just generally makes an overall better experience for your sites if it’s accessible.</p>
<p>So I would say that’s the biggest change in my mindset, and it has also made it easier for me to put more importance on it when I know that, “Okay, maybe even if somebody who’s disabled never accesses or never tries to use the site, I know that I’ve still made the experience better. I’ve still made a better site.”</p>
<p><strong>Nic</strong></p><p>I think your experience, what you describe, is a critical change in perception, and it probably is where a lot of developers out there are stuck at thinking, “Well, accessibility benefits only a few people, and I’m not building websites for these people anyway, so I can forget about it.” What would you say to the old you that was thinking that way? How would you convince yourself to actually pay more attention? What would be the argument that we could use to really convince people?</p>
<p><strong>Ire</strong></p><p>Well, I actually do a talk similar to this topic, which is about why accessibility is important and why it can be easy. So the main things that I do say in that talk, and which is the answer to the question is two things. The first is that accessibility, contrary to what many people believe, it’s not actually going to take you 10 times more effort or more time to make a site more accessible. I always point out the example of people trying to use a span or a div as a button instead of just using a button element. It does not take you more work to just use the correct element. So it’s more just about how you write your HTML or how you architect your app rather than you having to spend so much more time doing it to make it more accessible.</p>
<p>So the first thing is that it doesn’t have to be something that’s you’re taking on this huge new task and it’s going to be really, really difficult. It can actually be pretty simple, and it’s just about what you write or how you write it rather. The second thing is what I mentioned before, which is that you may not think about it, but if you make a site that is more easily navigable or your content is easier to read, that helps everyone. A good example of this is responsive design. When we were all building sites that were only for desktop, and the fonts were maybe really small, or it was laid out in a way that wasn’t really responsive and couldn’t really be changed much.</p>
<p>That was because we were just thinking, “Okay, everybody’s going to be on desktop.” But if at that time we had been thinking that, “Oh, what if somebody needs to increase the font size? Or what if somebody needs to have everything much bigger?” If we were already thinking in that mindset, the whole concept of responsive design and making sites work on mobile would have been a much easier shift if that makes sense. So it’s like … I’m trying to think of how to … I don’t know if that made more sense.</p>
<p><strong>Nic</strong></p><p>Yeah, that did make sense. I like the couple of aspects to it. I particularly like this thing of, you know, “Accessibility will not take you 10 times more effort to make happen if you actually use HTML properly.”</p>
<p><strong>Ire</strong></p><p>Yeah, exactly. I think even myself, and a lot of people used to think that you have to just do so much extra work. It’s only going to be a lot of extra work if you don’t think about it till the very last minute and then decide, “Oh, I need to make this accessible.” Then you realize that you’ve used all the wrong elements or you’ve relayed out everything using Flexbox instead of just using the actual source order in the DOM to make sure things make sense in that way. If you had just done it the normal way or the way that would work for all kinds of people, it would have been actually easier for you than doing it the way in which you’re trying to hack things in a strange way.</p>
<p><strong>Nic</strong></p><p>Yeah, yeah, absolutely. Ire, did you find you were facing barriers when you were learning about implementing accessibility and when you were doing it? And if you did, how did you get over them?</p>
<p><strong>Ire</strong></p><p>I think it was a bit daunting getting started just because my first instinct was to try and read the Web Content Accessibility Guidelines, and that’s a really large document. It’s probably one of the biggest specs or documents that has been created, so it was a bit daunting looking at that and thinking, “Oh, wait. Do I need to read all of this to understand accessibility or to build accessible websites? I quickly realized I didn’t need to do that. What I just needed to do was rely on a lot of tools that are available.”</p>
<p>Nowadays, there have been so many more tools that make trying to make your site more accessible. They make it pretty easy because you just click a button, and they’ll tell you exactly what you need to fix. So at the time, I was using a Chrome plugin called … I think it’s just called Accessibility plugin or something like that, and it basically added a tab to your developer tool so that you could inspect any element, and you could see, “Oh, does this button have the appropriate label? Is this not visible or anything like that?” It was also really helpful for things like color contrast and making sure that things were of the appropriate contrast ratio. That was really good at the time.</p>
<p>Now, with Lighthouse, which is built into Chrome. You can do pretty much the same thing. I think even into Chrome Developer Tools, they already have a lot of these features so you don’t need to install any plugin to have it anymore. It’s just there by default. I was mentioning Lighthouse. You can do really quick accessibility audits. So with two clicks, you just select, “Oh, I want to have a report on the accessibility of this particular page,” and it’ll give you a report and tell you other things you did well, which is great. But it also tell you the things that you need to fix specifically.</p>
<p>So that’s a really great starting point. If you’re just getting started with accessibility, you don’t necessarily know what the rules are: What is good, what is bad, what you should or shouldn’t do. It’s really great to rely on tools like this because they just tell you. &nbsp;It doesn’t go anywhere. Maybe it should actually be a button instead. There are so many tools. Another really great tool that I use is called Pa11y, and it’s a command-line tool. It does something similar to Lighthouse, but I think it gives a much more comprehensive report, so it’ll even tell you things that, “Oh, you need to make sure that this, like the title of your document. Does it actually correspond to what is on the page?”</p>
<p>It also just gives things like that where you should just think and you might not have really previously given much thought to. If you’re just getting started, you might say, “Oh, the title of my document should just be the title of my website.” But then it just gives you something to think about. Yeah, I really Pa11y as a way more comprehensive report, and you can even integrate it into things your continuous integration. So you can make sure that your sites doesn’t pass the test. It doesn’t move to production until it’s passed this Pa11y to make sure it’s actually accessible.</p>
<p>So there are so many tools that you can use now that it really just takes a lot of the effort of feeling like you need to know absolutely everything. It takes a lot of that away.</p>
<p><strong>Nic</strong></p><p>I like this concept of using automated testing tools as a way for new developers or developers that are new to accessibility to get familiar with accessibility, because obviously, automated tools will not catch every issues out there. But if you don’t know where to start, it probably is a great way to painlessly get a start with understanding accessibility. So thanks for that concept.</p>
<p><strong>Ire</strong></p><p>Yeah, it is because, like you said, if you don’t know where to start, a lot of these tools will just give you the right things to start thinking about. So if you had never really thought about labels for form elements before, and you get a warning that says, “Oh, this input doesn’t have a label,” then next time you’re writing a form, you’re already in your mind be thinking, “Oh, this needs a label,” and you wouldn’t need the tool to tell you the second time.</p>
<p><strong>Nic</strong></p><p>Yeah, I really like that. I’ve been doing accessibility for over 25 years by now, and I’ve had a love-hate relationship with automated testing tools because too many people relies too much on testing tools, and I think they’re really a powerful part of how we can test for accessibility. But I never really considered this idea that automated testing tool can be a form of learning about accessibility, and I think that’s a really powerful way to look at that. So thank you, Ire. That’s a really good thinking for me to ponder over the next few days.</p>
<p><strong>Ire</strong></p><p>Yeah, you’re welcome. Yeah, of course, tools won’t catch everything, but I think a lot of the tools have improved a lot over the years. So maybe when you first were looking at these tools, they were really catching much. But nowadays, I think they catch quite a lot, and they’re probably sufficient for at least beginning, and of course, with actual user testing, you can find more things. But it’s better to start with them than without, I think.</p>
<p><strong>Nic</strong></p><p>There’s no doubt about it. You have to use automated tools. It helps catch so many of the nitty-gritty of the coding errors and things that you might miss otherwise. I was reading a study last year or the year before. They pitched all the big-name automated testing tools together. It was a UK government department that did that, and the best automated testing tool for accessibility found only a little bit less than 40% of all the errors that they had created.</p>
<p><strong>Ire</strong></p><p>Oh, wow.</p>
<p><strong>Nic</strong></p><p>So it’s good. Yeah, it’s good to be able to find 40% of errors right there on a page. It’s a great tool, but you still might benefit from doing manual testing after the fact. But as you said earlier, as part of your coding practice and making sure that your project at least meets these things, these basic things that can be tested automatically, I think it’s mission-critical to have these automated tests and as part of your processes. So from designing to developing to QA and before release, absolutely.</p>
<p><strong>Ire</strong></p><p>Yeah, and I find that a lot of these tools tend to catch the probably more critical errors, like something like a missing label for example. That’s something that a tool will very easily be able to catch, and that’s also a very critical thing as well.</p>
<p><strong>Nic</strong></p><p>Yeah, that’s good stuff. Ire, what’s your favorite word?</p>
<p><strong>Ire</strong></p><p>My favorite word?</p>
<p><strong>Nic</strong></p><p>Yeah.</p>
<p><strong>Ire</strong></p><p>Oh, man. I’ve never thought of that before actually.</p>
<p><strong>Nic</strong></p><p>What’s the first word that comes to mind?</p>
<p><strong>Ire</strong></p><p>Chocolate.</p>
<p><strong>Nic</strong></p><p>Chocolate. I think that’s a good word. That’s a very good word. Do you prefer milk chocolate or dark chocolate or flavored chocolates?</p>
<p><strong>Ire</strong></p><p>Milk chocolate. Well, that might be my favorite thing, so I guess it’s also my favorite word because it instantly brings me joy.</p>
<p><strong>Nic</strong></p><p>What’s your greatest achievement in terms of web accessibility?</p>
<p><strong>Ire</strong></p><p>These are good questions. My greatest achievement … Actually, I think I might say an article I wrote might be my greatest achievement, and it’s an article which boils down the Web Content Accessibility Guidelines into … It’s kind of like a cheat sheet or at least that’s what I called the article, like Accessibility Cheat Sheet. I think it is my greatest achievement because it’s probably … I think it still is one of my most popular posts, so I think I feel like I probably had a lot of impact with that, and a lot of people have read it and realized that they need to do certain things.</p>
<p>So I would say maybe it’s probably had the most impact of anything I’ve ever done, so it’s probably my greatest achievement.</p>
<p><strong>Nic</strong></p><p>I think education is definitely a massive achievement, and if you’ve made an impact with that writing on all the people that have come and read it, I salute that. That’s a very important part of it. Ire, I think we’ll wrap it up at this point for this week. Thank you for being a guest and willing participant to my questioning.</p>
<p><strong>Ire</strong></p><p>Thank you so much for inviting me.</p>
<p><strong>Nic</strong></p><p>We’ll catch up next week.</p>
<p><strong>Ire</strong></p><p>Okay, speak to you soon.</p>
<p><strong>Nic</strong></p><p>Everyone out there, thank you for listening to the show. I hope you enjoyed it, and if you do, please do tell your friends about it. You can get the transcript for this and all other shows at <a href="https://a11yrules.com" style="text-decoration: underline;">https://a11yrules.com.</a> And a quick reminder, you can get yourself some neat accessibility branded swag at <a href="http://a11y.store" style="text-decoration: underline;">a11y.store</a>. Catch you next time.</p>

</details>

## Show Notes


