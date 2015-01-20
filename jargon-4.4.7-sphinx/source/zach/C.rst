===
C
===


calculator
===========






**Camel Book**: n.

Universally recognized nickname for the book *Programming Perl*, by
Larry Wall and Randal L. Schwartz, O'Reilly and Associates 1991, ISBN
0-937175-64-1 (second edition 1996, ISBN 1-56592-149-6; third edition
2000, 0-596-00027-8, adding as authors Tom Christiansen and Jon Orwant
but dropping Randal Schwartz). The definitive reference on
Perl







**camelCase**

A variable in a programming language is sait to be camelCased when all
words but the first are capitalized. This practice contrasts with the C
tradition of either running syllables together or marking syllable
breaks with underscores; thus, where a C programmer would write
thisverylongname or this\_very\_long\_name, the camelCased version would
be thisVeryLongName. This practice is common in certain language
communities (formerly Pascal; today Java and Visual Basic) and tends to
be associated with object-oriented programming.

Compare `*BiCapitalization* but where
that practice is primarily associated with marketing, camelCasing is not
aimed at impressing anybody, and hackers consider it respectable.



**cancelbot**: /kan´sel·bot/

[Usenet: compound, cancel + robot]

1. Mythically, a `*robocanceller* 
2. In reality, most cancelbots are manually operated by being fed lists
of spam message IDs.


**Cancelmoose[tm]**: /kan´sel·moos/

[Usenet] The archetype and model of all good
`*spam* <../S/spam.html>`__-fighters. Once upon a time, the 'Moose would
send out spam-cancels and then post notice anonymously to
``news.admin.policy``, ``news.admin.misc``, and
``alt.current-events.net-abuse``. The 'Moose stepped to the fore on its
own initiative, at a time (mid-1994) when spam-cancels were irregular
and disorganized, and behaved altogether admirably — fair, even-handed,
and quick to respond to comments and criticism, all without
self-aggrandizement or martyrdom. Cancelmoose[tm] quickly gained
near-unanimous support from the readership of all three above-mentioned
groups.

Nobody knows who Cancelmoose[tm] really is, and there aren't even any
good rumors. However, the 'Moose now has an e-mail address
(``<moose@cm.org>``) and a web site
(`http://www.cm.org/ <http://www.cm.org/>`__.) By early 1995, others had
stepped into the spam-cancel business, and appeared to be comporting
themselves well, after the 'Moose's manner. The 'Moose has now gotten
out of the business, and is more interested in ending spam (and cancels)
entirely.



**candygrammar**: n.

A programming-language grammar that is mostly `*syntactic
sugar* <../S/syntactic-sugar.html>`__; the term is also a play on
‘candygram’. `*COBOL* <COBOL.html>`__, Apple's Hypertalk language, and a
lot of the so-called ‘4GL’ database languages share this property. The
usual intent of such designs is that they be as English-like as
possible, on the theory that they will then be easier for unskilled
people to program. This intention comes to grief on the reality that
syntax isn't what makes programming hard; it's the mental effort and
organization required to specify an algorithm precisely that costs. Thus
the invariable result is that ‘candygrammar’ languages are just as
difficult to program in as terser ones, and far more painful for the
experienced hacker.

[The overtones from the old Chevy Chase skit on Saturday Night Live
should not be overlooked. This was a *Jaws* parody. Someone lurking
outside an apartment door tries all kinds of bogus ways to get the
occupant to open up, while ominous music plays in the background. The
last attempt is a half-hearted “Candygram!” When the door is opened, a
shark bursts in and chomps the poor occupant. [There is a similar gag in
“Blazing Saddles” —ESR] There is a moral here for those attracted to
candygrammars. Note that, in many circles, pretty much the same ones who
remember Monty Python sketches, all it takes is the word “Candygram!”,
suitably timed, to get people rolling on the floor. — GLS]



**canonical**: adj.

[very common; historically, ‘according to religious law’] The usual or
standard state or manner of something. This word has a somewhat more
technical meaning in mathematics. Two formulas such as ``9 + x`` and
``x +    9`` are said to be equivalent because they mean the same thing,
but the second one is in canonical form because it is written in the
usual way, with the highest power of ``x`` first. Usually there are
fixed rules you can use to decide whether something is in canonical
form. The jargon meaning, a relaxation of the technical meaning,
acquired its present loading in computer-science culture largely through
its prominence in Alonzo Church's work in computation theory and
mathematical logic (see `*Knights of the Lambda
Calculus* <../K/Knights-of-the-Lambda-Calculus.html>`__). Compare
`*vanilla* <../V/vanilla.html>`__.

Non-technical academics do not use the adjective ‘canonical’ in any of
the senses defined above with any regularity; they do however use the
nouns canon and canonicity (not \*\*canonicalness or \*\*canonicality).
The canon of a given author is the complete body of authentic works by
that author (this usage is familiar to Sherlock Holmes fans as well as
to literary scholars). ‘\ *The* canon’ is the body of works in a given
field (e.g., works of literature, or of art, or of music) deemed
worthwhile for students to study and for scholars to investigate.

The word ‘canon’ has an interesting history. It derives ultimately from
the Greek *κανον* (akin to the English ‘cane’) referring to a reed.
Reeds were used for measurement, and in Latin and later Greek the word
‘canon’ meant a rule or a standard. The establishment of a canon of
scriptures within Christianity was meant to define a standard or a rule
for the religion. The above non-techspeak academic usages stem from this
instance of a defined and accepted body of work. Alongside this usage
was the promulgation of ‘canons’ (‘rules’) for the government of the
Catholic Church. The techspeak usages (“according to religious law”)
derive from this use of the Latin ‘canon’.

Hackers invest this term with a playfulness that makes an ironic
contrast with its historical meaning. A true story: One Bob Sjoberg, new
at the MIT AI Lab, expressed some annoyance at the incessant use of
jargon. Over his loud objections, GLS and RMS made a point of using as
much of it as possible in his presence, and eventually it began to sink
in. Finally, in one conversation, he used the word canonical in
jargon-like fashion without thinking. Steele: “Aha! We've finally got
you talking jargon too!” Stallman: “What did he say?” Steele: “Bob just
used ‘canonical’ in the canonical way.”

Of course, canonicality depends on context, but it is implicitly defined
as the way *hackers* normally expect things to be. Thus, a hacker may
claim with a straight face that ‘according to religious law’ is *not*
the canonical meaning of canonical.



**can't happen**

The traditional program comment for code executed under a condition that
should never be true, for example a file size computed as negative.
Often, such a condition being true indicates data corruption or a faulty
algorithm; it is almost always handled by emitting a fatal error message
and terminating or crashing, since there is little else that can be
done. Some case variant of “can't happen” is also often the text emitted
if the ‘impossible’ error actually happens! Although “can't happen”
events are genuinely infrequent in production code, programmers wise
enough to check for them habitually are often surprised at how
frequently they are triggered during development and how many headaches
checking for them turns out to head off. See also `*firewall
code* <../F/firewall-code.html>`__ (sense 2).


**careware**: /keir´weir/, n.

A variety of `*shareware* <../S/shareware.html>`__ for which either the
author suggests that some payment be made to a nominated charity or a
levy directed to charity is included on top of the distribution charge.
Syn.: `*charityware* <charityware.html>`__; compare
`*crippleware* <crippleware.html>`__, sense 2.


**cargo cult programming**: n.

A style of (incompetent) programming dominated by ritual inclusion of
code or program structures that serve no real purpose. A cargo cult
programmer will usually explain the extra code as a way of working
around some bug encountered in the past, but usually neither the bug nor
the reason the code apparently avoided the bug was ever fully understood
(compare `*shotgun debugging* <../S/shotgun-debugging.html>`__, `*voodoo
programming* <../V/voodoo-programming.html>`__).

The term ‘cargo cult’ is a reference to aboriginal religions that grew
up in the South Pacific after World War II. The practices of these cults
center on building elaborate mockups of airplanes and military style
landing strips in the hope of bringing the return of the god-like
airplanes that brought such marvelous cargo during the war. Hackish
usage probably derives from Richard Feynman's characterization of
certain practices as “cargo cult science” in his book *Surely You're
Joking, Mr. Feynman!* (W. W. Norton & Co, New York 1985, ISBN
0-393-01921-7).


**cascade**: n.

1. A huge volume of spurious error-message output produced by a compiler
with poor error recovery. Too frequently, one trivial syntax error (such
as a missing ‘)’ or ‘}’) throws the parser out of synch so that much of
the remaining program text is interpreted as garbaged or ill-formed.

2. A chain of Usenet followups, each adding some trivial variation or
riposte to the text of the previous one, all of which is reproduced in
the new message; an `*include war* <../I/include-war.html>`__ in which
the object is to create a sort of communal graffito.



**case and paste**: n.

[from ‘cut and paste’]

The addition of a new `*feature* <../F/feature.html>`__ to an existing
system by selecting the code from an existing feature and pasting it in
with minor changes. Common in telephony circles because most operations
in a telephone switch are selected using **case** statements. Leads to
`*software bloat* <../S/software-bloat.html>`__.

In some circles of EMACS users this is called ‘programming by Meta-W’,
because Meta-W is the EMACS command for copying a block of text to a
kill buffer in preparation to pasting it in elsewhere. The term is
condescending, implying that the programmer is acting mindlessly rather
than thinking carefully about what is required to integrate the code for
two similar cases.

At `*DEC* <../D/DEC.html>`__ (now HP), this is sometimes called
clone-and-hack coding.



**case mod**

[from ‘case modification’]

1. Originally a kind of hardware hack on a PC intended to support
`*overclocking* <../O/overclock.html>`__ (e.g. with cutouts for
oversized fans, or a freon-based or water-cooling system).

2. Nowadays, similar drastic surgery that's done just to make a machine
look nifty. The commonest case mods combine acrylic case windows with
LEDs to give the machine an eerie interior glow like a B-movie flying
saucer. More advanced forms of case modding involve building machines
into weird and unlikely shapes. The effect can be quite artistic, but
one of the unwritten rules is that the machine must continue to function
as a computer.


**casters-up mode**: n.

[IBM, prob. fr. slang belly up] Yet another synonym for ‘broken’ or
‘down’. Usually connotes a major failure. A system (hardware or
software) which is down may be already being restarted before the
failure is noticed, whereas one which is casters up is usually a good
excuse to take the rest of the day off (as long as you're not
responsible for fixing it).



**casting the runes**: n.

What a `*guru* <../G/guru.html>`__ does when you ask him or her to run a
particular program and type at it because it never works for anyone
else; esp. used when nobody can ever see what the guru is doing
different from what J. Random Luser does. Compare
`*incantation* <../I/incantation.html>`__,
`*runes* <../R/runes.html>`__, `*examining the
entrails* <../E/examining-the-entrails.html>`__; also see the AI koan
about Tom Knight in `Some AI Koans <../koans.html>`__ (in Appendix A).

A correspondent from England tells us that one of ICL's most talented
systems designers used to be called out occasionally to service machines
which the `*field circus* <../F/field-circus.html>`__ had given up on.
Since he knew the design inside out, he could often find faults simply
by listening to a quick outline of the symptoms. He used to play on this
by going to some site where the field circus had just spent the last two
weeks solid trying to find a fault, and spreading a diagram of the
system out on a table top. He'd then shake some chicken bones and cast
them over the diagram, peer at the bones intently for a minute, and then
tell them that a certain module needed replacing. The system would start
working again immediately upon the replacement.




**catatonic**: adj.

Describes a condition of suspended animation in which something is so
`*wedged* <../W/wedged.html>`__ or `*hung* <../H/hung.html>`__ that it
makes no response. If you are typing on a terminal and suddenly the
computer doesn't even echo the letters back to the screen as you type,
let alone do what you're asking it to do, then the computer is suffering
from catatonia (possibly because it has crashed). “There I was in the
middle of a winning game of `*nethack* <../N/nethack.html>`__ and it
went catatonic on me! Aaargh!” Compare `*buzz* <../B/buzz.html>`__.




**cathedral**: n.,adj.

[see `*bazaar* <../B/bazaar.html>`__ for derivation] The ‘classical’
mode of software engineering long thought to be necessarily implied by
`*Brooks's Law* <../B/Brookss-Law.html>`__. Features small teams, tight
project control, and long release intervals. This term came into use
after analysis of the Linux experience suggested there might be
something wrong (or at least incomplete) in the classical assumptions.



**cat**: vt.

[from catenate via `*Unix* <../U/Unix.html>`__ cat(1)]

1. [techspeak] To spew an entire file to the screen or some other output
sink without pause (syn. `*blast* <../B/blast.html>`__).

2. By extension, to dump large amounts of data at an unprepared target
or with no intention of browsing it carefully. Usage: considered silly.
Rare outside Unix sites. See also `*dd* <../D/dd.html>`__,
`*BLT* <../B/BLT.html>`__.

Among Unix fans, cat(1) is considered an excellent example of
user-interface design, because it delivers the file contents without
such verbosity as spacing or headers between the files, and because it
does not require the files to consist of lines of text, but works with
any sort of data.

Among Unix haters, cat(1) is considered the
`*canonical* <canonical.html>`__ example of *bad* user-interface design,
because of its woefully unobvious name. It is far more often used to
`*blast* <../B/blast.html>`__ a file to standard output than to
concatenate two files. The name **cat** for the former operation is just
as unintuitive as, say, LISP's `*cdr* <cdr.html>`__.

Of such oppositions are `*holy wars* <../H/holy-wars.html>`__ made....
See also `*UUOC* <../U/UUOC.html>`__.



**CDA**: /C·D·A/

