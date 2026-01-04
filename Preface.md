# Preface
If you’re browsing a bookstore and trying to make sense of this book, try this:
Python is one of the most widely used programming languages in the
world. It’s part of nearly every role that computers play in our lives, and
its relative ease of use makes it an ideal way to get started with
programming.

This book is a tutorial that teaches Python language fundamentals in
depth. Its content is aimed at Python newcomers of all stripes, applies to
every role that Python plays, and is based on decades of feedback from
real learners like you.

This edition updates this book for a decade of changes in Python and its
world. It drops coverage of the now-defunct Python 2.X, explores new
tools added to Python through version 3.12, and applies to other
Pythons past and future.

The rest of this preface provides more background info on this book and its
subject. It explains what’s changed since the prior edition, debuts the book’s
examples package, and may help you get oriented before jumping into details.

### Python

By most metrics you’ll find on the web today, Python is now either the mostused
programming language on the planet or very near the top of the list. The
oft-cited TIOBE popularity index, for example, has ranked Python most popular
for several years. As this edition is being written in 2024, it lists Python at #1
and well ahead of its nearest followers, C, C++, and Java.

Popularity ranks are prone to change, of course, and rely on usage metrics that
are open to debate that we’ll skip here. Based on every signal available, though,
the Python revolution has clearly happened. It’s now a ubiquitous, go-to
language in web development, scientific programming, systems administration,
AI, and nearly everything else computers do today. Thanks to its relative
simplicity, Python is also commonly used to introduce newcomers to computer
science across the education spectrum.

In fact, it’s now fairly safe to say that Python played a pivotal role in changing
the world. By spearheading a shift from statically typed compiled languages to
dynamically typed scripting languages, Python ushered in changes that were at
least as profound as those of the earlier transition from machine language to
compiled languages. The scripting-language shift both enabled tasks formerly
impractical, and opened the field to nonprofessional contributors. In the process,
it propelled computers to a prominence that would have been unthinkable in
decades past. The internet, for example, simply could not be what it is today
without tools like Python. For better and worse, Python enables the new.

Lofty goals aside, all of this has two tangible implications for this book. First,
because this is now a post-revolution Python world, this edition does much less
cheerleading than its predecessors. There’s no reason to waste your time
promoting a tool that’s already arrived. This edition still summarizes Python’s
value proposition in Chapter 1, but the domains and tools that you’re likely to
explore after learning the basics here are readily available on the web and
change too regularly to cover in a fundamentals book like this in any event.
Second, Python’s popularity means that by reading this book, you’ll be adding a
valuable skill to your toolset, which will help you in a wide variety of computersoftware
tasks. Learning Python will both make entire domains accessible to you
and enable you to achieve programming goals that might otherwise be difficult
or impossible. Python users now enjoy a wealth of prior art ready to be
leveraged in a language that accelerates their work.

That said, Python isn’t the only game out there, and you’d also be well served by
learning computer science from the ground up—the full stack in developer
speak. Studying lower-level languages like C and Java, for example, can still
give you a much more complete perspective than scripting languages alone and
help you solve complex problems as they arise. Python itself, after all, is just a C
program in its most-used flavor.

Even so, Python is a great place to start, and enough for many a task. While it’s
not without warts and suffers from the thrashing that’s endemic to software
today, a multitude of developers still find Python a lot more fun to use than other
tools. Java and C++, for example, seem languages designed for middle
management: they hobble programmers with training wheels and bureaucratic
hurdles that have little to do with your program’s goals. Python, in sharp
contrast, remains more ally than obstacle. That viewpoint is naturally subjective,
but you’ve come to the right place to do the math on this yourself.

### This Book

This book is a tutorial on the Python language and a classic in its domain. It’s the
product of three decades spent using, promoting, and teaching Python, and dates
back to the mid-1990s, when Python was still at version 1.X, and the web was
just something developers mused about over lunch. Although the focus here is
firmly on the present, that legacy naturally adds some historical context that will
help you understand Python more deeply. Despite what you may have heard, the
past matters, especially in knowledge-based fields.

Just as importantly, this book has always been based on live-and-in-person
feedback from Python beginners struggling to learn Python for the first time.
This feedback mostly owes to Python training classes taught over a period of
two decades. While these classes have now gone the way of the dodo and Yahoo,
this book takes care to retain its learner-inspired material because that’s much—
if not most—of its value.

As a result, if you’re like most of the thousands of learners whose experiences
have been captured here, you’ll probably find that this book works like a selfpaced
version of the Python training sessions from which it arose. You may
sometimes even find that it answers your questions before they are asked
because a host of learners before you have had the same queries. This isn’t
clairvoyance; it simply reflects the fact that learning resources do best when they
listen to learners.

