[53: A Very Meta Show](http://nodeup.com/fiftythree)
===

Panel:

* Daniel Shaw
* Nizar Khalife
* Erik Isaksen
* Cliffano Subagio
* Matt Creager

Table of Contents:

1. [Introduction](#introduction)
2. [NodeUp Stories](#nodeup-stories)
3. [Favorite Episodes](#favorite-episodes)
4. [More](more)
5. [Sections](sections)
6. [To Come](to-come)

## Introduction

**Daniel Shaw**: Hello and welcome to NodeUp. This is dshaw and today NodeUp Episode 53 is a very very meta NodeUp. Today I'm joined by Erik Isaksen from West Virginia, Cliff Subagio all the way from Australia, and Nizar Khalife from Miami Florida. We're going to do a very meta NodeUp and talk about NodeUp and the NodeUp experience. I had a great chat with Nizar at Realtimeconf, and there's some reasons why I'm doing NodeUp that I feel are important, and that same conduct is shared with a lot of other people. So I wanted to chat about that; it's a fun conversion.

Our sponsors today are &Yet, Modulus, and Clock. Thanks so much for supporting NodeUp and supporting the Node community. So let's go around the horn and introduce ourselves. Erick, you want to tell us who you are and what you do?

01:38
**Erik Isaksen**: Sure, I'm a UX Engineer at [3Pillar Global]. That's sort of a new title for me. I've been kind of inventing this job. Basically, what I've been doing is I've been using node to do rapid prototyping for applications we're building. I'm also using AngularJS. My background is mostly in frontend technologies: JavaScript, CSS, HTML. And I've worked with Bloomberg doing some Ruby work the last three years.

02:05
**Daniel Shaw**: Fantastic. Cliff?

02:07
**Cliff Subagio**: I'm a software developer from Melbourne, Australia. It's 4 A.M. here, it's lovely. I've been a node.js user since 0.2 when promises were still there. I had a fun experience with taking promises out and replacing it with callbacks back then, when it was taken out of core. I've been a NodeUp listener since Episode One.

02:32
**Daniel Shaw**: Wow. Nizar?

02:33
**Nizar Khalife**:
I'm a web developer at [Nobox](https://www.facebook.com/Nobox), a digital marketing agency in Miami. They have offices in Puerto Rico too, where I'm originally from. I started listening to NodeUp this year, when I got into node heavily.

02:47
**Daniel Shaw**: Excellent, cool. So, a broad spectrum. Before I kick off the NodeUp stories, I want to give a shout out to our first sponsor, [&yet](http://www.andyet.com/). I want to give a special shout out for all they've done to support the node community. Nizar and I were just at [Realtimeconf](http://realtimeconf.com) -- and this is the last year of realtimeconf. The amount of heart and soul that they've poured into realtimeconf over the years and how much they've contributed to the community, making it special for everybody. We have the warmest of appreciation for everything that they do. I can't say enough good about what Adam Brault and his team brings to the world.

They put that same effort and dedication into everything that they build. I invite you to take a look at their chat, IRC, teams management product for the web. It's called [And Bang](https://andbang.com/) and it's a fantastic tool. They have dedicated themselves to building these world-class experiences and do that same work for clients like AT&T. They've become real leaders in the webRTC space, so if your company is looking to build anything in the spectrum of realtime JavaScript / webRTC, I invite you to reach out to &Yet. And even if you aren't going to reach out to them as a company, reach out and say thank you for all that they're doing, as a listener to NodeUp. I would appreciate it if you personally reach out to &yet and thank them because they've done so much. So thanks guys, for supporting NodeUp.

## Nodeup Stories

05:05
**Daniel Shaw**: Alright, the NodeUp stories. I want to kick this off and share a little bit of why I'm here. I started fairly on in NodeUp, wasn't on the first few episodes. Last year we were a bit differently organized and had more random hosts and as we came into 2013, everyone got a little more busy and I stepped up and have been the main host for the show since then. The reason why I did that was, during conference season 2012, I spoke to a lot of people while I was in Europe at LXJS and Node Dublin and there were individuals and groups -- for example, a team of two out of Lithuania who were dedicated to developing with node -- and NodeUp was the only contact that they had with the larger node community. I really empathized with this. Before coming out to San Francisco, my wife and I were living in West Virginia I'd gone to school after the dot com, and prior to that I was living in the middle of nowhere in Itialy, (in Umbria, Perugia if you know the area). I just had to go out of my way to hang out with any other developers who gave a shit at the level that I did. Same thing in West Virginia; I drove an hour and a half a couple evenings a month to go hang out with a Closure development group. I wasn't into Closure, I just wanted to hang out with JavaScript developers even if it wasn't anything I could possibly do. At a pair programming event, I met with the leader of that Closure group and really connected with his passion for programming and sharing. So I would hack with them fairly indirectly. So that's why I put so much into NodeUp. It means a lot to me. Going to conferences and having people come up and thank me for doing NodeUp really means a lot. I really appreciate it and thank everybody for powering through the "Ums" and various verbal ticks I have to make this something that allows everyone in the community all over the world to connect.

Nizar, we had the most recent chat. Why don't you fill everybody in and share a little about your experience with NodeUp. You're the new guy on the block.

08:30 - **Nizar Khalife**: I started earlier this year to really get into node thanks to a buddy of mine who I work with. When I first started I hacked on my own, silly little things like rearranging folder structures and things like that. The more I tried to solve problems the more I was hungry for information. I was like, "how do you do this, how to do you that?", so I started listening to NodeUp. I don't remember which episode I listed to first, but after that I went back and listed to all of 2013's episodes. And I actually listened to a couple episodes yesterday to freshen my memory. I've loved it so far -- it's been awesome. And I might even go back to 2012 and check those out at some point.

09:26 - **Daniel Shaw**: Yeah, I'm wondering how well those hold up! I haven't gone back. There was a particular rant, I believe in NodeUp 6, where I was in a work scenario where I was the socket.io guy. I was actually the only node guy on the team at a primarly Rails shop and the service had fallen over in private beta at 100 connections. It was like "No! This is not any sort of scale level that should be crippling the service!" So that was a particular nice rant that I refer to. I'd love to hear about it, as you dive back in. Most of it will be node 0.8, maybe there's some 0.6 back there. It feels like an eternity for me. I'm really curious to hear if those early NodeUps still have a lot of information that's great. There's a lot of technical meat in there. We've been trying to get a good transcription service set up. We've made a few stabs at it but we haven't really found the right solution. To get NodeUp professionally transcribed is $400-$500 an episode to do it right. It's something we keep iterating on. If someone is really interested in owning transcription of NodeUp, I think that would be a wonderful contribution.

Erik, would you like to share your experience?

11:34 - **Erik Isaksen**: A few years back I was working with some guys from the ThoughtWorks company. We were working on Ruby projects. Prior to that I worked mostly with JavaScript and CSS. If you got a bug in IE6, you sent it my way. I was that guy. Which was cool. It was really a great experience with them because I had a chance to learn TDD, working with XP-type of practices, and it was really enjoyable. So I started to ask what are some other technologies out there, and I saw a video on YUI Theatre Ryan Dahl that got me interested first. I was looking for resources and everywhere I went they said just load up express and here are these cookie cutter pieces. I was like well I'm not going to learn a lot this way so I need to find some more materials. And that's when I found NodeUp. I looked at the podcasts that were around and you guys were pretty much it. I was really happy when I started listening - this is really good material because you guys have people who are working in code, first of all, and you guys are also heavy users of this stuff. So it was really great - every time a new podcast would come out I'd be jogging through DC and listening to you guys.

Now that I'm working at 3Pillar, I'm prototyping and I get to choose whatever I want to use. So I decided I'm going to throw in Express and do that cookie cutter piece but I'm not going to build any scaffolding. I'm going to take this and see what I can do from the metal. And kind of build out my own controllers, build out my own models, and see what happens. I've been having a really great time. I've been doing it since July, full time.

14:17 - **Daniel Shaw**: I'd love to hear an update as that evolves. That's been my evolution; pushing back away from frameworks has been an increasing thing, especially as you're trying to grind out the raw performance. You can go far with that. I'm glad to see you adopting that and would love to see how that plays out.

So, Cliff. Cliff has a special story. And he's a big fan of kangaroos.

15:00 - **Cliff Subagio**: Second-best after Isaac and Michael, I guess. And your story, really. You guys really drum up about Australian Kangaroos. Back then, I think it was around 2011, the first NodeUp, well even before that I was on a Java/EE project. And for parts of the application we were looking for something that's more productive as a platform. We saw Ryan's talk introducing node and async I/O, and we thought "Hey, this is really making sense." And we started looking at node in really early days. When I found out about NodeUp, back then and even now I still listen to other podcasts, but I thought you guys are really relaxed when you recorded all the episodes. Really! When I listended to the first few episodes, I imagined all the hosts were drinking beer while talking about node, and this was so relaxing. Well, beer or tea, depending on your taste I guess. So Isaac, Michael, yourself, and all the others, you were going off about Australia for Bislr, and talking about kangaroos.

Actually, I got questions from friends outside Australia asking "are there lots of kangaroos in Australia" and I said "No, unless you go to the bush land or to the zoo." But the funny thing is, just last weekend -- and this is real, you can check it on BBC's website -- a kangaroo actually hopped into the airport terminal in Melbourne. They had to seal off part of the airport, I think it was the pharmacy, and they had to tranquilize the kangaroo and take it out. It's a funny coincidence but you might be able to see a kangaroo at the airport.  

(17:21 - 17:28 ... and I also keep notes about all the Australia ??? on my blog.)

Back then we had an application running with node 0.2 and it was actually in production until a few months ago. Which is quite interesting. It was stable on 0.2. It's really different on 0.4 and onward, but stable enough. My recent project with node involved trying a microservice architecture with node. It works quite nicely because each app can become a module and one way to bundle everything all together is to have each as a dependency in package.json. I think it fits really nicely with the idea of having one service doing one thing well and then node's idea of one tool doing one thing well. And we just pack them up all together. So that's my node and NodeUp experience.

18:40 - **Erik Isaksen**: Are you using anything specifically to mount those together?

18:42 - **Cliff Subagio**: No, just npm.

18:47 - **Daniel Shaw**: Great! You guys touched on a little bit of the impact on the node community. And we talked about NodeUp as individuals. I guess you could extend that as how you've seen NodeUp impact your friends. have you found that NodeUp has been at all helpful in orienting your friends or colleagues who are looking to embrace node? You've gone through that process as individuals, but what is the greater impact of NodeUp?

19:24 - **Nizar Khalife**: My buddy Joel, he definitely goes back and listens to the Performance Show, for example, if he's having his own performance pain. For starters, it's a great source of reference, to see how the leaders of the community have been solving their problems.

19:48 - **Erik Isaksen**: I agree with that, too. I find myself I have another former colleague who worked with node as well. I find myself going back to the API Episode. That was really useful for me. When I was a Bloomberg, we had a lot of services - we didn't use Active Record as much in Rails, so it was mostly smaller stuff for that. We had a lot of services running so I wanted to set up my own services and find out what would be the best thing for that, and [Restify](http://mcavage.me/node-restify/) seems really interesting to me.

20:30 - **Nizar Khalife**: Restify is awesome. I think the other thing that's really important compared to other tech podcasts I've listened to is what I mentioned before: having the people actually working on node coming up and giving their schpeel about what's coming up in the next version, or the next two versions, even. Early in the year, when you were talking about not even having released 0.10 yet, I think Isaac some things about 0.12. There's a lot of good knowledge and good insight, just having them come on a talk about the past, present, and future of node.

21:16 - **Name**: Yeah, you get so much more hearing it from the source, rather than having to sift through the docs, for sure.

21:21 - **Daniel Shaw**: Absolutely. Living in San Francisco and hanging out with some node core people like that, in casual conversations I have the opportunity to tune into some of that stuff. My goal is just to share that with the rest of the node community. But some of that core stuff is not going to apply to everybody. We all interact at different levels of the stack. The interntal implementations of buffers and stuff like that might not be directly relevant, but two things: (1) it might not be directly relevant until it is; you may be operating at the express level of the stack and then as Erik said, you strip that out and begin to go lower level as you need more performance. The biggest take-away from the experience at Voxer is exactly that: when you're really trying to maximize the I/O throughput you want to minimze your call chain and reduce the surface area of your computation. (2) The most efficient code is the code that isn't run, right? Not doing anything is the most efficient computation. Obviously that's not useful in most contexts, but it is useful as you're trying to maximize throughtput. And if you can minimize that surface area then you can really tune that down. 

23:29 - **Erik Isaksen**: Not just for performance, though. Having to build stuff from scratch really teaches you what's possible. After hearing [substack](https://github.com/substack) and some of the other guys talk, I would go to their githubs and look at the code to get an idea of what's going on. And then that was like "Okay, why are they doing this rather than the style I'm used to?" I'm used to JavaScript in the browser, before this. It definitely helps with learning, stripping away those layers. 

24:02 - **Nizar Khalife**: Yeah, in the browser in general, it's a lot less structured. There's not a right way to do things in the browser, necessarily. And even if you use a framework, there's different frameworks to choose from. There's not a concensus really on how you should do things. But I know there are -- even if not 100% of people agree -- some patterns that converge.

24:28 - **Erik Isaksen**: There's definitely more consistency. It's getting better, but we still have to deal with earlier browsers so there is a little bit of inconsistency there for sure.

24:38 - **Nizar Khalife**: And on that subject of the core stuff, it's not always about the nitty gritty under the hood things. It's also "Hey, in 0.10 the major thing is we have new streams". You may not be 100% on top of those changes to know what's going on. I think in 0.12 there's going to be some generator stuff coming in and that's nice to know that things are coming that you can play with.

25:10 - **Daniel Shaw**: I'm going to take a quick break and we'll talk about our next sponsor, [Modulus](http://modulus.io/). Modulus is a node.js hosting platform -- they have a great platform with built-in mongodb hosting so if you're building a MEAN stack app with mongodb as a key component of your they have fantastic instrumentation of how the database backs up to mongo and the performance statistics of your mongodb backend is very nicely integrated. There is built-in analytics for your app to see how things are performing. They offer free custom SSL in their packages, full websockets support, and you can run nearly every node.js version available. Those of you still running 0.4, I'd you to see if you guys can reach out to them and see if they'll run that for you. That would be fun. When you reach out to Modulus, use the promo code nodeup1 and you can get started with them for free. They are [modulus.io](https://modulus.io/) on the web and [@OnModulus](https://twitter.com/OnModulus) on Twitter. Thanks so much for the support, guys, and keep doing great things with creating a really dynamic hosting platform.

27:11 - **Daniel Shaw**: We've slipstreamed someone else into the show. All the way from Canada, Matt Creager is joining us. Matt, why don't you tell us a little about yourself. Matt's coming all the way from Halifax, Novia Scotia. Why don't you go ahead and fill in the blanks and add in your NodeUp story.

27:44 - **Matt Creager**: Hey folks, nice to meet you. This is my first ride in the slipstream, so that's exciting. Yeah, so I'm from Halifax, Nova Scotia, we don't have a huge node community here -- that might come as a surprise... or maybe not. I'm a member of the software engineering team at [GoInstant](https://goinstant.com/). We're building a platform for real-time apps on top of node to make it more accessible to client-side developers. 

Let's back up and say that NodeUp is the reason I currently work at GoInstant. It's the reason that I'm working on the project I'm working on, and the people that I'm working with. That is a big statement but it's absolutely the truth. I was part of a team at Blackberry that was working on these real-time dashboards and developing these real-time dashboards with the stack that we had was basically impossible (PHP). I'd attempted to introduce them to node and met so much resistance and pushback that I just started using node for my own projects. That lead me to this hackathon that was hosted in Halifax by GoInstant and I actually ended up striking up a conversation with of their team about NodeUp. I think it was the [Community Episode](http://nodeup.com/twentysix) that came up and the conversation led to having a couple of drinks and six months later I'm working at GoInstant with a bunch of guys that just hack on node all day. And I'm super excited about it. 

30:34 - **Name**: That's awesome.

30:36 - **Daniel Shaw**: I had a chance to meet the team at realtimeconf and it seems like you guys have a really great team and a wonderful contributions out there. Outside of the team, do you have anyone else to create community with up there?

30:55 - **Matt Creager**: That's a good question. In a way, what NodeUp really is to me is an example -- and obviously it's fundamental to the community and the community centers around it -- but really what is does is it teaches us how to build our own communities. And GoInstant is at the center of the node community in Halifax. As I speak I'm actually sitting in a startup incubator in Halifax and we've come over to do a presentation on node [GoInstant]. So we're really trying to get into the community and introduce node to the other people here who could use it to improve their tech stack.

31:34 - **Name**: you guys do local meetups up there?

31:39 - **Matt Creager**: Just hackathons at this point are the primary way that people get together. When I was at realtimeconf last week with dshaw I met Jason Campbell, the guy organizes [JS.LA](http://js.la/) and I really picked over his brain and got some ideas. So I'm seriously interested in trying to bring something like that to the Maritimes.

32:05 - **Daniel Shaw**: Fantastic. I couldn't be happier that that's NodeUp's contribution to the world: helping other communities develop. I guess most everybody tuned into International Nodebots Day this Summer. A really fun event, or a loosely affiliated anarchy of events accross the world. The great thing about that is those turned out to be seed events and other things have happened beyond that. I've gone on to start Nodebots SF. The Nodebots as a concept and a meetup experience is one that I particularly love because it's a fairly low barrier to entry to participation and it's extremely participatory. So rather than having a format that's discussion and talk, it's everybody getting together and talking and hacking on hardware. I've tried to extend that into a broader context and support that in new ways.

## Favorite Episodes

33:53 - **Daniel Shaw**: Let's chat real quick about some of the our favorite shows that have gone through NodeUp. I will kick that off with my favorite show, coming out of the realtime community, and that being my connection with node and why I got started with node -- building backends for websockets. The [Realtime Show](http://nodeup.com/thirtyfive) really shared a lot of the production challenges of creating effective realtime systems. We've done so well as a community to create a low barrier to entry for the codebases, socket.io especially, but actually running at scale in production is extremely challenging. Using websockets on modern Chrome if you have a great Internet connection? Awesome. But if you have a crappy Internet connection or God forbid you're on mobile, it's really a house of pain. That was absolutely my favorite episode that I've done and listened to. Lots of resources there.

35:44 - **Name**: I have two favorites. I really liked the [Module Authoring Show](http://nodeup.com/forty) where Isaac and substack and Michael discuss how you guys approach writing modules and designing the interface and all that. I got a lot out of that. They talked about the small module philosphy, which you've talked about in other podcasts. And also I really like the idea they owned up to having written modules that no longer match up to the standards of the modules they write now. It was cool to hear about the pain they went though to figure out and learn what they know now. So I really like that one. Another I like is [a leveldb show](http://nodeup.com/fortyone), where Max Ogden and Rod Vagg and Paolo Fragomeni were talking about leveldb. They went deep into it. I'd never been exposed to it before but the way systematic way they approached it really helped me understand it, and what it can be used for, and why you would use it over something like mongo. So those are two really good ones for me.

37:12 - **Name**: Ditto on the leveldb episode - I thought that was fantastic. Just listening to Rod was awesome. His voice was just great, too. I had never heard to levedb before that. I just Rod put up on [nodeschool.io](http://nodeschool.io/) he has a commandline lessons for leveldb, which I plan on trying. Don't know if you guys have seen that.

37:47 - **Daniel Shaw**: Yeah, nodeschool.io is becoming a phenominal resource. There's Learn You Node, there's leveldb, there's a new functional programming one -- I haven't had a chance to check that out -- and then of course there's the seminal work of substack and Max Ogden: Streams Adventure, which put that out as a format. It's been great to see all the support that it has provided.

38:30 - **Matthew Creager**: I downloaded that one and was using it on the plane all the way back. Plus one on that. It's awesome.

38:40 - **Name**: I leveled up after completing the stream adventure, for sure.

38:41 - **Name**: The last episode you guys have Isaac's talking about streams and the different changes in the API. Prior to node, I hadn't really used streaming in anything. It's really cool stuff. You can get some really good performance.

39:03 - **Cliff Subagio**: There are places where Isaac's talking about streams. Talking about streams 1, streams 2, and streams 3. I think that gives a sense of direction of where node's moving and the core guys are really open about it. That's quite different from other podcasts in a way, and it's really useful to the users, knowing what's coming up and why, what's the reasoning.

39:37 - **Daniel Shaw**: That's right, this is an open-contribution platform. It's a of technical effort to dive into core because you'll quickly get out of JavaScript land and get into C++, so there's a little bit of a challenge there. But everybody is welcome to contribute on whatever level they feel comfortable. If you want to get started with just improving the docs, that's a great place to start. The entire stack is open to contribution. You'll need to sign the contributor's license agreement, but that's basically the barrier. That, and the amount of work that you'd have to put into understanding it enough to meaningfully make changes. You'll have to work on code that was written by people who've spent a couple of years deep into it. But even if you don't get your contribution landed, I would guess that the process would grow your understanding of node -- and potentially leveldb -- so much that the benfit to you and your career would be phenominal.

All through the node community it's one of the strongest things that is a hallmark this sense of contribution. If you want to make an impact, if you want to change the way something's done. The best way to do it is by rolling up your sleeves and making a difference.

42:11 - **Cliff Subagio**: One thing this community really gets right is this focus on progression. I think Michael said in the community show, which is one of my favorites, that this feeling is anything can happen and anything is possible. That's what it feels like when you first start using node. You have these people who are really smart solving these really hard problems. And you're able to use this thing and build amazing stuff with it, and then the community onboards you and suddenly you're looking through core and then you're contributing to core. And people are encouraging you the whole way along. It's that progression that makes the node community so special. 

42:58 - **Name**: Can I add another favorite show -- [Episode 19: our favorite modules](http://nodeup.com/nineteen). Where you guys talk about favorite modules on NPM. That helps with visibility of some of the modules. I'm checking npmjs.org and there are 25,000 modules. You search npmjs and it comes up with ten recommendations and they look equally good, so you spend a lot of time figuring out which one really fills your need. But the modules recommend on that episode may not be an official blessing but it's a start.
