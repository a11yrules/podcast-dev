---
layout: podcast
title: "E76 - Interview with Amy Carney - Part 1"
type: podcast
summary: "Amy Carney tells us that accessibility comes down to a design perspective. We’re designing to include people, specifically people with disabilities. And that is based on enabling people with disabilities to access content and web applications online."

permalink: /podcast/e76-interview-with-amy-carney-part-1/
# Podcast Episode Metadata
episode_type: full
episode_number: 76

# Audio Information
audio_url: https://a11yrules.ams3.digitaloceanspaces.com/podcast/episodes/E076-a11y-rules-amy-carney-part-1.mp3
audio_type: "audio/mpeg"

# Duration
duration: "PT26M10S"
duration_formatted: "26:10"

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
    
<p><strong>Nic</strong></p><p> Welcome to the Accessibility Rules Podcast. This is episode 76. I’m Nic Steenhout and I talk with people involved in one way or another with web accessibility. If you’re interested in accessibility, hey, this show’s for you.</p>
<p>To get today’s show notes or transcript, head out to <a href="https://a11yrules.com" style="text-decoration: underline;">https://a11yrules.com.</a> Thanks to Twilio for sponsoring the transcript for this episode. Twilio, connect the world with the leading platform for voice, SMS, and video at <a href="http://Twilio.com" style="text-decoration: underline;">Twilio.com</a>.</p>

