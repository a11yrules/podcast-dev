---
layout: podcast
title: "E62 – Interview with Eric Bailey – Part 1"
type: podcast
summary: "Eric tells us, among other things, that relationship building is a good way to get passed the hostility some people have towards accessibility."

permalink: /podcast/e62-interview-with-eric-bailey-part-1/
# Podcast Episode Metadata
episode_type: full
episode_number: 62

# Audio Information
audio_url: https://a11yrules.ams3.cdn.digitaloceanspaces.com/podcast/episodes/E062-a11y-rules-eric-bailey-part-1.mp3
audio_type: "audio/mpeg"

# Duration
duration: "PT26M41S"
duration_formatted: "26:41"

# Series
series: "A11y Rules Podcast"

# Episode Artwork


# Author/Host
author: "Nic Steenhout"

guests:
  - eric-bailey
  

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
    <summary>
    <h2>Transcript</h2>
    </summary>
    <p><strong>Nic</strong>: Welcome to the A11y Rules Podcast. You’re listening to episode 62. I’m Nic Steenhout, and I talk with people involved in one way or another with web accessibility. If you’re interested in accessibility, hey, this show’s for you. To get today’s show notes or transcript, head out to <a href="https://a11yrules.com">https://a11yrules.com.</a></p>
    <p><strong>Nic</strong>: This week, I’m speaking to Eric Bailey. Thanks for joining me for this conversation around web accessibility, Eric. How are ya?</p>
    <p><strong>Eric</strong>: I’m doing well. Thanks for having me.</p>
    <p><strong>Nic</strong>: Thank you. Hey, as you’ve been listening to the show, you know by now that I like to let guests introduce themselves. So, in a brief intro, who’s Eric Bailey?</p>
    <p><strong>Eric</strong>: Yeah, wow. You think I would have prepared for that. So, I’m a designer, working at a agency called Thoughtbot in Boston, Massachusetts. I write articles for mostly CSS-Tricks and Smashing Magazine now, a couple other places on semantics and accessibility and usability and kind of the intersection of all three and the muddy space that is all those things converging.</p>
    <p><strong>Nic</strong>: Yeah. That sounds like it keeps you busy and out of mischief for most of your waking time.</p>
    <p><strong>Eric</strong>: Yeah, yeah. I … My partner is currently in grad school, so I’ve had some time to kind of, you know, fritter away with writing and sitting on the couch and watching too much Netflix.</p>
    <p><strong>Nic</strong>: Yeah, yeah. Hey, to get warmed up, tell me something that, one thing that most people would not know about you.</p>
    <p><strong>Eric</strong>: Oh, sure. So, I spent a year doing disaster relief in New Orleans after Hurricane Katrina, through-</p>
    <p><strong>Nic</strong>: Oh, wow.</p>
    <p><strong>Eric</strong>: Yeah. It was through a program called the AmeriCorps, which is a domestic Peace Corps. And so, I lived out of tents for a year, and yeah, it was an incredible experience.</p>
    <p><strong>Nic</strong>: That would have been a difficult time I would think, but also quite enriching and rewarding. Wouldn’t it?</p>
    <p><strong>Eric</strong>: Yeah, yeah. I think you said that very well. It was very intense, but made a lot of … Met a lot of incredible people. Made a lot of incredible friends. Definitely felt all the feelings. So, yeah, but I’m very happy to have been able to have done it.</p>
    <p><strong>Nic</strong>: How has that impacted on your experience as a developer?</p>
    <p><strong>Eric</strong>: Sure. I like things that work, and I like things that are robust and like, probably not the best term, but like battle tested. You know, the web, if you do it wrong, is a very flimsy medium, and it’s also one of the most actively hostile development environments you will ever work with. So, because of that, I like things that will hold up under stress or duress-</p>
    <p><strong>Nic</strong>: Yeah.</p>
    <p><strong>Eric</strong>: … or less than optimal situations.</p>
    <p><strong>Nic</strong>: So, obviously the main topic of the show is web accessibility, and every people I speak with, speak to, seems to have a slightly different definition of accessibility. So, how would you define that?</p>
    <p><strong>Eric</strong>: Sure. I think accessibility is good design, and good design is accessible. And I know that’s kind of like a tautology, but it’s … It kind of gets into the whole inclusive design mindset, where you should be proactively considering these things, as opposed to fixing them in post. So, it’s, you know, in my mind it’s a holistic practice, that kind of affects every aspect of what we do as app and web makers. I don’t know. It’s strange to me to kind of like keep it in this little box off to the side.</p>
    <p><strong>Nic</strong>: Why do you think we keep it in a box off to the side?</p>
    <p><strong>Eric</strong>: Yeah. Education. It’s, you know … So, if you’re learning about web design and web development … I’m gonna keep using this as a go-to example because it’s what I like to do, but it affects all of digital design. You know, if you go to a traditional CS (Computer Science) school, there are so many different little things to focus on that you can kind of go down this rabbit hole on learning about. In a traditional CS education, for most places, accessibility is not a priority. And this is kind of a pet issue that I don’t know what to do about because, you know, if you go to an engineering school, you definitely learn how to make a building not collapse, or how to work with the capabilities of the materials that you’ll be using. Same for architecture. You know, I think there’s a lot of comparisons you can make between building things and building websites.</p>
    <p><strong>Nic</strong>: Yeah.</p>
    <p><strong>Eric</strong>: So, it just, it bothers me because we’ve effectively taken one of the stools, one of the legs off the stool and kind of just thrown it away. And because of that, I think there’s far less chances of people kind of uncovering accessibility in a positive way. And then, you know, learning the ins and outs of how to do it. Usually, a lot of people I talk to become aware of it after a lawsuit has happened or the threat of a lawsuit, and that can really kind of skew your perception as a developer. You may be a decent person. I think most people are generally good people, but if you come into it from a sense of punitive, it can really color your experience.</p>
    <p><strong>Nic</strong>: Yeah. I’ve been struggling with that, you know, making accessibility, not just positive but fun, and flip it away from, you know, if you don’t make it accessible, you’ll get slapped with a lawsuit. But at the same time, it seems that it’s the only thing that actually get a reaction from people.</p>
    <p><strong>Eric</strong>: Yeah.</p>
    <p><strong>Nic</strong>: How do we get that, resolve that, you know, dichotomy between on one hand we want to have people come to it in a positive way, but on the other hand, the only thing that actually seems to make a difference is a lawsuit or the threat of a lawsuit.</p>
    <p><strong>Eric</strong>: Yeah. I wish I had the answer. Yeah. I’ve talked about this with others, and you know, there is a pragmatic element to it. There is definitely the kumbaya inclusion, you know. I don’t mean to sound dismissive here, but there comes a time where it is time to bring down the hammer. And that is because, you know, by definition of the practice, you are, you know, you’re removing people’s ability to accomplish things. And as the world gets more digital, it becomes so much more important with every passing day. And so, you know, I don’t think we should remove the possibility of a threat, I just, I wish … You know, I wish it … I guess not even wish, it’s just like being cognizant of the nuclear option and kind of what you can do before it gets to that. You know, like Lainey Feingold’s Structured Negotiation is a really interesting thing to read about, and I’m not going to paraphrase that ’cause I will butcher it.</p>
    <p><strong>Nic</strong>: Yeah. I like Lainey. I like her approach. I think it’s very effective. Yeah. So, Eric, let’s get back to you for a second. You define yourself as a designer, doing a lot of UI/UX work. Day to day, what does that look like from an accessibility perspective? How do you implement that?</p>
    <p><strong>Eric</strong>: Yeah, that’s a great question. So, we recently, on our internal Slack, had a conversation. There was a coworker who was very interested in coming to be more proficient in accessibility, and she kind of had the same question, like how do you do it? And to be completely honest, I normally will sneak it in, which is to say like most other coding and design practices, I’m not explicitly telling the client that I’m doing it because that’s just part of the skillset. So, the client says, “Make me a website about dogs.” I don’t bore them to death with the details of, you know, my eight-point design grid and sketch and my modular component library. I just do it, and hopefully I solve the problem that needs solving.</p>
    <p><strong>Eric</strong>: And so, when it comes time to practice accessibility there, so like making sure that that component library has, you know, good color contrast baked in. You know, making sure that the copy writing is at a decent reading level. If it comes time to take it to development, starting with good semantic markup. But, you know, it’s … Sneaking is kind of the bad way to say it ’cause it has this negative connotation, but it’s just I make it, I try to make it a non-issue, just ’cause it just … That’s what you get when you get my service.</p>
    <p><strong>Nic</strong>: Yeah. See, I like that because I often get asked, particularly at conferences, you know, “How do you … How do you, as a design studio get clients to pay for accessibility?” And I said, “Well, you don’t charge them. It’s just … It should be rolled into the service because, you know, you don’t charge clients extra for a secure website.” Well, I hope you wouldn’t. You wouldn’t be charging people extra for accessibility either. It should be part and parcel of that, and I think this stealth accessibility is perhaps an important way to do it for people that have clients or people that are in roles where they are part of a larger team that actually works on websites. They should just do it. Because, as you said, it should be part of your skill set.</p>
    <p><strong>Eric</strong>: Yeah, yeah. I’m actually optimistic. Net … I, you know, when interviewing potential candidates and like … I design systems a lot, and I like to read other people’s design systems ’cause I’m a giant nerd, but I see more and more kind of mentioning of these kinds of things, and, you know, it’s one of those … There’s always going to be room for improvement, and there’s always going to be little gotchas and ahas to be cognizant of. But I’m not seeing it more and more listed as an interest or concern on resumes or in design systems or in rating guidelines and stuff like that. And maybe that’s ’cause I’ve self-selected my own little filter bubble, but I, you know, aside from some specific technology concerns, it does seem like accessibility is finally getting a seat at the table.</p>
    <p><strong>Nic</strong>: Yeah, well I hope you’re right. I really hope you’re right. So, how did you become aware of web accessibility and its importance?</p>
    <p><strong>Eric</strong>: Sure.</p>
    <p><strong>Nic</strong>: What was a trigger for you to say, “Aha, this is important.”?</p>
    <p><strong>Eric</strong>: Yeah, so this is kind of a, this is … If you don’t mind me kind of monologuing for a bit.</p>
    <p><strong>Nic</strong>: Go for it.</p>
    <p><strong>Eric</strong>: Yeah, I … There was a couple … There was a lot of kind of conspiring things, but I don’t think there was one, single event. It seems kind of on the long arm of my career I’ve been pushed towards this. My mother was an occupational therapist, so I would always kind of help her demo out her assistive tech, and you know, we’d talk about her job. So, I was kind of made aware of some of these concerns at an early age. I was a big nerd, so I really liked learning how to write html, and with that kind of came learning about semantics, which is a lost art, unfortunately.</p>
    <p><strong>Eric</strong>: And then, I had a job at a nonprofit, and it was a wonderful organization that helped compile health and human services information. And part of that required making html kind of documents to deliver for findings, and that required Section 508 compliance. And through Section 508, I learned about the WCAG, WCAG or however you want to pronounce it, and it was like, “Oh, okay. So, it turns out that there are rules for making really good design then.” You know, by my definition of design that anybody can use, as opposed to something that’s like looks pretty.</p>
    <p><strong>Nic</strong>: Yeah.</p>
    <p><strong>Eric</strong>: So, I was like, “Okay, this is really interesting, so what else can I learn about it?” And you know, it kind of snowballed from there, but the thing that I always get when I get asked this question that really kind of honestly irritates me is that like to be interested in this, I must have some sort of disability condition or some sort of traumatic event that like is your super hero moment of being forged in the fires of awareness. But, you know, I’m … I have glasses, and I get migraines, and I suffer from some depression. But, you know, I’m relatively able-bodied and fortunate for that, and I think it’s just being a decent person kind of to just be interested in this stuff.</p>
    <p><strong>Nic</strong>: Yeah. I have noticed that a lot of people that are interested in accessibility have other first-hand experience of disability, or have close, personal family or friends with disabilities. But, I’m always really glad to hear when people that don’t have this really close tie actually have an interest in and believe in the importance of accessibility.</p>
    <p><strong>Eric</strong>: Yes, well that’s very reassuring to hear. Thank you.</p>
    <p><strong>Nic</strong>: So, I’m glad to hear that you come from that-</p>
    <p><strong>Eric</strong>: Cause another thing that I worry about is representation and while I personally enjoy writing about this stuff and kind of, you know, being active-</p>
    <p><strong>Nic</strong>: Are you there?</p>
    <p><strong>Eric</strong>: … on social networks and tweeting and all that, I want to make sure that I’m not speaking for people and making sure that representation is equitable.</p>
    <p><strong>Nic</strong>: What is [crosstalk 00:16:21].</p>
    <p><strong>Eric</strong>: So, it’s something that really always kind of bothers me, or just kind of sticks in the back of my mind.</p>
    <p><strong>Nic</strong>: How people with disabilities are often the impetus on making designers and developers interested in accessibility. And I was saying that I was glad you came to it without having that first-hand experience because we need more people that are interested in accessibility that don’t necessarily come to it from a first-hand experience.</p>
    <p><strong>Eric</strong>: Yeah, and … Yeah, that’s really good to hear because one thing I do kind of worry about or am concerned about is in writing these things and saying these things, making sure that I’m not co-opting representation and I’m also speaking from … You know, if I’m speaking from an authoritative place, making sure that it is well and true and, you know, not stealing the spotlight from somebody else, who could be sharing their experiences.</p>
    <p><strong>Nic</strong>: A long time ago, when I was doing more direct disability rights stuff, I went to a conference, the National Council on Independent Living Conference, and there were a lot of people with disabilities that just would not interact with people that were able-bodied or at least looked able-bodied, because you can’t always tell someone has a disability just by looking. And I was annoyed at the dismissal of allies of people with disabilities just because they don’t have a disability. I remain firm that, you know, I believe in this nothing about us without us, so people with disabilities need to be involved in web accessibility, but we also need all the allies we can get. And, you know, having read lots of your articles, especially on CSS-Tricks, I think your approach is really dynamite, so please keep doing what you’ve been doing.</p>
    <p><strong>Eric</strong>: Thank you very much, yeah. I … That’s really nice to hear. Wow. Yeah. That’s kind of the other, like my other, I guess, master plan, like I’m some superhero or something, is getting the conversation out of traditional accessibility channels if I can.</p>
    <p><strong>Nic</strong>: Yeah.</p>
    <p><strong>Eric</strong>: And, you know, I get some … I’ve spoken with some people where it’s like, “Oh, you should own your content. Make sure it’s on your site. Make sure you’re, you know, you have complete and total authority over things that you do.” And I completely agree for many things, but you know, it’s kind of secretly my hope that for each one of these things I kind of put out there into the ether, maybe there’s that moment for somebody else where they just kind of stumble across it.</p>
    <p><strong>Nic</strong>: Yeah.</p>
    <p><strong>Eric</strong>: You know, that’s a little vain, but I gotta have something.</p>
    <p><strong>Nic</strong>: Yeah, yeah. Hey, you’ve been doing this for what, about 10 years, more or less, 15 years?</p>
    <p><strong>Eric</strong>: Yeah, 10. I … I’m old.</p>
    <p><strong>Nic</strong>: Yeah, yeah, yeah. Well, we’re all old and getting older. But do you think your view of accessibility changed since you started doing this?</p>
    <p><strong>Eric</strong>: Yes.</p>
    <p><strong>Nic</strong>: How?</p>
    <p><strong>Eric</strong>: I’m less dogmatic, and I am more convinced that I know absolutely nothing, by which I mean I think there’s kind of a phase people go through, where they’re like, “Oh yes, semantic HTML directly equals perfect accessibility, so how dare you not use this tag in this one way because this is how platonically these things work.” And, you know, in my kind of continued exploration of the space, like any other technology, there’s bugs, there’s gotchas, there’s like interop problems, and, you know, the most semantically pure solution may ultimately not be the best usable solution, and then you start to get into this whole argument of push/pull of like well do you honor the spec at the expense of usability?</p>
    <p><strong>Nic</strong>: Yeah.</p>
    <p><strong>Eric</strong>: Or, do you make these concessions for people and then therefore create a living standard that doesn’t actually exist on paper? And then, you know, flash forward five hours later and you’re just crying in the shower ’cause nothing is true.</p>
    <p><strong>Nic</strong>: Yeah. Yeah. Have you faced barriers? Or, are you now facing barriers when it comes time to implementing accessibility?</p>
    <p><strong>Eric</strong>: Yes. In a consulting role, I often times will encounter … And it runs the gamut from people that are just, you know, not aware, to people that are actively hostile to the thinking. And, oops sorry. I got a … Screen saver came on. Apologies. So, you know, it’s one of things … Big picture, I think most people are good or want to do good, and I think this is, you know, you get more flies with honey than vinegar. So,-</p>
    <p><strong>Nic</strong>: Yep.</p>
    <p><strong>Eric</strong>: … I try to explain where I’m coming from, but you know, kind of … Sometimes, there’s that situation where somebody would be like, “No. Our brand is orange,” and orange is probably the worst color for contrast. You know, it’s frustrating to kind of marry the client’s objectives versus doing the right thing.</p>
    <p><strong>Nic</strong>: Yeah.</p>
    <p><strong>Eric</strong>: Yeah.</p>
    <p><strong>Nic</strong>: What’s one trick that you’ve found effective getting past the hostility of a client?</p>
    <p><strong>Eric</strong>: For me, it’s building a relationship with them. So, it kind of … Again, just kind of sneaking it through, and then if they comment about it, I’ll happily talk to them about it.</p>
    <p><strong>Nic</strong>: Right.</p>
    <p><strong>Eric</strong>: And you get that lovely aha moment of, you know, it’s … They view it as like, “Well, I’m getting the best of this, and I may not have known that this was a thing that existed before. But now I know that it’s this but better.”</p>
    <p><strong>Nic</strong>: Yeah.</p>
    <p><strong>Eric</strong>: And you know, if you ask me directly, like if it’s in the project’s acceptance criteria, I will talk your ear off all day, but-</p>
    <p><strong>Nic</strong>: Yeah. So, relationship building as a way to get past client hostility towards accessibility, I think that’s an important way to look at it. Thank you.</p>
    <p><strong>Eric</strong>: Yeah. My other trick is CICD tools that … So, instead of one person minding all the accessibility, like a robot on the server yells at you. We had a client that needed accessible work, and we found that the developers were disabling their linters locally, and so, you know, talking about bringing down the hammer, we’re like, “Okay, well if you’re gonna do that, our move is to put that on the server,” and you know.</p>
    <p><strong>Nic</strong>: Yeah. That’s actually quite sweet. Just disable your linters. No problem. Yeah. No problemo, mas problemas. What’s your favorite word?</p>
    <p><strong>Eric</strong>: My favorite word?</p>
    <p><strong>Nic</strong>: Uh-huh.</p>
    <p><strong>Eric</strong>: Oh boy. What’s popping in right now is cromulent, ’cause I watched a lot of The Simpsons growing up.</p>
    <p><strong>Nic</strong>: Okay.</p>
    <p><strong>Eric</strong>: It’s not a real word.</p>
    <p><strong>Nic</strong>: No, but it works. It’s part of The Simpsons, so it’s … I mean, it’s … Cultural heritage is important.</p>
    <p><strong>Eric</strong>: Yeah. What’s your favorite word?</p>
    <p><strong>Nic</strong>: Right now, it’s sunny.</p>
    <p><strong>Eric</strong>: Sunny.</p>
    <p><strong>Nic</strong>: Sunny, yeah. Sunny outlooks, sunny emotions, sunny everything right now would be it. But of course, ask me that same question in 15 minutes. It may change.</p>
    <p><strong>Eric</strong>: I’m setting my timer.</p>
    <p><strong>Nic</strong>: Yeah. Let’s not, but pretend we did, right?</p>
    <p><strong>Nic</strong>: All right, Eric, thank you so much for your time. Today has been wonderful. Let’s wrap this up for this week, and we’ll chat again next week.</p>
    <p><strong>Eric</strong>: Oh, Nic, thank you so much. This has been an absolute pleasure.</p>
    <p><strong>Nic</strong>: Thank you.</p>
    <p><strong>Nic</strong>: Everyone out there, thank you for listening to the show. I hope you enjoyed it, and if you do, please do tell your friends about it. You can get the transcript for this and all of the shows at <a href="https://a11yrules.com">https://a11yrules.com.</a> And a quick reminder, you can get yourself some neat Accessibility Rules branded swag at <a href="https://A11y.store">https://A11y.store.</a> Catch you next time.</p>
</details>

## Show Notes


