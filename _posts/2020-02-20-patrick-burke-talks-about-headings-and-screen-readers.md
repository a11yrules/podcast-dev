---
layout: podcast
title: "Patrick Burke talks about headings and screen readers"
type: podcast
summary: "Patrick tells us that having headings that describe the content on the page is critical for screen reader users. He feels proper hierarchy is nice, but not as important."

permalink: /podcast/patrick-burke-talks-about-headings-and-screen-readers/
# Podcast Episode Metadata
episode_type: full
episode_number: 12

# Audio Information
audio_url: https://a11yrules.ams3.digitaloceanspaces.com/podcast/episodes/E012-a11y-soundbite-patrick-burke.mp3
audio_type: "audio/mpeg"

# Duration
duration: "PT12M29S"
duration_formatted: "12:29"

# Series
series: "A11y Rules Soundbites"

# Episode Artwork


# Author/Host
author: "Nic Steenhout"

guests:
  - patrick-burke
  

# Content Rating
explicit: false

# Categories/Tags
categories: soundbites
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
    <p><strong>Nic</strong>:</p>
    <p>Hi, I’m Nic Steenhout and you’re listening to the Accessibility Rules Soundbite, a series of short podcasts where people with disabilities explain their impairments and what barriers they encounter on the web.</p>
    <p><strong>Nic</strong>:</p>
    <p>Thanks to Tenon for sponsoring the transcript for this episode. Tenon provides accessibility as a service. They offer testing, training and tooling to help fix accessibility fast.</p>
    <p><strong>Nic</strong>:</p>
    <p>Today I’m speaking with Patrick Burke. Patrick, welcome aboard.</p>
    <p><strong>Patrick</strong>:</p>
    <p>Hello, hello.</p>
    <p><strong>Nic</strong>:</p>
    <p>So, let’s get right into it. Patrick, what’s your impairment?</p>
    <p><strong>Patrick</strong>:</p>
    <p>I’m totally blind and have been since early childhood around 1967. So, lots of time to track down variables, speed tape recorders and braille stuff and whoa, and all of a sudden computers and screenwriters and that sort of stuff.</p>
    <p><strong>Nic</strong>:</p>
    <p>So, it would be fair to say that you are an experienced screen reader user then.</p>
    <p><strong>Patrick</strong>:</p>
    <p>Yep. Yep, from about right around 1990 or so.</p>
    <p><strong>Nic</strong>:</p>
    <p>Cool. What’s your favorite screen reader and browser combination at the moment?</p>
    <p><strong>Patrick</strong>:</p>
    <p>Right now, mostly NVDA and Firefox, kind of, I don’t know. And in the iPhone world, VoiceOver and Safari.</p>
    <p><strong>Nic</strong>:</p>
    <p>Now we’re talking on Twitter back and forth about barriers on the web and one of the barriers that I think you mentioned was headings. Can you tell us how good headings help you as a screen reader user or bad heading structure has an impact on you as a screen reader user?</p>
    <p><strong>Patrick</strong>:</p>
    <p>Well, basically, we’re trying to process the 2D screen in a linear format, so we need ways to jump around to important parts of the content. We tend to get stuck in things like long lists of navigation links and marathon paragraphs and that sort of thing. If it’s something we’re not interested in, you want to skip ahead, but how far ahead can you jump. You don’t want to miss anything important. So, headings, if people will use them, is a good way to mark those key parts of the page or document.</p>
    <p><strong>Nic</strong>:</p>
    <p>For people out there that are not familiar with screen reader users, you’re talking about jumping to list of links and headings and all that. Can you describe how you access that kind of information? Because it’s something that I think most sighted users relying on browsers don’t understand how that works. So, a bit of an intro would be great.</p>
    <p><strong>Patrick</strong>:</p>
    <p>So, we have a bunch of overlaid extra keyboard commands and unless you’re actually typing in a web form or something like that in a field, the screen readers will usually take over. So you can, at the simplest level, if you have a full keyboard, you hit H and you jump to the next heading, shift H, you jump back.</p>
    <p><strong>Patrick</strong>:</p>
    <p>They also have commands to get a list of all the headings or all the links to chop up the page in different ways. And again, it’s because we don’t see the overview of, “Oh, there’s two big blocks and then there’s the footer,” and, “Oh, there’s the large font in red and that’s the part that’s obviously important.” We don’t get any of that information. So we have to follow the code of the page and get our cues from that.</p>
    <p><strong>Patrick</strong>:</p>
    <p>So, the headings are, again, there’s one way, there are various other methods, but that’s the best one to try to have designers sort of match up a heading with a key block of information.</p>
    <p><strong>Nic</strong>:</p>
    <p>Right. So a heading, good heading structure is really about two things, I think, from what you’re telling me. It’s about being able to understand the structure of a page but also about being able to navigate within the page?</p>
    <p><strong>Patrick</strong>:</p>
    <p>Yeah. Again, there might be other key things like you might not want to read everything. You might just be looking for, “Where’s the email address?” [crosstalk 00:05:08]. You would do a different, you get the list of links on the page and just jump to those. But if you’re reading through, and especially if it’s a larger amount of information or a list of 20 products or something like that, an eCommerce site, then you would want a fast movement between all the different other blocks. And again, the most generally reliable way is with the headings.</p>
    <p><strong>Patrick</strong>:</p>
    <p>And actually the interesting part, we have many arguments about the importance of nesting headings properly, never having an H3 after an H1. You have to have an H2 and all that stuff.</p>
    <p><strong>Nic</strong>:</p>
    <p>Yeah.</p>
    <p><strong>Patrick</strong>:</p>
    <p>It’s useful if it’s done correctly. But for example, on VoiceOver, the commands available there obviously usually do not have a full keyboard using gesture commands. They do not differentiate between heading levels that I’ve ever found. So, you just go, it’s like next heading, next heading, next heading. It doesn’t matter if it’s a three or a four or whatever. So, it’s like just having them there and having them match the content is the biggest win.</p>
    <p><strong>Nic</strong>:</p>
    <p>That’s very interesting because I guess understanding that actually the hierarchy is not as important as having the headings is quite interesting to me. Because I always thought the structure of the heading, the R key, was just as critical as the rest. But it sounds like maybe it’s not as important.</p>
    <p><strong>Patrick</strong>:</p>
    <p>Yeah, I mean this ideally, yes. It’d be great to have a, you basically create a table of contents or a tree structure of the whole document based on the headings. But I mean just the way webpages are structured doesn’t allow for that a lot of times or it doesn’t lend itself to that, let’s say.</p>
    <p><strong>Patrick</strong>:</p>
    <p>So, if you have a menu and a submenu, navigation stuff and a search box and various things at the top or left part of the page and then you want the nice big H1 to be the center, the headline of the news article or the name of the company that you reach their website, so you want that to be the most important thing. But there’s all this other stuff before it so it’s like, well, each page doesn’t necessarily start with a nice H1 at the top and then two H2 sections neatly arranged in a bullet. So, I kind of take what I can get. If there are useful headings, that’s good. It usually suffices.</p>
    <p><strong>Patrick</strong>:</p>
    <p>There are some situations where like again, especially on new sites, why is the headline of the main article on that page, why is it an H4? It makes no sense, but it’s a smaller, smaller issue.</p>
    <p><strong>Nic</strong>:</p>
    <p>Cool.</p>
    <p><strong>Patrick</strong>:</p>
    <p>I guess it’s also worth mentioning particularly in the old days, I guess, before CSS and nice formatting stuff and you still run into it occasionally where people use the H2 because it has a nice large font in whatever implementation or whichever browser they’re using. That is a definite downside when that happens. It’s like when you get, generally you do not want to have an entire paragraph be an H2 or H5 or whatever it is.</p>
    <p><strong>Nic</strong>:</p>
    <p>Yeah, we still meet, encounter some of that when we’re doing auditing where a specific heading level has been used for styling because it fits in how they want to look. But I think, we’re in 2020. The people that still do that, it’s just lazy coding, really.</p>
    <p><strong>Nic</strong>:</p>
    <p>Hey Patrick, thank you for that info. That’s been really good. And I think most of our listeners are going to be enjoying that. I’d like to ask you, if you had one thing, one message you’d like designers and developers to remember about accessibility, what would that message be?</p>
    <p><strong>Patrick</strong>:</p>
    <p>I guess it’s going to have to be two parts. So if from the design point of view, consistency is the best, even if it’s a not so great design, if it’s consistent from one page to the next, at least I can remember what came before and use it to find that contact info on the contact page more quickly. So, surprises in the design process are generally not good, particularly for blind users.</p>
    <p><strong>Patrick</strong>:</p>
    <p>And I guess the biggest thing I would just say, don’t be surprised when people use your web content in unusual ways that you’ve never thought of.</p>
    <p><strong>Nic</strong>:</p>
    <p>Yeah.</p>
    <p><strong>Patrick</strong>:</p>
    <p>They’re listening to it at 300 words per minute or their magnifying it to 18 times its normal size or a whole variety of things. So, how do you prepare for all that? Use good standards based codes, and follow all of the standards.</p>
    <p><strong>Nic</strong>:</p>
    <p>Thank you.</p>
    <p><strong>Patrick</strong>:</p>
    <p>I guess that falls in the robust category of the [inaudible 00:11:39] like this. Be prepared for modifications to the content. [crosstalk 00:11:48].</p>
    <p><strong>Nic</strong>:</p>
    <p>Yeah. Patrick Burke, thank you very much for your time and your insights. I’m sure that our listeners will benefit from this discussion, so thank you and I’ll see you around on the internet somewhere.</p>
    <p><strong>Patrick</strong>:</p>
    <p>All right. Certainly hope it’s helpful. Thanks a lot, Nic.</p>
    <p><strong>Nic</strong>:</p>
    <p>Thanks. Cheers, and that’s it for now. Thanks for listening. If you enjoyed this Accessibility Soundbite, please support the show at <a href="https://patreon.com/steenhout.">https://patreon.com/steenhout.</a> That’s P-A-T-R-E-O-N dot C-O-M forward slash S-T-E-E-N-H-O-U-T.</p>
</details>

## Show Notes
<!-- leave blank -->