<p>This week I’m speaking to Amy Carney. Amy, thanks for joining me in this conversation about web accessibility. How are you?</p>
<p><strong>Amy</strong></p><p> I’m good.</p>
<p><strong>Nic</strong> </p><p>Good. I like to let guests introduce themselves. So, in a couple of sentences… who is Amy Carney?</p>
<p><strong>Amy</strong> </p><p>Well, I’m definitely more than one thing, as Daniel Tiger would say, my son’s show. I’m a web designer and developer, an Alaskan, a Kansan, a mum, a wife, and a middle child, though not necessarily in that order.</p>
<p><strong>Nic</strong> </p><p>That’s a few hats to wear. That’s cool.</p>
<p>Let’s get started by telling us one thing that most people would not know about you.</p>
<p><strong>Amy</strong> </p><p>Unless you went to school with me most people wouldn’t know that from 4th to 11th grade I was a drummer for our school band. So, I do just a variety of bass drums, snare drums, cymbals… kind of whatever triangle. So, yeah, that was really fun. The marching band was probably my favorite bu highschool.</p>
<p><strong>Nic</strong></p><p>And do you still play music?</p>
<p><strong>Amy</strong> </p><p>No. Probably not since I moved to Juno. I did fantasize that I would continue on after I was an adult and even dragged my drum set around with me up to Alaska, but they’re just sitting in boxes in the last city I was in. So they never made it to Juno with me. They’re still in our cabin in Stewart. So, no. I haven’t played for a long time. I still end up tapping out beats sometimes when I’m listening to music but that’s about it.</p>
<p><strong>Nic</strong></p><p> Professional hazard.</p>
<p>We’re talking about accessibility today. How would you define web accessibility?</p>
<p><strong>Amy</strong> </p><p>I think that for me it definitely comes down to a design perspective. We’re designing to include people, specifically people with disabilities. And that is based on enabling people with disabilities to access content and web applications online.</p>
<p><strong>Nic</strong> </p><p>That’s interesting because I’ve never heard that aspect of accessibility that it comes down to a design perspective. I’d love you to elaborate a little bit more on that because it’s a take that isn’t talked about very often.</p>
<p><strong>Amy</strong> </p><p>I think part of it comes from me. I do a lot more design work. I still do a lot of code which is what I enjoy but it’s a lot of HTML and CSS and as I’ve been doing this for about 5 years professionally… when you’re building something you have to be able to keep the user in mind and decide how they’re interacting with your page, and that has so many different components whether it’s the base HTML structure that’s underneath and how things are spaced out, how the reading flow would go even just for a visual person. &nbsp;And just user experience I guess. Which user experience is built with design and recently I’ve been reading Web for Everyone by Sarah Horton and Whitney Quesenbery. I don’t know if I pronounced that right…</p>
<p><strong>Nic</strong></p><p> Yeah</p>
<p><strong>Amy</strong> </p><p>… and so, and they really put a lot into that which is actually really refreshing to read because they draw a lot from not just WCAG but universal design which is design and just web design of how people are interacting with different pieces on a page so I’m not very far in their book yet but it’s been very great to hear that perspective because you’re right, I feel like when I really started out it was very development based on, okay what kind of code can we use to make it more accessible and I find when I teach people it ends up coming back around to you teaching them HTML all over again or you’re teaching them design tips that this is how you make it better for somebody and that’s why it makes it better for everybody because you’re designing an experience you aren’t just keeping things from being broken.</p>
<p><strong>Nic</strong> </p><p>That’s great. Thank you.</p>
<p>You say you’ve been doing this kind of work professionally for the last 5 years or so, what does your day to day work look like? Where does your role fall within web accessibility? Is it… you say you’re designing but are you working solely in accessibility or… how does that integrate itself?</p>
<p><strong>Amy</strong></p><p> Accessibility probably came up more like 2 years ago for me. So I was hired about 5 years ago with the Alaska State Libraries, Archives, and Museums, it’s a conjunction of all 3 sectors and it’s under the umbrella of the state of Alaska so it’s within state government and so with the Libraries, Archives and Museums that we call LAM I was hired on as their publication specialist which is kind of like a catch-all term. I think it started out as more of a marketing, kind of making posters and flyers and yeah, we need a webmaster too so why don’t we do that too…And the job …</p>
<p><strong>Nic</strong></p><p> Typical</p>
<p><strong>Amy</strong></p><p> … yeah, so the job has evolved even before I got to it. It started out even as a librarian position and it’s just kind of morphed over the years that it’s existed. So when I got hired on by that point they were saying, ‘We need somebody who’s about 80% webmaster and then, by the way, can you make posters and flyers? Have you done any work like that?’ and so, that’s another way I’m able to focus a lot on design is going between paper and between pixels… it’s actually really interesting to see the relationships. I know some people who have had design backgrounds and it’s helpful to them for web design and development but for me, it’s been learning because I was a librarian before this and so the last 2 years we’ve been making more of a push. I’ve mentioned it before where I was like, ‘Hey, I think this is an important issue but I don’t know how we get there’. And then our overarching department, the Department of Education has had to take it seriously in the last couple of years so we’re all learning together and doing that push so I’d say in the past year, even though I’m doing the day to day webmaster stuff like posting new content or creating new pages for information we have to offer, for services we have to offer, probably 90% of my time has been accessibility remediation just because we have a mandate and we are going through our own audit right now. And so, that’s been a learning experience which I am so grateful it’s there because I think it’s important. It’s not just we have to do this.</p>
<p><strong>Nic</strong></p><p> Was this mandate for your organization to have an accessible website… was that how you became aware of accessibility and how important it is or did you have other triggers before that?</p>
<p><strong>Amy</strong></p><p> I had some other ones before that. Reading just all the different aspects of web design and I was interested in it from a user experience perspective but I just didn’t know how to get there and I didn’t have any support or motivation from above to do it. So it’s just kind of like on the list, ‘yeah we will learn about that sometime’ and I want to learn about it but it’s just not the priority.</p>
<p><strong>Nic</strong></p><p> If I understand correctly you recently completed a ‘100 days of’. Is that right?</p>
<p><strong>Amy</strong></p><p> I did.</p>
<p><strong>Nic</strong></p><p> So you obviously did make the time to learn about accessibility because you learned about accessibility and spoke about accessibility on your site for 100 days. Tell us about that.</p>
<p><strong>Amy</strong> </p><p>Well, it’s actually a second round that I did. A couple of years ago when I really started trying to learn web accessibility that first round was kind of like, directionless. I was just grabbing anything I could find online, I didn’t know where I was going with it as far as I needed some guidance but didn’t know what that guidance was. So, it felt like a lot of random information at once and obviously WCAG. You hear about WCAG the Web Content Accessibility Guidelines but that was about it. And, starting to follow people on Twitter that helped some but this time around I needed those guideposts and some of my own success criteria, you could say. And so when I discovered the international association of accessibility professionals that had their certification for a web accessibility specialist I said, ‘this is what I’m looking for. This is the guidance I need’. It’s not just about the certification but they have actual things that make you a more educated person understanding web accessibility in depth. And so I used that as my goal and was able to do. The 100 days has worked for me before for coding, I used to do 100 days of code rounds that Alexander …</p>
<p><strong>Nic</strong> </p><p>Okay</p>
<p><strong>Amy</strong> </p><p>… and so that’s where I got the idea first to do 100 days the first time so this time I was like, this works for me. I can do it and stay committed and I’ll learn so much more for it. And I did. And that goal was actually good in studying for the certification. I feel I know so much more and am satisfied with what I learned as opposed to the first time around.</p>
<p><strong>Nic</strong> </p><p>That’s awesome. Do you think your view of accessibility has changed over your 2 rounds of hundred days of accessibility?</p>
<p><strong>Amy</strong> </p><p>You mean for better or worse? Or just the things that I know?</p>
<p><strong>Nic</strong> </p><p>Yeah, for better or worse. Has your philosophy or your understanding of it or maybe just things that went click, aha!</p>
<p><strong>Amy</strong> </p><p>Oh yeah, yeah. Well, I think the biggest change has been… this really isn’t as hard as we make it all out to be. When you first start out during my first round it’s kind of like… okay. It’s kind of like, mystifying. What are we supposed to be doing here? And yeah, we have these guidelines but is anybody really going to be sitting and doing a checklist of these guidelines. You know, something more beginner level like. Or friendly to someone who just doesn’t quite know what they’re getting into and I think the second round really became more of ‘I don’t expect anybody to follow my lead and do 100 days. That’s a bit much for most people but, I feel like as I did my tweets every day that it was like, ‘okay, this is advocacy and it’s education. Like, all these little things matter in accessibility and if you learn about this thing, cool. You’ve just made your site better if you do it this way. So, I feel like it came down to just publicly putting out tidbits now and then for people. Yeah, I definitely feel like it’s not as hard. And, there’s actually a really supportive community out there of people advocating for web accessibility and that’s been really cool too. That was hard to find in the beginning.</p>
<p><strong>Nic</strong> </p><p>The community is growing but I think also we are getting more and more interconnected and it’s easier to find one another. I’m certainly growing the number of people that I connect that are doing accessibility or have an interest in accessibility and that’s fantastic for me to see that happen, because 5 years, 6 years, 7 years ago especially on Twitter it was almost a small, very family like grouping of maybe a couple of dozen people at most but now we are connecting to all these people and I think it enriches the community and it enriches the message we are able to collectively put forward. I just think it’s wonderful.</p>
<p><strong>Amy</strong> </p><p>And maybe I’ve gotten lucky to see that transformation because I’ve … I don’t remember how long I’ve been on Twitter but through the hundred days of code I was able to connect with people with that hashtag and it was interesting to start getting broader perspectives of that and not such a narrow view of people I had met in person. And so it was neat to be able to use that and find the A11y hashtag and just slowly building on finding people and finding peoples articles that they’ve written online. It’s …. Yeah. That’s cool to see your perspective of how it’s transformed.</p>
<p><strong>Nic</strong></p><p> Did you come across barriers or difficulties when you were learning about accessibility and if so how did you get over it?</p>
<p><strong>Amy</strong></p><p> Well, the first round, like I say, I think WCAG was intimidating and that was before the web accessibility initiative had redesigned their site and so their site didn’t feel really friendly before. When I saw references to it I still kind of feel like I’m not quite making connections with the dots. So, yeah, I guess at the very first round I felt like there were more barriers. I think it clicked a lot more in the second round of having a particular goal, having that body of knowledge document from IAAP and having those … that guidance for like, okay, so yes, you need to understand and learn WCAG and you need to learn ARIA and I mean, that can be a life long learning there of understanding ARIA.</p>
<p><strong>Nic</strong></p><p>Yeah</p>
<p><strong>Amy</strong></p><p>But, also ATAG. I hadn’t known about ATAG before the offering tools for accessibility guidelines.</p>
<p><strong>Nic</strong></p><p>Yeah</p>
<p><strong>Amy</strong> </p><p>And so, that was good. It was like, okay, I know I need to learn these but they had additional guidance for that. Like, okay, here’s how to understand how people with disabilities might access the web depending on their assistive technology or strategies that they use. Even if it’s something as simple as finding the screen. So, yeah, the second round I didn’t feel like there’s quite as many barriers. Then it suddenly started clicking like ‘Oh, okay I need to continue just looking at people as the people having this experience and what these challenges feel like to them’ and then WCAG started falling better into place. I can’t remember every guideline or success criteria mostly but I start to remember a little bit as I start to encounter the different disabilities or the different assistive technologies. So, yeah, I don’t feel like I ran into as many barriers the second time. The first time I just felt kind of lost.</p>
<p><strong>Nic</strong> </p><p>Yeah, I’ll let you in on a secret that’s probably not all that well kept but most people that are doing accessibility don’t actually know WCAG top to bottom, front to back and all that. I certainly don’t. I know what all the criteria are all about, and if I need to reference that then I can find it easily but I would be the first one to admit I can’t quote you all the success criteria by ear. And, I think, for me anyway, at this point WCAG is important because it’s our guiding standard but it’s also tricky because it’s not, to me, it’s not about compliance. We shouldn’t use WCAG as a be all and end all. IT shouldn’t be the target. It should be a tool to help us make things more accessible. So…</p>
<p><strong>Amy</strong></p><p>I definitely agree. And, that I think is what I learned in the second round. That it’s a great starting point and it can be overwhelming but it’s not the endpoint. And that comes down to design again as you strive for a more universal experience for all and testing with actual people and seeing how it actually works for them and not just… kind of like automated testing. It’s like, okay, we’ve kind of met this and these are things being pointed out to us but it’s not the end. We need to keep checking that it works for real people.</p>
<p><strong>Nic</strong> </p><p>Yeah. Would you say your first round of testing was… the learning was more difficult because things were more scattered but having had that first round of learning you had more of an idea of where you’re going and then you found the resources at IAAP and that allowed you to really focus?</p>
<p><strong>Amy</strong></p><p> Mmmhmm</p>
<p><strong>Nic</strong></p><p> Do you think if you’d found the IAAP resource before your first round that your first round would’ve been easier?</p>
<p><strong>Amy</strong></p><p>That’s actually a very good question that I’ve even asked myself. Was this… do I feel like I’m late finding it or is it just a matter of progress, the way I’ve been searching out things and I don’t know? I sometimes think I don’t think I would’ve been ready to study all of that stuff in the body of knowledge that they put out because of some things that they review for me and it’s just like, ‘ oh yeah, yeah, yeah, I get that already.’ And I know what I need to add on and fill gaps but, yeah, a couple of years ago I felt, I feel it probably would’ve felt overwhelming. Even more overwhelming. Right now I’m just nervous about the [XA? 19:25], you know but I feel like I’m confident. And, before that, I think I would’ve felt just as overwhelmed about looking at the WCAG documentation.</p>
<p><strong>Nic</strong></p><p> Yeah</p>
<p><strong>Amy</strong> </p><p>And saying, ‘What is all this about?’ So yeah, it’s…</p>
<p><strong>Nic</strong> </p><p>So when is your exam?</p>
<p><strong>Amy</strong></p><p>April 3rd.</p>
<p><strong>Nic</strong></p><p>April 3rd. I will be thinking of you. I will be thinking of you and wishing you the best of luck for that.</p>
<p><strong>Amy</strong></p><p>Thanks.</p>
<p><strong>Nic</strong></p><p> What’s your greatest achievement in terms of web accessibility?</p>
<p><strong>Amy</strong></p><p> My greatest achievement?</p>
<p><strong>Nic</strong></p><p> Yeah</p>
<p><strong>Amy</strong></p><p> I think… because of these last 2 years and really pushing for it, despite the frustrations I walked away within the first round and not feeling like I actually learned what I hoped to learn, it motivated me to talk to people and so I actually ended up starting that year a web accessibility working group for the state of Alaska. It started out, it was a great time to spark a conversation. We had just started a new branch, the office of Information Technology, coz they were trying to do a lot of centralization with IT and they hired on their first CIO and he was very new, he had only been there a few months and I already had all this web accessibility stuff in mind and I said you know what, I think OIT needs to have some part in this so I contacted him, he responded and said, ‘Yes, we can have a meeting and talk about this.’ And so…</p>
<p><strong>Nic</strong> </p><p>Wow</p>
<p><strong>Amy</strong></p><p> … I brought in some other people, some other webmasters that I had already gotten to know that I knew were interested in web accessibility, that cared about it but just didn’t have any support or hold on really making a difference. And so, we had a conversation with him and he had a background with the Federal Department of Education and he was saying, “I don’t even know why this is in question here, this should be happening.” And so he goes, “I don’t know what the Office of Information Technology can do aside from if it’s any kind of procurement issues but, okay.” So we got that rolling, we involved them and we ended up starting an actual working group with this small group of people that I had and had one of their OIT staff sitting in on it and then we just started talking about, okay well, what do we want to accomplish? Well, we all know that we need training… I don’t know how we are going to do that but, okay. And then we need to set some kind of standard that’s actually… people know about because I think that some people had the idea that WCAG 2.0, a AA level was what we were striving for but I think it wasn’t Statewide knowledge as far as people working as webmasters so, we’re like, we really want to make sure that that’s understood by people. And, what about testing tools. I mean, I think a few copies of JAWS was floating around here but maybe if everybody could have a copy to test with and maybe some kind of automated testing tool because some departments had purchased some kind of scanning software and others don’t have anything. And so, we just had those conversations and we just kept meeting on a monthly basis not knowing what we were doing and eventually that State A to A coordinator position got filled which was a miracle because it had been open for, like, 2 or 3 years, vacant. And so we invited him to come and he was like, “This is great you’re doing this”, and “let’s see what we can do.” And so through his push, he’s had the higher up support to put out memos and recommendations and so after that time, we have now definitively gotten a policy saying okay, the State of Alaska is going to follow, or strive for WCAG 2.1 AA level…</p>
<p><strong>Nic</strong></p><p> Nice</p>
<p><strong>Amy</strong> </p><p>… And everybody was supposed to put that on their department homepage. Some kind of link stating this is what our efforts are going to be and then we’ve started discussions about trying to figure out, at a Statewide enterprise level, figuring out what automated testing scan we can have for everybody and exploring also what should all our public computers look like? What kind of tools should we offer people? What is our baseline? Is it just going to be magnification? Are we going to have a screen reader on there? Are we going to have special keyboards? Or mice? And so, we’ve made a lot of progress which is kind of astounding to everybody because some things just move really slow where people drag their feet and it’s been timing.</p>
<p><strong>Nic</strong> </p><p>Yeah</p>
<p><strong>Amy</strong> </p><p>It was all timing. And, I feel great that I was a part of that, of just asking that one guy, and he’s not even a CIO anymore, just like “Hey, can we meet about web accessibility?” So, I’m kind of proud of that.</p>
<p><strong>Nic</strong> </p><p>So you should be. This is amazing work. And, now you need to go to all the other States and replicate that.</p>
<p><strong>Amy</strong> </p><p>I would actually like to see what other States do and how they’re doing it or where they’re at I guess.</p>
<p><strong>Nic</strong> </p><p>Yeah. Hey, Amy, thank you so much for that wonderful conversation. I think we’re going to end this on a high note and resume next week. So, Amy Carney, thank you for being a guest on my show.</p>
<p><strong>Amy</strong> </p><p>Thanks for inviting me. It’s great to be a part of it.</p>
<p><strong>Nic</strong> </p><p>Everyone out there, thank you for listening to the show. I hope you enjoyed it and if you do, please do tell your friends about it.You can get the transcript for this, and all other shows at <a href="https://a11yrules.com" style="text-decoration: underline;">https://a11yrules.com</a> and a quick reminder, you can get yourselves some neat accessibility rules branded swag at <a href="https://a11y.store" style="text-decoration: underline;">https://a11y.store</a></p>
<p>Catch you next time!</p>

</details>

## Show Notes


