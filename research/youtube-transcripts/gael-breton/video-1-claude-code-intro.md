# YouTube Transcript Research

## Video Information

**Expert:**
Gael Breton

**Title:**
Claude Code for Non Developers intro

**Channel:**
Gael Breton

**Published:**
2026-02-15 (Approximate)

**Duration:**
00:24:00

**Video URL:**
https://www.youtube.com/watch?v=fLVVNRrJ2iw

**Transcript Source:**
youtube-transcript-api

---

## Why This Video Was Selected

This video introduces how marketers and non-developers can leverage developer terminal environments (Claude Code, VS Code) to build efficient, context-rich content automation pipelines. It explains how to bypass walled-garden chatbots in favor of file-based, API-connected AI systems.

---

## Executive Summary

Gael Breton introduces the "Claude Code for Non-Developers" course inside AI Accelerator. He explains why he shifted all his daily operational work (copywriting, newsletter production, community management) to VS Code and Claude Code, noting it is far more productive than basic web chatbots. He demonstrates the file manager layout, context-aware inline rewriting, long-term memory config (`claude.md`), circle community API automation using custom MCPs, and browser automation to scrape websites for design inspiration.

---

## Key Takeaways

- **Claude Code for Marketers:** Claude Code is a power-user environment for writing copy, managing campaigns, and automating business workflows without having to switch contexts or manually upload files.
- **Long-term Workspace Memory:** Using a `claude.md` file allows users to store permanent rules, company guidelines, and operational context that Claude references at the start of every session.
- **MCP and API Integrations:** Non-developers can connect Claude Code to external business APIs (e.g., Circle community, Stripe metrics) by simply pasting API documentation and letting Claude build custom MCP tools.
- **Continuous Learning Loop:** Marketers can collaborate with the AI, provide feedback on outputs, and instruct the model to update its own documentation to improve future executions.

---

## Transcript