It’s also worth noting up front that this book sometimes critiques Python changes
while presenting them. Critical thinking is crucial in engineering domains—
especially in one caught up in an arms race that convolutes tools used by
millions of people. On some levels, Python remains a constantly morphing
sandbox of ideas that too often prioritizes changer hubris over user need, and this
book is not shy about calling this out. That said, the main goal here is to educate,
not criticize, and opinions are always, well, opinionated. Although views here
reflect decades of using and teaching Python, you should always judge the net
worth of Python changes for yourself in whatever world you’ve been cast.

### This Edition

This edition completely drops coverage of Python 2.X, the earlier version of the
language, and adds new coverage of recent changes in Python 3.X, the newer and
incompatible version. When the prior edition was published in 2013, Python 2.X
was still widely used and probably even dominant. Because of that, the prior
edition had to cover both the established 2.X and the new and upcoming 3.X,
which at times made for a twisted tale indeed.

Over a decade later, 2.X has been officially sunsetted, and the Python world has
adopted 3.X so fully that 2.X constitutes an unwarranted distraction to today’s
Python learners. Hence, after a decades-long tenure, 2.X-specific content has
been cut here to make room for new 3.X topics and address book size in general.
Formally, this edition has been updated to be current with Python 3.12 and its
era, though it also previews 3.13 mods, and its focus on fundamentals makes it
generally applicable to both older and newer Python versions.

Before the emails start flooding in, this book wants to make clear that it regrets
the loss of historical context (and secretly pines for the simpler days of 2.X too).
But 3.X is a substantial topic all by itself, without bifurcating the story and
increasing the page count for a Python version that is now little used. So go well
into that good Python night, 2.X, and long live 3.X. Unless stated otherwise,
“Python” in this edition simply means the 3.X line in general and 3.12 and later
in particular.

In terms of 3.X mods, this edition newly covers f'…' f-string literals, := namedassignment
expressions, match statements, type hinting, async coroutines, starunpacking
proliferation, underscore digit separators, __main__.py package files,
__getattr__ module hooks, except* exception groups, dictionary-key
insertion order, positional-only function arguments, hash-based bytecode files,
and other additions, deprecations, and mutations that have cropped up over the
last decade plus.

Among these, type hinting and async coroutines are not covered in depth—by
design. The former is an optional and academic tool wholly unused by Python
itself and at odds with its core principles. The latter is an advanced applications
tool and has morphed constantly since its inception. And both quickly head over
complexity cliffs that push them out of scope for Python beginners. When
needed, supplemental info on such narrow topics is always just a search away on
the web. Here, the goal is learning to walk well before trying to run.

Among other noteworthy changes this time around:

The Unicode content in the advanced part’s Chapter 37 is new and
improved because this topic is now an essential in Python 3.X and the
world at large.

Usage coverage, including the new Appendix A, gives more focus to
macOS, Android, Linux, and iOS because not all of this book’s readers
use Windows.

Most code-file examples now have numbered captions because the
extra formality distinguishes them better in the book, and it’s worth the
space.

Some redundancy has been trimmed, but not all, because repetition is
useful and even important in learning resources.

The size of this book was reduced by the prior bullet, rewrites and flow
mods, and the net of 2.X cuts and 3.X inserts because it’s less to grok.

The size of the print version of this book was further reduced by
moving two advanced but optional chapters online (Chapters 38 and 39)
because it’s less to lug.

Fictitious names in examples are more gender neutral: “Bob” is now an
ambiguous “Pat” unless paired with “Sue” as before because it better
defuses bias.

The Monty Python references have been dropped because they can be
confusing and might be divisive, and borrowing personality from media
seems cheap.

Both first-person voice and personal anecdotes have been globally
sacked because you’ve bought this book to learn Python, not an author’s
life story.

About the last two: Python’s namesake was funny stuff, to be sure, but
compulsively aping the work of a nearly all-male comedy group can seem like
the secret handshake of an exclusive boys’ club in hindsight. And while an
occasional “I” or “my” might add color or credibility, overuse tends to come off
as narcissism. Hence, the former 1k “spam” are now symbols more inclusive,
and this book’s three-decade tenure will have to speak for itself.

Despite all the mods, this edition remains much more technical novel than
reference manual, and meaty enough to be comparable to a full-semester class
on Python and programming. It introduces topics and expands them in later
chapters as recurring themes, accumulating comprehensive coverage along the
way. There are Python quick-reference resources at python.org and a multitude
of blogs and videos that promise to teach Python rapidly. This book is for those
who know that learning something well requires a bit more.

### Media Choices

