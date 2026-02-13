---
layout: podcast
title: "E74 - Interview with Alli Berry - Part 1"
type: podcast
summary: "Alli tells us how experiencing lack of accessibility for a classmate of hers in the built environment helped her understand the importance of accessibility on the web."

permalink: /podcast/e74-interview-with-alli-berry-part-1/
# Podcast Episode Metadata
episode_type: full
episode_number: 74

# Audio Information
audio_url: https://a11yrules.ams3.digitaloceanspaces.com/podcast/episodes/E074-a11y-rules-alli-berry-part-1.mp3
audio_type: "audio/mpeg"

# Duration
duration: "PT26M25S"
duration_formatted: "26:25"

# Series
series: "A11y Rules Podcast"

# Episode Artwork


# Author/Host
author: "Nic Steenhout"

guests:
  -alli-berry
  

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
   <p><strong>Nic</strong>: Welcome to the Accessibility Rules Podcast. You’re listening to episode 74. I’m Nic Steenhout, and I talk with people involved in one way or another with web accessibility. If you’re interested in accessibility, hey, this show’s for you.</p>
  <p>To get today’s show notes or transcript, head out to <a href="https://a11yrules.com"">https://a11yrules.com.</a></p>
  <p>Thanks to Twilio for sponsoring the transcript for this episode. Twilio connect the world with the leading platform for voice, SMS, and video at <a href="http://Twilio.com"">Twilio.com</a>.</p>
  <p>This week I’m speaking to Alli Berry. Thanks for joining me with this conversation around web accessibility, Ali.</p>
  <p><strong>Alli</strong>: Thanks so much for having me.</p>
  <p><strong>Nic</strong>: So I like to let guests introduce themselves. In a brief intro, who is Alli Berry?</p>
  <p><strong>Alli</strong>: So I am the SEO and content lead for the Ascent by the Motley Fool. So, if you are familiar with investing at all the Motley Fool is a pretty big brand giving investment advice to people. So, my part of the business, we are a sub-brand of that, and we’re focused on creating free personal finance content, and my job is really to make sure our site is accessible … as accessible as possible for search engines, and to help our pages rank well, and to get our content to as many people as possible. And what’s fortunate about SEO is that often what is accessible for search engines is also what is accessible for humans so by approaching websites from an SEO perspective we’re at least on our way to helping make websites more accessible for humans too.</p>
  <p><strong>Nic</strong>: Yeah, that’s something I would like to explore a little bit in a moment but to really get warmed up… tell us one thing that most people would not know about yourself.</p>
  <p><strong>Alli</strong>:  Sure. I started my career as an ESL (English as a Second Language) teacher in Japan, and what I loved the most about doing that… I did that for a couple of years. I taught special education as well, so I came back to the US, and I really wanted to pursue that field of work so I got a job doing SEO, my very first SEO job, to pay the bills, and then I was doing a Masters in special education at night. And I ended up staying on the SEO path, there’s a lot going on in Chicago public schools at the time, and I decided I should probably just stick with the career path I was on but I’m super grateful that I had that background and experience ‘coz I had to read that ADA and the IDEA and learn about assistive tech, and I feel like having all of that background has really helped me better understand the people component to my job, and who is actually impacted by the decisions that we make on websites.</p>
  <p><strong>Nic</strong>: That’s interesting to hear about your background in special education. It seems that a lot of people in tech that are interested in accessibility have some kind of background that directly relates to disability in some way.</p>
  <p><strong>Alli</strong>: Yeah, whether they even realize it or not I think we impact so much, and I think often that gets lost.</p>
  <p><strong>Nic</strong>: How would you define web accessibility?</p>
  <p><strong>Alli</strong>: How do I define it? I think it’s allowing people to access content on the internet in the way that they want or need to consume it. Making flexible… making websites flexible enough that they can cater to all needs. Just so that, yeah… it’s important that people can access things in the way that they need to but also thinking about two peoples preferences as well.</p>
  <p><strong>Nic</strong>: Yeah the aspect of choice I think is important and often forgotten about even though the accessibility guidelines talk about it in a few ways. You mentioned that your primary role is SEO, how do you implement accessibility in your day to day work? Web accessibility that is.</p>
  <p><strong>Alli</strong>: So, basically what I do I’m always advocating for making sure that our web site is accessible as possible to search engine bots, right? So, thinking about all kinds of things from visual media, making sure that we’re using alt text on images or we’re transcribing videos using captions, transcribing podcasts, and also thinking about the mobile experience, and that’s becoming a much bigger deal in SEO. Google is now indexing the mobile version of websites over the desktop version so suddenly you have everyone thinking more about what a mobile experience looks like, and actually thinking about text enlargement which is helpful for both the aging population, people with visual impairment. That’s been interesting how that’s been aligning, a lot of time people are also thinking about… more about voice search and how information can be consumed via Alexa units or Google Home, and actually…</p>
  <p><strong>Nic</strong>: Yeah</p>
  <p><strong>Alli</strong>: …that’s super interesting because that’s something that people using speech to text readers have been obviously needing for forever but now you have the entire digital marketing community essentially thinking about that more as well.</p>
  <p><strong>Nic</strong>: It’s something I’ve always found interesting how accommodations and systems that are originally designed for people with disabilities come into the mainstream, and suddenly everybody’s paying attention to them. It’s an interesting circle.</p>
  <p><strong>Alli</strong>: Mmhmm</p>
  <p><strong>Nic</strong>: I often tell people that Google is the largest screenreader user on the planet. Would you agree with that? And if you do could you elaborate on that from a SEO perspective?</p>
  <p><strong>Alli</strong>: Yeah. Oh, that’s super interesting. I’ve never thought about it like that but I totally agree with that. I guess I often try to frame things too, like Google essentially, just another user with unique needs so kind of similar that they both struggle with the visual components. They struggle with things like iframes, it’s really important to have easy and simple navigation to help Google understand the most important pages to your website. Adding site search on your websites also super helpful because you can uncover what content is really hard for people to find. Again thinking about mobile. It completely is essentially a giant screen reader, and it’s almost better to think about Google as another human that’s trying to consume your content.</p>
  <p><strong>Nic</strong>: You did special education for a while. Is that how you became aware of the importance of web accessibility? Or was there something else that triggered that awareness?</p>
  <p><strong>Alli</strong>: That’s a good question. In terms of web accessibility yes. In terms of accessibility in general… when I was in school… when I was a middle school student one of my classmates had cerebral palsy so I was kind of her designated helper, and I used to take notes on carbon paper and give her copies. She and I and a bunch of our classmates went to Washington DC on a school trip, and I got to experience what it was like being in a wheelchair trying to get into really old government buildings. It was an awful experience. We had to walk … we had to go so much further just to get inside places. There were actually places we couldn’t go at all. We got stuck in an elevator in one of the monuments. Just as a 13-year old that experience really stuck with me, and I actually went home and wrote a letter to Paul Wellstone when I was 13. Because for my friend Amy that’s a part of her day to day, she’s very used to that experience. As somebody with privilege I … that was my first encounter with it, and it was an eye opening experience I guess, and that stuck with me for a long time. But then from the web perspective, learning assistive technology I’m certainly not an expert in it but at least having the exposure to it helped me see the complexity around web accessibility and how many things we need to be thinking about when we are creating websites, and stuff.</p>
  <p><strong>Nic</strong>: Do you think your experience in Washington when you were 13, obviously it opened your eyes but did it create a negative perception of what it might be like to live with a disability?</p>
  <p><strong>Alli</strong>: I don’t know about… I mean, it certainly it gave me a negative perspective on just how little thought people give to ableism, just to basic rights that people with disabilities have, and that’s getting completely disregarded a lot.</p>
  <p><strong>Nic</strong>: Mmmm</p>
  <p><strong>Alli</strong>:  Yeah.</p>
  <p><strong>Nic</strong>: Yeah</p>
  <p><strong>Alli</strong>: It definitely fired me up and got me thinking about how I can try to help.</p>
  <p><strong>Nic</strong>: That’s good. So you’ve been doing web work for what, about 5 years? More or less? 10 years?</p>
  <p><strong>Alli</strong>: I’ve been SEO since 2011 so I guess 8 years now</p>
  <p><strong>Nic</strong>: Yeah. 8 years. Cool. Has your view of accessibility changed over that time period or do you think things are more or less the same?</p>
  <p><strong>Alli</strong>:  Good question. I think, at least from my line of work people are becoming more and more aware of the need for accessibility.I think a lot of that is actually coming from fear, and I don’t know if that’s necessarily the best reason to be thinking about it but the fear of a lawsuit, of PR issues, is very real, and I work for a very large company. Accessibility is very top of mine because The Fool has had some issues with accessibility in their past. We … I worked for another company, Kaplan Professional Education, they were also realizing that they had.. They still had a ways to go on the accessibility front. But, I do feel like there’s been a lot more push to start actually making some changes which I think is a really good thing. And I think just as technology evolves, and stuff I guess my hope is that people are starting to think about accessibility from the beginning, rather than from cleaning things up after the fact.</p>
  <p><strong>Nic</strong>: It’s always easier to make it happen from the start rather than to try and retrofit accessibility in that. It’s interesting that it’s a topic that comes back over and over again with different guests I’m having. It’s this thing, you gotta bake it right in from the get-go. It’s like a blueberry muffin, you can’t put the blueberries in the muffin after the muffins are baked.</p>
  <p><strong>Alli</strong>: Exactly.</p>
  <p><strong>Nic</strong>: So…</p>
  <p><strong>Alli</strong>: Yeah, everything will work a lot better if it’s in the planning from the beginning.</p>
  <p><strong>Nic</strong>: Have you faced barriers in your… I’ll say work as a champion, internal organization champion of accessibility … are you finding barriers or is this fear of lawsuit really pushing everybody from legal to dev teams to everybody in the organization?</p>
  <p><strong>Alli</strong>: There’s, I would say, at least in my current role this is I think the most aware a larger team has ever been about accessibility. But, I do think, of course, there’s going to be barriers. One thing that would be amazing to have that I don’t think exists anywhere is to have a tool that would allow you to see if a page is failing some sort of assistive technology and why. You can put a search, or a website into a Google search console type tool, and see that search engines can accessibility something and why … it would be really cool if you could do that for different types of technology as well. Just because, a lot of times we don’t know what wouldn’t work for somebody unless you do user testing with people.</p>
  <p><strong>Nic</strong>: Yeah, that’s an interesting concept. There are a few automated testing tools that basically do a Yes, No, Pass, Fail kind of approach for some of the things but what you’re talking about is more an emulator of the various assistive technologies out there. Is that correct?</p>
  <p><strong>Alli</strong>: Yeah. I think there’s a hole in the market for it. That would be a really cool thing to develop. I wish I knew how.</p>
  <p><strong>Nic</strong>: That’s an interesting thought, maybe one of our listeners that are so technically minded might look at doing something like that. On the other hand, it’s interesting, because assistive technologies seem to be used differently by different people, and the same setup will behave completely differently from person to person so it would be interesting to see if something like that can be developped.</p>
  <p><strong>Alli</strong>: Yeah. I don’t know. I challenge everyone out there to come up with something.</p>
  <p><strong>Nic</strong>: There’s a challenge let’s make sure we put it out there. Jumping about on a different topic… Ali, what’s your favorite word?</p>
  <p><strong>Alli</strong>: I knew you were going to ask this question ‘coz I’ve listened to enough episodes now to know it’s always coming…. I was thinking about this, and I don’t know if I have a favorite word necessarily but does it have to be in English?</p>
  <p><strong>Nic</strong>: No, not at all</p>
  <p><strong>Alli</strong>: Okay. Well, there’s a word in Japanese that I think is really interesting. The full… I guess it’s technically 2 words, Kuuki Yomenai a lot of times people just shorten it to KY but it means ‘someone who can’t read the air. Or like somebody who can’t pick up on social cues, on social expressions…. Just can’t read a room and kind of adjust themselves accordingly. I think it’s an interesting word just because there isn’t an equivalent in English, and I think that says a lot about the cultural difference between Japanese culture and American culture. The Japanese are a lot more… it’s a collective society, there’s a lot more emphasis on fitting in whereas we’re a little bit more individualistic and being unique, and … I don’t know, I just think there’s … I think that’s cool to.. You can uncover bits and pieces about a culture from the language. Especially when there’s no equivalent word in your language and thinking about why.</p>
  <p><strong>Nic</strong>: Yeah, for some reason what you’re describing makes me think of situation awareness or lack thereof. Does that relate or is it different?</p>
  <p><strong>Alli</strong>:  No, I think that’s it. Situational awareness, and just… In Japanese culture you’re not going to ever receive direct feedback, as an American that can be really frustrating because we are very feedback oriented so a lot of it is dependent on you being able to pick up on when you’ve done something wrong, and kind of correct yourself, and that can be a really hard thing to tackle. So, yeah… it’s just a very different culture.</p>
  <p><strong>Nic</strong>: That’s interesting</p>
  <p><strong>Alli</strong>: Is there anything in French that’s… doesn’t have an English equivalent? I know you speak French.</p>
  <p><strong>Nic</strong>: Yeah there’s probably quite a few things but my bigger problems from having grown up in French and learning English as a fourth language have been what I would call false friends. Words that are on the surface very similar but in reality quite different. For example the word eventually. In French, we say “<span lang="fr">éventuellement</span>” and they are very similar however, there is a significant difference. In English eventually means, yeah we will get to there at some point in the course of things whereas in French “<span lang="fr">éventuellement</span>” means we may or may not get there depending on the events we are going to encounter.</p>
  <p><strong>Alli</strong>: Huh</p>
  <p><strong>Nic</strong>: So these kinds of … these kinds of false friends can be really throwing people for a loop, and causing a lot of angst when you’re trying to communicate something, and you’re not realizing the subtleness of words that sound so similar, that appear to be so similar that have some massive differences.</p>
  <p><strong>Alli</strong>: Yeah. That’s so interesting. Language is such a hard thing to master.</p>
  <p><strong>Nic</strong>: Language is fascinating. I mean, it’s veering off the topic of accessibility in some way but at the same time, I think communication and words and language is part of accessibility we have to make sure we’re speaking clearly and there are things in English that boggle me. Of course, there are things in French that boggle me too but things like why do you drive on a parkway and park on a driveway.</p>
  <p><strong>Alli</strong>: That is a great question</p>
  <p><strong>Nic</strong>: Yeah</p>
  <p><strong>Alli</strong>: I never thought about that. … Exactly, it’s totally counter-intuitive, and we expect everyone to just know that and accept it.</p>
  <p><strong>Nic</strong>: Talking about language, bring it back to the topic of accessibility, one of the things that we tend to promote a lot is the concept of plain language or plain English because we’re in English now. Does plain English help in SEO? And if so, how?</p>
  <p><strong>Alli</strong>: Yeah. That’s a great question. So, yes, plain language is definitely helpful. I used to do content audits when I worked for an agency, and depending on the topic we would generally… we had a tool that could tell us kind of the average reading level of somebodies content, and actually, the 8th-grade reading level is about what we would… we are shooting for in the majority of most cases. So, that’s definitely a helpful piece but I think it also comes back to keywords, and a huge piece of SEO is uncovering how people talk about essentially what your company does. Like, how do people… so, for example, just thinking about credit cards because I guess that’s what I focus a lot on… uncovering how people search for credit cards, the terms that they use, what are their longer queries about credit cards, figuring out what the search volume is. There’s a bunch of tools that will give you an average monthly search volume, and then matching that language on your website in a way that’s really natural. Trying to pick up how people are talking about what you do and then giving them the answers in the language that they’re seeking it.</p>
  <p><strong>Nic</strong>: There’s really a nice intersection between the 2 fields, I think that needs to be explored, and perhaps if… perhaps if more stakeholders understood the importance of accessibility and how it can help with SEO maybe some things would change. Of course, we don’t want to just look at doing accessibility just because it’s good for search engine optimization but it’s certainly something to look at.</p>
  <p></p>
  <p><strong>Alli</strong>: I totally agree. Yeah. you certainly wouldn’t want to do it only for the SEO component but you can make a pretty compelling argument about revenue on a couple of different fronts because there’s, like, organic is such a big piece of traffic for a lot of websites, and revenue and then there’s also the component of 20% of the population has a disability so that’s also potential customers. So when you combine all of that information together it’s actually a pretty compelling business reason to make changes.</p>
  <p><strong>Nic</strong>: For what it’s worth there was a new census data that came out at the end of last year, it’s actually 25% of the US population that has a significant condition that significantly affects one or more condition of daily living. So, it’s 1 in 4 now not 1 in 5.</p>
  <p><strong>Alli</strong>: Wow. Thank you. Thank you for that.</p>
  <p><strong>Nic</strong>: Hey, Ali, what’s your greatest achievement in terms of web accessibility?</p>
  <p><strong>Alli</strong>: Hmm what is my greatest achievement? … In terms of web accessibility, and not SEO accessibility … well, I don’t know if this is my greatest achievement, this is my most recent achievement. We have, and it’s small but it’s important. We have an agency partner whose doing a lot of research studies for us and they do a really great job of serving people and getting unique data but they keep… they’ve been putting the data into… the majority of the good interesting information, they’ve been putting it into images. And that’s been a big challenge for us to get all the important information into, say, alt text so that it’s accessible for everybody. Right? I had to have a hard conversation with them this week and explain why we need all of that information into our articles and not necessarily just in the image, in the visualization component of it. And explaining both why that matters for people and why that matters for search, so, I’m hoping… because they create a lot of content for a lot of different brands, that they actually take a step back and look at the larger picture of how they can do this better for everyone. Fingers crossed.</p>
  <p><strong>Nic</strong>: Yeah, that would be great if 3rd party vendors that ‘oh well, this client is requesting this change for accessibility but it makes sense. Let’s implement it for all our clients.’ That would be powerful if that happened because I think the uptake on accessibility would probably be a little bit faster if that happened.</p>
  <p><strong>Alli</strong>: Yeah. I really hope that they rethink kind of, how they do things because, I mean, they said yes it makes sense for your brand but it’s like, no it makes sense for every brand. So… again, there’s just so many people out there that need to access information in different ways so let’s do better.</p>
  <p><strong>Nic</strong>: Let’s do better. That’s a great statement to end this week on. Alli Berry, thank you for joining me and talking about accessibility in SEO and language and all that good stuff.</p>
  <p><strong>Alli</strong>: Thanks for having me</p>
  <p><strong>Nic</strong>: And we will talk next week,</p>
  <p><strong>Alli</strong>: Sounds good. Thanks!</p>
  <p><strong>Nic</strong>: Everyone out there, thank you for listening to the show. I hope you enjoyed it and if you do, please do tell your friends about it.You can get the transcript for this, and all other shows at <a href="https://a11yrules.com"">https://a11yrules.com</a> and a quick reminder, you can get yourselves some neat accessibility rules branded swag at <a href="https://a11y.store"">https://a11y.store</a></p>
  <p>Catch you next time!</p>

</details>

## Show Notes
<!-- leave blank -->

