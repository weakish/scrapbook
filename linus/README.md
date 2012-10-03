Interviews with Linus
=====================

This is my own digest,
subject to my own taste.

Small and silent machines
-------------------------

Scott Merrill interviewed Linus Torvalds (published on [Thursday, April 19th, 2012][merrill]),
in which Linus talks about the reason he uses a 11-inch MacBook Air:
because he prefers small and silent machines, be it laptop or desktop.
Although Linus is not an apple fan,
since he think they've done some really bad things too,
Apple's guts of focusing on consistently trying to revolutionize the world
did impressed him.

[merrill]: http://techcrunch.com/2012/04/19/an-interview-with-millenium-technology-prize-finalist-linus-torvalds

Also, Linus found the Raspberry PI concept interesting,
for taking advantage of how technology gets cheaper
to really push the price down to the point where it’s
really cheap. 

It is the journey that matters
------------------------------

When asked if he wanted to answer some question which had not been asked by interviewers,
Linus sad no, and emphasis it is **process** that matters.

> But any particular question? No. That’s not what I tend to find
> interesting – I enjoy the process, and the argument, and the flow
> of ideas of an interview, I don’t think there’s a “perfect
> question”, much less a “perfect answer that I wish somebody had
> asked me the question for”. So you’re not asking for something that
> I think I have.
> 
> But to expand on that, and to perhaps give you something of an
> answer anyway: this is very much true for me in software
> development too. I like the *process*. I like writing software. I
> like trying to make things work better. In many ways, the end
> result is unimportant – it’s really just the excuse for the whole
> experience. It’s why I started Linux to begin with – sure, I kind
> of needed an OS, but I needed a *project* to work on more than I
> needed the OS.
> 
> In fact, to get a bit “meta” on this issue, what’s even more
> interesting than improving a piece of software, is to improve the
> *way* we write and improve software. Changing the process of
> making software has sometimes been some of the most painful parts
> of software development (because we so easily get used to certain
> models), but that has also often been the most rewarding parts. It
> is, after all, why “git” came to be, for example. And I think open
> source in general is obviously just another “process model” change
> that I think is very successful.
> 
> So my model is kind of a reverse “end result justifies the means”.
> Hell no, that’s the stupidest saying in the history of man, and I’m
> not even saying that because it has been used to make excuses for
> bad behavior. No, it’s the worst possible kind of saying because it
> totally misses the point of everything.
> 
> It’s simply not the end that matters at all. It’s the means – the
> journey. The end result is almost meaningless. If you do things the
> right way, the end result *will* be fine too, but the real
> enjoyment is in the doing, not in the result.
> 
> And I’m still really happy to be “doing” 20 years later, with not
> an end in sight.


Two way trust in development
----------------------------

Regarding to kernel development,
Linus pointed out that they have a very strict “no regressions” rule
to try to make it as painless as possible for people to upgrade smoothly,
which encourages people to upgrade instead of staying back.

And Linus think it's still fairly easy to get involved in kernel development,
if not starting in a central place.

Linus explained the network of trust model of kernel development:

> The whole model is built on a network of trust among developers
> that have come to know each other over the years. There’s no way I
> can test all the platforms we support – the same way there is no
> way I can check every single commit that gets merged through me.
> And I wouldn’t even really even *want* to check each hardware or
> each change – the point of open source and distributed development
> is that you do things together. We have a few tens of “highlevel”
> maintainers for various subsystems (eg networking, USB drivers,
> graphics, particular hardware architectures etc etc), and even
> those maintainers can’t test everything in their area, because they
> won’t have that particular hardware etc. I trust them, and they in
> turn trust the people they work with.
> 
> I think any big project is about finding people you can trust, and
> really then depending on that trust. I don’t *want* to
> micro-manage people, and I couldn’t afford to even if I did want
> to.
> 
> And the thing is, smart people (and people who have what I call
> “good taste”, which is often even more important) may be rare, but
> you do recognize them. I think one of my biggest successes is
> actually outside Linux: recognizing how good a developer Junio
> Hamano was on git, and trusting him enough to just ask if he would
> be willing to maintain the project. Being able to let go and
> trusting somebody else is *important*, because without that kind
> of trust you can’t get big projects done.


In another interview with [BBC][], Linus added that trust is a two-way street.
And that is the reason why Linus did not want to ever work for a commercial Linux company:

[BBC]: http://www.bbc.co.uk/news/technology-18419231


