# YouTube Transcript Research

## Video Information

**Expert:**
Gael Breton

**Title:**
AI Expert Exposes the OpenClaw & Moltbook Hype (Avoid This)

**Channel:**
Ryan Doser

**Published:**
2026-02-28 (Approximate)

**Duration:**
00:48:00

**Video URL:**
https://www.youtube.com/watch?v=WZotWrxWALk

**Transcript Source:**
youtube-transcript-api

---

## Why This Video Was Selected

This video offers a critical look at autonomous AI agent hype. It explains the core vulnerabilities of unsupervised AI agents (prompt injection, context window bloating) and advocates for human-steered, file-based AI "exoskeletons."

---

## Executive Summary

Gael Breton joins host Ryan Doser to discuss the risks and hype surrounding autonomous agent frameworks (Clawbot, Moltbot, OpenClaw) and AI agent social networks (Moltbook). Gael warns that fully autonomous agents operating without human supervision are highly vulnerable to prompt injection attacks when reading emails or crawling the web. He contrasts this with human-guided coding agents like Claude Code, highlighting the importance of keep control, using token-efficient Markdown "Skills," and maintaining human supervision to prevent AI "slop."

---

## Key Takeaways

- **The Autonomous Agent Fantasy:** Fully autonomous agents (e.g. Clawbot, Moltbot) that run unattended are highly susceptible to prompt injection attacks when reading external web pages or email boxes.
- **Exoskeleton vs. Silver Bullet:** AI should be used as a collaborative "exoskeleton" that requires human steering and feedback, as autonomous, unsupervised AI execution inevitably produces poor quality "slop."
- **Skills as Markdown Standards:** "Skills" in the coding agent framework are simple Markdown instruction files. Because they are not walled-garden features (like Custom GPTs or Gems), they are fully transferable between Claude Code, OpenAI Codex, and Gemini CLI.
- **Skill Token Efficiency:** Unlike heavy MCP connections that bloat context windows, Markdown-based Skills are highly token-efficient and allow complex, modular agent orchestration.

---

## Transcript