As of this writing, this book is destined to be available in three forms: print (i.e.,
paper), ebook (e.g., PDF, ePub, and Kindle), and online (a.k.a. web). The latter
means the publisher’s subscription service, currently branded as the O’Reilly
learning platform (f.k.a. Safari). Naturally, each medium has valid uses that vary
per reader. For instance, many prefer print for linear reads and electronic media
for random searches and code copy/paste.

You’re welcome to use the forms that work best for you, of course, but should
carefully weigh the inherent privacy trade-offs of online media. By now, it
should be abundantly clear that online anything comes with a potential for covert
use and sale of customer information and access, which print and ebook media
largely avoid. While monetization schemes vary, online users just might have a
legion of salespeople peering over their shoulders as they use products for which
they’ve already paid in full.

So please be careful out there. Unless you must use an employer’s online
subscription, this book suggests vetting your media options wisely and generally
recommends its print and ebook forms to protect your privacy whenever
possible. Your life really shouldn’t be turned into a revenue stream unless you
get reimbursed for it.

One last media tip: this book may also be fed by its publisher into generative AI
models, the current hot topic in the tech press. Although this may prove useful
for looking up isolated facts, it’s not deep learning and isn’t necessarily any
more reliable than the least of the gossip it regurgitates. Until the world figures
this out, please use wisely.

### Updates and Examples

As most authors would attest, it’s shockingly easy to miss typos in material
you’ve read hundreds of times, and incompatible change is a norm in computer
book topics. Hence, this edition, like all its predecessors, expects to be updated
regularly after its publication.

This book’s supplements, example files, and clarifications and corrections (a.k.a.
errata) will all be maintained on the web. Here are the main coordinates for these
online resources; as usual, consult your local search engine if these change over
time:

### Author website
This site will be used to post general notes and updates related to this text or
Python itself—a hedge against future changes and a sort of virtual appendix
to this book.

### Book examples
This site will host this book’s examples package, with both individual files to
view and save online and a ZIP file of all the examples to download to your
device.

### Publisher website
This site will maintain this edition’s errata list, and chronicle patches applied
to the text in reprints. It will also link to other formats, including ebooks.
The second of these is home to the examples’ source code. Please see the usage
notes there, as well as the examples’ coverage in “Where to Run: Code Folders”.
There is no plan to host the examples on GitHub today, because that site’s
learning curve is a lot to ask of beginners, and its commercial agendas should be
cause for concern.

At any of the preceding websites, all error reports and suggestions for this book
are welcome, and this feedback is invaluable for book quality. But please keep it
fact-based and civil. Posts on the errata list have been mostly constructive, but
the list has limited utility, and has been known to attract the usual trolls. Such is
life in the age of global conversation.

### Conventions and Reuse
This book’s mechanics will make more sense once you start reading it, but as a
reference, this book uses the following typographical conventions:

Italic
Used for email addresses, URLs, filenames, pathnames, and emphasizing
new terms when they are first introduced

Constant width
Used for program code, the contents of files and the output from commands,
and to designate modules, methods, statements, and system commands

Constant width bold
Used in code sections to show commands or text that would be typed by the
user, and, occasionally, to highlight portions of code

Constant width italic
Used for replaceables (content you must fill in) and some comments in code
sections

### NOTE
This element indicates a tip, suggestion, or general note relating to the nearby text. The icon
may make more sense if you imagine a crow sounding an alarm.
Three more quick content notes here: first, you’ll find occasional sidebars
(delimited by boxes) and footnotes throughout, which are often optional reading
but provide additional context on the topics being presented. For instance, the
sidebars that begin with “Why You Will Care:” amplify language topics with
real-world use cases.

Second, Python error messages are often shortened in this book to conserve
space. Please run offending code on your own device for the full text. Some
messages include stack traces, and some have sprouted location indicators and
speculative “Did you..?” help in the latest Python that might be useful for
beginners, though veterans’ mileage may vary; either way, the extra text is
excessive in a book tight on space.

Finally, the publisher maintains a standard statement about reusing code in this
book, though the short, interactive code snippets used broadly here are hardly
worth the legalese. Please see the book websites described earlier for the formal
reuse story if you must care.

### Acknowledgments
In keeping with the depersonalization goal discussed earlier, this edition will
forego the usual lengthy acknowledgments of its predecessors. Instead, it
extends simple gratitude to the scores of former students and readers, who
largely shaped this book; the publishing company, which enabled this book to
both reach learners and improve with time; the host of users, contributors, and
promoters, who made Python what it is today; and the subject of this book’s
dedication page, who patiently tolerated yet another book project. This one
might be the last, but you never know what a bored author might next do.