> I simply do not want people to have even the appearance of bias - I
> want people to be able to trust that I'm impartial not only because
> they've seen me maintain the kernel over the years, but because
> they know that I simply don't have any incentives where I might
> want to support one Linux company over another.
> 
> These days, I do work full-time on Linux, and I'm paid to do it,
> but that didn't happen until I felt comfortable that there was a
> way that could be pretty obviously neutral, through a industry
> non-profit that doesn't really sell Linux itself.
> 
> And even then, in order to allay all fears, we actually made sure
> that my contract explicitly says that my employment does not mean
> that the Linux Foundation can tell me what to do.


Open source and selfishness
---------------------------

In the BBC interview, Linus also gave his opinions of open source,
to allow everybody to be "selfish":


> In many ways, I actually think the real idea of open source is for
> it to allow everybody to be "selfish", not about trying to get
> everybody to contribute to some common good.
> 
> In other words, I do not see open source as some big goody-goody
> "let's all sing kumbaya around the campfire and make the world a
> better place". No, open source only really works if everybody is
> contributing for their own selfish reasons.
> 
> Now, those selfish reasons by no means need to be about "financial
> reward", though.
> 
> The early "selfish" reasons to do Linux tended to be centred about
> just the pleasure of tinkering. That was why I did it - programming
> was my hobby - passion, really - and learning how to control the
> hardware was my own selfish goal. And it turned out that I was not
> all that alone in that.
> 
> Big universities with computer science departments had people who
> were interested in the same kinds of things.
> 
> And most people like that may not be crazy enough to start writing
> their own operating system from scratch, but there were certainly
> people around who found this kind of tinkering with hardware
> interesting, and who were interested enough to start playing around
> with the system and making suggestions on improvements, and
> eventually even making those improvements themselves and sending
> them back to me.
> 
> And the copyright protected those kinds of people. If you're a
> person who is interested in operating systems, and you see this
> project that does this, you don't want to get involved if you feel
> like your contributions would be somehow "taken advantage of", but
> with the GPLv2 [licence], that simply was never an issue.
> 
> The fundamental property of the GPLv2 is a very simple
> "tit-for-tat" model: I'll give you my improvements, if you promise
> to give your improvements back.
> 
> It's a fundamentally fair licence, and you don't have to worry
> about somebody else then coming along and taking advantage of your
> work.
> 
> And the thing that then seemed to surprise people, is that that
> notion of "fairness" actually scales very well.
> 
> Sure, a lot of companies were initially fairly leery about a
> licence that they weren't all that used to, and sometimes doubly so
> because some portions of the free software camp had been very
> vocally anti-commercial and expected companies to overnight turn
> everything into free software.
> 
> But really, the whole "tit-for-tat" model isn't just fair on an
> individual scale, it's fair on a company scale, and it's fair on a
> global scale.
> 
> Once people and companies got over their hang-ups - renaming it
> "open source" and just making it clear that this was not some kind
> of anti-commercial endeavour definitely helped - things just kind
> of exploded.
> 
> And the thing is, if your competition doesn't put in the same kind
> of effort that you do, then they can't reap the same kinds of
> rewards you can: if they don't contribute, they don't get to
> control the direction of the project, and they won't have the same
> kind of knowledge and understanding of it that you do.
> 
> So there really are big advantages to being actively involved - you
> can't just coast along on somebody else's work.


Of course what Linus has said only applies to copyleft style licences like GPL,
not MIT style licences.


More on Raspberry Pi
--------------------

As for the desktop market, Linus said in consumer market,
'you really do need to be pre-installed'.

Well, Raspberry Pi is sort of desktop.
Linus thinks throw-away cheap computers will help reaching a few kids
you wouldn't otherwise have reached.


> So I personally come from a "tinkering with computers" background,
> and yes, as a result I find things like Raspberry Pi to be an
> important thing: trying to make it possible for a wider group of
> people to tinker with computers and just playing around.
> 
> And making the computers cheap enough that you really can not only
> afford the hardware at a big scale, but perhaps more important,
> also "afford failure".
> 
> By that I mean that I suspect a lot of them will go to kids who
> play with them a bit, but then decide that they just can't care.
> 
> But that's OK. If it's cheap enough, you can afford to have a lot
> of "don't cares" if then every once in a while you end up
> triggering even a fairly rare "do care" case.
> 
> So I actually think that if you make these kinds of platforms cheap
> enough - really "throw-away cheap" in a sense - the fact that you
> can be wasteful can be a good thing, if it means that you will
> reach a few kids you wouldn't otherwise have reached.