The “Communications Decency Act”, passed as section 502 of a major
telecommunications reform bill on February 8th, 1996 (“Black Thursday”).
The CDA made it a federal crime in the USA to send a communication which
is “obscene, lewd, lascivious, filthy, or indecent, with intent to
annoy, abuse, threaten, or harass another person.” It also threatened
with imprisonment anyone who “knowingly” makes accessible to minors any
message that “describes, in terms patently offensive as measured by
contemporary community standards, sexual or excretory activities or
organs”.

While the CDA was sold as a measure to protect minors from the putative
evils of pornography, the repressive political aims of the bill were
laid bare by the Hyde amendment, which intended to outlaw discussion of
abortion on the Internet.

To say that this direct attack on First Amendment free-speech rights was
not well received on the Internet would be putting it mildly. A
firestorm of protest followed, including a February 29th 1996 mass
demonstration by thousands of netters who turned their `*home
page* <../H/home-page.html>`__\ s black for 48 hours. Several
civil-rights groups and computing/telecommunications companies mounted a
constitutional challenge. The CDA was demolished by a strongly-worded
decision handed down in 8th-circuit Federal court and subsequently
affirmed by the U.S. Supreme Court on 26 June 1997 (“White Thursday”).
See also `*Exon* <../E/Exon.html>`__.


**cdr**: /ku´dr/, /kuh´dr/, vt.

[from LISP] To skip past the first item from a list of things
(generalized from the LISP operation on binary tree structures, which
returns a list consisting of all but the first element of its argument).
In the form cdr down, to trace down a list of elements: “Shall we cdr
down the agenda?” Usage: silly. See also `*loop
through* <../L/loop-through.html>`__.

Historical note: The instruction format of the IBM 704 that hosted the
original LISP implementation featured two 15-bit fields called the
address and decrement parts. The term cdr was originally Contents of
Decrement part of Register. Similarly, car stood for Contents of Address
part of Register.

The cdr and car operations have since become bases for formation of
compound metaphors in non-LISP contexts. GLS recalls, for example, a
programming project in which strings were represented as linked lists;
the get-character and skip-character operations were of course called
CHAR and CHDR.



**cd tilde**: /C·D til·d@/, vi.

To go home. From the Unix C-shell and Korn-shell command **cd ~**, which
takes one to one's **$HOME** (**cd** with no arguments happens to do the
same thing). By extension, may be used with other arguments; thus, over
an electronic chat link, **cd ~coffee** would mean “I'm going to the
coffee machine.”



**chad box**: n.

A metal box about the size of a lunchbox (or in some models a large
wastebasket), for collecting the `*chad* <chad.html>`__ (sense 2) that
accumulated in `*Iron Age* <../I/Iron-Age.html>`__ card punches. You had
to open the covers of the card punch periodically and empty the chad
box. The `*bit bucket* <../B/bit-bucket.html>`__ was notionally the
equivalent device in the CPU enclosure, which was typically across the
room in another great gray-and-blue box.




**chad**: /chad/, n.

1. [common] The perforated edge strips on printer paper, after they have
been separated from the printed portion. Also called
`*selvage* <../S/selvage.html>`__, `*perf* <../P/perf.html>`__, and
`*ripoff* <../R/ripoff.html>`__.

2. The confetti-like paper bits punched out of cards or paper tape; this
has also been called chaff, computer confetti, and keypunch droppings.
It's reported that this was very old Army slang (associated with
teletypewriters before the computer era), and has been occasionally
sighted in directions for punched-card vote tabulators long after it
passed out of live use among computer programmers in the late 1970s.
This sense of ‘chad’ returned to the mainstream during the finale of the
hotly disputed U.S. presidential election in 2000 via stories about the
Florida vote recounts. Note however that in the revived mainstream usage
chad is not a mass noun and ‘a chad’ is a single piece of the stuff.

There is an urban legend that chad (sense 2) derives from the Chadless
keypunch (named for its inventor), which cut little u-shaped tabs in the
card to make a hole when the tab folded back, rather than punching out a
circle/rectangle; it was clear that if the Chadless keypunch didn't make
them, then the stuff that other keypunches made had to be ‘chad’.
However, serious attempts to track down “Chadless” as a personal name or
U.S. trademark have failed, casting doubt on this etymology — and the
U.S. Patent Classification System uses “chadless” (small c) as an
adjective, suggesting that “chadless” derives from “chad” and not the
other way around. There is another legend that the word was originally
acronymic, standing for “Card Hole Aggregate Debris”, but this has all
the earmarks of a `*backronym* <../B/backronym.html>`__. It has also
been noted that the word “chad” is Scots dialect for gravel, but nobody
has proposed any plausible reason that card chaff should be thought of
as gravel. None of these etymologies is really plausible.

|image0|

This is *one* way to be `*chad* <chad.html>`__\ less.

(The next cartoon in the Crunchly saga is
`75-10-04 <../B/bit-bucket.html#crunchly75-10-04>`__. The previous
cartoon was `74-12-29 <../W/winged-comments.html#crunchly74-12-29>`__.)



**chain**

