# Awesome Bugs [![Status?](https://img.shields.io/badge/butt%20mangler-aardvark-ff60b4.svg)](http://files.samhart.net/humor/angry_angry.gif)

> An opinionated list of truly awesome bugs

I am easily amused. Since the dawn of time, circa
[4000 years ago](http://flyingspaghettimonster.wikia.com/wiki/Pastafarianism),
I've been collecting and bookmarking bugs which I find awesome. At some point,
it's not entirely clear when, I was inspired by
[@sindresorhus](https://github.com/sindresorhus)'s 
[awesome](https://github.com/sindresorhus/awesome), and the glut of awesome
lists, to collect these bugs in their own awesome list (because that's what
the world needs, more curated lists.) This is that.

*UNFUNNY WARNING:* DO NOT COMMENT ON OR MESS WITH ANY OF THESE BUGS! Seriously,
this list should be considered READ-ONLY. Do not use this list to troll or
harass the nice people making software. Everything here is included because
*I* found it funny. This isn't, by any means, an encouragement for action
(even in those cases where I editorialize). Seriously... read for the laughs,
but leave the parties involved alone!

## Table of Contwebs

- [FAQ](FAQ.md)
- [PEBKAC](#pebkac)
- [Patches, PRs and Code Snippets](#patches-prs-and-code-snippets)
- [Code Gone Wild](#code-gone-wild)
- [Data Insanity](#data-insanity)
- [Something Else](#something-else)

Yeah, maybe once I find a way to organize this that makes sense...

## PEBKAC

* [xscreensaver: Fake crash screensaver should not be enabled by default](https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=553529)

   [xscreensaver](https://www.jwz.org/xscreensaver/) is awesome, and jwz is a God.
   This collection of screensavers includes several that simulate various
   computer crash screens. They are the best screensavers, scientifically
   speaking, but that doesn't prevent people from being confused by them. It
   also has one of the best original author smackdowns in history.

* [apt-get moo doesn't look like a cow](https://bugs.launchpad.net/ubuntu/+source/apt/+bug/56125)

   Answering the age-old question: How many engineers does it take to change an ASCII cow?

   Also answering the age-old question: How many years does it take to change an ASCII cow?

   Nine. the answer to the second question is apparently *nine*.

* [Dwarf Fortress starting during apt-get upgrade](https://askubuntu.com/questions/938606/dwarf-fortress-starting-during-apt-get-upgrade)

    Only you can prevent name collisions.

## Patches, PRs and Code Snippets

* [Add internal state field to irq_desc](http://www.spinics.net/lists/linux-tip-commits/msg11099.html)

   For when you really need people to stay off your lawn.

* [0xB16B00B5? Really?](https://lkml.org/lkml/2012/7/13/154)

   If you're not getting it, then check the [punchline](https://lkml.org/lkml/2012/7/13/209).

* [Re: RFC page-table walkers vs memory order](https://lwn.net/Articles/509149/)

   Leading underscores are also how I increase entropy on my single-character passwords.

## Code Gone Wild

* [Insulting source code](https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=477454)

   Why don't you tell us how you *really* feel?

* [gethostbyname() etc break for /etc/hosts with both ::1 and 127.0.0.1 localhost entries](https://sourceware.org/bugzilla/show_bug.cgi?id=4980)

   The definite argument for granting developers the ability to permanently
   shut down and close bugs in their issue tracking systems.

* ["quodlibet" package is useless](https://bugs.gentoo.org/show_bug.cgi?id=124595)

* [SHOW TABLES removes tables from Cluster](https://bugs.mysql.com/bug.php?id=40854)

## Data Insanity

* [Critical bug Skype 7.4.85.102: simple message crush client](https://community.skype.com/t5/Windows-archive/Critical-bug-Skype-7-4-85-102-simple-message-crush-client/td-p/3996419) |
[Alternate link to article, since bug post may be gone for good](https://venturebeat.com/2015/06/02/these-8-characters-crash-skype-and-once-theyre-in-your-chat-history-the-app-cant-start/)

   http://: will undoubtedly grow up to marry Bobby Tables.

* [Outage Postmortem - July 20, 2016](http://stackstatus.net/post/147710624694/outage-postmortem-july-20-2016)

   All joking aside, this was a *fascinating* postmortem on a truly devious
   little bug. Amazing how the tiniest bits of regexp can bring a major
   website to its knees.

* [GitLab.com melts down after wrong directory deleted, backups fail](https://www.theregister.co.uk/2017/02/01/gitlab_data_loss/) | [Incident report](https://about.gitlab.com/2017/02/01/gitlab-dot-com-database-incident/)

   rm -rf is not your friend.

## Something Else

* [number_format when passed a 0 as first function argument, returns null](https://bugs.php.net/bug.php?id=50696)

   PHP is a [delightful](http://phpsadness.com/sad/52) and [well-loved](https://www.google.com/search?q=php+sucks)
   language and, as shown by this bug, has both brilliant practitioners and careful
   developers who would never introduce API changing bugs.

* [User-triggerable NULL pointer dereference due to utter plebbery](https://jira.mongodb.org/browse/PYTHON-532)

   Jibbers McGee is the hero the internet needs.

* [A glitch on Netflix caused some BBC nature show to get Aziz Ansari subtitles](https://www.reddit.com/r/funny/comments/4vv5f6/a_glitch_on_netflix_caused_some_bbc_nature_show/)

   And that goose was never seen again...

* [Physical security let down by deliberate backdoor](https://www.amazon.com/review/R1OPKA227Q6P5)

   Gotta love the response from the maker of the lock. Because, as we all know,
   only PhDs in computer science can write trivial scripts.

* [Re: Bug#843021: RFP: yarn -- a fast, reliable, and secure package manager for Node.js](https://lists.debian.org/debian-devel/2016/11/msg00103.html)

   What I love about this is the hubris of the upstream developer in their glib
   response to the bug. Upstream does apparently *zero* research to see if there
   was a namespace collision, picked a simple name for what could be a major
   project, and then blinkardly refuses to adopt a more general name when
   its pointed out that *a)* the name is for something older and already
   established and *b)* one of the biggest and most widely used Linux distros
   on the planet has a problem with the name (and has a simple solution).
   Gotta love millennial developers who think they are so GODDAMNED smarter
   than the rest of us.... But I'm not bitter. Also, Javascript developers, AMMIRITE?

* [Using OCR To Fix a Hilarious Bug](http://artsy.github.io/blog/2015/11/04/Using-OCR-To-Fix-A-Hilarious-Bug/)

* [The case of the 500-mile email](https://www.ibiblio.org/harris/500milemail.html)

* [Players Try Bringing Missingno Into Pokémon Sun and Moon, Get A Glitch Instead](http://kotaku.com/players-try-bringing-missingno-into-pokemon-sun-and-moo-1791621674)

   Missingo was a Pokemon caused by a glitch in an older Pokemon game. New
   Pokemon game comes out and lets you pull in your pocket monsters from past
   games. People try to pull in old glitched perckit mernster, get suprise of
   new glitches breaking the new game in new and exciting ways.

* [Bug #16925 for File-Remote: check of OS is invalid](https://rt.cpan.org/Public/Bug/Display.html?ShowHeaders=1;id=16925)

   Snarky comebacks in bug reports are like fine cheese, best when aged, left
   in a corner, and forgotten for five years.
