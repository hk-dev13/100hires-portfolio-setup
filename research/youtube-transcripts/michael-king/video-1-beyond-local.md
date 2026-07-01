# YouTube Transcript Research

## Video Information

**Expert:**
Michael King

**Title:**
Beyond Local Episode 20: Interview with Mike King

**Channel:**
Chris Jones (Beyond Local)

**Published:**
2020-10-16 (Approximate based on interview context)

**Duration:**
00:51:30

**Video URL:**
https://www.youtube.com/watch?v=k7bzmM3jkwk

**Transcript Source:**
youtube-transcript-api

---

## Why This Video Was Selected

This video was selected because it deeply explores Michael King's background as an advanced developer and how he integrates software engineering principles into SEO. Understanding his perspective on Information Retrieval (IR) and Natural Language Generation (NLG) is crucial for building robust, scalable AI-powered SEO content production workflows.

---

## Executive Summary

In this interview, Michael King discusses his journey from being an independent hip-hop artist to founding the technical SEO agency iPullRank. He provides detailed insights into advanced SEO strategies, highlighting the importance of treating SEO as an engineering discipline. He specifically covers the use of transformer technologies (like BERT and GPT) for programmatic content generation and the implementation of automated internal linking systems using entity mapping.

---

## Key Takeaways

- **Technical Content Optimization:** Search engines use statistical models to evaluate content. Utilizing TF-IDF, named entity recognition, and topic modeling allows marketers to reverse-engineer and meet these statistical expectations.
- **Natural Language Generation (NLG) in SEO:** Transformer models can be leveraged to programmatically generate highly relevant and original content at scale, which is particularly effective for large sites like e-commerce category pages.
- **Automated Internal Linking:** Internal link structures can be managed programmatically by using "edit distance" to match target keywords in copy, leading to more scalable and impactful internal linking strategies.
- **Developer Perspective:** Viewing search algorithms through the lens of a software developer provides a more accurate understanding of how search engines operate and helps avoid reactionary behavior to standard software rollbacks or updates.

---

## Transcript

