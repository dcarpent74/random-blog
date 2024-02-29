# Thoughts on Complexity and Simplification

I attended the first [Bleeding Edge Web meetup](https://edgeatx.org) here in
Austin.  It was the first in a long time, but exemplary of how great Austin
meetups can be.  I would love to see a recording show up somewhere...  I am
pretty sure it was Zoom recorded, so I still have some hope, but as of yet, I am
not sure where I would find it if it does get posted.  However, they do have
slides for this one [here](https://www.edgeatx.org/slides/) under February
2024.  The slides of interest here, however take just a little bit more work.
They are embedded in
[this GitHub repository](https://github.com/tedpatrick/htmx-talk) which is not
just simply slides, but the subject of the presentation.  Thus you can follow
the instructions on this repository and launch a web server to see the slides,
which are an [HTMX](https://htmx.org/) example.

I found this very interesting despite not being a front-end developer. I usually
tell people "front-end to me is back-end to you."  That is to say that my
development experience is more about system software, middleware and such.  The
closest thing to front-end that I do is either writing command-line utilities
for developers or IT admins, or playing with things like
[TiddlyWiki](https://tiddlywiki.com) in an attempt to make more magical
documentation. What is really missing without the video of this presentation,
however, is the guided tour and commentary that Ted gave while demonstrating
HTMX to us.

To capture the basics of what was conveyed here, lets just put things this way.
First HTMX looks to be just dead simple. Ted commented, "after about an hour
your average 13-year-old could be dangerously productive." I pretty much know
some basic HTML from the old days. Add several decades of general hacking in
lots of different languages (I dabbled in customized open source builds and
spent a decade of being a production build engineer that had to, among other
things, often determine if build breaks were a problem in our build environment
or something introduced by a development team). And I've done just enough
JavaScript hacking and playing with TiddlyWiki to be mildly dangerous but
definitely not respectable.

I looked at all of this and felt like I was transported back to the old pre-web
HyperCard days. Lots of promise, and a bunch of crazy things that were just
simple to do, but now instead of being trapped in this little Mac based
application, this could be added to a modern web server and with some other
basic web skills turned into a powerful yet simple way to produce web content
that seemed only accessible to those who live among all of the JavaScript
frameworks I have avoided my whole career (TiddlyWiki being the primary
exception, but here I think of myself as the analogue of a junior user-space
programmer in a world built by the kernel developers).

However, being a long enough regular attender of this meetup (I joined and kept
coming because I could tell this was a successfully run meetup, and as a junior
meetup organizer myself, I stayed to learn those organizing skills), it was also
clear to me the demonstration of how much HTMX promises to reduce front-end code
bases.  Add a couple attributes to your HTML, write your back-end to feed little
snippets of partial HTML, and you have just replaced a whole pile of compiled
JavaScript framework code... Awesome!

Anyway, a couple days later I run into this gem of a talk called
[Quit Simplifying](https://www.youtube.com/watch?v=lchJi2B_DlE) by Florian Haas.
Slides for that are [here](https://fghaas.github.io/quit-simplifying/) and it
also importantly refers to this blog post by Mike Hadlow called
[The Configuration Complexity Clock]
(http://mikehadlow.blogspot.com/2012/05/configuration-complexity-clock.html)
As I listened to this, I thought about Ted's talk, and a bunch of other things.
I also though about AI, which is also is something Ted is also engaged with at
the moment.

I suppose I can also throw in
[this other talk]
(https://www.destroyallsoftware.com/talks/the-birth-and-death-of-javascript)
as well, which seems to me to be somewhat relevant to all of this.  These other
two talks were shared in a thread in the #_hangops channel of the hangops Slack
(introduced to me by the
[Austin DevOps meetup](https://www.meetup.com/austin-devops/)
community) where people were sharing some of their favorite conference talks.