1. vi. [orig. from BASIC's **CHAIN** statement] To hand off execution to
a child or successor without going through the `*OS* <../O/OS.html>`__
command interpreter that invoked it. The state of the parent program is
lost and there is no returning to it. Though this facility used to be
common on memory-limited micros and is still widely supported for
backward compatibility, the jargon usage is semi-obsolescent; in
particular, most Unix programmers will think of this as an
`*exec* <../E/exec.html>`__. Oppose the more modern subshell.

2. n. A series of linked data areas within an operating system or
application. Chain rattling is the process of repeatedly running through
the linked data areas searching for one which is of interest to the
executing program. The implication is that there is a very large number
of links on the chain.



**chainik**: /chi:´nik/

[Russian, literally “teapot”] Almost synonymous with
`*muggle* <../M/muggle.html>`__. Implies both ignorance and a certain
amount of willingness to learn, but does not necessarily imply as little
experience or short exposure time as `*newbie* <../N/newbie.html>`__ and
is not as derogatory as `*luser* <../L/luser.html>`__. Both a novice
user and someone using a system for a long time without any
understanding of the internals can be referred to as chainiks. Very
widespread term in Russian hackish, often used in an English context by
Russian-speaking hackers esp. in Israel (e.g. “Our new colleague is a
complete chainik”). FidoNet discussion groups often had a “chainik”
subsection for newbies and, well, old chainiks (eg. su.asm.chainik,
ru.linux.chainik, ru.html.chainik). Public projects often have a chainik
mailing list to keep the chainiks off the developers' and experienced
users' discussions. Today, the word is slowly slipping into mainstream
Russian due to the Russian translation of the popular yellow-black
covered “foobar for dummies” series, which (correctly) uses “chainik”
for “dummy”, but its frequent (though not excessive) use is still
characteristic hacker-speak.



**channel hopping**: n.

[common; IRC, GEnie] To rapidly switch channels on
`*IRC* <../I/IRC.html>`__, or a GEnie chat board, just as a social
butterfly might hop from one group to another at a party. This term may
derive from the TV watcher's idiom, channel surfing.



**channel**: n.

[IRC] The basic unit of discussion on `*IRC* <../I/IRC.html>`__. Once
one joins a channel, everything one types is read by others on that
channel. Channels are named with strings that begin with a ‘#’ sign and
can have topic descriptions (which are generally irrelevant to the
actual subject of discussion). Some notable channels are **#initgame**,
**#hottub**, **callahans**, and **#report**. At times of international
crisis, **#report** has hundreds of members, some of whom take turns
listening to various news services and typing in summaries of the news,
or in some cases, giving first-hand accounts of the action (e.g., Scud
missile attacks in Tel Aviv during the Gulf War in 1991).




**Chernobyl packet**: /cher·noh´b@l pak'@t/, n.

A network packet that induces a `*broadcast
storm* <../B/broadcast-storm.html>`__ and/or `*network
meltdown* <../N/network-meltdown.html>`__, in memory of the April 1986
nuclear accident at Chernobyl in Ukraine. The typical scenario involves
an IP Ethernet datagram that passes through a gateway with both source
and destination Ether and IP address set as the respective broadcast
addresses for the subnetworks being gated between. Compare `*Christmas
tree packet* <Christmas-tree-packet.html>`__.



**chickenboner**: n.

[spamfighters] Derogatory term for a spammer. The image that goes with
it is of an overweight redneck with bad teeth living in a trailer,
hunched in semi-darkness over his computer and surrounded by rotting
chicken bones in half-eaten KFC buckets and empty beer cans. See
`http://www.spamfaq.net/terminology.shtml#chickenboner <http://www.spamfaq.net/terminology.shtml#chickenboner>`__
for discussion.



**chicken head**: n.

[Commodore] The Commodore Business Machines logo, which strongly
resembles a poultry part (within Commodore itself the logo was always
called chicken lips). Rendered in ASCII as ‘C=’. With the arguable
exception of the `*Amiga* <../A/Amiga.html>`__, Commodore's machines
were notoriously crocky little `*bitty
box* <../B/bitty-box.html>`__\ es, albeit people have written
multitasking Unix-like operating systems with TCP/IP networking for
them. Thus, this usage may owe something to Philip K. Dick's novel *Do
Androids Dream of Electric Sheep?* (the basis for the movie *Blade
Runner*; the novel is now sold under that title), in which a
‘chickenhead’ is a mutant with below-average intelligence.

**chiclet keyboard**: n.

A keyboard with a small, flat rectangular or lozenge-shaped rubber or
plastic keys that look like pieces of chewing gum. (Chiclets is the
brand name of a variety of chewing gum that does in fact resemble the
keys of chiclet keyboards.) Used esp. to describe the original IBM PCjr
keyboard. Vendors unanimously liked these because they were cheap, and a
lot of early portable and laptop products got launched using them.
Customers rejected the idea with almost equal unanimity, and chiclets
are not often seen on anything larger than a digital watch any more.



**Chinese Army technique**: n.

Syn. `*Mongolian Hordes
technique* <../M/Mongolian-Hordes-technique.html>`__.



**choad**: /chohd/, n.

Synonym for ‘penis’ used in ``alt.tasteless`` and popularized by the
denizens thereof. They say: “We think maybe it's from Middle English but
we're all too damned lazy to check the OED.” [I'm not. It isn't. —ESR]
This term is alleged to have been inherited through 1960s underground
comics, and to have been recently sighted in the Beavis and Butthead
cartoons. Speakers of the Hindi, Bengali and Gujarati languages have
confirmed that ‘choad’ is in fact an Indian vernacular word equivalent
to ‘fuck’; it is therefore likely to have entered English slang via the
British Raj.



**choke**: v.

[common] To reject input, often ungracefully. “NULs make System V's
lpr(1) choke.” “I tried building an `*EMACS* <../E/EMACS.html>`__ binary
to use `*X* <../X/X.html>`__, but cpp(1) choked on all those
**#define**\ s.” See `*barf* <../B/barf.html>`__,
`*vi* <../V/vi.html>`__.



**chomper**: n.

Someone or something that is chomping; a loser. See
`*loser* <../L/loser.html>`__, `*bagbiter* <../B/bagbiter.html>`__,
`*chomp* <chomp.html>`__.



**chomp**: vi.

1. To `*lose* <../L/lose.html>`__; specifically, to chew on something of
which more was bitten off than one can. Probably related to gnashing of
teeth.

2. To bite the bag; See `*bagbiter* <../B/bagbiter.html>`__.

A hand gesture commonly accompanies this. To perform it, hold the four
fingers together and place the thumb against their tips. Now open and
close your hand rapidly to suggest a biting action (much like what
Pac-Man does in the classic video game, though this pantomime seems to
predate that). The gesture alone means ‘chomp chomp’ (see `Verb
Doubling <../verb-doubling.html>`__ in the `Jargon
Construction <../construction.html>`__ section of the Prependices). The
hand may be pointed at the object of complaint, and for real emphasis
you can use both hands at once. Doing this to a person is equivalent to
saying “You chomper!” If you point the gesture at yourself, it is a
humble but humorous admission of some failure. You might do this if
someone told you that a program you had written had failed in some
surprising way and you felt dumb for not having anticipated it.



**CHOP**: /chop/, n.

[IRC] See `*channel op* <channel-op.html>`__.



**Christmas tree**: n.

A kind of RS-232 line tester or breakout box featuring rows of blinking
red and green LEDs suggestive of Christmas lights.


**Christmas tree packet**: n.

A packet with every single option set for whatever protocol is in use.
See `*kamikaze packet* <../K/kamikaze-packet.html>`__, `*Chernobyl
packet* <Chernobyl-packet.html>`__. (The term doubtless derives from a
fanciful image of each little option bit being represented by a
different-colored light bulb, all turned on.) Compare
`*Godzillagram* <../G/Godzillagram.html>`__.


**chrome**: n.

[from automotive slang via wargaming] Showy features added to attract
users but contributing little or nothing to the power of a system. “The
3D icons in Motif are just chrome, but they certainly are *pretty*
chrome!” Distinguished from `*bells and
whistles* <../B/bells-and-whistles.html>`__ by the fact that the latter
are usually added to gratify developers' own desires for featurefulness.
Often used as a term of contempt.


**C**: n.

1. The third letter of the English alphabet.

2. ASCII 1000011.

3. The name of a programming language designed by Dennis Ritchie during
the early 1970s and immediately used to reimplement
`*Unix* <../U/Unix.html>`__; so called because many features derived
from an earlier compiler named ‘B’ in commemoration of *its* parent,
BCPL. (BCPL was in turn descended from an earlier Algol-derived
language, CPL.) Before Bjarne Stroustrup settled the question by
designing `*C++* <C-plus-plus.html>`__, there was a humorous debate over
whether C's successor should be named ‘D’ or ‘P’. C became immensely
popular outside Bell Labs after about 1980 and is now the dominant
language in systems and microcomputer applications programming. C is
often described, with a mixture of fondness and disdain varying
according to the speaker, as “a language that combines all the elegance
and power of assembly language with all the readability and
maintainability of assembly language” See also `*languages of
choice* <../L/languages-of-choice.html>`__, `*indent
style* <../I/indent-style.html>`__.



The Crunchly on the left sounds a little ANSI.



**chug**: vi.

To run slowly; to `*grind* <../G/grind.html>`__ or
`*grovel* <../G/grovel.html>`__. “The disk is chugging like crazy.”


**Church of the SubGenius**: n.

A mutant offshoot of `*Discordianism* <../D/Discordianism.html>`__
launched in 1981 as a spoof of fundamentalist Christianity by the
‘Reverend’ Ivan Stang, a brilliant satirist with a gift for promotion.
Popular among hackers as a rich source of bizarre imagery and references
such as “Bob” the divine drilling-equipment salesman, the Benevolent
Space Xists, and the Stark Fist of Removal. Much SubGenius theory is
concerned with the acquisition of the mystical substance or quality of
`*slack* <../S/slack.html>`__. There is a home page at
`http://www.subgenius.com/ <http://www.subgenius.com/>`__.


**Cinderella Book**: n.

[CMU] *Introduction to Automata Theory, Languages, and Computation*, by
John Hopcroft and Jeffrey Ullman, (Addison-Wesley, 1979). So called
because the cover depicts a girl (putatively Cinderella) sitting in
front of a Rube Goldberg device and holding a rope coming out of it. On
the back cover, the device is in shambles after she has (inevitably)
pulled on the rope. See also `*book titles* <../B/book-titles.html>`__.



**CI$**: //, n.

Hackerism for ‘CIS’, CompuServe Information Service. The dollar sign
refers to CompuServe's rather steep line charges. Often used in `*sig
block* <../S/sig-block.html>`__\ s just before a CompuServe address.
Syn. `*Compu$erve* <CompuServe.html>`__.



**Classic C**: /klas´ik C/, n.

[a play on ‘Coke Classic’] The C programming language as defined in the
first edition of `*K&R* <../K/K-ampersand-R.html>`__, with some small
additions. It is also known as ‘K&R C’. The name came into use while C
was being standardized by the ANSI X3J11 committee. Also ‘C Classic’.

An analogous construction is sometimes applied elsewhere: thus, ‘X
Classic’, where X = Star Trek (referring to the original TV series) or X
= PC (referring to IBM's ISA-bus machines as opposed to the PS/2
series). This construction is especially used of product series in which
the newer versions are considered serious losers relative to the older
ones.


**clean**

1. adj. Used of hardware or software designs, implies ‘elegance in the
small’, that is, a design or implementation that may not hold any
surprises but does things in a way that is reasonably intuitive and
relatively easy to comprehend from the outside. The antonym is ‘grungy’
or `*crufty* <crufty.html>`__.

2. v. To remove unneeded or undesired files in a effort to reduce
clutter: “I'm cleaning up my account.” “I cleaned up the garbage and now
have 100 Meg free on that partition.”



**click of death**: n.

A syndrome of certain Iomega ZIP drives, named for the clicking noise
that is caused by the malady. An affected drive will, after accepting a
disk, will start making a clicking noise and refuse to eject the disk. A
common solution for retrieving the disk is to insert the bent end of a
paper clip into a small hole adjacent to the slot. “Clicked” disks are
generally unusable after being retrieved from the drive.

The clicking noise is caused by the drive's read/write head bumping
against its movement stops when it fails to find track 0 on the disk,
causing the head to become misaligned. This can happen when the drive
has been subjected to a physical shock, or when the disk is exposed to
an electromagnetic field, such as that of the CRT. Another common cause
is when a package of disks is armed with an anti-theft strip at a store.
When the clerk scans the product to disarm the strip, it can demagnetize
the disks, wiping out track 0.

There is evidence that the click of death is a communicable disease; a
“clicked” disk can cause the read/write head of a "clean" drive to
become misaligned. Iomega at first denied the existence of the click of
death, but eventually offered to replace free of charge any drives
affected by the condition.



**CLM**: /C·L·M/

[Sun: ‘Career Limiting Move’]

1. n. An action endangering one's future prospects of getting plum
projects and raises, and possibly one's job: “His Halloween costume was
a parody of his manager. He won the prize for ‘best CLM’.”

2. adj. Denotes extreme severity of a bug, discovered by a customer and
obviously missed earlier because of poor testing: “That's a CLM bug!”



**clobber**: vt.

To overwrite, usually unintentionally: “I walked off the end of the
array and clobbered the stack.” Compare `*mung* <../M/mung.html>`__,
`*scribble* <../S/scribble.html>`__, `*trash* <../T/trash.html>`__, and
`*smash the stack* <../S/smash-the-stack.html>`__.



**clock**

n.,v.

1. [techspeak] The master oscillator that steps a CPU or other digital
circuit through its paces. This has nothing to do with the time of day,
although the software counter that keeps track of the latter may be
derived from the former.

2. vt. To run a CPU or other digital circuit at a particular rate. “If
you clock it at 1000MHz, it gets warm.”. See
`*overclock* <../O/overclock.html>`__.

3. vt. To force a digital circuit from one state to the next by applying
a single clock pulse. “The data must be stable 10ns before you clock the
latch.”



**clocks**: n.

Processor logic cycles, so called because each generally corresponds to
one clock pulse in the processor's timing. The relative execution times
of instructions on a machine are usually discussed in clocks rather than
absolute fractions of a second; one good reason for this is that clock
speeds for various models of the machine may increase as technology
improves, and it is usually the relative times one is interested in when
discussing the instruction set. Compare `*cycle* <cycle.html>`__,
`*jiffy* <../J/jiffy.html>`__.



**clone-and-hack coding**: n.




**clone**: n.

1. An exact duplicate: “Our product is a clone of their product.”
Implies a legal reimplementation from documentation or by
reverse-engineering. Also connotes lower price.

2. A shoddy, spurious copy: “Their product is a clone of our product.”

3. A blatant ripoff, most likely violating copyright, patent, or trade
secret protections: “Your product is a clone of my product.” This use
implies legal action is pending.

4. [obs] PC clone: a PC-BUS/ISA/EISA/PCI-compatible 80x86-based
microcomputer (this use is sometimes spelled klone or PClone). These
invariably have much more bang for the buck than the IBM archetypes they
resemble. This term fell out of use in the 1990s; the class of machines
it describes are now simply PCs or Intel machines.

5. [obs.] In the construction Unix clone: An OS designed to deliver a
Unix-lookalike environment without Unix license fees, or with additional
‘mission-critical’ features such as support for real-time programming.
`*Linux* <../L/Linux.html>`__ and the free BSDs killed off this product
category and the term with it.

6. v. To make an exact copy of something. “Let me clone that” might mean
“I want to borrow that paper so I can make a photocopy” or “Let me get a
copy of that file before you `*mung* <../M/mung.html>`__ it”.



**clover key**: n.

[Mac users] See `*feature key* <../F/feature-key.html>`__.




**clue-by-four**

[Usenet: portmanteau, clue + two-by-four] The notional stick with which
one whacks an aggressively clueless person. This term derives from a
western American folk saying about training a mule “First, you got to
hit him with a two-by-four. That's to get his attention.” The
clue-by-four is a close relative of the `*LART* <../L/LART.html>`__.
Syn. clue stick. This metaphor is commonly elaborated; your editor once
heard a hacker say “I smite you with the great sword Cluebringer!”



**clustergeeking**: /kluh´st@r·gee\`king/, n.

[CMU] Spending more time at a computer cluster doing CS homework than
most people spend breathing.



**C\|N>K**: n.

[Usenet] Coffee through Nose to Keyboard; that is, “I laughed so hard I
`*snarf* <../S/snarf.html>`__\ ed my coffee onto my keyboard.”. Common
on ``alt.fan.pratchett`` and `*scary devil
monastery* <../S/scary-devil-monastery.html>`__; recognized elsewhere.
The `Acronymphomania
FAQ <http://www.lspace.org/faqs/acronym-faq.g.html>`__ on
``alt.fan.pratchett`` recognizes variants such as T\|N>K = ‘Tea through
Nose to Keyboard’ and C\|N>S = ‘Coffee through Nose to Screen’.



**coaster**: n.

1. Unuseable CD produced during failed attempt at writing to writeable
or re-writeable CD media. Certainly related to the coaster-like shape of
a CD, and the relative value of these failures. “I made a lot of
coasters before I got a good CD.”

2. Useless CDs received in the mail from the likes of AOL, MSN, CI$,
Prodigy, ad nauseam.

In the U.K., beermat is often used in these senses.


**coaster toaster**

A writer for recordable CD-Rs, especially cheap IDE models that tend to
produce a high proportion of `*coaster* <coaster.html>`__\ s.



**COBOL fingers**: /koh´bol fing´grz/, n.

Reported from Sweden, a (hypothetical) disease one might get from coding
in COBOL. The language requires code verbose beyond all reason (see
`*candygrammar* <candygrammar.html>`__); thus it is alleged that
programming too much in COBOL causes one's fingers to wear down to stubs
by the endless typing. “I refuse to type in all that source code again;
it would give me COBOL fingers!”


**COBOL**: /koh´bol/, n.

[COmmon Business-Oriented Language] (Synonymous with
`*evil* <../E/evil.html>`__.) A weak, verbose, and flabby language used
by `*code grinder* <code-grinder.html>`__\ s to do boring mindless
things on `*dinosaur* <../D/dinosaur.html>`__ mainframes. Hackers
believe that all COBOL programmers are `*suit* <../S/suit.html>`__\ s or
`*code grinder* <code-grinder.html>`__\ s, and no self-respecting hacker
will ever admit to having learned the language. Its very name is seldom
uttered without ritual expressions of disgust or horror. One popular one
is Edsger W. Dijkstra's famous observation that “The use of COBOL
cripples the mind; its teaching should, therefore, be regarded as a
criminal offense.” (from *Selected Writings on Computing: A Personal
Perspective*) See also `*fear and
loathing* <../F/fear-and-loathing.html>`__, `*software
rot* <../S/software-rot.html>`__.



**cobweb site**: n.

A World Wide Web Site that hasn't been updated so long it has
figuratively grown cobwebs.



**code grinder**: n.

1. A `*suit* <../S/suit.html>`__-wearing minion of the sort hired in
legion strength by banks and insurance companies to implement payroll
packages in RPG and other such unspeakable horrors. In its native
habitat, the code grinder often removes the suit jacket to reveal an
underplumage consisting of button-down shirt (starch optional) and a
tie. In times of dire stress, the sleeves (if long) may be rolled up and
the tie loosened about half an inch. It seldom helps. The `*code
grinder* <code-grinder.html>`__'s milieu is about as far from hackerdom
as one can get and still touch a computer; the term connotes pity. See
`*Real World* <../R/Real-World.html>`__, `*suit* <../S/suit.html>`__.

2. Used of or to a hacker, a really serious slur on the person's
creative ability; connotes a design style characterized by primitive
technique, rule-boundedness, `*brute force* <../B/brute-force.html>`__,
and utter lack of imagination.

Contrast `*hacker* <../H/hacker.html>`__, `*Real
Programmer* <../R/Real-Programmer.html>`__.



**code**

1. n. The stuff that software writers write, either in source form or
after translation by a compiler or assembler. Often used in opposition
to “data”, which is the stuff that code operates on. Among hackers this
is a mass noun, as in “How much code does it take to do a `*bubble
sort* <../B/bubble-sort.html>`__?”, or “The code is loaded at the high
end of RAM.” Among scientific programmers it is sometimes a count noun
equilvalent to “program”; thus they may speak of “codes” in the plural.
Anyone referring to software as “the software codes” is probably a
`*newbie* <../N/newbie.html>`__ or a `*suit* <../S/suit.html>`__.

2. v. To write code. In this sense, always refers to source code rather
than compiled. “I coded an Emacs clone in two hours!” This verb is a bit
of a cultural marker associated with the Unix and minicomputer
traditions (and lately Linux); people within that culture prefer v.
‘code’ to v. ‘program’ whereas outside it the reverse is normally true.



**code monkey**: n

1. A person only capable of grinding out code, but unable to perform the
higher-primate tasks of software architecture, analysis, and design.
Mildly insulting. Often applied to the most junior people on a
programming team.

2. Anyone who writes code for a living; a programmer.

3. A self-deprecating way of denying responsibility for a
`*management* <../M/management.html>`__ decision, or of complaining
about having to live with such decisions. As in “Don't ask me why we
need to write a compiler in COBOL, I'm just a code monkey.”



**Code of the Geeks**: n.

see `*geek code* <../G/geek-code.html>`__.


**code police**: n.

[by analogy with George Orwell's ‘thought police’] A mythical team of
Gestapo-like storm troopers that might burst into one's office and
arrest one for violating programming style rules. May be used either
seriously, to underline a claim that a particular style violation is
dangerous, or ironically, to suggest that the practice under discussion
is condemned mainly by anal-retentive
`*weenie* <../W/weenie.html>`__\ s. “Dike out that goto or the code
police will get you!” The ironic usage is perhaps more common.







**codes**: n.

[scientific computing] Programs. This usage is common in people who hack
supercomputers and heavy-duty
`*number-crunching* <../N/number-crunching.html>`__, rare to unknown
elsewhere (if you say “codes” to hackers outside scientific computing,
their first association is likely to be “and cyphers”).


**codewalker**: n.

A program component that traverses other programs for a living.
Compilers have codewalkers in their front ends; so do cross-reference
generators and some database front ends. Other utility programs that try
to do too much with source code may turn into codewalkers. As in “This
new **vgrind** feature would require a codewalker to implement.”



**coefficient of X**: n.

Hackish speech makes heavy use of pseudo-mathematical metaphors. Four
particularly important ones involve the terms coefficient, factor, index
of X, and quotient. They are often loosely applied to things you cannot
really be quantitative about, but there are subtle distinctions among
them that convey information about the way the speaker mentally models
whatever he or she is describing. Foo factor and foo quotient tend to
describe something for which the issue is one of presence or absence.
The canonical example is `*fudge factor* <../F/fudge-factor.html>`__.
It's not important how much you're fudging; the term simply acknowledges
that some fudging is needed. You might talk of liking a movie for its
silliness factor. Quotient tends to imply that the property is a ratio
of two opposing factors: “I would have won except for my luck quotient.”
This could also be “I would have won except for the luck factor”, but
using *quotient* emphasizes that it was bad luck overpowering good luck
(or someone else's good luck overpowering your own). Foo index and
coefficient of foo both tend to imply that foo is, if not strictly
measurable, at least something that can be larger or smaller. Thus, you
might refer to a paper or person as having a high bogosity index,
whereas you would be less likely to speak of a high bogosity factor. Foo
index suggests that foo is a condensation of many quantities, as in the
mundane cost-of-living index; coefficient of foo suggests that foo is a
fundamental quantity, as in a coefficient of friction. The choice
between these terms is often one of personal preference; e.g., some
people might feel that bogosity is a fundamental attribute and thus say
coefficient of bogosity, whereas others might feel it is a combination
of factors and thus say bogosity index.


**cokebottle**: /kohk´bot·l/, n.

Any very unusual character, particularly one you can't type because it
isn't on your keyboard. MIT people used to complain about the
‘control-meta-cokebottle’ commands at SAIL, and SAIL people complained
right back about the ‘escape-escape-cokebottle’ commands at MIT. After
the demise of the `*space-cadet
keyboard* <../S/space-cadet-keyboard.html>`__, cokebottle faded away as
serious usage, but was often invoked humorously to describe an
(unspecified) weird or non-intuitive keystroke command. It may be due
for a second inning, however. The OSF/Motif window manager, mwm(1), has
a reserved keystroke for switching to the default set of keybindings and
behavior. This keystroke is (believe it or not) ‘control-meta-bang’ (see
`*bang* <../B/bang.html>`__). Since the exclamation point looks a lot
like an upside down Coke bottle, Motif hackers have begun referring to
this keystroke as cokebottle. See also `*quadruple
bucky* <../Q/quadruple-bucky.html>`__.



**cold boot**: n.

See `*boot* <../B/boot.html>`__.



**co-lo**: /koh´loh\`/, n.

[very common; first heard c.1995] Short for ‘co-location’, used of a
machine you own that is physically sited on the premises of an ISP in
order to take advantage of the ISP's direct access to lots of network
bandwidth. Often in the phrases co-lo box or co-lo machines. Co-lo boxes
are typically web and FTP servers remote-administered by their owners,
who may seldom or never visit the actual site.


**COME FROM**: n.

A semi-mythical language construct dual to the ‘go to’; **COME FROM**
<label> would cause the referenced label to act as a sort of trapdoor,
so that if the program ever reached it control would quietly and
`*automagically* <../A/automagically.html>`__ be transferred to the
statement following the **COME FROM**. **COME FROM** was first proposed
in R. Lawrence Clark's *A Linguistic Contribution to GOTO-less
programming*, which appeared in a 1973
`*Datamation* <../D/Datamation.html>`__ issue (and was reprinted in the
April 1984 issue of *Communications of the ACM*). This parodied the
then-raging ‘structured programming’ `holy
wars <../H/holy-wars.html>`__ (see `considered
harmful <considered-harmful.html>`__). Mythically, some variants are
the assigned COME FROM and the computed COME FROM (parodying some nasty
control constructs in FORTRAN and some extended BASICs). Of course,
multi-tasking (or non-determinism) could be implemented by having more
than one **COME FROM** statement coming from the same label.

In some ways the FORTRAN DO looks like a **COME FROM** statement.
After the terminating statement number/\ **CONTINUE** is reached,
control continues at the statement following the DO. Some generous
FORTRANs would allow arbitrary statements (other than **CONTINUE**) for
the statement, leading to examples like:

+--------------------------------------------------------------------------+
| .. code:: programlisting                                                 |
|                                                                          |
|           DO 10 I=1,LIMIT                                                |
|     C imagine many lines of code here, leaving the                       |
|     C original DO statement lost in the spaghetti...                     |
|           WRITE(6,10) I,FROB(I)                                          |
|      10   FORMAT(1X,I5,G10.4)                                            |
|                                                                          |
+--------------------------------------------------------------------------+

in which the trapdoor is just after the statement labeled 10. (This is
particularly surprising because the label doesn't appear to have
anything to do with the flow of control at all!) While sufficiently
astonishing to the unsuspecting reader, this form of **COME FROM**
statement isn't completely general. After all, control will eventually
pass to the following statement. The implementation of the general form
was left to Univac FORTRAN, ca. 1975 (though a roughly similar feature
existed on the IBM 7040 ten years earlier). The statement **AT 100**
would perform a **COME FROM 100**. It was intended strictly as a
debugging aid, with dire consequences promised to anyone so deranged as
to use it in production code. More horrible things had already been
perpetrated in production languages, however; doubters need only
contemplate the **ALTER** verb in `*COBOL* <COBOL.html>`__. **COME
FROM** was supported under its own name for the first time 15 years
later, in C-INTERCAL (see `*INTERCAL* <../I/INTERCAL.html>`__,
`*retrocomputing* <../R/retrocomputing.html>`__); knowledgeable
observers are still reeling from the shock.


**command key**: n.

[Mac users] Syn. `*feature key* <../F/feature-key.html>`__.



**comment out**: vt.

To surround a section of code with comment delimiters or to prefix every
line in the section with a comment marker; this prevents it from being
compiled or interpreted. Often done when the code is redundant or
obsolete, but is being left in the source to make the intent of the
active code clearer; also when the code in that section is broken and
you want to bypass it in order to debug some other part of the code.
Compare `*condition out* <condition-out.html>`__, usually the preferred
technique in languages (such as `*C* <C.html>`__) that make it possible.



**comm mode**: /kom mohd/, n.

[ITS: from the feature supporting on-line chat; the first word may be
spelled with one or two m's] Syn. for `*talk
mode* <../T/talk-mode.html>`__.



**Commonwealth Hackish**: n.

Hacker jargon as spoken in English outside the U.S., esp. in the British
Commonwealth. It is reported that Commonwealth speakers are more likely
to pronounce truncations like ‘char’ and ‘soc’, etc., as spelled
(/char/, /sok/), as opposed to American /keir/ and /sohsh/. Dots in
`*newsgroup* <../N/newsgroup.html>`__ names (especially two-component
names) tend to be pronounced more often (so soc.wibble is /sok dot
wib´l/ rather than /sohsh wib´l/).

Preferred `*metasyntactic
variable* <../M/metasyntactic-variable.html>`__\ s include
`*blurgle* <../B/blurgle.html>`__, **eek**, **ook**, **frodo**, and
**bilbo**; `*wibble* <../W/wibble.html>`__, **wobble**, and in
emergencies **wubble**; **flob**, **banana**, **tom**, **dick**,
**harry**, **wombat**, **frog**, `*fish* <../F/fish.html>`__,
`*womble* <../W/womble.html>`__ and so on and on (see
`*foo* <../F/foo.html>`__, sense 4). Alternatives to verb doubling
include suffixes -o-rama, frenzy (as in feeding frenzy), and city
(examples: “barf city!” “hack-o-rama!” “core dump frenzy!”).

All the generic differences within the anglophone world inevitably show
themselves in the associated hackish dialects. The Greek letters beta
and zeta are usually pronounced /bee´t@/ and /zee´t@/; meta may also be
pronounced /mee´t@/. Various punctuators (and even letters - Z is called
‘zed’, not ‘zee’) are named differently: most crucially, for hackish,
where Americans use ‘parens’, ‘brackets’ and \`braces' for (), [] and
{}, Commonwealth English uses ‘brackets’, ‘square brackets’ and ‘curly
brackets’, though ‘parentheses’ may be used for the first; the
exclamation mark, ‘!’, is called pling rather than bang and the pound
sign, ‘#’, is called hash; furthermore, the term ‘the pound sign’ is
understood to mean the £ (of course). Canadian hacker slang, as with
mainstream language, mixes American and British usages about evenly.

See also `*attoparsec* <../A/attoparsec.html>`__,
`*calculator* <calculator.html>`__, `*chemist* <chemist.html>`__,
`*console jockey* <console-jockey.html>`__, `*fish* <../F/fish.html>`__,
`*go-faster stripes* <../G/go-faster-stripes.html>`__,
`*grunge* <../G/grunge.html>`__, `*hakspek* <../H/hakspek.html>`__,
`*heavy metal* <../H/heavy-metal.html>`__, `*leaky
heap* <../L/leaky-heap.html>`__, `*lord high
fixer* <../L/lord-high-fixer.html>`__, `*loose
bytes* <../L/loose-bytes.html>`__, `*muddie* <../M/muddie.html>`__,
`*nadger* <../N/nadger.html>`__, `*noddy* <../N/noddy.html>`__,
`*psychedelicware* <../P/psychedelicware.html>`__, `*raster
blaster* <../R/raster-blaster.html>`__, `*RTBM* <../R/RTBM.html>`__,
`*seggie* <../S/seggie.html>`__, `*spod* <../S/spod.html>`__, `*sun
lounge* <../S/sun-lounge.html>`__, `*terminal
junkie* <../T/terminal-junkie.html>`__, `*tick-list
features* <../T/tick-list-features.html>`__,
`*weeble* <../W/weeble.html>`__, `*weasel* <../W/weasel.html>`__,
`*YABA* <../Y/YABA.html>`__, and notes or definitions under `*Bad
Thing* <../B/Bad-Thing.html>`__, `*barf* <../B/barf.html>`__,
`*bogus* <../B/bogus.html>`__, `*chase
pointers* <chase-pointers.html>`__, `*cosmic
rays* <cosmic-rays.html>`__, `*crippleware* <crippleware.html>`__,
`*crunch* <crunch.html>`__, `*dodgy* <../D/dodgy.html>`__,
`*gonk* <../G/gonk.html>`__, `*hamster* <../H/hamster.html>`__,
`*hardwarily* <../H/hardwarily.html>`__,
`*mess-dos* <../M/mess-dos.html>`__, `*nybble* <../N/nybble.html>`__,
`*proglet* <../P/proglet.html>`__, `*root* <../R/root.html>`__,
`*SEX* <../S/SEX.html>`__, `*tweak* <../T/tweak.html>`__,
`*womble* <../W/womble.html>`__, and `*xyzzy* <../X/xyzzy.html>`__.



**compact**: adj.

Of a design, describes the valuable property that it can all be
apprehended at once in one's head. This generally means the thing
created from the design can be used with greater facility and fewer
errors than an equivalent tool that is not compact. Compactness does not
imply triviality or lack of power; for example, C is compact and FORTRAN
is not, but C is more powerful than FORTRAN. Designs become non-compact
through accreting `*feature* <../F/feature.html>`__\ s and
`*cruft* <cruft.html>`__ that don't merge cleanly into the overall
design scheme (thus, some fans of `*Classic C* <Classic-C.html>`__
maintain that ANSI C is no longer compact).



**compiler jock**: n.

See `*jock* <../J/jock.html>`__ (sense 2).



**compo**: n.

[`*demoscene* <../D/demoscene.html>`__\ ] Finnish-originated slang for
‘competition’. Demo compos are held at a
`*demoparty* <../D/demoparty.html>`__. The usual protocol is that
several groups make demos for a compo, they are shown on a big screen,
and then the party participants vote for the best one. Prizes (from
sponsors and party entrance fees) are given. Standard compo formats
include `*intro* <../I/intro.html>`__ compos (4k or 64k demos), music
compos, graphics compos, quick `*demo* <../D/demo.html>`__ compos (build
a demo within 4 hours for example), etc.



**compress**: vt.

[Unix] When used without a qualifier, generally refers to
`*crunch* <crunch.html>`__\ ing of a file using a particular C
implementation of compression by Joseph M. Orost et al.: and widely
circulated via `*Usenet* <../U/Usenet.html>`__; use of
`*crunch* <crunch.html>`__ itself in this sense is rare among Unix
hackers. Specifically, compress is built around the Lempel-Ziv-Welch
algorithm as described in “A Technique for High Performance Data
Compression”, Terry A. Welch, *IEEE Computer*, vol. 17, no. 6 (June
1984), pp. 8--19.



**Compu$erve**: n.

See `*CI$* <CIS.html>`__. Synonyms CompuSpend and Compu$pend are also
reported.



**computer confetti**: n.

Syn. `*chad* <chad.html>`__. [obs.] Though this term was common at one
time, this use of punched-card chad is not a good idea, as the pieces
are stiff and have sharp corners that could injure the eyes. GLS reports
that he once attended a wedding at MIT during which he and a few other
guests enthusiastically threw chad instead of rice. The groom later
grumbled that he and his bride had spent most of the evening trying to
get the stuff out of their hair.

[2001 update: this term has passed out of use for two reasons; (1) the
stuff it describes is now quite rare, and (2) the term
`*chad* <chad.html>`__, which was half-forgotten in 1990, has enjoyed a
revival. —ESR]



**computron**: /kom´pyoo·tron\`/, n.

1. [common] A notional unit of computing power combining instruction
speed and storage capacity, dimensioned roughly in
instructions-per-second times megabytes-of-main-store times
megabytes-of-mass-storage. “That machine can't run GNU Emacs, it doesn't
have enough computrons!” This usage is usually found in metaphors that
treat computing power as a fungible commodity good, like a crop yield or
diesel horsepower. See `*bitty box* <../B/bitty-box.html>`__, `*Get a
real computer!* <../G/Get-a-real-computer-.html>`__,
`*toy* <../T/toy.html>`__, `*crank* <crank.html>`__.

2. A mythical subatomic particle that bears the unit quantity of
computation or information, in much the same way that an electron bears
one unit of electric charge (see also `*bogon* <../B/bogon.html>`__). An
elaborate pseudo-scientific theory of computrons has been developed
based on the physical fact that the molecules in a solid object move
more rapidly as it is heated. It is argued that an object melts because
the molecules have lost their information about where they are supposed
to be (that is, they have emitted computrons). This explains why
computers get so hot and require air conditioning; they use up
computrons. Conversely, it should be possible to cool down an object by
placing it in the path of a computron beam. It is believed that this may
also explain why machines that work at the factory fail in the computer
room: the computrons there have been all used up by the other hardware.
(The popularity of this theory probably owes something to the *Warlock*
stories by Larry Niven, the best known being *What Good is a Glass
Dagger?*, in which magic is fueled by an exhaustible natural resource
called *mana*.)



**condition out**: vt.

To prevent a section of code from being compiled by surrounding it with
a conditional-compilation directive whose condition is always false. The
`*canonical* <canonical.html>`__ examples of these directives are **#if
0** (or **#ifdef notdef**, though some find the latter
`*bletcherous* <../B/bletcherous.html>`__) and **#endif** in C. Compare
`*comment out* <comment-out.html>`__.



**condom**: n.

1. The protective plastic bag that accompanies 3.5-inch microfloppy
diskettes. Rarely, also used of (paper) disk envelopes. Unlike the write
protect tab, the condom (when left on) not only impedes the practice of
`*SEX* <../S/SEX.html>`__ but has also been shown to have a high failure
rate as drive mechanisms attempt to access the disk — and can even
fatally frustrate insertion.

2. The protective cladding on a `*light pipe* <../L/light-pipe.html>`__.

3. keyboard condom: A flexible, transparent plastic cover for a
keyboard, designed to provide some protection against dust and
`*programming fluid* <../P/programming-fluid.html>`__ without impeding
typing.

4. elephant condom: the plastic shipping bags used inside cardboard
boxes to protect hardware in transit.

5. n. obs. A dummy directory ``/usr/tmp/sh``, created to foil the
`*Great Worm* <../G/Great-Worm.html>`__ by exploiting a portability bug
in one of its parts. So named in the title of a ``comp.risks`` article
by Gene Spafford during the Worm crisis, and again in the text of The
Internet Worm Program: An Analysis*, Purdue Technical Report CSD-TR-823.



**confuser**: n.

Common soundalike slang for ‘computer’. Usually encountered in compounds
such as confuser room, personal confuser, confuser guru. Usage: silly.



**con**: n.

[from SF fandom] A science-fiction convention. Not used of other sorts
of conventions, such as professional meetings. This term, unlike many
others imported from SF-fan slang, is widely recognized even by hackers
who aren't `*fan* <../F/fan.html>`__\ s. “We'd been corresponding on the
net for months, then we met face-to-face at a con.”


**connector conspiracy**: n.

[probably came into prominence with the appearance of the KL-10 (one
model of the `*PDP-10* <../P/PDP-10.html>`__), none of whose connectors
matched anything else] The tendency of manufacturers (or, by extension,
programmers or purveyors of anything) to come up with new products that
don't fit together with the old stuff, thereby making you buy either all
new stuff or expensive interface devices.

(A closely related phenomenon, with a slightly different intent, is the
habit manufacturers have of inventing new screw heads so that only
Designated Persons, possessing the magic screwdrivers, can remove covers
and make repairs or install options. A good 1990s example is the use of
Torx screws for cable-TV set-top boxes. Older Apple Macintoshes took
this one step further, requiring not only a long Torx screwdriver but a
specialized case-cracking tool to open the box.)

In these latter days of open-systems computing this term has fallen
somewhat into disuse, to be replaced by the observation that “Standards
are great! There are so many of them to choose from!” Compare `*backward
combatability* <../B/backward-combatability.html>`__.



**cons**: /konz/, /kons/

[from LISP]

1. vt. To add a new element to a specified list, esp. at the top. “OK,
cons picking a replacement for the console TTY onto the agenda.”

2. cons up: vt. To synthesize from smaller pieces: “to cons up an
example”.

In LISP itself, **cons** is the most fundamental operation for building
structures. It takes any two objects and returns a dot-pair or
two-branched tree with one object hanging from each branch. Because the
result of a cons is an object, it can be used to build binary trees of
any shape and complexity. Hackers think of it as a sort of universal
constructor, and that is where the jargon meanings spring from.



**considered harmful**: adj.

[very common] Edsger W. Dijkstra's note in the March 1968
*Communications of the ACM*, *Goto Statement Considered Harmful*, fired
the first salvo in the structured programming wars (text at
`http://www.acm.org/classics/ <http://www.acm.org/classics/>`__). As it
`turns out <http://www.theregister.co.uk/content/4/26585.html>`__, the
title under which the letter appeared was actually supplied by CACM's
editor, Niklaus Wirth. Amusingly, the ACM considered the resulting
acrimony sufficiently harmful that it will (by policy) no longer print
an article taking so assertive a position against a coding practice.
(Years afterwards, a contrary view was uttered in a CACM letter called,
inevitably, *‘Goto considered harmful’ considered harmful'*'. In the
ensuing decades, a large number of both serious papers and parodies have
borne titles of the form *X considered Y*. The structured-programming
wars eventually blew over with the realization that both sides were
wrong, but use of such titles has remained as a persistent minor in-joke
(the ‘considered silly’ found at various places in this lexicon is
related).



**console**: n.

1. The operator's station of a `*mainframe* <../M/mainframe.html>`__. In
times past, this was a privileged location that conveyed godlike powers
to anyone with fingers on its keys. Under Unix and other modern
timesharing OSes, such privileges are guarded by passwords instead, and
the console is just the `*tty* <../T/tty.html>`__ the system was booted
from. Some of the mystique remains, however, and it is traditional for
sysadmins to post urgent messages to all users from the console (on
Unix, /dev/console).

2. On microcomputer Unix boxes, the main screen and keyboard (as opposed
to character-only terminals talking to a serial port). Typically only
the console can do real graphics or run `*X* <../X/X.html>`__.



**console jockey**: n.

See `*terminal junkie* <../T/terminal-junkie.html>`__.


**content-free**: adj.

[by analogy with techspeak context-free] Used of a message that adds
nothing to the recipient's knowledge. Though this adjective is sometimes
applied to `*flamage* <../F/flamage.html>`__, it more usually connotes
derision for communication styles that exalt form over substance or are
centered on concerns irrelevant to the subject ostensibly at hand.
Perhaps most used with reference to speeches by company presidents and
other professional manipulators. “Content-free? Uh... that's anything
printed on glossy paper.” (See also `*four-color
glossies* <../F/four-color-glossies.html>`__.) “He gave a talk on the
implications of electronic networks for postmodernism and the
fin-de-siecle aesthetic. It was content-free.”



**control-C**: vi.

1. “Stop whatever you are doing.” From the interrupt character used on
many operating systems to abort a running program. Considered silly.

2. interj. Among BSD Unix hackers, the canonical humorous response to
“Give me a break!”


**control-O**: vi.

“Stop talking.” From the character used on some operating systems to
abort output but allow the program to keep on running. Generally means
that you are not interested in hearing anything more from that person,
at least on that topic; a standard response to someone who is flaming.
Considered silly. Compare `*control-S* <control-S.html>`__.



**control-Q**: vi.

“Resume.” From the ASCII DC1 or `*XON* <../X/XON.html>`__ character (the
pronunciation /X-on/ is therefore also used), used to undo a previous
`*control-S* <control-S.html>`__.



**control-S**: vi.

“Stop talking for a second.” From the ASCII DC3 or XOFF character (the
pronunciation /X-of/ is therefore also used). Control-S differs from
`*control-O* <control-O.html>`__ in that the person is asked to stop
talking (perhaps because you are on the phone) but will be allowed to
continue when you're ready to listen to him — as opposed to control-O,
which has more of the meaning of “Shut up.” Considered silly.



**Conway's Law**: prov.

The rule that the organization of the software and the organization of
the software team will be congruent; commonly stated as “If you have
four groups working on a compiler, you'll get a 4-pass compiler”. The
original statement was more general, “Organizations which design systems
are constrained to produce designs which are copies of the communication
structures of these organizations.” This first appeared in the April
1968 issue of `*Datamation* <../D/Datamation.html>`__. Compare `*SNAFU
principle* <../S/SNAFU-principle.html>`__.

The law was named after Melvin Conway, an early proto-hacker who wrote
an assembler for the Burroughs 220 called SAVE. (The name ‘SAVE’ didn't
stand for anything; it was just that you lost fewer card decks and
listings because they all had SAVE written on them.) There is also Tom
Cheatham's amendment of Conway's Law: “If a group of N persons
implements a COBOL compiler, there will be N-1 passes. Someone in the
group has to be the manager.”



**cookbook**: n.

[from amateur electronics and radio] A book of small code segments that
the reader can use to do various `*magic* <../M/magic.html>`__ things in
programs. Cookbooks, slavishly followed, can lead one into `*voodoo
programming* <../V/voodoo-programming.html>`__, but are useful for
hackers trying to `*monkey up* <../M/monkey-up.html>`__ small programs
in unknown languages. This function is analogous to the role of
phrasebooks in human languages.



**cooked mode**: n.

[Unix, by opposition from `*raw mode* <../R/raw-mode.html>`__] The
normal character-input mode, with interrupts enabled and with erase,
kill and other special-character interpretations performed directly by
the tty driver. Oppose `*raw mode* <../R/raw-mode.html>`__, `*rare
mode* <../R/rare-mode.html>`__. This term is techspeak under Unix but
jargon elsewhere; other operating systems often have similar mode
distinctions, and the raw/rare/cooked way of describing them has spread
widely along with the C language and other Unix exports. Most generally,
cooked mode may refer to any mode of a system that does extensive
preprocessing before presenting data to a program.



**cookie bear**: n. obs.

Original term, pre-Sesame-Street, for what is now universally called a
`*cookie monster* <cookie-monster.html>`__. A correspondent observes “In
those days, hackers were actually getting their yucks from...sit down
now...Andy Williams. Yes, *that* Andy Williams. Seems he had a rather
hip (by the standards of the day) TV variety show. One of the best parts
of the show was the recurring ‘cookie bear’ sketch. In these sketches, a
guy in a bear suit tried all sorts of tricks to get a cookie out of
Williams. The sketches would always end with Williams shrieking (and I
don't mean figuratively), ‘No cookies! Not now, not ever...NEVER!!!’ And
the bear would fall down. Great stuff.”



**cookie file**: n.

A collection of `*fortune cookie* <../F/fortune-cookie.html>`__\ s in a
format that facilitates retrieval by a fortune program. There are
several different cookie files in public distribution, and site admins
often assemble their own from various sources including this lexicon.



**cookie**: n.

A handle, transaction ID, or other token of agreement between
cooperating programs. “I give him a packet, he gives me back a cookie.”
The claim check you get from a dry-cleaning shop is a perfect mundane
example of a cookie; the only thing it's useful for is to relate a later
transaction to this one (so you get the same clothes back). Syn. `*magic
cookie* <../M/magic-cookie.html>`__; see also `*fortune
cookie* <../F/fortune-cookie.html>`__. Now mainstream in the specific
sense of web-browser cookies.



**cookie jar**: n.

An area of memory set aside for storing `*cookie* <cookie.html>`__\ s.
Most commonly heard in the Atari ST community; many useful ST programs
record their presence by storing a distinctive `*magic
number* <../M/magic-number.html>`__ in the jar. Programs can inquire
after the presence or otherwise of other programs by searching the
contents of the jar.



**cookie monster**: n.

[from the children's TV program *Sesame Street*] Any of a family of
early (1970s) hacks reported on `*TOPS-10* <../T/TOPS-10.html>`__,
`*ITS* <../I/ITS.html>`__, `*Multics* <../M/Multics.html>`__, and
elsewhere that would lock up either the victim's terminal (on a
timesharing machine) or the `*console* <console.html>`__ (on a batch
`*mainframe* <../M/mainframe.html>`__), repeatedly demanding “I WANT A
COOKIE”. The required responses ranged in complexity from “COOKIE”
through “HAVE A COOKIE” and upward. Folklorist Jan Brunvand (see
`*FOAF* <../F/FOAF.html>`__) has described these programs as urban
legends (implying they probably never existed) but they existed, all
right, in several different versions. See also
`*wabbit* <../W/wabbit.html>`__. Interestingly, the term cookie monster
appears to be a `*retcon* <../R/retcon.html>`__; the original term was
`*cookie bear* <cookie-bear.html>`__.



**copious free time**: n.

[Apple; orig. fr. the intro to Tom Lehrer's song *It Makes A Fellow
Proud To Be A Soldier*]

1. [used ironically to indicate the speaker's lack of the quantity in
question] A mythical schedule slot for accomplishing tasks held to be
unlikely or impossible. Sometimes used to indicate that the speaker is
interested in accomplishing the task, but believes that the opportunity
will not arise. “I'll implement the automatic layout stuff in my copious
free time.”

2. [Archly] Time reserved for bogus or otherwise idiotic tasks, such as
implementation of `*chrome* <chrome.html>`__, or the stroking of
`*suit* <../S/suit.html>`__\ s. “I'll get back to him on that feature in
my copious free time.”



**copper**: n.

Conventional electron-carrying network cable with a core conductor of
copper — or aluminum! Opposed to `*light pipe* <../L/light-pipe.html>`__
or, say, a short-range microwave link.



**copybroke**: /kop´ee·brohk/, adj.

1. [play on copyright] Used to describe an instance of a copy-protected
program that has been ‘broken’; that is, a copy with the copy-protection
scheme disabled. Syn. `*copywronged* <copywronged.html>`__.

2. Copy-protected software which is unusable because of some bit-rot or
bug that has confused the anti-piracy check. See also `*copy
protection* <copy-protection.html>`__.



**copycenter**: n.

[play on ‘copyright’ and ‘copyleft’]

1. The copyright notice carried by the various flavors of freeware BSD.
According to Kirk McKusick at BSDCon 1999: “The way it was characterized
politically, you had copyright, which is what the big companies use to
lock everything up; you had copyleft, which is free software's way of
making sure they can't lock it up; and then Berkeley had what we called
‘copycenter’, which is ‘take it down to the copy center and make as many
copies as you want’”.



**copyleft**: /kop´ee·left/, n.

[play on copyright]

1. The copyright notice (‘General Public License’) carried by
`*GNU* <../G/GNU.html>`__ `*EMACS* <../E/EMACS.html>`__ and other Free
Software Foundation software, granting reuse and reproduction rights to
all comers (but see also `*General Public
Virus* <../G/General-Public-Virus.html>`__).

2. By extension, any copyright notice intended to achieve similar aims.



**copyparty**: n.

[C64/amiga `*demoscene* <../D/demoscene.html>`__] A computer party
organized so demosceners can meet other in real life, and to facilitate
software copying (mostly pirated software). The copyparty has become
less common as the Internet makes communication easier. The demoscene
has gradually evolved the `*demoparty* <../D/demoparty.html>`__ to
replace it.



**copy protection**: n.

A class of methods for preventing incompetent pirates from stealing
software and legitimate customers from using it. Considered silly.



**copywronged**: /kop´ee·rongd/, adj.

[play on copyright] Syn. for `*copybroke* <copybroke.html>`__.



**core cancer**: n.

[rare] A process that exhibits a slow but inexorable resource
`*leak* <../L/leak.html>`__ — like a cancer, it kills by crowding out
productive tissue.



**core dump**: n.

[common `*Iron Age* <../I/Iron-Age.html>`__ jargon, preserved by Unix]

1. [techspeak] A copy of the contents of `*core* <core.html>`__,
produced when a process is aborted by certain kinds of internal error.

2. By extension, used for humans passing out, vomiting, or registering
extreme shock. “He dumped core. All over the floor. What a mess.” “He
heard about X and dumped core.”

3. Occasionally used for a human rambling on pointlessly at great
length; esp. in apology: “Sorry, I dumped core on you”.

4. A recapitulation of knowledge (compare `*bits* <../B/bits.html>`__,
sense 1). Hence, spewing all one knows about a topic (syn. `*brain
dump* <../B/brain-dump.html>`__), esp. in a lecture or answer to an exam
question. “Short, concise answers are better than core dumps” (from the
instructions to an exam at Columbia). See `*core* <core.html>`__.

|image0|

A `*core dump* <core-dump.html>`__ lands our hero in hot water.

(This is the last cartoon in the Crunchly saga. The previous cartoon was
`76-05-01 <../S/Stone-Age.html#crunchly76-05-01>`__.)



**core**: n.

Main storage or RAM. Dates from the days of ferrite-core memory; now
archaic as techspeak most places outside IBM, but also still used in the
Unix community and by old-time hackers or those who would sound like
them. Some derived idioms are quite current; in core, for example, means
‘in memory’ (as opposed to ‘on disk’), and both `*core
dump* <core-dump.html>`__ and the core image or core file produced by
one are terms in favor. Some varieties of Commonwealth hackish prefer
`*store* <../S/store.html>`__.



**core leak**: n.

Syn. `*memory leak* <../M/memory-leak.html>`__.



**Core Wars**: n.

A game between assembler programs in a machine or machine simulator,
where the objective is to kill your opponent's program by overwriting
it. Popularized in the 1980s by A. K. Dewdney's column in *Scientific
American* magazine, but described in *Software Practice And Experience*
a decade earlier. The game was actually devised and played by Victor
Vyssotsky, Robert Morris Sr., and Doug McIlroy in the early 1960s
(Dennis Ritchie is sometimes incorrectly cited as a co-author, but was
not involved). Their original game was called ‘Darwin’ and ran on a IBM
7090 at Bell Labs. See `*core* <core.html>`__. For information on the
modern game, do a web search for the ‘rec.games.corewar FAQ’ or surf to
the `King Of The Hill <http://www.koth.org/>`__ site.



**cosmic rays**: n.

Notionally, the cause of `*bit rot* <../B/bit-rot.html>`__. However,
this is a semi-independent usage that may be invoked as a humorous way
to `*handwave* <../H/handwave.html>`__ away any minor
`*randomness* <../R/randomness.html>`__ that doesn't seem worth the
bother of investigating. “Hey, Eric — I just got a burst of garbage on
my `*tube* <../T/tube.html>`__, where did that come from?” “Cosmic rays,
I guess.” Compare `*sunspots* <../S/sunspots.html>`__, `*phase of the
moon* <../P/phase-of-the-moon.html>`__. The British seem to prefer the
usage cosmic showers; alpha particles is also heard, because stray alpha
particles passing through a memory chip can cause single-bit errors
(this becomes increasingly more likely as memory sizes and densities
increase).

Factual note: Alpha particles cause bit rot, cosmic rays do not (except
occasionally in spaceborne computers). Intel could not explain random
bit drops in their early chips, and one hypothesis was cosmic rays. So
they created the World's Largest Lead Safe, using 25 tons of the stuff,
and used two identical boards for testing. One was placed in the safe,
one outside. The hypothesis was that if cosmic rays were causing the bit
drops, they should see a statistically significant difference between
the error rates on the two boards. They did not observe such a
difference. Further investigation demonstrated conclusively that the bit
drops were due to alpha particle emissions from thorium (and to a much
lesser degree uranium) in the encapsulation material. Since it is
impossible to eliminate these radioactives (they are uniformly
distributed through the earth's crust, with the statistically
insignificant exception of uranium lodes) it became obvious that one has
to design memories to withstand these hits.



**cough and die**: v.

Syn. `*barf* <../B/barf.html>`__. Connotes that the program is throwing
its hands up by design rather than because of a bug or oversight. “The
parser saw a control-A in its input where it was looking for a
printable, so it coughed and died.” Compare `*die* <../D/die.html>`__,
`*die horribly* <../D/die-horribly.html>`__, `*scream and
die* <../S/scream-and-die.html>`__.



**courier**

[BBS & cracker cultures] A person who distributes newly cracked
`*warez* <../W/warez.html>`__, as opposed to a
`*server* <../S/server.html>`__ who makes them available for download or
a `*leech* <../L/leech.html>`__ who merely downloads them. Hackers
recognize this term but don't use it themselves, as the act is not part
of their culture. See also `*warez d00dz* <../W/warez-d00dz.html>`__,
`*cracker* <cracker.html>`__, `*elite* <../E/elite.html>`__.



**cowboy**: n.

[Sun, from William Gibson's `*cyberpunk* <cyberpunk.html>`__ SF] Synonym
for `*hacker* <../H/hacker.html>`__. It is reported that at Sun this
word is often said with reverence.



**cow orker**: n.

[Usenet] n. fortuitous typo for co-worker, widely used in Usenet, with
perhaps a hint that orking cows is illegal. This term was popularized by
Scott Adams (the creator of `*Dilbert* <../D/Dilbert.html>`__) but
already appears in the January 1996 version of the `*scary devil
monastery* <../S/scary-devil-monastery.html>`__ FAQ, and has been traced
back to a 1989 `*sig block* <../S/sig-block.html>`__. Compare
`*hing* <../H/hing.html>`__, `*grilf* <../G/grilf.html>`__,
`*filk* <../F/filk.html>`__, `*newsfroup* <../N/newsfroup.html>`__.



**C++**: /C'·pluhs·pluhs/, n.

Designed by Bjarne Stroustrup of AT&T Bell Labs as a successor to
`*C* <C.html>`__. Now one of the `*languages of
choice* <../L/languages-of-choice.html>`__, although many hackers still
grumble that it is the successor to either Algol 68 or Ada (depending on
generation), and a prime example of `*second-system
effect* <../S/second-system-effect.html>`__. Almost anything that can be
done in any language can be done in C++, but it requires a `*language
lawyer* <../L/language-lawyer.html>`__ to know what is and what is not
legal — the design is *almost* too large to hold in even hackers' heads.
Much of the `*cruft* <cruft.html>`__ results from C++'s attempt to be
backward compatible with C. Stroustrup himself has said in his
retrospective book *The Design and Evolution of C++* (p. 207), “Within
C++, there is a much smaller and cleaner language struggling to get
out.” [Many hackers would now add “Yes, and it's called
`*Java* <../J/Java.html>`__\ ” —ESR]

|image0|

Nowadays we say this of C++.


**CP/M**: /C·P·M/, n.

[Control Program/Monitor; later `*retcon* <../R/retcon.html>`__\ ned to
Control Program for Microcomputers] An early microcomputer
`*OS* <../O/OS.html>`__ written by hacker Gary Kildall for 8080- and
Z80-based machines, very popular in the late 1970s but virtually wiped
out by MS-DOS after the release of the IBM PC in 1981. Legend has it
that Kildall's company blew its chance to write the OS for the IBM PC
because Kildall decided to spend a day IBM's reps wanted to meet with
him enjoying the perfect flying weather in his private plane (another
variant has it that Gary's wife was much more interested in packing her
suitcases for an upcoming vacation than in clinching a deal with IBM).
Many of CP/M's features and conventions strongly resemble those of early
`*DEC* <../D/DEC.html>`__ operating systems such as
`*TOPS-10* <../T/TOPS-10.html>`__, OS/8, RSTS, and RSX-11. See
`*MS-DOS* <../M/MS-DOS.html>`__, `*operating
system* <../O/operating-system.html>`__.



**C Programmer's Disease**: n.

The tendency of the undisciplined C programmer to set arbitrary but
supposedly generous static limits on table sizes (defined, if you're
lucky, by constants in header files) rather than taking the trouble to
do proper dynamic storage allocation. If an application user later needs
to put 68 elements into a table of size 50, the afflicted programmer
reasons that he or she can easily reset the table size to 68 (or even as
much as 70, to allow for future expansion) and recompile. This gives the
programmer the comfortable feeling of having made the effort to satisfy
the user's (unreasonable) demands, and often affords the user multiple
opportunities to explore the marvelous consequences of `*fandango on
core* <../F/fandango-on-core.html>`__. In severe cases of the disease,
the programmer cannot comprehend why each fix of this kind seems only to
further disgruntle the user.



**CPU Wars**: /C·P·U worz/, n.

A 1979 large-format comic by Chas Andres chronicling the attempts of the
brainwashed androids of IPM (Impossible to Program Machines) to conquer
and destroy the peaceful denizens of HEC (Human Engineered Computers).
This rather transparent allegory featured many references to
`*ADVENT* <../A/ADVENT.html>`__ and the immortal line “Eat flaming
death, minicomputer mongrels!” (uttered, of course, by an IPM
stormtrooper). The whole shebang is now `available on the
Web <http://www.e-pix.com/CPUWARS/cpuwars.html>`__.

It is alleged that the author subsequently received a letter of
appreciation on IBM company stationery from the head of IBM's Thomas J.
Watson Research Laboratories (at that time one of the few islands of
true hackerdom in the IBM archipelago). The lower loop of the B in the
IBM logo, it is said, had been carefully whited out. See `*eat flaming
death* <../E/eat-flaming-death.html>`__.



**cracker**: n.

One who breaks security on a system. Coined ca. 1985 by hackers in
defense against journalistic misuse of `*hacker* <../H/hacker.html>`__
(q.v., sense 8). An earlier attempt to establish worm in this sense
around 1981--82 on Usenet was largely a failure.

Use of both these neologisms reflects a strong revulsion against the
theft and vandalism perpetrated by cracking rings. The neologism
“cracker” in this sense may have been influenced not so much by the term
“safe-cracker” as by the non-jargon term “cracker”, which in Middle
English meant an obnoxious person (e.g., “What cracker is this same that
deafs our ears / With this abundance of superfluous breath?” —
Shakespeare's King John, Act II, Scene I) and in modern colloquial
American English survives as a barely gentler synonym for “white trash”.

While it is expected that any real hacker will have done some playful
cracking and knows many of the basic techniques, anyone past `*larval
stage* <../L/larval-stage.html>`__ is expected to have outgrown the
desire to do so except for immediate, benign, practical reasons (for
example, if it's necessary to get around some security in order to get
some work done).

Thus, there is far less overlap between hackerdom and crackerdom than
the `*mundane* <../M/mundane.html>`__ reader misled by sensationalistic
journalism might expect. Crackers tend to gather in small, tight-knit,
very secretive groups that have little overlap with the huge, open
poly-culture this lexicon describes; though crackers often like to
describe *themselves* as hackers, most true hackers consider them a
separate and lower form of life. An easy way for outsiders to spot the
difference is that crackers use grandiose screen names that conceal
their identities. Hackers never do this; they only rarely use *noms de
guerre* at all, and when they do it is for display rather than
concealment.

Ethical considerations aside, hackers figure that anyone who can't
imagine a more interesting way to play with their computers than
breaking into someone else's has to be pretty
`*losing* <../L/losing.html>`__. Some other reasons crackers are looked
down on are discussed in the entries on `*cracking* <cracking.html>`__
and `*phreaking* <../P/phreaking.html>`__. See also
`*samurai* <../S/samurai.html>`__, `*dark-side
hacker* <../D/dark-side-hacker.html>`__, and `*hacker
ethic* <../H/hacker-ethic.html>`__. For a portrait of the typical
teenage cracker, see `*warez d00dz* <../W/warez-d00dz.html>`__.



**crack**

[warez d00dz]

1. v. To break into a system (compare `*cracker* <cracker.html>`__).

2. v. Action of removing the copy protection from a commercial program.
People who write cracks consider themselves challenged by the copy
protection measures. They will often do it as much to show that they are
smarter than the developer who designed the copy protection scheme than
to actually copy the program.

3. n. A program, instructions or patch used to remove the copy
protection of a program or to uncripple features from a demo/time
limited program.

4. An `*exploit* <../E/exploit.html>`__.



**cracking**: n.

[very common] The act of breaking into a computer system; what a
`*cracker* <cracker.html>`__ does. Contrary to widespread myth, this
does not usually involve some mysterious leap of hackerly brilliance,
but rather persistence and the dogged repetition of a handful of fairly
well-known tricks that exploit common weaknesses in the security of
target systems. Accordingly, most crackers are incompetent as hackers.
This entry used to say 'mediocre', but the spread of
`*rootkit* <../R/rootkit.html>`__ and other automated cracking has
depressed the average level of skill among crackers.



**crack root**: v.

[very common] To defeat the security system of a Unix machine and gain
`*root* <../R/root.html>`__ privileges thereby; see
`*cracking* <cracking.html>`__.


**crank**: vt.

[from automotive slang] Verb used to describe the performance of a
machine, especially sustained performance. “This box cranks (or, cranks
at) about 6 megaflops, with a burst mode of twice that on vectorized
operations.”



**crapplet**: n.

[portmanteau, crap + applet] A worthless applet, esp. a Java widget
attached to a web page that doesn't work or even crashes your browser.
Also spelled ‘craplet’.



**CrApTeX**: /krap´tekh/, n.

[University of York, England] Term of abuse used to describe TeX and
LaTeX when they don't work (when used by TeXhackers), or all the time
(by everyone else). The non-TeX-enthusiasts generally dislike it because
it is more verbose than other formatters (e.g.
`*troff* <../T/troff.html>`__) and because (particularly if the standard
Computer Modern fonts are used) it generates vast output files. See
`*religious issues* <../R/religious-issues.html>`__,
`*TeX* <../T/TeX.html>`__.


**crash and burn**: vi.,n.

A spectacular crash, in the mode of the conclusion of the car-chase
scene in the movie *Bullitt* and many subsequent imitators (compare
`*die horribly* <../D/die-horribly.html>`__). The construction
crash-and-burn machine is reported for a computer used exclusively for
alpha or `*beta* <../B/beta.html>`__ testing, or reproducing bugs (i.e.,
not for development). The implication is that it wouldn't be such a
disaster if that machine crashed, since only the testers would be
inconvenienced.



**crash**

1. n. A sudden, usually drastic failure. Most often said of the
`*system* <../S/system.html>`__ (q.v., sense 1), esp. of magnetic disk
drives (the term originally described what happens when the air gap of a
hard disk collapses). “Three `*luser* <../L/luser.html>`__\ s lost their
files in last night's disk crash.” A disk crash that involves the
read/write heads dropping onto the surface of the disks and scraping off
the oxide may also be referred to as a head crash, whereas the term
system crash usually, though not always, implies that the operating
system or other software was at fault.

2. v. To fail suddenly. “Has the system just crashed?” “Something
crashed the OS!” See `*down* <../D/down.html>`__. Also used transitively
to indicate the cause of the crash (usually a person or a program, or
both). “Those idiots playing `*SPACEWAR* <../S/SPACEWAR.html>`__ crashed
the system.”

3. vi. Sometimes said of people hitting the sack after a long `*hacking
run* <../H/hacking-run.html>`__; see `*gronk
out* <../G/gronk-out.html>`__.



**crawling horror**: n.

Ancient crufty hardware or software that is kept obstinately alive by
forces beyond the control of the hackers at a site. Like `*dusty
deck* <../D/dusty-deck.html>`__ or
`*gonkulator* <../G/gonkulator.html>`__, but connotes that the thing
described is not just an irritation but an active menace to health and
sanity. “Mostly we code new stuff in C, but they pay us to maintain one
big FORTRAN II application from nineteen-sixty-X that's a real crawling
horror....” Compare `*WOMBAT* <../W/WOMBAT.html>`__.

This usage is almost certainly derived from the fiction of H.P.
Lovecraft. Lovecraft may never have used the exact phrase “crawling
horror” in his writings, but one of the fearsome Elder Gods that he
wrote extensively about was Nyarlethotep, who had as an epithet “The
Crawling Chaos”. Certainly the extreme, even melodramatic horror of his
characters at the weird monsters they encounter, even to the point of
going insane with fear, is what hackers are referring to with this
phrase when they use it for horribly bad code. Compare
`*cthulhic* <cthulhic.html>`__.



**CRC handbook**

Any of the editions of the *Chemical Rubber Company Handbook of
Chemistry and Physics*; there are other CRC handbooks, such as the *CRC
Standard Mathematical Tables and Formulae*, but “the” CRC handbook is
the chemistry and physics reference. It is massive tome full of
mathematical tables, physical constants of thousands of alloys and
chemical compounds, dielectric strengths, vapor pressure, resistivity,
and the like. Hackers have remarkably little actual use for these sorts
of arcana, but are such information junkies that a large percentage of
them acquire copies anyway and would feel vaguely bereft if they
couldn't look up the magnetic susceptibility of potassium permanganate
at a moment's notice. On hackers' bookshelves, the CRC handbook is
rather likely to keep company with an unabridged Oxford English
Dictionary and a good atlas.

**creationism**: n.

The (false) belief that large, innovative software designs can be
completely specified in advance and then painlessly magicked out of the
void by the normal efforts of a team of normally talented programmers.
In fact, experience has shown repeatedly that good designs arise only
from evolutionary, exploratory interaction between one (or at most a
small handful of) exceptionally able designer(s) and an active user
population — and that the first try at a big new idea is always wrong.
Unfortunately, because these truths don't fit the planning models
beloved of `*management* <../M/management.html>`__, they are generally
ignored.



**creep**: v.

To advance, grow, or multiply inexorably. In hackish usage this verb has
overtones of menace and silliness, evoking the creeping horrors of
low-budget monster movies.



**creeping elegance**: n.

Describes a tendency for parts of a design to become
`*elegant* <../E/elegant.html>`__ past the point of diminishing return,
something which often happens at the expense of the less interesting
parts of the design, the schedule, and other things deemed important in
the `*Real World* <../R/Real-World.html>`__. See also `*creeping
featurism* <creeping-featurism.html>`__, `*second-system
effect* <../S/second-system-effect.html>`__,
`*tense* <../T/tense.html>`__.



**creeping featurism**: /kree´ping fee´chr·izm/, n.

[common]

1. Describes a systematic tendency to load more
`*chrome* <chrome.html>`__ and `*feature* <../F/feature.html>`__\ s onto
systems at the expense of whatever elegance they may have possessed when
originally designed. See also `*feeping
creaturism* <../F/feeping-creaturism.html>`__. “You know, the main
problem with `*BSD* <../B/BSD.html>`__ Unix has always been creeping
featurism.”

2. More generally, the tendency for anything complicated to become even
more complicated because people keep saying “Gee, it would be even
better if it had this feature too”. (See
`*feature* <../F/feature.html>`__.) The result is usually a patchwork
because it grew one ad-hoc step at a time, rather than being planned.
Planning is a lot of work, but it's easy to add just one extra little
feature to help someone ... and then another ... and another.... When
creeping featurism gets out of hand, it's like a cancer. The GNU hello
program, intended to illustrate `*GNU* <../G/GNU.html>`__ command-line
switch and coding conventions, is also a wonderful parody of creeping
featurism; the distribution changelog is particularly funny. Usually
this term is used to describe computer programs, but it could also be
said of the federal government, the IRS 1040 form, and new cars. A
similar phenomenon sometimes afflicts conscious redesigns; see
`*second-system effect* <../S/second-system-effect.html>`__. See also
`*creeping elegance* <creeping-elegance.html>`__.



**creeping featuritis**: /kree´ping fee'·chr·i:\`t@s/, n.

Variant of `*creeping featurism* <creeping-featurism.html>`__, with its
own spoonerization: feeping creaturitis. Some people like to reserve
this form for the disease as it actually manifests in software or
hardware, as opposed to the lurking general tendency in designers'
minds. (After all, -ism means ‘condition’ or ‘pursuit of’, whereas -itis
usually means ‘inflammation of’.)



**cretin**: /kret´in/, /kree´tn/, n.

Congenital `*loser* <../L/loser.html>`__; an obnoxious person; someone
who can't do anything right. It has been observed that many American
hackers tend to favor the British pronunciation /kret´in/ over standard
American /kree´tn/; it is thought this may be due to the insidious
phonetic influence of Monty Python's Flying Circus.



**cretinous**: /kret´n·@s/, /kreet´n·@s/, adj.

Wrong; stupid; non-functional; very poorly designed. Also used
pejoratively of people. See `*dread high-bit
disease* <../D/dread-high-bit-disease.html>`__ for an example.
Approximate synonyms: `*bletcherous* <../B/bletcherous.html>`__,
`*bagbiting* <../B/bagbiting.html>`__, `*losing* <../L/losing.html>`__,
`*brain-damaged* <../B/brain-damaged.html>`__.


**crippleware**: n.

1. [common] Software that has some important functionality deliberately
removed, so as to entice potential users to pay for a working version.

2. [Cambridge] Variety of `*guiltware* <../G/guiltware.html>`__ that
exhorts you to donate to some charity (compare
`*careware* <careware.html>`__, `*nagware* <../N/nagware.html>`__).

3. Hardware deliberately crippled, which can be upgraded to a more
expensive model by a trivial change (e.g., cutting a jumper).

An excellent example of crippleware (sense 3) is Intel's 486SX chip,
which is a standard 486DX chip with the co-processor diked out (in some
early versions it was present but disabled). To upgrade, you buy a
complete 486DX chip with *working* co-processor (its identity thinly
veiled by a different pinout) and plug it into the board's expansion
socket. It then disables the SX, which becomes a fancy power sink. Don't
you love Intel?



**critical mass**: n.

In physics, the minimum amount of fissionable material required to
sustain a chain reaction. Of a software product, describes a condition
of the software such that fixing one bug introduces one plus
`*epsilon* <../E/epsilon.html>`__ bugs. (This malady has many causes:
`*creeping featurism* <creeping-featurism.html>`__, ports to too many
disparate environments, poor initial design, etc.) When software
achieves critical mass, it can never be fixed; it can only be discarded
and rewritten.



**crlf**: /ker´l@f/, /kru´l@f/, /C·R·L·F/, n.

(often capitalized as ‘CRLF’) A carriage return (CR, ASCII 0001101)
followed by a line feed (LF, ASCII 0001010). More loosely, whatever it
takes to get you from the end of one line of text to the beginning of
the next line. See `*newline* <../N/newline.html>`__. Under
`*Unix* <../U/Unix.html>`__ influence this usage has become less common
(Unix uses a bare line feed as its ‘CRLF’).



**crock**: n.

[from the American scatologism crock of shit]

1. An awkward feature or programming technique that ought to be made
cleaner. For example, using small integers to represent error codes
without the program interpreting them to the user (as in, for example,
Unix make(1), which returns code 139 for a process that dies due to
`*segfault* <../S/segfault.html>`__).

2. A technique that works acceptably, but which is quite prone to
failure if disturbed in the least. For example, a too-clever programmer
might write an assembler which mapped instruction mnemonics to numeric
opcodes algorithmically, a trick which depends far too intimately on the
particular bit patterns of the opcodes. (For another example of
programming with a dependence on actual opcode values, see `The Story of
Mel' <../story-of-mel.html>`__ in Appendix A.) Many crocks have a
tightly woven, almost completely unmodifiable structure. See
`*kluge* <../K/kluge.html>`__, `*brittle* <../B/brittle.html>`__. The
adjectives crockish and crocky, and the nouns crockishness and
crockitude, are also used.



**crossload**: v.,n.

[proposed, by analogy with `*upload* <../U/upload.html>`__ and
`*download* <../D/download.html>`__] To move files between machines on a
peer-to-peer network of nodes that act as both servers and clients for a
distributed file store. Esp. appropriate for anonymized networks like
Gnutella and Freenet.



**cross-post**: vi.

[Usenet; very common] To post a single article simultaneously to several
newsgroups. Distinguished from posting the article repeatedly, once to
each newsgroup, which causes people to see it multiple times (which is
very bad form). Gratuitous cross-posting without a Followup-To line
directing responses to a single followup group is frowned upon, as it
tends to cause `*followup* <../F/followup.html>`__ articles to go to
inappropriate newsgroups when people respond to various parts of the
original posting.



**crudware**: /kruhd´weir/, n.

Pejorative term for the hundreds of megabytes of low-quality
`*freeware* <../F/freeware.html>`__ circulated by user's groups and BBS
systems in the micro-hobbyist world. “Yet *another* set of disk catalog
utilities for `*MS-DOS* <../M/MS-DOS.html>`__? What crudware!”



**cruft**: /kruhft/

[very common; back-formation from `*crufty* <crufty.html>`__]

1. n. An unpleasant substance. The dust that gathers under your bed is
cruft; the TMRC Dictionary correctly noted that attacking it with a
broom only produces more.

2. n. The results of shoddy construction.

3. vt. [from hand cruft, pun on ‘hand craft’] To write assembler code
for something normally (and better) done by a compiler (see
`*hand-hacking* <../H/hand-hacking.html>`__).

4. n. Excess; superfluous junk; used esp. of redundant or superseded
code.

5. [University of Wisconsin] n. Cruft is to hackers as gaggle is to
geese; that is, at UW one properly says “a cruft of hackers”.



**cruftsmanship**: /kruhfts´m@n·ship /, n.

[from `*cruft* <cruft.html>`__] The antithesis of craftsmanship.



**cruft together**: vt.

(also cruft up) To throw together something ugly but temporarily
workable. Like vt. `*kluge up* <../K/kluge-up.html>`__, but more
pejorative. “There isn't any program now to reverse all the lines of a
file, but I can probably cruft one together in about 10 minutes.” See
`*hack together* <../H/hack-together.html>`__, `*hack
up* <../H/hack-up.html>`__, `*kluge up* <../K/kluge-up.html>`__,
`*crufty* <crufty.html>`__.



**crufty**: /kruhf´tee/, adj.

[very common; origin unknown; poss. from ‘crusty’ or ‘cruddy’]

1. Poorly built, possibly over-complex. The
`*canonical* <canonical.html>`__ example is “This is standard old crufty
`*DEC* <../D/DEC.html>`__ software”. In fact, one fanciful theory of the
origin of crufty holds that was originally a mutation of ‘crusty’
applied to DEC software so old that the ‘s’ characters were tall and
skinny, looking more like ‘f’ characters.

2. Unpleasant, especially to the touch, often with encrusted junk. Like
spilled coffee smeared with peanut butter and catsup.

3. Generally unpleasant.

4. (sometimes spelled cruftie) n. A small crufty object (see
`*frob* <../F/frob.html>`__); often one that doesn't fit well into the
scheme of things. “A LISP property list is a good place to store
crufties (or, collectively, `*random* <../R/random.html>`__ cruft).”

This term is one of the oldest in the jargon and no one is sure of its
etymology, but it is suggestive that there is a Cruft Hall at Harvard
University which is part of the old physics building; it's said to have
been the physics department's radar lab during WWII. To this day (early
1993) the windows appear to be full of random techno-junk. MIT or
Lincoln Labs people may well have coined the term as a knock on the
competition.



**crumb**: n.

Two binary digits; a `*quad* <../Q/quad.html>`__. Larger than a
`*bit* <../B/bit.html>`__, smaller than a
`*nybble* <../N/nybble.html>`__. Considered silly. Syn.
`*tayste* <../T/tayste.html>`__. General discussion of such terms is
under `*nybble* <../N/nybble.html>`__.


**crunch**

1. vi. To process, usually in a time-consuming or complicated way.
Connotes an essentially trivial operation that is nonetheless painful to
perform. The pain may be due to the triviality's being embedded in a
loop from 1 to 1,000,000,000. “FORTRAN programs do mostly
`*number-crunching* <../N/number-crunching.html>`__.”

2. vt. To reduce the size of a file by a complicated scheme that
produces bit configurations completely unrelated to the original data,
such as by a Huffman code. (The file ends up looking something like a
paper document would if somebody crunched the paper into a wad.) Since
such compression usually takes more computations than simpler methods
such as run-length encoding, the term is doubly appropriate. (This
meaning is usually used in the construction file crunch(ing) to
distinguish it from
`*number-crunching* <../N/number-crunching.html>`__.) See
`*compress* <compress.html>`__.

3. n. The character ``#``. Used at XEROX and CMU, among other places.
See `*ASCII* <../A/ASCII.html>`__.

4. vt. To squeeze program source into a minimum-size representation that
will still compile or execute. The term came into being specifically for
a famous program on the BBC micro that crunched BASIC source in order to
make it run more quickly (it was a wholly interpretive BASIC, so the
number of characters mattered). `*Obfuscated C
Contest* <../O/Obfuscated-C-Contest.html>`__ entries are often crunched;
see the first example under that entry.



**cryppie**: /krip´ee/, n.

A cryptographer. One who hacks or implements cryptographic software or
hardware.



**cthulhic**: /kthool´hik/, adj.

Having the nature of a Cthulhu, the horrific tentacled green monstrosity
from H.P. Lovecraft's seminal horror fiction. Cthulhu sends dreams that
drive men mad, feeds on the flesh of screaming victims rent limb from
limb, and is served by a cult of degenerates. Hackers think this
describes large `*proprietary* <../P/proprietary.html>`__ systems such
as traditional `*mainframe* <../M/mainframe.html>`__\ s, installations
of SAP and Oracle, or rooms full of Windows servers remarkably well, and
the adjective is used casually. Compare
`*Shub-Internet* <../S/Shub-Internet.html>`__ and `*crawling
horror* <crawling-horror.html>`__.



**CTSS**: /C·T·S·S/, n.

Compatible Time-Sharing System. An early (1963) experiment in the design
of interactive timesharing operating systems, ancestral to
`*Multics* <../M/Multics.html>`__, `*Unix* <../U/Unix.html>`__, and
`*ITS* <../I/ITS.html>`__. The name `*ITS* <../I/ITS.html>`__
(Incompatible Time-sharing System) was a hack on CTSS, meant both as a
joke and to express some basic differences in philosophy about the way
I/O services should be presented to user programs. See
`*timesharing* <../T/timesharing.html>`__



**cube**: n.

1. [short for ‘cubicle’] A module in the open-plan offices used at many
programming shops. “I've got the manuals in my cube.”

2. A NeXT machine (which resembles a matte-black cube).



**cup holder**: n.

The tray of a CD-ROM drive, or by extension the CD drive itself. So
called because of a common tech support legend about the idiot who
called to complain that the cup holder on his computer broke. A joke
program was once distributed around the net called “cupholder.exe”,
which when run simply extended the CD drive tray. The humor of this was
of course lost on people whose drive had a slot or a caddy instead.


**cursor dipped in X**: n.

There are a couple of metaphors in English of the form ‘pen dipped in X’
(perhaps the most common values of X are ‘acid’, ‘bile’, and ‘vitriol’).
These map over neatly to this hackish usage (the cursor being what
moves, leaving letters behind, when one is composing on-line). “Talk
about a `*nastygram* <../N/nastygram.html>`__! He must've had his cursor
dipped in acid when he wrote that one!”



**cuspy**: /kuhs´pee/, adj.

[WPI: from the `*DEC* <../D/DEC.html>`__ abbreviation CUSP, for
‘Commonly Used System Program’, i.e., a utility program used by many
people. Now rare.]

1. (of a program) Well-written.

2. Functionally excellent. A program that performs well and interfaces
well to users is cuspy. Oppose `*rude* <../R/rude.html>`__.

3. [NYU] Said of an attractive woman, especially one regarded as
available. Implies a certain curvaceousness.



**cut a tape**: vi.

To write a software or document distribution on magnetic tape for
shipment. Has nothing to do with physically cutting the medium! Early
versions of this lexicon claimed that one never analogously speaks of
‘cutting a disk’, but this has since been reported as live usage.
Related slang usages are mainstream business's ‘cut a check’, the
recording industry's ‘cut a record’, and the military's ‘cut an order’.

All of these usages reflect physical processes in obsolete recording and
duplication technologies. The first stage in manufacturing an old-style
vinyl record involved cutting grooves in a stamping die with a precision
lathe. More mundanely, the dominant technology for mass duplication of
paper documents in pre-photocopying days involved “cutting a stencil”,
punching away portions of the wax overlay on a silk screen. More
directly, paper tape with holes punched in it was an important early
storage medium. See also `*burn a CD* <../B/burn-a-CD.html>`__.


**cybercrud**: /si:´ber·kruhd/, n.

1. [coined by Ted Nelson] Obfuscatory tech-talk. Verbiage with a high
`*MEGO* <../M/MEGO.html>`__ factor. The computer equivalent of
bureaucratese.

2. Incomprehensible stuff embedded in email. First there were the
“Received” headers that show how mail flows through systems, then MIME
(Multi-purpose Internet Mail Extensions) headers and part boundaries,
and now huge blocks of radix-64 for PEM (Privacy Enhanced Mail) or PGP
(Pretty Good Privacy) digital signatures and certificates of
authenticity. This stuff all serves a purpose and good user interfaces
should hide it, but all too often users are forced to wade through it.



**cyberpunk**: /si:´ber·puhnk/, n.,adj.

[orig. by SF writer Bruce Bethke and/or editor Gardner Dozois] A
subgenre of SF launched in 1982 by William Gibson's epoch-making novel
*Neuromancer* (though its roots go back through Vernor Vinge's *True
Names* (see the `Bibliography <../pt03.html#bibliography>`__ in Appendix
C) to John Brunner's 1975 novel *The Shockwave Rider*). Gibson's
near-total ignorance of computers and the present-day hacker culture
enabled him to speculate about the role of computers and hackers in the
future in ways hackers have since found both irritatingly naïve and
tremendously stimulating. Gibson's work was widely imitated, in
particular by the short-lived but innovative *Max Headroom* TV series.
See `*cyberspace* <cyberspace.html>`__, `*ice* <../I/ice.html>`__,
`*jack in* <../J/jack-in.html>`__, `*go
flatline* <../G/go-flatline.html>`__.

Since 1990 or so, popular culture has included a movement or fashion
trend that calls itself ‘cyberpunk’, associated especially with the
rave/techno subculture. Hackers have mixed feelings about this. On the
one hand, self-described cyberpunks too often seem to be shallow
trendoids in black leather who have substituted enthusiastic blathering
about technology for actually learning and *doing* it. Attitude is no
substitute for competence. On the other hand, at least cyberpunks are
excited about the right things and properly respectful of hacking talent
in those who have it. The general consensus is to tolerate them politely
in hopes that they'll attract people who grow into being true hackers.


**cyberspace**: /si:´br·spays\`/, n.

1. Notional ‘information-space’ loaded with visual cues and navigable
with brain-computer interfaces called cyberspace decks; a characteristic
prop of `*cyberpunk* <cyberpunk.html>`__ SF. Serious efforts to
construct `*virtual reality* <../V/virtual-reality.html>`__ interfaces
modeled explicitly on Gibsonian cyberspace are under way, using more
conventional devices such as glove sensors and binocular TV headsets.
Few hackers are prepared to deny outright the possibility of a
cyberspace someday evolving out of the network (see `*the
network* <../T/the-network.html>`__).

2. The Internet or `*Matrix* <../M/Matrix.html>`__ (sense #2) as a
whole, considered as a crude cyberspace (sense 1). Although this usage
became widely popular in the mainstream press during 1994 when the
Internet exploded into public awareness, it is strongly deprecated among
hackers because the Internet does not meet the high, SF-inspired
standards they have for true cyberspace technology. Thus, this use of
the term usually tags a `*wannabee* <../W/wannabee.html>`__ or outsider.
Oppose `*meatspace* <../M/meatspace.html>`__.

3. Occasionally, the metaphoric location of the mind of a person in
`*hack mode* <../H/hack-mode.html>`__. Some hackers report experiencing
strong synesthetic imagery when in hack mode; interestingly, independent
reports from multiple sources suggest that there are common features to
the experience. In particular, the dominant colors of this subjective
cyberspace are often gray and silver, and the imagery often involves
constellations of marching dots, elaborate shifting patterns of lines
and angles, or moire patterns.


**cycle**

1. n. The basic unit of computation. What every hacker wants more of
(noted hacker Bill Gosper described himself as a “cycle junkie”). One
can describe an instruction as taking so many clock cycles. Often the
computer can access its memory once on every clock cycle, and so one
speaks also of memory cycles. These are technical meanings of
`*cycle* <cycle.html>`__. The jargon meaning comes from the observation
that there are only so many cycles per second, and when you are sharing
a computer the cycles get divided up among the users. The more cycles
the computer spends working on your program rather than someone else's,
the faster your program will run. That's why every hacker wants more
cycles: so he can spend less time waiting for the computer to respond.

2. By extension, a notional unit of *human* thought power, emphasizing
that lots of things compete for the typical hacker's think time. “I
refused to get involved with the Rubik's Cube back when it was big. Knew
I'd burn too many cycles on it if I let myself.”

3. vt. Syn. `*bounce* <../B/bounce.html>`__ (sense 4), from the phrase
‘cycle power’. “Cycle the machine again, that serial port's still hung.”



**cycle of reincarnation**: n.

See `*wheel of reincarnation* <../W/wheel-of-reincarnation.html>`__.



**cycle server**: n.

A powerful machine that exists primarily for running large compute-,
disk-, or memory-intensive jobs (more formally called a compute server).
Implies that interactive tasks such as editing are done on other
machines on the network, such as workstations.



**cypherpunk**: n.

[from `*cyberpunk* <cyberpunk.html>`__] Someone interested in the uses
of encryption via electronic ciphers for enhancing personal privacy and
guarding against tyranny by centralized, authoritarian power structures,
especially government. There is an active cypherpunks mailing list at
``<cypherpunks-request@toad.com>`` coordinating work on public-key
encryption freeware, privacy, and digital cash. See also
`*tentacle* <../T/tentacle.html>`__.