> [Music] hey guys this is chris jones your host for beyond local this is episode 20 and we're going
> to do something different here i met with the lseo team and we said we're coming up on our 20th
> episode in a couple of weeks this is a couple weeks ago and we said let's do something you know
> unique let's kind of mix it up and so you know the team thought hey chris you've been in the
> industry for a long time you're friends with a lot of the most influential people who would be the
> most infl well who would be the most interesting person we could interview and i'm not gonna lie you
> know my seo team uh looks up to mike king as one of the foremost thought leaders on technical seo
> and i said he's my brother and he's a good friend and i want to dive into a couple of things with
> mike that maybe people don't know and of course we're going to get to the juice at the end of
> technical seo but let's welcome mike king to beyond local welcome mike thank you thank you thank you
> chris thank you so much for having me i'm very excited to be here for sure man um so we've known
> each other for a bunch of years uh in full disclosure we spoke at a show i think it was called
> internet marketing rock stars how many years ago is that five years six years eight years it's
> probably like six years ago at this point six years ago i think were we in berlin germany i think
> right uh no i think we were in another maybe hamburg was it hamburg yeah yeah yeah and it was it was
> actually really cool because like i'd never met you i heard your name before and you were just like
> immediately cool person you know you were just like we we connected on both being from like the you
> know kind of philadelphia pennsylvania area and yeah you're just immediately cool and i was like why
> have i never met this guy before yeah and we've hung out a lot since then we've gone to munich
> germany together several times for seo oktoberfest and we've gotten to know each other i'm going to
> ask you to tell the viewers more about mike king but but before we get there i'm going to say let me
> tell you about what i loved you when i met you for the first time um i'd only later got to geek out
> with you about seo there were two things that that i really loved about you number one you're so
> entrepreneurial and i remember at that time this may have been either early i pull rank days or
> whatever but i just saw this entrepreneurial spirit this guy that's got big goals big ambitions
> nothing's going to stop him and then the second connection was the entertainment industry so um you
> know you you toured the world as a professional rapper um and so but i don't want to tell your bio
> dude tell my friends the viewers more about mike king and please you know be don't be apologetic
> here give them give them what they want to hear yeah um i mean you know where where the story starts
> is probably most interesting to people is that i'm a self-taught coder so i've been coding since i
> was 12. and um you know at the same time i have kind of like a fresh print story my parents moved me
> out of philly for high school because they were scared i was going to get in too much trouble and so
> they moved me to connecticut to go to a private school and i just really felt the need to be more in
> touch with like my urban roots and so i started doing everything hip-hop related i started from
> doing graffiti to break dancing to djing and then also emceeing and ultimately what i realized is
> that i was only going to be really really good at one of those things so i stuck with rapping and
> then i went to school i went to howard university um studied computer science but i was just way
> more into making music i was like you know i can only rap till i'm probably like 30 so i can go back
> to school whenever i want and so ultimately you know i left school and just started you know trying
> to put out records independently so first first 12-inch vinyl and i put out uh i basically use all
> the savings bonds that i collected over over you know my young life and and pressed the single and
> sold a ton of copies um in like japan and all these places and so it started to get me opportunities
> to go on the road but the thing is um and this is relevant to the marketing thing and i'll get to
> that but thing is like being an independent rapper is just like being a consultant in that no one is
> creating anything for you you've got to create these opportunities so in a lot of ways that was my
> way of learning how to be an entrepreneur because like how am i going to make money day to day and
> so um i had to do all this outreach across the web to like find people to book me and you know it
> was either they pay you the money to get there or they pay you for the show so at one point i was
> making like counterfeit uh uh greyhound bus passes so i could do shows all over america and you know
> we ultimately got caught in in uh sacramento which is like literally the farthest place from
> philadelphia across the map so the whole point that i'm making with that is that you know i i just
> was like all right i need to make this rap career happen and you know it's all about like okay where
> do i find resources how do i create opportunities and a lot of that experience is what prepared me
> to become a marketer so i was doing that from like um basically eight years like full time as my
> main thing but in 06 i got into a bike accident and i didn't have health insurance so i had to get a
> job to pay for my medical bills and the first place to hire me was an seo agency and it was a small
> shop um they were like oh you know a lot about coding you can figure this out and i'm like cool no
> doubt i can do that but at the same time it wasn't my primary focus like i was doing really well at
> the job um they made me like the manager of the production staff after like something like six
> months or something like that and um you know when i got that job i was like all right i'm gonna
> keep it until i go on tour because i was about to go on my first european tour that november this is
> august and you know i got to almost november and i was like all right i got to get my notice but i
> was really enjoying the job and i told my boss and he was like oh no you can just work from home
> work from the road i was like what that's a thing so here i am on my first european tour with this
> guy his rap name is dos noun and the reason why i bring him up is because he's important to the
> story as well but i'm on on the on these trains in like sweden and germany and all these places and
> i'm like i got this really heavy laptop where i'm doing seo for websites from the road and this is
> like they just gave us the website it wasn't like we write articles about your website and tell you
> what to do it's like here's a website optimize it so i was doing that and then when we would get to
> places i would just like upload what i did and then everybody be happy and we just kept it moving i
> would go do my show so suffice to say like after a few years of that um i kept my jobs until my
> bosses would piss me off and i just go back on tour because you know being entrepreneurial you're
> like i don't have to sit here and take this i can do any number of things right so ultimately i got
> a job at razor fish and um razorfish being one of the bigger multinational agencies with one of the
> better big agency seo teams and i really loved working with those folks um and at that time i
> started to become more aware of the actual seo community so this is like 2010. like i had never been
> to a conference i wasn't reading the blogs i was just figuring things out myself reinventing the
> wheel all over the place now the reason why i brought up my friend dos now is one time around the
> time where i started razor fish we were on a train somewhere in europe doing shows and he was like
> hey mike i know you're doing this seo thing my cousin owns an seo software company and i'm like what
> who's your cousin he's like yeah my cousin's name is rand fishkin i was like what like i was
> completely mind blown at this point i had no idea that these two worlds were gonna intersect this
> way right and so you know once i started at razorfish i reached out to rand and then i ended up
> meeting him at a meetup in new york and then you know just like quickly uh building a relationship
> with him not in the you know i'm trying to build a relationship with somebody way it's like oh you
> happen to be my best friend's cousin let's like connect i do the same thing and you know then um the
> other part of the story is that when i was at razorfish i was just a contractor they gave me 24
> hours a week and i really wanted a full-time employee role um but you know when they interviewed me
> they didn't feel as though i had the agency polish because again my experience was just doing seo
> not consulting about seo so um you know they just gave me the the contractor role and i was doing
> all types of stuff like i was i was tearing through work like i was i was getting things done so
> fast so well from my perspective and i was also building tools and all these other things because i
> was just like yo i want this job i want to show improve here like let's get this done and ultimately
> they couldn't get the head count for me they just kept extending my contract so i was like all right
> i got to get proactive here because it's starting to you know make me very frustrated so i was like
> i'm going to go to another publicist agency because that's the holding company that rage and fish is
> under and i'm going to get a job offer and i'm going to bring it back to razor fish and razor fish
> will have to hire me so i did that and they were like we still can't get the head count so i moved
> to new york worked at a publicist modem um and at that same time that's when i started getting more
> involved in the community i started you know blogging for moz and this is this is another reason why
> i bring brought up the the counterfeit uh you know bus pass thing so i i've been writing for moz and
> my blog posts have become very popular because you know i took very creative approaches to what i
> was writing about a lot of extended metaphors and things and mozcom was coming up and i was like yo
> i have to go i have to meet these people you know like all these people i'm typing to online every
> day like i have to actually meet them in person and so i went to my boss at the time at uh modem and
> i was like hey you know can you guys send me to this conference and they kept giving me the run
> around for like weeks like oh yeah we'll get back to you we'll get back to you and then ultimately i
> was like you know what i'm just gonna use my vacation time i'm gonna book the flight i'm just gonna
> go and it was the the best decision i made like at the start of my career because so many
> relationships that i built on that one trip created so many other things like so you know i got to
> connect better with rand um there's a guy named jamie steven who used to be a cmo of moz turns out
> he and i actually worked together when i was a high school intern at microsoft and we were featured
> in microsoft's newsletter like the company newsletter together for something that we had built
> called intern web which is like a social media platform before social media platforms existed and
> anyway so connected with all these people got really inspired at mozcon i remember i was watching
> will reynolds for the first time and i was like oh they let black people do this too cool and i
> submitted my proposal for uh to speak at smx east right while i was watching him and i got the i got
> picked to give the talk and so you know there was all of that that happened and then i spoke at smx
> east um leading up to that i connected with a lot of people like dennis g who i didn't know at all
> just someone said like oh you should meet him and he randomly happened to be in the city so we
> caught up and we were just talking about like some of the things that he talked about and how it
> overlapped with what i was talking about and again that's another person that i've been friends with
> ever since who was just immediately cooling me so tell people real quick who dennis is because you
> and i know him as one of our good friends but he's one of the top growth marketers in the world
> right oh absolutely one of the best one of the best at growth period you know um his his background
> he's worked at like ebay airbnb uh fanatics and now he's at paypal so he he's just been doing great
> things in this space clear thought leader uh who is just a really generous person who's always down
> to like give feedback and connect you with people um and just like a general cool guy so i've i've
> been lucky to meet a lot of people like that in this career and in my life in general um but yeah so
> you know with all of that i ended up uh going to a couple other agencies and just realizing you know
> there's a lot about working at agencies that i don't like and there's a lot about how agencies are
> constructed that i don't like and i was like i think it's a good idea for me to just start my own
> thing and that was i pulled rank and here we are six years later so dude tell us about the uh the
> the picture that you have in your backdrop there is that your house currently or is that some uh
> some future goal this is a future goal right here so this is a house in the hamptons um you know i
> there's a lot of goals that i had when i was younger that i think were just too small for me and so
> now i'm like you know getting my more bigger um hairy audacious goals so i went to the the hamptons
> for the first time for my birthday in august and you know i was just driving around trying to go to
> a beach and i'm riding around i'm like whoa look at these houses these houses are crazy i want that
> house right there and then after i go home from the beach i look up where i was and they're like
> this is called billionaires row or billionaire's lane or whatever it is i was like oh i guess i need
> to be a billionaire then [Laughter] so we're going to dive more into uh into i pull rank and and
> your experience so far in entrepreneurship but but before we go there and this is awesome dude this
> is like the documentary of mike king and i'm just so proud to be buddies with you and to be able to
> to hear the story and your willingness to share it man dude you've you've inspired you know tens of
> thousands or hundreds of thousands of digital marketers out there and and i think that we could only
> aspire to emulate your style man i mean it's just badass and and i hope uh you know folks that may
> may not have known you will take more of an interest check out your kick-ass blog check out some of
> the podcasting you're doing and some of the other stuff they're going to hear about as we go through
> this interview but before we jump to entrepreneurship dude i i'd be remiss if i didn't say where's
> your headspace in terms of hip-hop and music you know is that something you might go back to is that
> something you're you're working on yeah the thing is this man like i i've never i was never like
> y'all retired from rapping like you know i still do things here and there and even when i first
> started doing a lot of public speaking in like this conference circuit i would get shows after the
> conference and in some cases like marketing festival in the czech republic i did the after party for
> the conference um the czech republic is a good example because i actually have a really large fan
> base out there like i played festivals with like 25 000 people out there and things like that so um
> that's always going to be a part of who i am it's just how do i find a way to do it where the
> opportunity cost isn't so high and so a few years ago i acquired a website called
> undergroundhiphop.com which is a 20 year old e-commerce site and my goal was to make it more like a
> media site kind of like up rocks or complex and things like that um it was just you know too
> difficult for the lack of support that we had for it that's not to say that venture is going to be
> completely dead it's just that i need to reconfigure it in a way where it's more self-propelling i
> think what we need to do is make it more like a marketplace more like an etsy type site with the
> media component built on top of it but i've got a lot of things that i want to do in that space
> because i think there's a lot of things that are just broken in the music space you know i i'd come
> up with a new approach to record deals that um it's more like an affiliate marketing model than it
> is like here's a bad loan for your record and then you never recoup on it so um there's just some
> initial difficulty as far as like that learning curve of explaining that to rappers when they know
> one very specific model where they're getting taken advantage of all the time so i think it's going
> to just take you know more time effort and resources to make it work but i i completely expect to do
> something more meaningful and game changing in that space dude the crazy thing is is as i'm
> listening to you i'm i'm thinking back you know people that know me know that they know the pepper
> jam story they know that i had this opportunity to become a professional investor i'll tell you one
> of the pieces of advice that i give to startup entrepreneurs is this big idea of of the most
> influential and most wealthy people in our society are the combination of entrepreneurs and artists
> the ones that don't shut off their creative genius just because they want to make money or the the
> opposite which is i want to make money i want to buy the house so therefore you know it's not going
> to this is not going to work i got to i got to put my dreams aside thing i love about what i just
> heard is is dude you've got that combination and by the way having both artistry and entrepreneurial
> spirit are super difficult because you know the the one kind of turns down the other and uh you know
> the the jay-z's the beyonce's the you know there are certain people who've mixed the two together
> that have become just extraordinarily successful so there's no doubt in my mind that there will be a
> day there will be a time maybe sooner rather than later where you combine these two these two you
> know areas of interest and expertise that you have entrepreneurship and artistry to really create
> something special um entrepreneurship oh yeah totally man totally so entrepreneurship right uh
> clearly in your in your in your blood you could hear it in your voice everything we've talked to up
> to this point has an angle where it's like you know like i gotta make this you know big i've gotta
> grow and scale it and i remember when did you when did you found ipool rank august of 2014 august of
> 2014. so if if our math of us speaking at that internet marketing rockstar is you know the same time
> yeah yeah so i remember some of the you know we just had some discussions about hey you know that
> you were going to do this so you've got six years of experience as an entrepreneur um by all
> accounts you're doing it right you're doing it well and your reputation is very very strong but what
> are some of the challenges or some of the mistakes that you've made up to this point that could
> could kind of be used as tips for other entrepreneurs to kind of avoid or to try to you know reduce
> or mitigate yeah my number one thing around that is process is everything so for me um i'm not a
> process oriented person by design it's more like like if if you ask me to do something two times i'm
> gonna do it completely differently both times because i'm like all right how can i do this better
> how can i rethink this how do i break this down to its its atomic components and then rebuild it in
> a way that it's just better most people don't think that way most people are like you know what are
> the steps to do this walk me through those steps help me understand those steps and then i'm going
> to paint by numbers for the rest of my life um and so my expectation was like i'll just hire smart
> people and they'll be able to do these things better than me and they'll just figure it out and it's
> it's going to be better than the things that i'm doing that's just not how it works the way it works
> is that you give people a clear path and clear instructions and then once they get comfortable they
> start making changes to the little components of it so if i had anything to say i would say you know
> sit down as soon as you are to a point where you're like i want to bring other people on write down
> how you're doing things in very detailed prescriptive ways so that anyone that you bring on can pick
> up where you left off um i i definitely think for me that was a big failure for the first like three
> years of my business because people would come on and just not really know what to do and i just had
> these expectations that everyone was like me and that's just not true so that's the the main one um
> other than that i would say uh you know really nail down the hiring process and understand what you
> work well with and that's not to say that we can't have culture ads and all these other things you
> definitely need that but if there are certain um characteristics of people that just don't work well
> for you it's not gonna work you know it's just the reality right like so you may try to contort
> yourself to work within the bounds of how those people work but then what ends up happening is like
> you know that person leaves and you're like well i made all these concessions to support having this
> person with me and then you just have like this bad taste in your mouth about who you who yourself
> were who you yourself was were you know what i'm saying who you were during that time yeah and also
> that experience of working with that person you're not able to maximize it so i think you just got
> to be very clear about what your strength your strengths and weaknesses are and what you can manage
> best within your organization to get you to where you need to go that's great advice uh folks still
> watching feel free to post a question for mike and you know after the interview he'll he'll do his
> best to answer it i really appreciate you guys engaging with us mike king what do you love most
> about entrepreneurship i love the ability to make something that doesn't exist exists and you know
> because so much of of my experience in the world is like this shouldn't be that way it should be
> this way or any number of ways that are better and so you know so many businesses are so entrenched
> in the way they do things and again that goes back to my aversion to process um i love the
> opportunity to be like all right that's broken let's fix it we fixed it now it exists or the idea of
> just like creating something out of thin air so you know being a creative as well as a technical
> person um it's very easy to be like i imagine this thing let me make this thing like that that was
> my whole life for eight years with music it was like okay um i imagine a song that no one's rapping
> or or or a style of rapping that no one is doing i am now doing that and now people get to see it
> and they enjoy it and i was right so uh it's the same thing with entrepreneurship like if i want to
> make a product we make the product and then we put it out and people enjoy it or they don't and then
> we learn from it so i just really love the opportunity to create things that don't exist it's
> awesome dude so give us a sense not revenue but in terms of how many people you employ and then my
> question is is where do you see ipool rank in five years so um the employment number i mean we've
> got 15 full-time people but we've got like over 100 other people that we bring in and out for
> different projects um and where do i see us going i think my my original goal for starting this
> agency wasn't just just to be another agency i wanted us to use the revenue from this client work
> that we do to fuel other ventures so you know the thing about venture capital that i i don't like is
> that effectively someone is buying a piece of your company and then becoming your boss to some
> degree and so what i always liked is this idea of like no we can make this money and then we can
> make things that basically compound that money that we've made so that's been my end goal but what
> i've realized recently is that the same people that want to support your agency aren't necessarily
> the same people that want to be your like venture group and so i think in the next year or two what
> we're going to end up doing is building like that internal venture group just to build things on the
> back of the revenue that we generate from our clients so in five years i pull rank will be like a
> studio a design a product studio sweet how about 10 years out and by the way the the bat i'm still
> seeing that picture behind you and i'm thinking uh you know when we look at what uh there's so many
> stories you know sem rush just you know raised i think 30 million dollars um you know i've bought
> and sold companies in in this in this arena um you mentioned our our mutual friend will reynolds uh
> can't disclose much but will's been a friend of mine for a long time another philly guy um and and
> he's got you know two offices the the guys you know he's he's i think when we think about like sir
> interactive you know this is a company probably with 130 employees or something at this point i'm
> hypothetically saying might have a value certainly north of 50 million bucks those kind of
> opportunities if an ipool rank becomes that you know you could potentially have an exit if you look
> out 10 years if that was something you wanted for let's just say north of 50 million bucks you get
> you sell your agency for for 50 million bucks the house behind you is is in cash and uh and you get
> to do all that other stuff i'm not trying to put words into your mouth but if you went out 10 years
> what would i pull rank look like yeah i don't think i don't think i personally will want to be
> running an agency ten years from now that's not to say that i won't potentially own an agency 10
> years from now but i would expect that i pour rank is completely self-sufficient 10 years from now
> and i will be you know kind of like that jay-z model that you kind of mentioned where he's he's all
> over he's seen he's overseeing a bunch of different ventures right like he's got roc nation he's got
> um his different beverages and things like that i don't see myself going into those specific spaces
> but you know i i see myself going very deep into software going deep into media and uh looking for
> ways to combine those worlds because again i just see that there's a lot of holes in those worlds
> that can be filled with ideas that i believe are viable so in answer to your question i see myself
> diversified a lot more than just running an agency 10 years from now dude it's brilliant well
> hopefully we look back on this because it's what i really interpreted there is that you're building
> something that could have enterprise value in the b's in the billions you know and so uh i was just
> trying to kind of explore i'm a big personal professional development person you know that um and
> one thing that i love to do with successful people like yourself is to try to get into your head
> about the dreams that you have how you visualize the future because listen the law of attraction
> your ability to attract things into your life that you want is the real deal and uh hopefully the
> 76ers hat represents a new future for us with doc being our new coach and next year us winning a
> championship and the house behind you uh hopefully you'll live in that in the next five years i mean
> so i i never say this one out loud because it sounds too much like garyvee but i want to own the
> sixers i want to buy the six sweet and you know if if it gets to the point where i'm this
> billionaire that i'm imagining that would definitely be one of the things that i would want to do
> i've been a sixers fan my whole life you know i live in new york now i'm not a nets fan i've been
> i've been a sixers fan my whole life so it's one of those things where it's like when you write down
> those big hairy audacious goals it's on that list at the top dude i love it so all right let's set
> up the final segment of this documentary on mike king um so we're gonna talk about seo um and you
> could clarify anything i'm about to say i'm just going to set it up the thing the thing that's that
> that makes you super unique in this industry is that um your technical skills come from years of
> experience as an advanced developer what are some of the uh program programming languages that that
> you're most familiar with are you like are you are you like a lamp guys are you like php et cetera
> or so if you were to ask me to like build something in an hour yeah i'm gonna go lamp um because
> that's just like what i know best in the in the web development sphere but you know what i probably
> know best in general is c plus okay um and being that php and c plus are very similar like it was
> easy for me to pick it up um as of late i've been trying to do more things in node and then where
> there are just like really good libraries i do some things in python but uh my primary language
> would be php so do you still code or do you have coders to do the coding both so it depends on what
> the project is because like i said i love to continue to make things and if i'm so like oh i've been
> working on biz dev or i've been working on you know uh process management and all these other things
> i'm like nah let me get my hands dirty and make something uh but more often than not it's our
> developers that are doing it cool so but that is your your mindset when you're thinking about seo
> you're thinking about programmatic seo you're thinking about seo at scale you're thinking about um
> how to leverage development uh to do things that others might be trying to do manually and failing
> correct yep yeah i think it's partially that and it's also thinking about how is google solving this
> problem right like what makes sense for how they may construct this and i'm not gonna sit here and
> act like i know the algorithms and things like that but i think that some things that we assume in
> the seo space don't make as much sense if you look at them through the developer lens like as an
> example people look to immediately um review and react to algorithm updates that doesn't make any
> sense because when a software company rolls something out they may roll out you know let's say five
> changes at once and they may roll back two or three of them and so if you do an analysis like three
> days after an algorithm update goes out your insights may not be the same as next week when they've
> rolled back components of that and so i always tell people like you know give it two weeks give it a
> month before you make any decisions based on what you saw because you have no idea of of how much of
> that is still in play so that's what i mean like if you if you're not if you don't have these mental
> models you may follow a lot of the assumptions that you hear in our seo um [Music] echo chamber but
> when you know things from a software perspective you can be like all right that's not real that's
> not real this is probably true and then you're just able to be more discerning sweet i'm gonna save
> the the three-ring circus of seo and your your book for the tail end here let's get let's dive in so
> so so mike is a a programmatic seo guy technical highly highly technical background as a developer
> takes a kind of a developer mindset and mixes it with with seo strategy let's talk about a couple of
> the key sort of if you will google ranking factors that we could all agree on are super important
> let's start with content when you and i were kind of prepping for this and just me following your
> stuff and totally uh loving it you talked about this concept of technical content optimization using
> um you know natural language generation and other things talk to us a little bit more about that and
> why it works yeah so one of the things that was really interesting to me when i started going over
> to um uh oktoberfest and smx munich and all this i kept hearing from people that tf idf was like
> this magic bullet and for anyone that doesn't know what that means term frequency inverse document
> frequency it's basically a way of saying that um when something ranks or when documents rank for a
> given keyword the search engines learn from those documents to determine you know what overlapping
> keywords are in those documents so if a new document wants to rank or new page wants to rank it has
> to also feature um you know these what we call proof terms and so i started really diving into that
> and i was like you know it can't just be this it also has to be what's called name entity
> recognition and also uh topic models and things like that and so i really just started to understand
> that space a lot better and it really drove me more into the information retrieval stuff and then
> everything was just you know a lot more that i needed to learn and so what i realized from all that
> research and testing and things is that search engines have statistical expectations for your
> content based on what ranks and so you can learn those by running those same type of operations on
> those pages that are ranking and then use those insights to adjust your existing content or engineer
> new content and so we've we've had a lot of success just doing that you know what i ultimately um
> concluded on all of that as well is that we as seos kind of over index on thinking links work so
> well and so that kind of reinforces links working so well but what i believe is happening in the
> scoring functions or algorithms is that there's different weightings for different components and
> the waiting for content is actually far higher than the waiting is for links it's just that we don't
> focus as much on the content aspect and so being that my team has you know made that switch to
> focusing more on the content engineering we're seeing a lot of impact just from doing those things
> without the need for building a ton more links can you is the is the use case here an e-commerce
> company that you know has lots of duplicate content and needs to spin up some original content or um
> is this what we're talking about right now really for for for the whole spectrum anyone who who's
> really trying to uh improve their rankings and put content up and maybe in in in the case that you
> just mentioned ahead of other ranking factors like links yeah absolutely so this is more of the
> latter this applies to anything now what you're talking about or what you mentioned um there was
> also this idea of natural language generation which has exploded in the last like two three years
> and um so there's this this uh technology called transformer technology bert is is like you know i
> think it was the first transformer technology i could be wrong and that's what google rolled out and
> so a lot of different companies and groups have taken learnings from that to build out other
> technologies so the way transformer technology works is basically you get a bunch of pages and then
> you start to learn the um the relationships between words so if i look at 500 pages i start to
> understand like okay this word usually comes after that word and so you can use that same idea to
> generate content and so people may have heard of gpt3 which came from openai which is a group that
> elon musk founded where they can generate copy that sounds like a human actually wrote it and so
> we're at this point where this technology exists and you can augment it in such a way that you can
> use it to generate content that will perform in organic search now my primary use case is like you
> said for e-commerce sites like category pages we all know that's where we primarily focus when we're
> doing seo for e-commerce sites because there's too many product pages so you primarily focus on the
> category page what people generally do is they put that paragraph a copy at the bottom of the page
> and then you know suddenly they're ranking it's content that no one ever reads you can make that
> content programmatically now and you can also inject data from your site to it so it it's completely
> relevant and it's completely original and so there is no excuse for people having blank category
> pages at this point it's a really good opportunity that i think a lot of people should be executing
> let's talk about uh internal linking strategy and i think one of the you you had mentioned uh this
> in other interviews our our mutual friend dennis g um and how uh ebay would programmatically uh be
> able to see where they're ranking say positions 11 through say 19 and do some programmatic things to
> [Music] basically prioritize internal links to those to those positioned keywords to pop them onto
> the first page but give us give us a flavor of how mike king and ipool rank think about internal
> linking from a technical seo point of view yeah i mean it's it's very much derived from what uh
> dennis and his team are doing at ebay and so what we do is we work with our clients to say like all
> right we need to have some sort of like internal mechanism to get more internal links to the pages
> that we want and more often than not it's like one of those link widgets or link blocks like those
> are easier to do but for our more advanced clients we'll work with them to effectively build a very
> similar uh appliance to what dennis and his team have done and so if you look at that post that
> dennis had published on his site um it's a really robust you know system architecture we've been
> able to do it in a more simplified way but key things that we do one um we pull in the rankings and
> we make adjustments based on that we also are doing what's called edit distance to determine what
> words or what phrases within the copy on different pages match with their target keywords the most
> so then drop those links there you got to make sure you got the right rules in place because
> otherwise you'll end up with the whole copy blocks full of links um we try to do like somewhere
> between three and five links that we're injecting per page but there's also like a console where
> they can say okay we need more links to this page or we can delete a bunch of links at scale and it
> it's definitely not a quick thing for us to deploy because you know we ought to work with their
> product teams to get buy-in and then ultimately build it but every time we've done it it's like they
> have cor they have control over their rankings like they they click a couple buttons a few days
> later things pop onto the first page it's it's magic um i mean it's not magic but the other thing is
> that um one of the things that we always do is is uh with broken link targets so if you've got like
> you know hundreds of thousands of millions of links pointing to pages that no longer exist we're
> also doing entity mapping between notes and so because if you just like redirect broadly or if you
> redirect to a page that has nothing to do with it it's not going to help you and in some fact some
> places it may actually hurt your rings and so we do that externally and we also do that internally
> because we want those um source and target matches to be as close as possible and again this is just
> another thing that i've uncovered by learning more about information retrieval that that's something
> that google is actively looking for it's not just like the raw number of links and we always talk
> about this idea of link quality but none of our tools are telling us like this is the best match of
> content versus the content that you're linking from and so we're doing more of those approaches to
> get the most value out of it so final topic on the seo piece is external links right so traditional
> or not traditional uh link building and you know one of the things that i think makes ipool rank uh
> unique is that you guys sort of take a machine learning approach to this and you guys have
> programmatically built some tools that allow you to sort of simulate um what would be a high hit
> rate for outreach and and being able to even use some ai and other forms of of language processing
> etc to to communicate with prospective link partners can you give us can you give us a sense of how
> you go about that yeah so another thing i realized a few years ago is that link building is just
> like outbound sales it is literally the exact same skill set it's just you're trying to convince
> someone to give you a link rather than give you money right and so i realized there's a lot of
> software in that space for uh managing that whole process and also like how you can like overcome
> objections and things like that and then i was like okay well if we combine this with chat bot
> software we can have these emails automatically be checked and if it's one where someone's like oh
> yeah we only we only do links if you pay us well that response can be detected and then we can
> automatically respond to that so we're doing two things we're classifying all the emails that come
> in from our outreach and then the ones that have objections that are obvious we automatically
> respond to those and then we're starring in gmail programmatically the ones that we think are going
> to be um good good prospects so that way our our link building folks are only focusing on the things
> that are going to be high value to us rather than wasting their time spending cycles effectively
> arguing with people on the internet so it's allowed us to really focus in on where the value is and
> get better results so you mentioned earlier uh you know that year old hip-hop buddy uh dose noun was
> wasn't he the one that was related to rand fishkin so you know i know you've always taken that
> platform at maz khan seriously so we're in a pandemic currently but mike king doesn't doesn't lay
> down this dude steps it up this guy this guy rewrites what it's what it's like to be an entrepreneur
> artist uh sort of double-headed uh you know monster um so you you you had an opportunity uh to to
> virtually right wasn't it virtually beyond that mozcon stage and you did something that's never been
> done before and you did it at a level of quality that's that's actually uh speaks for itself and you
> came up with this video called runtime the three ring circus of seo it's about a 32 or 33 minute
> video um that's just that's just awesome can you give us like a 60 60 seconds on on why so mozcon is
> kind of like the super bowl of seo conferences to me it was my first conference and i revere it in
> that way so when they told me that they were going to move to virtual this year i was pretty
> disappointed but then i realized like no this is an opportunity to do something different and next
> level so yeah we made a movie and um you know i was like all right this is an opportunity to
> maximize this medium because it's going to be pre-recorded it's going to be virtual and so i got my
> team involved um because obviously that's a team effort and i wrote the script um melissa fernandez
> our design lead she came up with like the visual treatment and you know the the other voices that
> are not me are our office manager nefekara aaron she also sings the song that begins the movie so
> you know we we just got the opportunity to use a bunch of like right and left brain thinking and
> make something that we're really proud of dude it was genius um just brilliant i'll put it in the
> the comments here in the description so that people could watch it um finally so i think you've kind
> of sort of made it public at least among your close friends um you're working on a book and you've
> pitched it um i don't want to speak out of line but maybe of course having having written a book
> sometimes titles change and stuff but you're probably looking at something around the science of seo
> so tell us more about this yeah so for everything that i've learned on the technical side especially
> more like the information retrieval side i think that's a lot there's a lot of value in that
> information for our community so i think that a lot of our seo books are more like just straight up
> marketing books and i don't think there's one really core technical seo book so that's what i want
> to create i want to create the book that talks about you know ir nlp api all this python stuff that
> people are doing and really x is kind of like the the seo bible for technical seo like kind of the
> same way that a lot of people think of the art of seo as like the main book that you want to read
> i'm thinking of it as like the companion book for when you really want to dive into the technical
> components of these things so um and i have no problem with making it public that i'm working on
> this i think it's actually will be of value to people that want to write books in the future because
> for me i've wanted to write this book for a long time i just didn't really know how to do it and so
> um you know i want to like be very public about the process so people can learn from it and it also
> just kind of doubles as a way to create anticipation for the book too i have a sister podcast called
> the brightest minds like when you get further along what i'd like to do is is definitely the two of
> us but maybe we could even bring on one or two of our author friends and what we'll do is 30 to 45
> minutes and lay out the process and each of us could kind of talk about how we got it done um and
> and what were the rewards and and kind of the disappointments of of being and for you i know some of
> those things you'll learn once you do pick your publisher and you go to market um but i think that
> to your point you know to just help out other you know digital marketing professionals and others
> for me dude when i was you know a teenager and i was dreaming you know what do we dream about right
> i don't know maybe somebody wants to be an astronaut i'm like i'm i'm going to write a book one day
> and at that at that time it was it was one of those things where people are like yeah stay focused
> on your schooling you know do your thing and to think that in 2008 i i wrote the book uh seo visual
> blueprint went into three prints and sold over 100 000 copies like there's there's some economics
> that that that played out to that that i never expected uh among other things so let's deep dive on
> that in a future podcast but mike dude this has been awesome uh i think that forget me and how i
> enjoyed it i just know folks are going to eat this up and watch it and be inspired man thank you so
> much for your time man your brother i love you if there's anything i could do to support your
> continued success and you don't need it but i'll be here man to be your champion and to be your
> cheerleader dude because i really have mad respect for you and uh you're one of the smartest guys
> i've ever met in that artistry side man you remind me you remind me of some of the people and you
> you know some of the influencers that i've met who've who've achieved high levels of success in the
> in the entertainment industry um dude you're i can't wait to just watch your career over these next
> five to ten years man you're gonna you're gonna exceed all your expectations so congrats on your
> success up to this point thanks for damn near almost an hour of your time today um have an awesome
> day man i pull rank rocks and everything you're doing rock so thanks mike thanks chris i really
> appreciate you thanks for having me all right take care [Music] [Applause] [Music] [Applause]
> [Music] [Music] you

---

## Research Notes

- **Personal observations:** Mike's ability to combine creative vision with technical execution (C++, PHP) sets the foundation for his advanced programmatic SEO strategies.
- **Related concepts:** Natural Language Generation (NLG), Transformer technology (BERT/GPT), Information Retrieval (IR), Entity Mapping, TF-IDF.
- **Ideas worth investigating further:** 
  1. How to build an automated internal linking system using edit distance for matching keywords to text. 
  2. Setting up a pipeline for generating programmatic category page content using modern LLMs based on his NLG concepts.
