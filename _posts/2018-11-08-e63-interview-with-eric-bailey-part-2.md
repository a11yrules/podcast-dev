---
layout: podcast
title: "E63 – Interview with Eric Bailey – Part 2"
type: podcast
summary: "Eric tells us accessibility shouldn’t be just technical curiosity. It’s about people."

permalink: /podcast/e63-interview-with-eric-bailey-part-2/
# Podcast Episode Metadata
episode_type: full
episode_number: 63

# Audio Information
audio_url: https://a11yrules.ams3.cdn.digitaloceanspaces.com/podcast/episodes/E063-a11y-rules-eric-bailey-part-2.mp3
audio_type: "audio/mpeg"

# Duration
duration: "PT27M49S"
duration_formatted: "27:49"

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
    <p><strong>Nic</strong>: Welcome to the Accessibility Rules podcast. This is Episode 63. I’m Nic Steenhout and I talk with people involved in one way or another with web accessibility. If you’re interested in accessibility, hey! This show is for you. To get today’s show notes or transcript head out to <a href="https://a11yrules.com">https://a11yrules.com</a></p>
    <p><strong>Nic</strong>: Welcome back everyone. In this episode I’m continuing my conversation with Eric Bailey. Last week was really quite good: we spoke about ways to reduce client hostility, which involved relationship building. We spoke about implementing accessibility by stealth, because it really should be part of your skillset, and do check out the episode if you haven’t already.  Eric, welcome back.</p>
    <p><strong>Eric</strong>: And what my favorite word was…(laughing)</p>
    <p><strong>Nic</strong>: Yes? What was your favorite word?</p>
    <p><strong>Eric</strong>: “Cromulent”, which is down on paper forever now. (laughing)</p>
    <p><strong>Nic</strong>: Right, well, going from “cromulent”, building on that, Eric, let’s start the show with something really positive. What is your greatest achievement in terms of web accessibility?</p>
    <p><strong>Eric</strong>: My greatest achievement? Oof…I helped maintain the A11y Project started by Dave Rupert many years ago to create a centralized repository of accessibility information.  It was one of those things where I did a little bit of work and got some attention and was “called to the big leagues”, I guess. I was asked to become a maintainer and while I want to sink a lot more time into it, I do think it’s a great resource in that it just sits there and points to other great resources. So, being able to ensure that that stays alive, I’m very happy to be able to contribute to it.</p>
    <p><strong>Nic</strong>: I think one of the problems accessibility has is that the information is so fragmented, all over the place, and the work of the accessibility project is so important because it centralizes a lot of that information. It reminds me in some ways of Yahoo!, way, way before Yahoo! was a Yahoo! we’ve known (inaudible), it was quite instrumental, I think, in making things happen. I view the accessibility project that way.</p>
    <p><strong>Eric</strong>: Thank you. Hopefully, we never turn into the Yahoo! where good ideas go to die (laughing).</p>
    <p><strong>Nic</strong>: Maybe you’ll become the Yahoo! that makes you a billionaire.</p>
    <p><strong>Eric</strong>: Yeah…</p>
    <p><strong>Nic</strong>: If that happens, please don’t forget me.</p>
    <p><strong>Eric</strong>: Oh no, not totally (laughing). I’m still bitter about Yahoo! Pipes getting killed. I used that service.</p>
    <p>I think the fragmentation is a very interesting thing because technology moves so fast and front-end even faster, and sometimes this information is solid information but just for even that six-month window when it was relevant and then it may turn into an anti pattern.  And that’s very…</p>
    <p>Last episode I spoke about getting increasingly more unsure of if what I am saying and hearing is correct and accurate, and that’s part of it, can I trust this source? Has it been battle-tested and put through the full range of every screenreader and browser combination that’s supported? I’m going to get a little depressing for a second here but I’ve seen more than my fair share of “accessible” out-of-the-box solutions that vaguely work in VoiceOver but that completely fall apart with NVDA or JAWS.</p>
    <p><strong>Nic</strong>:  Or are just that, “focus styles, what’s that?”</p>
    <p><strong>Eric</strong>: That’s my pet project… (laughing)</p>
    <p><strong>Nic</strong>:  I came across a site the other day that really amazed me. They went and defined the focus style, no, they went and defined the background color on the link to be the exact same color as the focus style on the default browser outline. So, you could not actually see the default browser…</p>
    <p><strong>Eric</strong>: Oh, that’s perfect! (laughing) Wow!</p>
    <p><strong>Nic</strong>:  I think that took some doing, to do that…</p>
    <p><strong>Eric</strong>: Yeah, there’s some situations where I’m not even mad, I’m just curious, like, what happened here?</p>
    <p><strong>Nic</strong>:  Sometimes you go beyond anger and you just have to shake your head and laugh.</p>
    <p><strong>Eric</strong>: Yeah.</p>
    <p><strong>Nic</strong>:  So, we’re talking a little bit about frustration. What would you say your greatest frustration is? Is it focus styles, or, what’s the frustration on web accessibility?</p>
    <p><strong>Eric</strong>: I’m going to stick with focus styles because I recently spoke about it. That’s kind of like another big picture concern/learning phase you go through when dealing with accessibility is the web is more than just mice and trackpads and keyboards, and also accessibility is more than just making it work on a screenreader. The talk was kinda trying to demonstrate that and say there’s a reason that this property exists and its because browsers were made by some very smart people and its a specific acknowledgement that the web is more than just this and its silly to think of them as ugly because of your perceived aesthetic values. It’s a very practical and pragmatic thing that people use.</p>
    <p><strong>Nic</strong>:  How do you resolve the conflict between aesthetic values of developers or designers and the necessity to have accessibility built in? That seems to be something that comes into conflict reasonably often.</p>
    <p><strong>Eric</strong>: Hmmm… It’s easy to get on your high-horse and say, oh, this is all in the service of utility but I usually frame it, like I’ll try to frame it in terms of “don’t you want everybody to use your product or your service?” It’s basically like saying, “No, I don’t want your money, no thank you”.  Like, “I wish to not have the most money, or the most customers.” That’s… sometimes that works, sometimes it doesn’t. (laughing)</p>
    <p><strong>Nic</strong>:  Do you that there’s something that everybody knows about web accessibility, conventional wisdom, if you want?</p>
    <p><strong>Eric</strong>: I don’t think so. I’ve run into so many, well, not even so many, just of the people that I know I don’t think there’s been one common thread like I think since people are created stereotyping I think a lot of people go to a person in a wheelchair or a blind individual but I think that’s more the culture being kind of bad and not necessarily because they specifically researched it.</p>
    <p><strong>Nic</strong>:  Do you think maybe people with disabilities have dug themselves into a pit with this? Wheelchair users are very good at screaming when there’s no access into buildings and folks who are blind have been very vocal about the lack of accessibility for them on the web. Twenty years later when we are thinking web accessibility, we’re thinking mostly about people who are blind, and when we’re thinking building accessibility, mostly we’re thinking about wheelchair access. But obviously as we’ve been talking about, there’s much more to it than that.</p>
    <p><strong>Eric</strong>:  Now, these are voices that need to be heard and and these complaints are very valid. I don’t even know if complaints is the right word. I think it’s also in making yourself in volunteering your personal life and your time and your effort and resources to bringing these things to the public discussion, I think you are expanding the ability of somebody to become aware of those issues. For you especially, I appreciate you discussing some of these things on Twitter because I know you’re sacrificing some of your privacy. Opening up the internet, and the world, to a little slice of your life. I appreciate it. I’m always very interested to learn things that I may not have known before. And then there’s kind of a snowball effect on that.</p>
    <p><strong>Nic</strong>:  Thanks for that.</p>
    <p><strong>Eric</strong>:  Thank you.</p>
    <p><strong>Nic</strong>:  Can you think of one reason for which people fail to succeed at implementing accessibility?</p>
    <p><strong>Eric</strong>:  Deadlines…</p>
    <p><strong>Nic</strong>:  Deadlines? How so?</p>
    <p><strong>Eric</strong>:  The whole move fast and break things, thing. It’s pretty pervasive in the current development culture. It’s great for great for being first to market but it’s also great wracking up technical debt. Part of that technical debt is accessibility. It compounds and compounds. My go to example is Snapchat. It’s falling apart right now because its user-experience is completely incomprehensible (laughing) There’s your cognitive concern right there. It fails at all the POUR criteria basically. And then Instagram came and ate their lunch because they label their buttons. That kind of thing.</p>
    <p><strong>Nic</strong>:  You’re talking about deadlines and technical debt and all that. The one example which is for me very applicable right now is Guttenberg and WordPress. They basically said “look we’re not actually going to an accessibility audit of Guttenberg because if we do that we will not be able to meet our release timeline”. That just bewilders me. i don’t understand this.</p>
    <p><strong>Eric</strong>:  It makes me very mad, honestly. Because isn’t WordPress running 30% of sites on the internet?</p>
    <p><strong>Nic</strong>:  Yes</p>
    <p><strong>Eric</strong>:  That is one fact that is incredible. On top of that it did have this understanding in the industry as being a very comparatively… a more positive experience if you are using assistive technology to navigate and to kind of just… I don’t want to say “snub your nose at it”, because I know there’s some very passionate people kind of helping to move it along. But the way they’ve been approaching it has left a really bad taste in my mouth. Again, kind of in episode 1 when we were saying “I don’t want to bring down the hammer, but this all could have been fixed with planning and not just racing to get something arbitrary out of the door”.</p>
    <p><strong>Nic</strong>:  And probably as well some buy-in from leadership. Because there’s great people working on accessibility but they are hamstrung I think.</p>
    <p><strong>Eric</strong>:  Yeah. That quote of “do an audit and write a blog post about it” left a very bad taste in my mouth. It seems incredibly dismissive. As if this wasn’t actual people being affected. It’s more of a technical curiosity to be observed and then move on.</p>
    <p><strong>Nic</strong>:  Technical curiosity. I like that expression. Thank you. How do you avoid that kind of failure between deadlines and technical curiosity rather than… How do we avoid failure with that?</p>
    <p><strong>Eric</strong>:  I don’t know. I mean… Shifting left is great. Making these concerns known earlier. But I think to your point, you need organizational buy-in. Because if it’s not a priority, there will be this ripple effect of it not being… You model the behavior you wish to see. If you’re not discussing accessibility, it will propagate to the project managers who won’t throw it in the backlog, and won’t add it to the acceptance criteria or write it into the QA test. I guess… You don’t want to be in a position where you’re just patching holes after holes. It’s just unsustainable</p>
    <p><strong>Nic</strong>:  Yeah. Last episode you mentioned building relationships as a way to reduce client hostility towards accessibility. I think that this building relationship would be very appropriate here in terms of getting leadership buy-in. But at the same time there’s sustainability issue that you mentioned. You can’t spend all of your time building relationships with all the people out there.</p>
    <p><strong>Eric</strong>:  (laughing). There’s only so many hours in the day.</p>
    <p><strong>Nic</strong>:  That’s right.</p>
    <p><strong>Eric</strong>:  That’s a really good point about sustainability. Because an audit is a snapshot. Websites are not static. I’m sure if you’ve done audits, you’ve been in the position where checking things.. You log in half an hour later and it’s changed because somebody implemented a feature. It’s a snapshot of a thing in time that isn’t just reflective of the reality of what this thing is. I don’t know. (laughing) It bugs me.</p>
    <p><strong>Nic</strong>:  Yeah.. What would you say the greatest challenge is for the field of accessibility moving forward?</p>
    <p><strong>Eric</strong>:  I think the atmosphere is better. The inclusive design movement is in vogue for now, and that’s great. Empathy in design is a bit of a buzzword. I like that it’s being considered and quantified. I think honestly the biggest concern I have is single page applications, and how they throw out a lot of what you get for free with other ways of building websites, for better or for worse. You know you can make them accessible, but there’s this weird disconnect I feel between what the documentation says you can do versus what’s actually done.I think developer education is a problem there where the market incentivises people who know buzzwords. And not necessarily what those buzzwords means and do.</p>
    <p><strong>Nic</strong>:  Yeah. I’ve recently looked at a single page application that had code that looked more or less like &lt;a role=”button” tabindex=”0″&gt;</p>
    <p><strong>Eric</strong>:  (laughing) Yep</p>
    <p><strong>Nic</strong>:  And I came back to it and I still couldn’t believe what I was reading and I think this concept of you have a lot of easy accessibility wins when you’re using semantic HTML the way it was intended to be used. Then you go and you start trying to reinvent the wheel with divs and ARIA and you never get quite there. you always have conflict somewhere.</p>
    <p><strong>Eric</strong>:  That’s another kind of… They’re related to a certain extent. Like the over-reliance on ARIA. It’s sort of like compliance via shotgun blast. Like… I’m going to slap as much ARIA as I can onto this and hope it works. And then you get into these situations where you have… you know… You have your role shifted tabindexed button that does nothing (laughing) And I don’t know what’s happening here. I probably don’t want to hear the answer</p>
    <p><strong>Nic</strong>:  I don’t know what’s happening either. And I wish we had the answers.</p>
    <p>Who inspires you Eric?</p>
    <p><strong>Eric</strong>:  Oh… Many people. Yourself. Cordelia, Heydon Pickering, Carie Fisher, Scott Vinkle, Scott O’Hara, (incomprehensible), I’m blanking more because I’ve been put on the spot. But I don’t know. Twitter is a burning trash fire of a social media service, but I have my nice bubble of thoughtful people that I’ve made for myself. It’s nice in this day and age that you can have these relationships that you wouldn’t have otherwise been able to have had if you weren’t physically near them or working with them. It’s always nice to see them in person if we’re at the same conference. Or even if we’re just exchanging some tweets. Or reading stuff.</p>
    <p><strong>Nic</strong>:  If you were to not be a designer, what profession other than the one you’re doing would you like to attempt?</p>
    <p><strong>Eric</strong>:  Ohh. That’s a good one. Probably a sociologist.</p>
    <p><strong>Nic</strong>:  Sociologist?</p>
    <p><strong>Eric</strong>:  Yeah. So very poor. I love reading about just all the diversity and all the interesting things that people do and say. It’s fascinating stuff and I can’t get enough of it.</p>
    <p><strong>Nic</strong>:  What strikes me is that in many ways that ties in to design and making things work for people with disabilities. It’s about diversity. It’s about people.</p>
    <p><strong>Eric</strong>:  Yeah. Can I quote you on that?</p>
    <p><strong>Nic</strong>:  Absolutely!</p>
    <p><strong>Eric</strong>:  Great.</p>
    <p><strong>Nic</strong>:  You’ll even have it on black on white when the transcript comes out.</p>
    <p><strong>Eric</strong>:  Yeah, just copy/paste!</p>
    <p><strong>Nic</strong>:  There you go. Please attribute, attribute, attribute.</p>
    <p><strong>Eric</strong>:  Of course.</p>
    <p>I don’t know. Design is weird. because it feels like the industry went through a transformation about 5 or 6 years ago where it was “your job is to make pretty things in Photoshop” and then kinda switched into “your job is to be armchair psychologists, and also make pretty things”. It’s been a very interesting career. I’m pretty lucky to have been able to have been in it for as long as I have.</p>
    <p><strong>Nic</strong>:  I hope you keep doing what you’re doing because you are making an impact. I routinely forget that I know something, do a Google and “oh, there’s an article by Eric Bailey on CSS Tricks”, and I think “oh yeah, I knew that”</p>
    <p><strong>Eric</strong>:  (laughing)</p>
    <p><strong>Nic</strong>:  It’s good to have that out there.</p>
    <p><strong>Eric</strong>:  I would say if anybody who’s listening is interested, yourself as well, Chris Koyer is a great person, very friendly. Writing for him is a lot of fun. If that’s something you’re interested in, like… I was terrified the first article I submitted because I grew up reading it and like “oh my god I get to take my shot at it”. And he’s just very friendly and accomodating and his staff is as well. I know he’s always looking for good information. Especially in that intersection of accessibility and front end and CSS. If it’s something you’re interested in, i so totally recommend giving it a shot.</p>
    <p><strong>Nic</strong>:  I will keep that in mind. Although lately my creative juices are all going towards the podcast</p>
    <p><strong>Eric</strong>:  (laughing) Podcasting takes a lot of work.</p>
    <p><strong>Nic</strong>:  It does. But it’s also rewarding. i started this, on my god, a year and a half ago now. I didn’t know then that I’d get so much out of it now. It’s really been great. Anyway…</p>
    <p>Back to you because this episode is about you. I would like to wrap it up by asking you what’s the one thing people should remember about accessibility?</p>
    <p><strong>Eric</strong>:  Sure. It’s a wholistic concern. It’s more than just a developer in a chair, or a designer at a white board. I think it’s something you can integrate into every aspect of digital design. If that’s something that you can kind of start thinking about and active measures to include.</p>
    <p><strong>Nic</strong>:  cool.</p>
    <p>Eric, thank you so much. I’ve loved talking with you about accessibility. We’ve interacted on social media and Slack but having this discussion was really dynamite. So thank you.</p>
    <p><strong>Eric</strong>:  Thank you. I love the podcast and I’m so happy to be able to contribute to it.</p>
    <p><strong>Nic</strong>:  Excellent. Well, Eric, I’ll catch you around.</p>
    <p><strong>Eric</strong>:  Thank you.</p>
    <p><strong>Nic</strong>:  Everyone out there thank you for listening to the show. I hope you enjoyed it. If you do please do tell your friends about it. You can get the transcript for this and all of the shows at <a href="https://a11yrules.com">https://a11yrules.com.</a> And a quick reminder that you can get yourself some neat A11y Rules branded swag at <a href="https://a11y.store">https://a11y.store.</a> Catch you next time.</p>
</details>

## Show Notes