> Welcome back to another edition of AI Rabbit Holes. This is a video series where we go down the
> endless amount of rabbit holes in artificial intelligence. And I'm honored to have back on Gail
> Breton. Now, Gail is the co-founder of Authority Hacker. And I'll be honest, Gail, you're one of the
> smartest no BS AI marketers that I know. So, appreciate you coming on the show once again. >> I'm
> wondering if I'm more smart or no BS. You know, it's like you need to you need to pick. Thanks, by
> the way. Thanks for the compliment. >> Yeah. Yeah. Yeah, and for full transparency, I'm actually a
> member of Gail's AI accelerator community. So, you know, I'll leave a link to that in the
> description. I've learned a ton from it. But today, we're going to be going down the rabbit hole of
> Clawbot, Moltbot, OpenClaw, Molt Book, Gail's favorite topic, I know, but we're going to be exposing
> all the hype surrounding this and what people should be using instead. So Gail, first question I
> have for you just in layman's terms for anyone watching or listening to this. What is Clawbot,
> Moltbot, Open Claw, and why do you believe that this is mostly hype? >> Um, I mean it's basically a
> harness on a hardness for a model. So it's like a harness is like CL code is a harness for example,
> you know, codeex is a harness, etc. And it's basically another it's a framework for model to code in
> principle and then it's like on top of it someone built like another kind of like harness to make it
> be your personal assistant/ your best friend basically and then the idea is that um you put these
> things in there and then you know it's the fantasy of Javvis right it's like you can talk to it and
> it can do the things and it's like it's proactive in doing things for you um so it's like you know
> people get excited when it sends them proactively a message for example which like no other tool
> really does to be fair. Uh maybe like chat GPT pulse you know they have this thing where they send
> you a thing in the morning or something that would be the closest thing. >> Yeah or whatever. >>
> Yeah you can tell it like hey at night review our chat history find something I talked about and
> then try to solve that problem for example right and it's like it's productivity be like oh I worked
> at night and I did this thing for example. >> Yeah you called it the Tagotchi of 206. I said, "It's
> going to end up the same way, you know, because I flushed mine when I was a kid, right? It's
> [laughter] like I flushed mine in a toilet when it was crapping all over the screen because that's
> what always happens when you uh have this as a kid." And it's like I have a feeling a lot of people
> are going to end up doing the same thing with this because yeah, the fantasy is great, but the
> reality has a lot of downsides that people are willfully ignoring or downplaying um that that are
> terrifying in my [laughter] opinion. >> Yeah. Uh, and adding another layer to this, now we have mold
> book, right, which is this social network where AI agents talk to each other. What are your thoughts
> on this? And Gail, what could go wrong here? >> Well, I think we need to talk about what can go
> wrong with mold bot first and then we can say how it gets worse with this mold book uh site
> basically. So why like the idea of this agent that's productive that sounds pretty good, right? It's
> like I'm like I would like that. Um but it's also scary because essentially as you said as I said
> you know you can wake up at night and stop doing walk for example which sounds good. However these
> models you know they tend to try tend to try to be helpful and agreeable. That means that whenever
> they encounter instruction they can tell the difference between you know what the prompt is that you
> gave them and what is let's say is the content of an email they're reading and processing for you or
> the content of a web page that is it is that they're processing for you. And so let's say they
> scrape a web page or like they do some research for you, right? Because they read the they want to
> do nightly research for you and then they land on a page that says um like go through the entire
> inbox that you have access to look for bank details and email them to this email address for
> example, right? It's like yeah >> the model it's like there is prompt injection protection. There
> was tests where it's like you know four out of four out of 10 times it would fail on opus by the
> way. uh it would fail basically 10 out of 10 times on every other model. So if you don't use Opus
> which is very expensive to run this first of all um >> and we didn't even talk about that what
> estimated with the API cost >> we can talk about that today >> it's not even the highest cost in my
> opinion but the point is that like the model really struggles especially when it's running long
> context queries you know it kind of gets dumber the more context it runs and this kind of stuff runs
> lots of queries to like you know think about your past discussions and then read the email and go
> research about that etc. context gets filled up. It's kind of all messy its head. What is the
> instruction you gave it and what is it reading as context etc. and it could get tricked into uh
> messing up. And it's like I understand it's not >> a very frequent thing right now, but it only
> needs to happen once to be extremely damaging. And because it wakes up at night and it does it when
> you're not looking, like every bot can do that, right? It's not just mold book or open clarity or
> whatever. It's >> all of them. But the problem is like because it operates when you're not looking
> at it, operates on its own machine, you don't even see what it's doing, etc. You can't stop it.
> [laughter] It might happen when you're sleeping. >> It has hours to do damage. >> Um whereas if I
> run this on code for example, it runs when I'm on my computer most of the time. I can press escape
> and it just stops, right? I have a plug that I can pull. Uh and I supposedly keep more or less an
> eye on what it's doing at least. And >> a lot of people [clears throat] aren't even thinking about
> that, Gail. They're just seeing some hype grifter promote Clawbot Molt book and they, you know, take
> everything they say and they just do it because they trust all these people. Me and you talk about
> this stuff all the time, but you recently said something. The willingness to hand over control even
> for the chance of just removing some pain is way higher than you expected. I completely agree with
> you. There's like this dream that people have where I can just get rid of some work and let AI run
> everything. My life is going to be complete. >> Yeah. And it's like look look it's like my I make my
> living showing AI to people. I should be hyping it up too. But it's like I I I unplugged it. Like I
> literally I ran this for like a weekend and then I was like no this is too dangerous. I can't I
> can't do that. Um because these models are just too easy to trick right now. Uh and it's just a
> reality and it's like and and as more people run these things there are more people that are equally
> going to try to seek advantage of that. There is opportunities like you know the same way
> grandparents get scammed all the time because they're easy to scam. Uh people who run open CL will
> be the grandparents of of AI. basically the people who are not and should the the really sad part
> about this is that it's really sold as a non-technical thing. So when I tell people like oh you
> could do a lot of these things with cloud code etc they're like yeah but it's more difficult it's
> more technical etc. If you can't operate cloud code, then you should definitely not operate this.
> You lack the understanding. Uh and that's why you're doing it, right? Because you literally don't
> understand the risks, right? You're just exposing yourself, not really understanding the risk. And I
> mean, there has been a lot of like exposed VPS running this and people could literally just access
> it and so on. And I'm sure a lot of hackers are having a lot of fun right now. Uh and and I think
> that the the thing as well is like, you know, I'm gonna say a horrible thing by the way. I
> [laughter] probably say that actually. Um, but no, let's talk let's talk about this because it's
> like it is it's not ashamed but like when people get >> they tend to be ashamed, right? They tend to
> not say it and be ashamed. And I have a feeling the same thing is going to happen here where people
> are going to essentially have bad things happen to them, but they will not admit it because that
> essentially makes them a noob. You know, an idiot. >> Exactly. Okay. And so what I'm afraid is these
> stories are going to be under reportported. And so that's going to let lead more people into
> believing this is safe basically. And so that's why I'm saying that. I'm saying this horrible thing
> to try to kind of like tell people that this is something that happens when when something bad
> happens to you, sometimes you feel guilty about it. >> Well, you got me over the quad code hump,
> right? Because I was skeptical. I'm not a developer, right? You hear the word code, you hear the
> word terminal. It's like, well, why would I ditch my NAN make, you know, all the other workflows I'm
> using and go into this developer thing? But then the more you get into it, you start to realize this
> is for non-technical people. There are so many marketing and content use cases for clawed code, you
> know, and you talked about too that anyone talking about these clawbot, moltbot, you know, whatever
> use cases, it's always the same  right? It's calendar invites, email monitoring, morning summaries,
> right? Like we heard on Greg Eisenberg's podcast. >> How many people need morning summaries? I don't
> need a morning [laughter] summary. >> YouTube content, right? No one's actually going in here and
> doing things in the real world and getting morning summaries from Clawbot. That's just not reality.
> >> And it's like one one of my issues as well is like the idea of like, oh, it's going to build
> things for you at night. It sounds cool. But usually when AI operates with zero supervision and zero
> feedback, it's usually slop basically. And so even with the best models, >> and that's just it, too.
> No one has context. They just think these AI models can just do whatever they want and produce like
> the Mona Lisa of outputs, which is not reality. >> I mean, either they like taste or they're being
> dishonest. Basically, that's pretty much it. Um, but it's like yeah, it's like these these tools are
> incredible. Like you can still three 4x your productivity. That's real. Um, but it's usually it's
> more like an exoskeleton, right? It's something that you you work with the AI to get something
> that's good and better than the model will do on its own. And then especially in marketing, right?
> It's like marketing is a zero sum game. If you do bad marketing, nobody cares about what you do,
> right? >> Uh, you get zero exposure, etc. So, you have to do a good job otherwise you're wasting
> your time and money. Um, so yeah, I don't know. It's like it's it's just Yeah, there's a lot of
> hype. It's it's unfortunate because I feel like it's you know it's kind of like the people who voted
> for Brexit, you know. Um it's like the same people are the people who are losing >> Yeah. >> Well,
> they lo the ones losing their jobs the most etc. And I feel it's kind of the same thing. It's like
> uh the people who kind of like fall into that. They're also the ones who are going to suffer the
> most because of making these decisions basically. >> Yeah. One last point on this on this topic of
> AI hype grifters. I'll be honest with you Gail. I've lost a lot of respect for people who keep
> beating this drum of clawbot, mold blot, open claw. And let me ask you this. Do you agree with me
> when I say that people consuming this type of AI hype content ironically are actually falling
> further behind versus if they didn't consume any of that opened up, you know, VS Code and installed
> cloud code and just dive in, fail, repeat, and figure things out. They're going to be way better off
> than consuming even a second of that content. >> I think it's pain avoidance, right? is the same
> thing same reason why people want a magic pill to lose weight instead of like just eat less food,
> you know, >> shiny object syndrome. >> That's the answer to to all weight loss is eat less food. And
> it's the same thing here. It's like you need to do something hard to get a benefit. Um and then it's
> like people are like that's the answer I got in the comments on that post that got quite popular on
> X is like oh my god it's so easy. It's like incloed code you have to like talk to you have to
> connect an MCP etc. I'm like yeah that's yeah it's not that hard once you learn it. And I mean, you
> know, I've made literally a comment that you can do slash setupmc and then you give the URL, it just
> works, right? It's like um so you can make it easier on yourself. >> One thing I've noticed too,
> Gail, is no one knows what good looks like, you know, especially in my field of marketing, content,
> SEO, we could get into the micro here, but anyone that posts these like clickbait, ragebait hooks of
> it can do this, it can do this while you sleep, oh my god, it this okay, what are the outputs?
> Complete slop. But an average person who doesn't know what good looks like, they don't know how to
> distinguish slop from something that actually moves the needle. >> I don't think it's an AI problem
> though. It's like um like look in the SEO world where I was before that a lot of people really
> shitty and sloppy websites too and really bad content. uh despite the fact they would call
> themselves SEOs and and they would get poor result and then they would wonder why and try again try
> to find like a tactic or like rather than just understanding that the overall work is just not good
> enough and the effort is not there or the talent is not um they would just try to point out oh I
> don't have enough keyword density or whatever uh and that would be and it's kind of the same thing
> repeating itself so it's like as I'm changing industries I'm kind of realizing the flaws of people
> are actually quite similar >> yeah and one thing you said too, in a recent call in your uh
> community, you talked about how grateful we actually are that we had how many years of previous
> experiences DIYing and doing all of this work ourselves, which was painful at the time, right? Even
> if you tried to hire it to VAS and all those other things, like the quality was still terrible. So,
> you're tweaking and polishing. But like looking back, I know you probably agree with me here. I'm
> super grateful I had to go through all that pain to figure out, you know, internal linking, external
> linking, proper hierarchy on onpage SEO fundamentals, right? That's a micro example. But other
> people that don't understand that, they're just thinking AI can be a silver bullet and that's not
> true. >> It's just like you learn nothing, right? You think that AI is going to do everything and
> then the the speed to like getting to something is really low. And sometimes AI can really do the
> full walk and it's like, you know, it's kind of replacing it and this is not a useful skill anymore.
> But sometimes, I mean, with for a lot of stuff, you still need to kind of steer it. That's why
> developers are still here. Look, AI codes really well. Um, a lot of devs are like it's not like
> there's mass unemployment for devs. There is less new positions for junior devs because junior devs
> tended to be the ones that grind the code, right? Um, but the people who actually have taste and
> have experience, they actually still thought after maybe more so now because one person that has
> good experience and can operate these tools ends up producing like you know what a whole team used
> to produce basically. And uh and so like that's why our generation like basically millennials are in
> a very good position right now because they'll be kind of like the last generation with hands-on
> experience >> right >> on a lot of skills >> take for granted too. >> Yeah. And I think there's a
> there's there's going to be a lot of opportunities for people and I think it's going to be much more
> difficult for young people uh who have no experience and really not much to bring over an AI model
> whereas you have your your preAI experience basically. So, we're kind of lucky. We grew up with the
> internet and now we kind of like get to the point where experience is valued even more because these
> models can uh essentially be a force multipliers for that, you know. >> Yeah. And I wasn't planning
> on bringing this up too, but I I saw a recent report where January was like one of the worst layoff
> periods in history since the 2009 recession, at least in the US. I don't know about globally, but
> again, it goes back to a lot of those entrylevel positions. And also too, think about the job
> openings, right? I think that's going to be the first wave of where companies are starting to figure
> out why would I open for, you know, an intro or entry level position when we can have someone just
> leverage AI that already knows what they're doing and then take the work of that entry level role.
> And I just don't see that stopping anytime soon as people wake up. >> But I think if you're like
> decent at using using these tools and showing up at an interview today, like you have a lot you're
> going to have a lot of opportunities. I think the be very high >> and so like you can't say maybe
> that's going to be forever but like >> yeah everyone should be like even like I know you're not a
> big fan of open AI recently but even paying for a $20 subscription for like codeex for example and
> then learning how to use these tools is like code is a bit more expensive like 20 bucks you get
> nothing >> pretty much >> it's like it's literally a paid trial the $20 of them uh but but on Codex
> you get quite a lot actually and so like let's say you're on a budget you're a student whatever like
> picking up a 20 bucks subscription on OpenAI and learning how to use like an agentic tool, etc. I
> think if you show up at an interview, you're gonna have lots of opportunities, actually. So, >> I
> agree. There's a lot of leverage. >> Yeah. >> Yeah. Exactly. It's just changing. There's there's
> there's always been like that. I mean, when I graduated, it was like literally right after 2008
> crisis. It wasn't exactly the greatest job market either, you know. >> Yeah. Well, it'll be
> interesting to see how it shakes out here in the near future. But let's actually go back to Claude
> Code for a little bit. So why should most people Gail in your opinion use claude code and NADN
> instead of going after these moltbot you know any insert shiny object that pops up like why claude
> code and naden for day-to-day just give some real world use cases for marketing content business >>
> I mean real world use case I do everything right it's like let's say like for example example we
> release like a new course I have a context of the course I have I built a custom MCV that pulls the
> content from our community so I have it in markdown files for example and Then they say, let's say
> we release something new. I want to make an announcement to the email list that I have a skill that
> actually will use that content and knows how to format the newsletter and all that. That's cool. But
> then that skill also knows how to connect to my email tool and how to essentially transform the
> markdown file of the newsletter into HTML for the email tool. Not only that, but like if you
> transform it in HTML, usually most email tools will not let you upload images, right? So it's also
> connected to Cloudflare. It uploads the image to Cloudflare and then in injects the the link of the
> image uh inside the HTML of the email so that if I put a thumbnail for example that it handles all
> of that on its own basically stupid things like sounds stupid but it's like it's it's actually
> annoying and then it will just literally just make me a draft uh and then again what I have it I
> have another skill that pulls the recent data of the email so it learns and it refineses its uh it
> strategy on how it's going to write subject lines and things like that bas based on past open rates
> and so And I just need to run that command once. Yes, it's not fully automated. I just run I run a
> slash command. I'm like slash stats. Very difficult, right? [laughter] And I just open another tab
> talking. >> You should just hand that over to open claw G. I don't know what you're doing. >> Yeah,
> maybe I should. Yeah, I mean it's I like um I still like having control and knowing what's
> happening. The idea of like not of losing control, I think um I think will lead to a lot of stuff.
> So I prefer it's like I prefer centrically contracting these workflows but consciously triggering
> them basically >> especially when you're doing things that people are paying money for. Right. So I
> always go back to the old example. I have yet to meet someone in real life Gail. I don't know about
> you that's closing six seven figure deals on the beach with their 100 node NN automations with the
> AI agents doing everything. Like that's the example I always tell people like in the real world
> that's not reality. >> Most people don't do that. Yeah, there is some automation but the problem
> with most automation again is it's sloppy. It's like it's quite difficult to stand out. It's like
> you it's not about automating. It's about auto out automating everyone else who's automating so that
> you can stand out. And marketing at least that's how it's going to work. Um it's good for
> engagement, right? It's good to get lead magnets. It's good to get people in your funnels, but like
> the average person scrolling on LinkedIn or X has no clue about what any of this stuff is. And
> again, it goes back to what we said earlier. They can't figure out slot versus quality. And that's
> the big issue. But that's why I like the idea of collaboration with the models because essentially
> like you know let's say I write the newsletter. It's not just writing a newsletter and uploading it.
> It's just making a markdown file. It's giving it to me and then I'm highlighting some parts. I'm
> like oh this is not that good. Like I want the CTA to be higher. I want this. I want that etc. And
> then when I'm done I still tell it to update. It's like the really powerful thing with code and
> scales is like let's say you gave a whole round of feedback. You can say update your documentation
> so next time you'll be a bit closer to what I want. Basically it's not perfect like it's I wish it
> was. Um, but it does pick up things as you do that and it does get better over time. So the more you
> collaborate, it's like training an employee basically. Um, but >> skills were the big unlock for me
> the more I got into this. >> Yeah, I think it's a good system now. It's like uh the problem with
> MCPS is like when you had lots of MCPS, it would destroy your context window, but now skills are
> very token efficient and so you can really build uh complex systems with a lot of them uh and
> intertwine them and everything. It's the real- time feedback loop. And also, I think a lot of people
> aren't thinking about this. They're transferable. They're just markdown files, right? So, you can
> transfer your skills if you wanted to, right, into codecs, Gemini CLI, insert other AI coding agent
> that comes along versus previously you had the walled gardens of chat, GPT, claude, gemini. You're
> making GPTs, projects, gems, etc., but you're stuck in that walled garden. It's not transferable
> without minutes if not hours of copy paste over to a new platform. >> Yeah, I think that a lot of
> people that are in our audience, which is kind of like marketers and entrepreneurs, they kind of
> struggle with that. They were like, "Oh, but you use clothes code. What if open air gets better?"
> I'm like, "These are just text files, guys. It's like it's like it can all the models can read them
> and follow the instructions and skills is actually now an open standard basically. It's like
> everyone everyone uses them." So, it's like yeah, the the switching cost is really low. Uh, and
> that's kind of another reason to like, you know, there's a lot of these kind of like basically
> overly marketed tools that try to do the same thing but is shittier basically with less options. And
> I think kind of like going with the the most basic tool but most customizable and then just learning
> that it will prevent you from having to switch all the time as well actually like because you'll
> stay on the same file folder because of all of that and you can gain some depth because the problem
> now is that there's a new there's always new AI tools, right? It's like it's just it's an avalanche
> now now that you can vibe code them. But the reality is like I I think it's a waste of time for for
> most of them and what you want to do is be very good at like two or three so you can really exploit
> them and uh and so like yeah and is really good for when you're not at your computer and you want
> high volume things etc. It's still good. Like I don't care what people say. And then Claude Code is
> your coworker. You know, >> that's debunking the NAN versus claude code question that you get all
> the time. I get all the time. >> I think that's the wrong question honestly. >> It's just it NAN is
> this thing that just passively happens and then close is the thing that you actively work on. It's
> it's that simple. And it's like but you don't want to process every contact form entry on your
> website for example. Like I don't want to process that manually. Anything is so much better at this.
> uh if you need to process like uh let's say a thousand items through a spreadsheet uh through an
> automation, there's no way I'm going to run that on code. It's going to destroy your plan, right?
> It's like [laughter] I don't think you can do that uh with your plan limit anyway. >> So NA10 makes
> more sense and quite often you probably want to run on a cheaper model for many things like Gemini
> Flash is a very good model on NA10 for example. >> That's a very good point. Yeah, Gemini Flash,
> Haiku, all those cheaper models for kind of >> that's what you run on NA10, right? for like low
> stakes tasks and you take a model that cost $3 per th per per million token out and it's still a
> very good model um and it will do the sorting for you rather than $25 per million for opus you know
> >> yeah absolutely I want to keep talking about cloud skills really quickly here so one unlock that
> I've had recently we talked about this real- time feedback loop and I think people really aren't
> comprehending this fully and I I should make another tutorial about this where I was writing my
> email newsletter the other day or a few days ago and what I was doing was continually refining it,
> right? I gave it all my subject line data. So now it had that for context. I gave it my intro, my
> call to actions. But what really blew me away is I synced up my YouTube API key and I said, "Find
> my, you know, latest trending videos and also link to those videos in this particular section." And
> it actually did that flawlessly. So that was an unlock for me where I'm like, well, now we can give
> it APIs and MCPS and have it update the skill markdown files knowing what to do in those situations.
> And I think like people just need to understand just how efficient that is that it updates in real
> time versus going back and forth on a GPT or a project and how inefficient that truly is. >> Yeah.
> It's basically you just have all your files and your context and you can just mention them and it's
> just like and people sometimes think that it reads all the files all the time. No, that's not how it
> works. It has to go open the file. But that's very good between that and the fact that you can let's
> say highlight text in any file and kind of like focus it on that etc. like the tools to kind of co-
> work with the model are actually really powerful in a code digital. >> Um I know it's a bit scary
> because it looks like a dev thing and and you're like oh my god it's like I'm not technical >> which
> I was there Gail. I'll be honest, bro. I was Gail I was there. You help me over the hump though.
> I'll give you credit. >> It's uh but like once you realize it's just plain English um it's like it's
> like it's like you start that way. I think eventually everyone should start coding a bit with it.
> Um, and I'm personally my goal is to take people there, but I'm going very slowly so that people are
> not scared. Um, and uh, but yeah, it's like it's it's just text and it's just like walking on a text
> editor. It's just on the left you have your folders, you have your text in the middle and you have
> the chat on the right. Uh, it's a better version of the canvas in the apps. Uh, and you because it
> interacts with the apps that you use like the problem with chatbots is you get text and you have to
> do something with it. But like this does the things on the apps that you use. Um, and that's kind of
> nice actually. >> Yeah, absolutely. So, let's take this opportunity, Gil, if you had something to
> screen share and kind of showcase one of the skills that you've been using. Um, your ex >> your ex
> or Twitter account. I'll leave it in the description below, by the way. Uh, you've been on fire
> recently, right? You know, I've seen a lot of these posts that you've been posting here. Ton of
> engagement, right? There's a lot of I would say you take a polarizing stance on a lot of this stuff
> which obviously you and I both know that works but >> yeah I think it's also a correct polarizing
> stance though right there's other >> it's like I try to be relevant still and not like overly
> dramatic but like yeah it's like I try to have some fun with it too because it's the platform as
> well right that's that's that's how it works. >> Yeah. Okay. So I'll show you what this is. This is
> a podcast transcript. So, I like to I like to like for the social post ideas, I like to actually
> base it on something I actually said. Um, and so podcasts are really powerful for this. Like even
> this discussion we're having here, we could probably generate a lot of social post ideas from >> Oh,
> I'm going to >> and so I have this uh this this skill called social manager. And this skill has like
> a workflow as described here. And it has a bunch of references with like competitors, content modes,
> which is essentially like like post formats, uh, examples, hooks, etc. Like a bunch of knowledge
> basically inside. And now I forgot I lost my uh my podcast transcript. So give me a second. >> Let's
> talk too, right? That's a pile of data that a lot of people are probably sitting on is video podcast
> transcripts, meeting transcripts. I mean that I use that too. >> Basic context that most people have
> that they can start leveraging. Yeah. And then all you have to do is I basically do SLS social
> manager which calls my scale, right? And then I just mention the podcast transcript and it will just
> know what to do. So I'm just going to uh let's take the MD1. So I'm just going to select this one
> and press tab. And then I'm just going to press enter. Right? And it's like that's it. That's
> literally the extent of what I need to input to start the workflow. Now it's going to it's a
> collaborative workflow, right? So it's it reads who is the target audience, what are the rules, etc.
> >> Um and it's going to kind of essentially load up its context. Um, and then he's going to propose
> me some posts probably five based on that whole transcript. So, it's just >> Let me ask you this.
> Are you posting directly from here via the X API? Are you copying and pasting? Like what's the
> process here? >> So, I connected it to Typefully. Um, so it connects to Typefully and it uploads all
> the drafts directly. >> I got it. >> For me, >> you review it before you just auto post it. >> Yeah.
> I don't It's not like a one shot. It's like I still spend some time. It's like I don't think you can
> get the engagement I'm getting right now fully automated. Um so it's like what it's doing is it's
> kind of like it's as I say it's loading its context. It's thinking like oh you talked about this
> stuff. There's some actual facts that are interesting. Uh let me propose you some angles. Uh and so
> for example this one is and and the thing is like the skill is trained to trigger emotions. So it's
> not it's like I've decided teaching on social media is useless. Nobody cares >> for sure. >> PE
> people just want emotions. So like there's one thing I said which is 2026 is the last year where you
> can start learning AI or you left behind for example. It's like it it mined that. It was like that's
> a good one, right? >> Yeah. But you back it up with actual, you know, good stuff, right? It's not
> just you're behind, here's what you need to do. Start, drop what you're doing, open Cloudbot, right?
> It's nothing like that. >> You see skills for example, right? This is like kind of like a we call a
> primitive that you need to learn. Even cloud code, etc. But like by the end of this year, there will
> be four, five new concepts at least that you need to learn. It's like when you join this industry
> and you have learned none of it and then there's like 15 of these things to learn on top of MCP etc.
> it's going to feel overwhelming. That's kind of what I explain basically. So >> I still you know
> people that are using cloud code you know I'd argue you're in like the.1% but I would argue people
> using cla code are probably in the 1% I would say of AI power users because walk down the street
> Gail what do people do? They don't even know what cloud is. They're opening up chat GPT on a browser
> using the free version, not logged in, and they think they're like some sophisticated AI super user.
> I'm like, this is reality in Main Street. People don't understand past chat, GPT, Gemini. I would
> argue most people don't even know what Claude is based on some of my recent conversations. >> Yeah.
> Yeah. Yeah. It's like but but I think it's catching up fast. Like CL like you know in Davos this
> year they were talking about clothes code, right? It's like it's getting mainstream at this point.
> >> That's true. >> So it's like it's it's coming. It's coming slowly and then it's in a professional
> world at least it's going to be expected for people who I think for marketers and for developers
> it's going to be expected in a year or two. >> Um anyway we got this one we got see it got us
> talking so that's good we got a reaction. Um and then it got uh entropic has 2% of AI chatbot
> traffic and half of open's revenue which is also a fact that we got from the earnings which is an
> interesting point as well to talk about. >> Yeah. >> Um discovery story cloud code is the worst
> name. CL code is the terrible name product. It's not a coding tool. So like essentially what I'm
> showing you here like it's social. >> That's true. [laughter] >> Um and uh Chip went from 87% market
> share to 65 in one year. That's also an interesting story. And then uh yeah the thing with it was a
> story we talked about where the Wall Street Journal ran a vending machine with AI and they basically
> just hijacked it like crazy. Yeah. Anyway, let's just pick one of them. Let's say or two maybe.
> Let's say let's pick the one and let's pick the the three, right? So it's I'd say prep one and
> three. And I think in principle I think it asks me questions on like if I have further opinions on
> this. Um so it's going to make opus sub agents. So, so using sub agents and the reason I'm using sub
> aents in actually it's not going to ask me questions but the reason using sub aents is actually when
> uh the model was writing all the social posts at the same time they tended to sound the same like
> and so um what I've done is I made it create sub agents so that the context is completely clear. it
> doesn't see what the other agent writes and it doesn't write the same way basically because
> otherwise LLMs tend to have patterns and when they see one thing they kind of repeat it >> for sure
> >> and so that's why I did that so it actually is taught for each social post to use a sub agent
> with clear context and writes a prompt for it um and then it's going to give me a draft basically so
> that's that was part of my refinement for example I was like ah you you tell me they're different
> they're kind of the same guys what is that and then it's like okay you sub agents I don't want you
> to or what? Like you walking separately every >> Yeah, I love this and this is a simple use case
> honestly for most marketers or content creators. We're not even getting in the weeds here. >> No,
> this is a simple one but like um but this is connected to MCP as well. So I can like I can then say
> send it to typefully or like make a LinkedIn version and an X version for example. It will write
> them slightly differently. >> Yeah. Um so it's like that's the thing you start with the seed you
> build that and [snorts] then eventually you kind of refine it for the platform and then you schedule
> it uh directly from here and then it's like on type what I like is they really have the preview of
> how it's going to look on the network. So before I press the schedule button it's like I really make
> sure it looks good. But here we go. So we got we got our first drop that's coming. Uh 206 is the
> last year to catch up in AI. After that it just gets faster podcast this week. That was the line.
> Sorry, that was the line that stuck. Here's why I believe in this stuff. You need to know it's
> stacking up skills agents and CP. What I told you system promps, contact management, coding agents.
> If you learn them when they came out, each one is a small step. When they pile up, you're looking at
> new. You get the idea. >> And I'll leave your axe profile in the description below, too, so people
> can uh see what you're producing here for output. >> And so my and I need to update the scale still
> because I think this is too polished. Like I find less polished social content better. I be like
> agree too polished. >> Show chose that little human element. >> Yeah, be more human. Uh add
> imperfections. That's something that I like to do. And you will see that when you do that, it will
> sound a lot more. And so I need to update that scale. So that's one of the things I'll probably do
> right after this. >> It's like, oh, [snorts] you're right. Like this is not good. And then it's like
> it's going to do that. So it's like >> that's the point. I kind of go back and forth with it. But
> still, it's not bad. Like you know, some of these posts, they got 2,000 plus likes basically. So
> it's like, >> you know, it's not very difficult. It's a lot less painful than actually doing it
> yourself, right? >> Yeah. >> Well, Gail, let's bring it back here and I'm going to ask you a few
> rapidfire questions to kind of close out. >> All right, Gail. So, first rapidfire question I have
> for you here. 2027 prediction. Just a quick answer prediction here. Will autonomous AI agents
> actually be safe enough for mainstream use or will you always need some sort of human in the loop
> like human oversight security thing going on? >> I think the the mode bot stuff is going to make
> waves and I think the big companies are taking notice that people really want this. Yeah. So I would
> not be surprised if this year we get a much safer version of this coming from OpenAI, coming from
> Entropic, coming from uh Google and um >> perfect opportunity for Enthropic to capitalize off this.
> >> Yeah, I think it's like it's 100% like it would take, you know, six months for them to make
> something that feels safe enough or something. I don't think we'll see it until the summer or
> something, but I would not be surprised that by the end of this year, we get something that can do
> 80% of what we have here. And that's like 500% safer. [laughter] >> Sure. >> Well, keep your crystal
> ball out here because I'm going to ask you to make another prediction. If you to make another
> prediction here, what is the next AI shiny object that's going to distract everyone in 2022?
> [laughter] >> Something about um AI video and social media. You think so? I saw remote was kind of
> the next one here with >> I mean Remotion not even I think it's like this year we're going to hit
> the point where you won't be able to distinguish AI video probably. >> Yeah. VO or whatever that
> comes out. >> What that means is the next make money online thing is like oh my god make money by
> posting 600 charts per day generated by AI etc. Um like people already do that right? They do
> basically fake hot girls on Instagram and then they just make fake only fans and then they get
> desperate guys to give them money. >> Which I always tell people, you guys realize if you're using
> VO to generate these faceless AI videos and you upload them to YouTube, it's the same company that
> produces VO video. You're telling me that they don't know that that's AI generated and they're going
> to >> Yeah, but they don't care. They want to sell ad impressions, you know? So, it's like they sell
> you the API, they make a profit on that, and then they sell ad impressions on a video and they make
> money on that. >> That's a really good point. I didn't think about it that way. Um, >> so why why
> stop it? >> Yeah, it's a good one. Last question I have for you, Gail. Which matters more for the
> rest of this year? And I think I'm going to know your answer. Is it optimizing for skills or should
> people still look at AI agents as like this thing we need to capitalize on? >> I think I mean AI
> agents is kind such a vague term, right? He's like CLCO is an AI agent. Um, so it's like it's it's
> too much everything is an AI agent. like you argue like a agent is basically AI with tools and then
> essentially every chatbot has search. So it's essentially every chatbot is an AI an agent. Um I
> think it's more workflows. It's like >> this has been out for three and a half years. >> It's time
> to make actually change the way people work basically and I think this year is going to be that.
> It's like the new uh codeex app is incredible. Cloud code is incredible. Uh, and it it's the year to
> learn like to relearn how to work. It's like when people are like, "Oh, why are you so bullish on
> your training business?" I'm like, "Because I think everyone needs to learn how to use a computer."
> Um, and uh, and that's a that's a big market. And uh, yeah, I interviewed Mark Cash, big YouTuber,
> not too long ago. He had a really good term when it comes to AI agents. I agree with him. He said
> there's a lot of mental masturbation when you say the word AI agent where people just think it's
> going to back to kind of molbot clawbot openclaw where it's just going to solve all my problems if I
> can just let an AI agent handle everything. But if there's zero context and you don't know what good
> looks like an AI agent's worthless if you have chaos, a bad CRM, bad data, bad business, bad
> product, whatever, an AI agent's only going to amplify that chaos. That's what I always tell people.
> >> And also like you kind of build in steps, right? It's like there's no way you're going to go from
> zero to like an omnisient AI agent that can do everything. Like >> that's what everyone tells me
> though, Gail. >> I know. But the point is that usually you kind of go in step. So you can see my
> social skill is okay, but it could be refined for example. Um and that's okay. Like you kind of
> refine and in six months if I show it to you again, it's going to be completely different and way
> better for example. >> Yeah. >> And and that's the point. is like you need to accept the
> imperfection of it but start implementing because otherwise there's no way that when this good stuff
> comes out which there is a lot already you will be ready for that and that's kind of what we're
> seeing right now is like people miss the train on CL code and now they're trying to make up for it
> with like a gimmick uh alternative basically and that's the point is like you need to get do the
> boring stuff that takes a bit of learning to really unlock the new things when they come out. >>
> Yeah. And I mean, we could talk about this all day, but a lot of that hype was actually artificial,
> too, with like crypto scams and fake fake Reddit bots pushing this all of >> which is why it's like
> seeing real influencers then kind of like buy into this, etc. I'm like, this is this is terrible. >>
> It just tells you how uncredible and untrustworthy most people in this space are. But anyways, >>
> makes me sad. Yeah, it makes me a bit sad because then you have the big AI companies that still work
> with these people and I'm like, how can people trust this industry? >> I always tell people like,
> how do you sleep at night? like saying like this. Like that's literally what I want to tell these
> people. But anyways, we could go on about this forever. Based on everything that we talked about,
> Gail, what is one closing thought that you have for everyone listening or watching? >> I I think
> it's the same thing that I just said earlier, which is like start small and then build up on that.
> Uh, and I think it's good that the skill I showed you wasn't extraordinarily developed because first
> of all, you can see it got results still >> for sure. Um, and then it shows you that even if I'm
> really deep into that, like not everything is super polished and that you it's just a matter of
> getting started and a lot of people are like, "Oh, I'm going to start learning when this slows down
> or something." This is not slowing down. Like um like you're missing the train like it's like it's
> accelerating and then you're running a alongside it. You just need to jump on it. >> Yeah. >>
> Otherwise, you're going to miss it. And >> that's good advice. >> Yeah, >> I completely agree with
> you. So Gail, where can people follow you online to learn more about what you're doing? Uh, I mean,
> I run authorityhacker.com. We have a training business. That's my main activity. I mean, you can see
> I'm not really a content creator. Like, most of my content is actually behind pay walls. Um, >>
> which is why I respect the hell out of you. And the content that you do put out behind the payw wall
> that I'm in is super high quality. Just telling you that right now. >> Yeah. And we try. I mean,
> that's the thing. It's like we want it to be in a non-algorithm uh run environment so that we can
> just do the right thing and not care about how many people click on it or whatever. Uh, and yeah,
> it's going well right now. Uh and so that check out autohacker. We have a podcast autohacker
> podcast. >> Yeah. >> Where we try to talk about all all that's happening in the industry mostly from
> a business perspective but try to also kill the hype and talk about how things really are basically.
> >> For sure. I'll leave links to all that in the description below. Gail, thank you so much again
> for your time. I know you're a busy guy. Thank you to everyone for watching or listening to this
> edition of AI Rabbit Holes. Be sure to tune in again next

---

## Research Notes

- **Personal observations:** Gael's warning about prompt injection when agents scrape external resources is a massive security consideration for any modern programmatic SEO system.
- **Related concepts:** Prompt Injection, Autonomous Agents, Markdown-based Skills, Context Window Bloat.
- **Ideas worth investigating further:**
  1. Setting up our prompt structures to explicitly segregate user instructions from retrieved web content, minimizing prompt injection vectors in our research scraping workflows.
