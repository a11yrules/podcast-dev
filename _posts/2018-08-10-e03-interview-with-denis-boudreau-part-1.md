---
layout: podcast
title: "E03 – Interview with Denis Boudreau – Part 1"
type: podcast
summary: "This is the first part of my interview with Denis Boudreau. Denis talks about his understanding of accessibility, the importance of not approaching it as a “checklist”, its place in the UI/UX continuum, how becoming a parent helped him become more empathetic, and more!"

permalink: /podcast/e03-interview-with-denis-boudreau-part-1/
# Podcast Episode Metadata
episode_type: full
episode_number: 03

# Audio Information
audio_url: 
audio_type: "audio/mpeg"

# Duration
duration: "PT26M09S"
duration_formatted: "26:09"

# Series
series: "A11y Rules Podcast"

# Episode Artwork


# Author/Host
author: "Nic Steenhout"

guests:
  - denis-boudreau
  

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
    <p><strong>Nicolas:</strong> Support for the Accessibility Rules Podcast comes from people like you. I really do appreciate your support.</p>
    <p>Welcome, this is the Accessibility Rules Podcast. I’m Nic Steenhout, and I talk with people involved, in way or another with web accessibility. Today, we’re talking with Denis Boudreau. Denis is a good friend, that I’ve known for several years and I wanted to know and understand a bit more about his perceptions and philosophies about accessibility.</p>
    <p>Good morning, Denis! Thanks for joining me with this conversation around web accessibility.</p>
    <p><strong>Denis</strong>: Good morning.</p>
    <p><strong>Nicolas</strong>: I like to let guests introduce themselves, so in a brief elevator pitch introduction, who is Denis Boudreau?</p>
    <p><strong>Denis</strong>: Well, my name’s Denis. I’m from Montreal, Canada. I work for Deque Systems. I’ve been working in Accessibility for about 17 years, doing mostly consulting, and training, and strategy with different clients, and that’s about it.</p>
    <p><strong>Nicolas</strong>: Okay, thank you. To get started, tell me one thing that most people don’t know about you.</p>
    <p><strong>Denis</strong>: I don’t tend to be someone who talks about his personal life much, so people may not know that I have three kids, aged 15, 13, and 9, who are very much into music. My kids all go to music school. As a matter of fact, my oldest son went to a summer camp last week, and we went to a concert last Sunday, which was really great. ‘Cause he ended up playing Game of Thrones, among other things.</p>
    <p><strong>Nicolas</strong>: How cool.</p>
    <p><strong>Denis</strong>: That was pretty cool.</p>
    <p><strong>Nicolas</strong>: That’s got to keep you busy, three kids? You must have developed a good sense of organization to survive that?</p>
    <p><strong>Denis</strong>: You would expect. You would expect, but not exactly. Yeah, I guess more than 15 years ago, my skills are better now, but there’s still room for improvement for sure.</p>
    <p><strong>Nicolas</strong>: Alright, thank you for that. So, we’re talking about web accessibility primarily today. There’s many variations on the definition of, “What exactly is web accessibility?” So how would you define that?</p>
    <p><strong>Denis</strong>: I like to define it with a very simple statement, which is that content needs to be usable by anyone on any device. Something I picked up a couple years ago, I used to define accessibility as being this very complicated thing, about making content accessible to people with disabilities, and people that are aging, and then there were all these other things that came into play, but ultimately what I realized that it boils down to content being usable by anyone, regardless of the device that they use.</p>
    <p><strong>Nicolas</strong>: Thank you, I think you mentioned in the past that you didn’t like to think about accessibility in terms of a checklist of things that needs to be met to comply. How do you feel about that now?</p>
    <p><strong>Denis</strong>: I feel very much the same way. Like most people, I started in accessibility, and accessibility started making sense to me by following checklists. That was the only way I could wrap my head around it. But what I have come to realize is that when you lean heavily on those checklists, you miss a lot of things. So, over the years I’ve come to integrate what those checklists are, and I still have that in mind as I assess a website for instance, but I really think about it in terms of user experience now, as opposed to just checklists.</p>
    <p>So, it’s not so much that I want to be checking off every item on a list, but rather make sure that the experience that I work on, whether while designing a site, or working with a client that has an existing site, the goal is really to make sure that people don’t run into barriers or issues as they’re using that site, regardless again, of the disabilities that they may have or the devices that they may use.</p>
    <p>So, yes, a lot of people do look at accessibility as a very binary thing, where you need to be compliant, or it’s not okay. I don’t tend to look at it that way at all anymore. Of course, every now and then you’ll work with a client that basically asks you for that specifically, and in those situations you do have to abide by that, but the way that I like to look at it, is really from the perspective of, “Can our users access the content without any barriers?”</p>
    <p><strong>Nicolas</strong>: Yeah. You mentioned UI a little bit. Where do you see the separation line between accessibility and UI or UX?</p>
    <p><strong>Denis</strong>: Again, if you had asked me that question five years ago, I would have had a very different answer I guess. Now, I look at accessibility as a subset of UX, a subset of usability. I don’t see it as a different practice at all, I see it as a simple … it’s very connected to user interface design, or user experience design. It’s just from a different perspective. It’s a more narrowed focus, I would say.</p>
    <p>If you look at UX, for instance, the goal of a UX designer will be to make sure the experience that he or she creates will work well with the intended audience. That they will get satisfaction and pleasure from using that interface. In accessibility, we do the same thing, but our focus is not so much on this particular type of user, but rather users that happen to have a disability or users that happen to be older, and may struggle with content, or users that may be marginalized by technology, one way or another.</p>
    <p>That’s where our focus is, but we usually want the same things, which is to create an experience that is satisfying for users.</p>
    <p><strong>Nicolas</strong>: Right.</p>
    <p><strong>Denis</strong>: Yeah, so I guess I don’t know where that line is anymore between the two. To me, accessibility is just a design now. That’s really what it is.</p>
    <p><strong>Nicolas</strong>: Yeah, I like that. I like that. You said you’re an Accessibility Consultant, so if I were to ask you, “Where does your role fall within the work of Web Accessibility?” “How do you include accessibility in your work, beyond the obvious, that it’s what I do?” How would you explain that?</p>
    <p><strong>Denis</strong>: Well, for the most part, my role these days is related to training. That’s where most of my energy goes into. So developing training content for Deque internally, leading some of the efforts that we have in developing content that we can deliver to our clients, so a lot of my effort goes there. Some of my effort also goes towards design, best practices. Inclusive design, for instance. A little bit of strategy as well, helping clients build programs for accessibility.</p>
    <p>So, I’ll be working, for instance, with a client where they have some knowledge internally, but they can’t really figure out how to bring it to the next level. So, we’ll work with their executives, we’ll work with their managers, we’ll work with their stakeholders who work with their developer designers, like everyone, and help them put together a strategy. A plan to make it a more holistic … like create a more holistic approach to accessibility within the organization, for instance. So, there’s that.</p>
    <p>Assessments of course, ’cause I believe that in order to remain relevant, you always have to assess sites, because you have to keep on top of the new and shiny things that are out there as well. So, just keeping that muscle flowing, so to speak, with assessments is also a big aspect of it. A lot of my work also, I guess, is related to public speaking. So, representing Deque in different conferences, or just sharing ideas with folks. That’s about it.</p>
    <p><strong>Nicolas</strong>: Yeah, that sounds like it would keep you busy, on top of being organized with kids, and work life balance.</p>
    <p><strong>Denis</strong>: Yeah, I can’t complain.</p>
    <p><strong>Nicolas</strong>: So, and you said that you’ve been doing accessibility in one way or another for about 17 years now.</p>
    <p><strong>Denis</strong>: Correct.</p>
    <p><strong>Nicolas</strong>: How did you become aware of the need for web accessibility? What was the trigger for that?</p>
    <p><strong>Denis</strong>: It came as a total unexpected discovery, I would say. I started in Web Development in 1997, and for about 3 years, I was working as a developer for a company in Montreal. Back then, you could not get training for web, you just had to pick it up, and that’s what I did. But I always had a knack for researching, and finding why things weren’t working, so very quickly I became sort of a lead on my team, to make sure that our process rather, would be as efficient as possible.</p>
    <p>That meant trying to figure out why we’re spending so much time debugging Netscape 3, for instance, because we were developing for IE 3 back then, but basically our main browser on Windows, so anytime that we had issues with my designer friend’s computer, which she was working on a Mac, for instance, so anytime we had an issue with that, or something wasn’t showing up on Netscape, we had to figure out where that was. That was my job. So, I became known for being the person to go to, to debug and figure out those things.</p>
    <p>Because of that, I guess resourcefulness that I had, which basically meant being able to open up a browser and search for answers on Northern Light, or Alta Vista, back then, one day a project manager came to me, and said, that we had won this bid for a redesign of a project for a University Hospital in Montreal, and they needed a site that blind people could use, because they had an aisle in that hospital for people with visual impairments. The project manager just dropped that thing on my lap, and said, “Figure something out, we have no idea what they’re talking about.” Neither did I.</p>
    <p>So again, my good friend Northern Light came into play, and I discovered the Web Content Accessibility Guidelines 1.0, which had been released a year before.</p>
    <p><strong>Nicolas</strong>: Right.</p>
    <p><strong>Denis</strong>: I had no idea about that stuff, so that was in 2000. So, 1999 was when WCAG 1 was released, so I discovered that, and it instantly appealed to me. So while we never got that project, and we never really got to do anything with accessibility back then, that’s when I got interested in the idea. That’s when I started to read about it, and for a couple of years I was focused mostly on open web standards. ‘Cause 2000 was when the web standards project came together, WASP came together, modern browsers, following best practices for the open web and everything. So, I was very much into that, and accessibility sparked the same kind of interest in me.</p>
    <p>Over the years, I started blogging about that stuff, and meeting people with disabilities in Montreal, and it just became a passion. It actually gave me a sense of purpose, because by 2002, pretty much done with web development, it always felt like you were creating the same exact site with a different logo and different color palette, but every company was pretty much doing the same thing online. So, I had done a couple of really big sites, and I was kind of bored with it, but then accessibility came along, and it just gave me purpose. All of a sudden, it wasn’t creating another brochure for someone, but rather enabling people to access that content.</p>
    <p>As development became more complicated, and the browser supported more elements and the interfaces we created became more complex, inaccessibility became a much bigger problem, and that fueled me. I’ve never looked back since. So that’s what I’ve been doing since then.</p>
    <p><strong>Nicolas</strong>: That’s a very interesting timeline, and way to get into this line of work. I like that for you, it gave you a sense of purpose. It’s almost like going back to this question of checklists vs think about the people. So, you’re a compassionate person who wants to make a change in people’s lives. I can related to that.</p>
    <p><strong>Denis</strong>: I try to be. I try to be.</p>
    <p><strong>Nicolas</strong>: What would you say your personal experience of disability is?</p>
    <p><strong>Denis</strong>: My personal experience is only through the eyes of my good friends that I’ve made over the years. I don’t really have anyone in my immediate family, who has a disability, I’m the closest to someone who is disabled because I’m color blind, so I do understand a couple of things from that perspective, but yeah my experience basically comes from meeting people that had disabilities, and understanding over the years, what it means to them to be able to do some things, or feeling like they have to rely on other people to do things that I take for granted.</p>
    <p>So my experience is really from the outside. That’s one of the things that I had picked up over the years, is that one of the worst things that someone like me could do, is try to pretend that I understand what people with disabilities go through, when they experience any kind of issues on the web, for instance, because I just don’t. I have a theoretical understanding of what that is, but I’ve also grown, I guess, a respect for what that represents, and the fact that I can’t really define it internally or personally.</p>
    <p>So yeah, my experience is through the folks that I have met, who have a wide variety of disabilities. I’ve pretty much met everything that’s out there by now. I do a lot of usability testing, people with disabilities, so you meet people that have a very different approach to using the web than you do, in those situations, and you were talking about being compassionate or empathetic, it just comes with the territory I think.</p>
    <p>When you see someone struggling to use your interface, if you’ve crafted and you’ve spent so much time on, and they’re not able to do something because of the colors that you’ve chosen, or because of the placement, or the location of those elements, or because content just flashes on the screen and makes it difficult for them to focus, those are all things that are really eye opening.</p>
    <p>So yeah, my experience comes from that. It comes from seeing other people use the web, and struggling with the things that we just aren’t aware of.</p>
    <p><strong>Nicolas</strong>: Yeah, that’s good. I like that. It’s strange, because I’ve met some people with disabilities that are clueless about anyone else’s experience than their own, and I’ve met people without disabilities that have a greater understanding about the needs out there. So, for me it’s always interesting to try and figure out who is doing what, and what’s their background, and how do they get to that point, and what kind of an understanding is there about the work that’s being done?</p>
    <p>So, I like that you have such a varied experience, even though it’s not a direct personal experience per say, but you’ve had a chance to get really good rounded perspective, because you’ve worked with so many different people with so many different impairments.</p>
    <p><strong>Denis</strong>: See one thing, as you were talking, it sort of came to me. I think that the most valuable thing that I ever got, that helped me grow in understanding this has nothing to do with accessibility or even the new people with disabilities. It has everything to do with becoming a father. Before I was a dad, before I had kids, I really wouldn’t care much about other people, it was about me. Then, all of a sudden, I had these little people around me, running around, and I became much more aware of others, and much more sensitive to others, I guess.</p>
    <p>So, I think that’s what really sparked it. I had my first kid in 2001, so that was like one year after discovering WCAG, so that’s always been there. I like to think, at the very least, that as I was growing and understanding, that not everybody was using the web the same way that I did, I also had that sensitivity about how unfair that was, because I was also caring about other people more at that point. I was starting to open up to other people. I think that really had a huge impact. Yeah, I think that’s somewhat related to why I care now.</p>
    <p><strong>Nicolas</strong>: Yeah, I can see that happening. Which hurdles did you face personally? How did you overcome them as you were growing in your understanding of accessibility and all this involved around that? Were there barriers that you faced?</p>
    <p><strong>Denis</strong>: Every day, I would say. I mean every single day, there’s a barrier, there’s a struggle, there’s something that I don’t understand, something that is complicated, something that I don’t feel adequate or competent for. There’s always something to learn, so generally speaking I would say there are many barriers all the time. One very specific that comes to mind was going from that point where I relied on say, the WCAG 2 standard as a checklist, to developing a more holistic approach to assessing for instance.</p>
    <p>That was definitely a big hurdle, and I pushed back on stopping to use a checklist for the longest time, and I had a good friend of mine, she was always heckling me about the fact that I relied on that checklist so much, and that there was more to it than just a couple of requirements. While, what she was saying made sense to me, I just could not accept it, because I felt that if I was going to just drop that checklist, I would no longer know what to do.</p>
    <p>It took me years to understand that once you knew what that checklist was about, you basically just follow your gut. You go on a site, you look at the content that’s there, you look at the interface, maybe you open up a screen reader, maybe you open Dragon Naturally Speaking, you use different tools, you try to use it from those perspectives, and you see things are not working, or you notice that things are missing. It’s not so much that capture every single detail that the page may have that would not comply, but that you find the things that are really going to have an impact, and you fix those things ones by one until you can’t find anything anymore.</p>
    <p>When you can no longer find anything, then you involve other people that have disabilities, and they will help you find more things that you never could have found yourself. Going from that initial phase of I had this checklist, I check every single box, I’m good, my job’s done, to the other phase that I described, where it’s a very holistic and iterative approach to fixing things and finding issues, and refining what you have, and then finding other people that have, say they are blind, or that are deaf, or that have mobility impairment, any type of disabilities involved in as well, and working with them to find more things to fix, or to improve.</p>
    <p>Going from one mindset to the other was probably the biggest hurdle that I faced in my career, I would say.</p>
    <p><strong>Nicolas</strong>: That sounds like a pretty major shift in thinking. It was. It was, yeah.</p>
    <p><strong>Denis</strong>: You’re talking about fixing things one thing at a time, how do you reconcile that with what seems to be asked from a lot of accessibility consultants by businesses, which is audit our site? So, how do you put that in practice between just doing pure assessment if you will, and taking this approach of iterative fixing, one thing at a time?</p>
    <p><strong>Nicolas</strong>: I think it’s true education for the most part. Most of the clients that I work with are coming to us because there’s a concern. Someone may have filed a complaint, they may be worried of getting sued, they may have heard about this accessibility thing, and now they’re worried for one reason or another, most of the people I work with come from that place.</p>
    <p>Then, my job becomes to guide them gently through those checklists to make sure that they feel safe about that part, but then also educate them that there’s more to it than just that. So, in those situations where someone comes in and says, “We’re under litigation,” for instance and, “We need to make sure that we are WCAG 2 AA Complaint.” That’s a very different perspective than just to say, “I heard about accessibility at a talk,” or someone gave a talk, or maybe they came and listened to me speaking, and it sparked a light bulb. They want to do this. They have the ability in the organization to make a significant change, and they say, “I want to approach it that way, I like what you said, I never thought about the fact that we were unknowingly discriminating against people, and I can’t have that, I want to fix things.”</p>
    <p>Then they’re being much more proactive about being inclusive. So, that’s definitely what I prefer, because from that point we work from the perspective of, “How can we make things better for everyone?” But most of the time, the clients that we get don’t come from there. Hopefully, they get to that place eventually, because as they integrate those concepts, then their own understanding expands, and they become more aware and more empathetic as well. That’s what we hope for all of our clients, that they get to that point, where they really want to do more, because it’s the right thing to do.</p>
    <p>Reconciling the two is difficult in a way, but you just have to be pragmatic about it. Every little improvement counts, and every little improvement is a step towards a better user experience. So, all the stuff that we can do while under the client’s perspective is great stuff, like some clients may be saying, “We want to hear about the requirements and the failures of WCAG, we don’t want to hear about best practices,” for instance. We’ll still try to listen to those things, because ultimately we’re also helping them provide a better experience to their users, and by doing so, we’re also minimizing the possibility of them receiving a complaint as a result of content that’s not accessible.</p>
    <p>I think a big part of my job is to help others understand that there’s more to it, than just that checklist like I said. But it starts with the checklist for most people, because they have no other way to understand. I, as a consultant need to be very empathetic to the fact that it took me years to go from that checklist to that other state, so I can’t expect them to understand that over the course of a project in that sense.</p>
    <p>It might take more time, but by being welcoming and warm, and understanding, and guiding them gently through those steps, showing them that using a particular technique that meets WCAG will still leave a lot of people unattended for, or uncared for, then hopefully they understand that, “Yeah, this other technique might be a little more difficult to put together, but it will be better for more users, so therefore we’re going to go for that one instead.”</p>
    <p><strong>Denis</strong>: Yeah.</p>
    <p><strong>Nicolas:</strong> So, there’s that. But, it’s all about trying to care as much as possible, and be patient, so people understand why it matters as much as it does.</p>
    <p><strong>Denis</strong>: Yeah, it does matter quite a bit doesn’t it? On that note, Denis I think we’re going to wrap this segment of conversation. Thank you for your fantastic and candid answers to my question. We will finish our chat next week, if that’s alright with you?</p>
    <p><strong>Nicolas</strong>: Sure. Yep.</p>
    <p><strong>Denis</strong>: Thank you, we’ll connect next week again.</p>
    <p><strong>Nicolas</strong>: Yeah, take care. I’ll talk to you later.</p>
    <p><strong>Denis</strong>: Great.</p>
    <p><strong>Nicolas</strong>: Is your website accessible? Contact me through my website at <a href="http://incl.ca" rel="noopener noreferrer"">incl.ca</a>, if you want my help to figure it out.</p>
</details>

## Show Notes
<!-- leave blank -->