> Hey everyone, welcome to this new course of AI Accelerator. It's honestly one of the courses I'm the
> most excited for this year and since we started AI accelerator because I think it's going to unlock
> so many workflows for so many of you guys and that's because we're talking about clothes code and if
> I have to make a confession for most of my actual productive work like not on my phone etc but on my
> computer to try to achieve things for the company most of that work in the last few months has been
> done inside clo code inside a tool called VS code because I found it so much more productive than
> other chatbots. I can do pretty much everything I need to do as a marketer, not as a coder inside
> this interface without necessarily having to switch context, having to go in different tools, etc.
> It can interact with all of them. It can call APIs. It can write newsletters for me. It can do
> anything I need inside that interface. So, I know when a lot of you guys are hearing cloud code, you
> think that you're going to be developing. I will make a separate kind of like vibe coding building a
> website with clothes code miniourse but this course is really not about that. It's about using the
> tool. It's about knowing all these features. It's about using it in the context of being a business
> owner or a manager. Still, we're going to be using it within the context of a text editor that is
> originally meant for development work. And trust me, I'm not the only one that believes this.
> Actually, Entropic just released this new code work, which is essentially code on the desktop app.
> and it does a lot of the things that we're going to learn, but the version I'm going to teach you is
> going to be significantly more powerful than what you can achieve inside the code app, which is why
> I am sticking by this. And I think that you should use the version that I'm going to teach you. But
> overall, they are bringing these kind of agents outside the IDE and for a good reason. It's because
> it's significantly more powerful than the basic chatbot that you're probably using. So, let me go
> ahead and show you what this looks like. This is the environment that we're going to set up. And I
> know it looks scary. I know you might have seen some devs using these kind of tools, but really it's
> not that crazy. The left part here is basically a file manager. So you can see there is folders that
> I can open up and down. So I have my projects here. Then for example, I have got course I have my
> lessons and then in the module one I have the first lesson which is the lesson I'm recording. Now if
> I click on it, you see it opens a text file in the middle. So you can see I can actually just go and
> see the text. I can edit it if I want. So, if I want to put a little smiley here, I can do that. And
> it's just a way for me to select my files the way I would select them on my Finder where I may have
> folders and files. Same thing here. And actually, if I just want to add files to my VS Code, I can
> literally just grab a file and then drag and drop it. For example, in dump, which is where I drop my
> files, and boom, my file is added. So, it's just that simple, not that scary. The second thing that
> we have, as you can see, is the middle column, which is essentially our text file. It's just us
> editing things. In this case, this is the things that I'm talking about in this lesson. So, I've
> covered the I'm not a coder and I'm just showing you how it works right now. And on the right side,
> you basically have your chatbot, which works exactly like any chatbot that you've been using before.
> So, if I say hi and I send this to Clude, it should be responding to me the way Cloud would respond.
> Hey there, how can I help you today? However, this is a much better version of Cloud that you may
> ever be using inside your chatbot. So you know when you're working in chatbots for example you need
> to kind of like upload your files you need to kind of give context etc. Whereas here I have a bunch
> of tools to give context to code immediately. For example let's say that I want to improve this
> section that says but I'm not a coder objection that you guys may have when you're watching this.
> Well, actually when I am in my editor here and I select, you can see that code actually sees I've
> selected these lines and I can just give a prompt here without necessarily giving it the context of
> the stuff that is highlighted because it already has it without me doing anything. So if I say
> rewrite this but more funny it's going to essentially be able to read the file I've selected get my
> prompt and then I can just tell it if I like it or not. And if I like it, the thing that it can do
> that code could not do is it can edit this file back and put it for me. So I'll be like, yep, change
> it to this version on the file. And if I tell that, it will be able to go ahead and change the copy
> right away. Now, if I asked it in the prompt to actually do the edit right away, it would have done
> it. But in this case, it's going to be able to read the file. It proposes the changes. I can see the
> before and the after, for example, and I can click okay. And if I didn't want to have to approve
> this, I could say always allow. But I'm going to say yes here. And bada boom, bada boom, my file is
> edited. It's really powerful, for example, for marketing copy, for emails, for landing pages, even
> for articles. It just makes collaboration with the LLM really simple and easy. And I can go further.
> Let's imagine that I want this to be rewritten in the same style as maybe a previous community post
> that I've done. So for example, I have the post that announced the road map for example. So I can go
> back to my what is cloud code. I you see I still have this edited and I can mention another file and
> have code read that file and then use that as inspiration for the edit. I say actually rewrite it in
> the style of and then I can do the add sign and I say 2024 accelerator road map. You can see I see
> my files here. I can select it and if I press enter clo knows what file I'm talking about. is going
> to go and read the content of that file and that's going to be part of the prompt. It's going to
> understand the style. It's going to rewrite the section that I have selected only. Do you want to
> update it? I say yes. It's going to go ahead and edit it. So, you can see my ability to change the
> context with code and work on campaigns when I have pre-made documentation etc. is really quite
> powerful. Now, that is just one tiny bit of why cloth code is awesome, but that alone could convince
> me to use it. The next one is actually you can do long-term memory. So the problem with most LLMs is
> when you create a new chat, you know, all the history is gone and there's not much left in terms of
> context on what you're working. When you work on code on any coding agent, you actually have a file
> called cloud.md. Now cl.m can be created by cl code or you can just edit it yourself and gives
> information that code reads at the beginning of every conversation so that it gives it context on
> what you're working with, how you like things to be done, etc. So you can see for example, it tells
> it this is my AI membership operation workspace. there is some documentation in docs. For example,
> there's some autohacker context here that explains what the company is about. It's going to
> essentially go and read that file and then it will open related files if it needs to. But the point
> is when I start a chat with clothes here, it has a lot of context about what we do and I can just
> edit it by typing in this file and that gives it long-term memory. So for example, if I ask it, what
> do you know about authority hacker? you will see that it's going to read it this file. It's going to
> see that there is context and it actually knows all this stuff by default. And so that is really
> handy because that context on top of the stuff that I've selected on top of the file that I
> mentioned allows me to build perfect context really really quickly when I'm working with an LLM. Now
> the next reason I think code is something that you should be learning is that it can actually
> connect to different parts of your business. So you can see now we're working on text files and it's
> kind of cute and stuff but like our community doesn't run on text files. Our email tool doesn't run
> on text files. Like how do I actually do stuff? Well actually you can connect it through MCPS and
> you can see for example in MCP service here I have one called circle. This is an MCP that cloud made
> itself. It created that connection. It doesn't exist officially if you go and check this out. But I
> just gave the API documentation to cloud and it built it. And all I can do is I can just talk to
> code and it's going to be able to do things for me. So for example, I can administrate the entire
> community from this window. I can say use the circle MCP and check for any questions posts we
> haven't answered to in the last seven days and prep drafts for them. Research if needed. What it's
> going to do is it's going to go on circle. It's going to call its little circle MCP. It's going to
> ask me if it can use it, which yep, you can use it. And it's going to grab all the posts of the last
> seven days. It's going to check the comments. It's going to make sure that they've all been
> responded to and that everyone has their questions answered. It's going to think about the question,
> research it, prepare me a draft, and when I approve it, it can respond for me. So I can run the
> entire circle community here. I can still review the post. I'm not going to like essentially ignore
> people. But I can do this without necessarily having to login myself, change my context, etc. So you
> can see it's reading all the comments here. It's thinking and it should give me a little report
> after it's done reading everything. You can see it didn't check the introduce yourself. So I decided
> to go for that. It made its own little to-do list here, which the normal code doesn't tend to do.
> That does it. And normally it should prepare me some drafts if it needs to. And you can see the
> summary is now coming through. So Christian needs a welcome response. It hasn't been done. Zapier to
> NA10 it's been answered but John for asked a follow-up question. Custom GPT jailbreak is answered.
> And you can see now it prepared answers for all these post and it even gave me the link. So if I
> actually click I can just open the post and you can see that post exists, right? It wasn't
> hallucinated. Let me check the response for Christian for example. It's like it's a little bit
> corporate. Doesn't sound like me. So I could say update the response for Christian using the tone of
> community post. The point is I have some documentation on how I like to write. So it's going to
> essentially go and read the documentation in there and change the way it writes. So you can see it's
> reading and it's going to update the answer. So you can see it's a collaborative work and it doesn't
> operate autonomously but it does a lot of heavy lifting for me. So let's see the new draft to change
> everything. Most of it is nice. That's why we focus on stuff that works practical workflow. If you
> want to start building the get side with an end course is a solid entry point. Very good. Once
> you're comfortable check the automated SEO pipeline. Yep. And so it asks me if it if I'm ready to
> post I say yes. Post it. and principle is going to connect back to circle put the answer there and
> we'll be good and hopefully Christian you won't be mad that I use code to answer to your comment but
> the idea is to show that I can operate everything without leaving VS code if I want to now if I
> actually go and refresh that post you can see the answer has been posted by code and that's the lack
> of context switching that I was talking about and it's very nice because at the same time I maintain
> full control of what Christian's receiving I still make sure there's no slop here and that is
> treated correctly. But AI has helped do a lot of the heavy lifting and that can happen for pretty
> much any system that you have that has an API code can connect to it and operate it for you directly
> from this interface using all the context and documentation of your company to follow the rules. Now
> it can do even more because actually cloud can operate Chrome using the Chrome integration that CL
> has. So I'm going to make a new chat and let's imagine that I really like Ali Abdar's new website. I
> think it looks very good and I'd like to kind of review it and brainstorm ideas to improve authority
> hackers design. I think our design is okay but I think this is a little bit rough for example. So
> this is not something I would necessarily spend my time doing because I have more important things
> to do. I can ask Clo to open a browser go through the two websites and prepare report of things that
> we should use as inspiration from Ali Abdal's website. So, what I'm going to do is I'm going to
> create this. And in this case, we're going to go in the terminal version of clo code, which looks a
> little bit scarier. And I'm going to show you how to set it up, but it has more options like the
> ability to operate Chrome, for example. So, here I'm going to type my prompt, and you'll see it
> works exactly the same way. I'll just say I like Ali Abdal new design. I want to steal good ideas
> from him to make authorityhacker.com a more premium looking site. Can you review both and prepare a
> report of the elements we should steal from him screenshots welcome use Chrome and then I'll just
> basically send that to Clude and in principle what it's going to do because it has the Chrome
> integration which I'm going to show you how to set up is going to open its own Chrome window as you
> see now it's going to start basically operating the browser in the background so I expect that it's
> going to start navigating to Ali Abdal and it's going to essentially scroll through it and take
> screenshots, review it, then review my website, then prepare a report for me and I can just review
> it and you can see like it's just scrolling on its own and it's just navigating and operating. So
> what I suggest is we'll let it work because that's exactly how I would do it. I would just let it
> operate and just make another conversation and while this workflow is happening I can do something
> else. And that's the power of code that I want you to realize. Now this is cool but you can actually
> also teach your workflows to code in a way that you could not to a normal chatbot. So let me
> actually collapse all these things like my projects etc. my dump and I want to show you this skill
> area. And this skill area is basically me teaching AI how to do complex workflows. I want to talk
> about something that happened last night. We released the podcast for the first time in a while and
> I was late in boosting the podcast and now when you do YouTube videos you know if you want to get
> good results you should AB test your thumbnails. So I need three thumbnails but the good news is I
> have taught code how to create YouTube thumbnails. The challenge with YouTube thumbnails is when you
> generate faces they tend to not look like you. So the way I talk to generate YouTube thumbnails is
> to actually use nanobana API which again I did not code. I just gave it the API URL and it made it
> for me to generate the background and then it adds my photo on top of it. So, let me actually show
> you what this actually does in real life to just give you an idea of the kind of workflows that you
> can operate. If I go in my downloads, you see, for example, it generated this background. And when
> this background was generated, you can see it's just like the base of a YouTube thumbnail and it
> took a photo that I gave it of me and added me on there. And that is a pretty decent YouTube
> thumbnail. Not only did he generate these thumbnails, it actually generated the ideas for these
> thumbnails. And the way it generated the idea for these thumbnails is I created some assets here
> which are examples of thumbnails that I really like. I gave it these assets. It looks at them where
> it brainstorms thumbnails. It gives me the concepts and it gave me all the concepts. I said, "Yep, I
> like this one. I don't like this one." It generated the thumbnails using Nanobanana. you're running
> its own custom script and then I could review it and give some feedback which I didn't like
> everything right away. We kind of work together. For example, I think you can move me a bit on the
> right on the thumbnail one to not cover 21% and maybe a bit bigger. So I kind of give it feedback
> like I gave to a designer and eventually it gave me the after 15 or 20 minutes it gave me this
> thumbnail which is decent. It gave me this one which I think is pretty good as well. Then the next
> one, the code red one was also very good. I think this one might be winning the AB test right now.
> And it just did that based on the inspiration nano banana background adding my photo. And then the
> last one that I showed you about quitting TGPT, that's the four thumbnails that are essentially
> testing against each other. And that's the kind of workflow that you can test. And not only that,
> but let's say the workflow doesn't go perfectly. Like sometimes you can see I had to give it
> feedback and we just had a chat back and forth until we had it. You can then tell CL to review the
> chat. identify the issues and update its workflow documentation so next time it doesn't make the
> same mistakes. So it's essentially learning like a co-orker or like an employee. And when you do the
> work together, you end up essentially upskilling it and having it do a better job. And you can do
> that for any kind of workflow, even involving complex APIs, even involving many steps, editing
> articles. I do my newsletter that way. I do meta ads that way. Our community posts are all written
> that way as well. The email strategy for our price increase campaign right now is run this way.
> Basically any kind of repetitive workflow that I do is now basically built as skills and skills is
> something we're going to release after the release of this course to give you guys workflows
> basically. And meanwhile you can see that my terminal is actually done. It actually has done the
> research here. It gave me ideas of things that it can still so visual Ali Abdal has this kind of
> like warm beige background blah blah blah hacker is like clean clinical still this switch from pure
> white to warm cream blah blah blah handdrawn annotations. I just basically did that report after
> being done reviewing the website. So you can see what I was teaching you. Clo did a report for me
> and I could say save it it as a file in the marketing folder and it's going to basically put that
> report that I can use as context later when I want to edit my website. You can see it's actually
> offering me to save the file and it's like essentially now if I open this file you can see it saved
> my report here and I can use this as context but I think you can go even further with cloud code. I
> know I said it wouldn't be a coding course but I think it's so good at coding that you can ask it to
> make some very basic dashboards for you and things that will help you run your business better. So
> again I'm going to give you a practical example of how I am actually doing it. So you see I'm using
> this thing in real life. We are trying to grow AI accelerator right now and so it's quite important
> for us to understand the effect of marketing on ourselves. You know the kind of emails we're sending
> like how many more sales are we doing compared to last week last month etc. And it's like stripe as
> a dashboard doesn't necessarily do the best job at doing this. So I gave my API key, my stripe API
> key in readonly to code and I was like can you just make me a dashboard right and I talked to it for
> like 20 minutes on what I wanted and essentially what happened is I actually got code to generate
> this dashboard for me. You can see how many subscriptions I have today versus yesterday or versus
> the last three months. In this case is a new stripe account that you're seeing. This is not all our
> subscriptions but the point is this three months average is not going to be correct but like this
> one compared to yesterday is pretty correct. new revenue this week, this month, etc. Like you can
> see how you're doing against your average. I can see the recurring revenue. I can see the churn
> rate, active subscribers, how much money do I make per types of plan. You can see churn versus new
> sales. You can see revenue projections, etc. The point is this was three prompts to code and it
> generated this dashboard for me. I don't have to put it on the internet. I don't have to make it
> super safe, etc. but visualizing your data that way. I think it can help you just do a better job
> with you know making decisions for example. So that's something that you can do with cloud code and
> I think that's going to unlock a lot of workflows for you guys especially if you connect multiple
> data sources. So I guess the question now is like what if I'm not a cloud user? What if I use OpenAI
> or what if I use Gemini? Can I do this stuff? Well, you can mostly do this stuff. All of these
> competitors actually have something similar to cloud code. I personally find cloud code is by far
> the best allrounder for this kind of work because it's a really good agent. It's a good copyriter.
> It's fast and it's just easy to use. It understands what you mean very easily if you're not
> technical. Whereas the open AI models, for example, tend to be better for engineers but less for
> marketers. Regardless, you can use any of these if you want and use skills for example on Codeex,
> which is the OpenAI one. We have a chat interface with some options here. And you also can do it
> with Gemini. If I close it on my terminal and I type Gemini for example, it should just open Gemini
> for me and you can install it and run it in the terminal. And the good news is you don't really need
> to pay extra to use these things. If you pay a subscription to code, you can use code. If you pay a
> subscription to Chad GPT, you can use codeex. If you pay a subscription to Gemini, you can use the
> Gemini CLI. So you can use your current plans of whatever chatbot you use and do the same setup that
> we're going to do here. The one thing I'll say is for code, if you start using it a lot, there's a
> good chance that if you are on the $20 plan, you're going to run out of credits. Now, don't upgrade
> until you actually hit the limits because they prorrate you anyway. So, there is no reason why you
> should pay more than you need to when you are doing this if you're not actually using it. But just
> know that it's a possibility still given the amount of work it can do for you. It's a still it's
> basically unlimited Upwork developer plus like an intern that can do work for you, etc. for $100 per
> month. Really, your job this year is to figure out how to get value out of this $100 subscription
> because it can do so much for you. So, I hope this convinced you that this is a really good thing to
> set up. Consider this a power user chatbot setup for real productive work. In the next videos, I'm
> going to show you how to set up everything step by step. We're going to start very simple. This is
> my current workspace which is a little bit busy, but we're going to start from an empty project and
> we're going to set everything up as if nothing was installed on your computer. You'll be able to
> build up to this step by step as I teach you every single feature and how it can be used. So
> hopefully you're excited and I'll see you in the next

---

## Research Notes

- **Personal observations:** Gael's point about switching costs is crucial—storing prompts and workflows as raw markdown files (Skills) means your AI setup is fully portable and doesn't trap you in a single vendor's ecosystem.
- **Related concepts:** Claude Code, Workspace Memory (`claude.md`), MCP, Natural Language API Integration.
- **Ideas worth investigating further:**
  1. Standardizing our research workflow prompts into markdown files (`SKILL.md`) to establish a reusable "Skill" directory that can run on any CLI agent.
