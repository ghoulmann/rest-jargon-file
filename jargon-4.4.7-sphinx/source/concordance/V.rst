===
V
===

V7
====



**V7**: /V´sev´en/, n.

See `Version 7 <Version-7.html>`__.


vadding
=========


**vadding**: /vad´ing/, n.

[from VAD, a permutation of ADV (i.e., `ADVENT <../A/ADVENT.html>`__),
used to avoid a particular `admin <../A/admin.html>`__'s continual
search-and-destroy sweeps for the game] A leisure-time activity of
certain hackers involving the covert exploration of the ‘secret’ parts
of large buildings — basements, roofs, freight elevators, maintenance
crawlways, steam tunnels, and the like. A few go so far as to learn
locksmithing in order to synthesize vadding keys. The verb is to vad
(compare `phreaking <../P/phreaking.html>`__; see also
`hack <../H/hack.html>`__, sense 9). This term dates from the late
1970s, before which such activity was simply called ‘hacking’; the older
usage is still prevalent at MIT.

The most extreme and dangerous form of vadding is elevator rodeo, a.k.a.
elevator surfing, a sport played by wrasslin' down a thousand-pound
elevator car with a 3-foot piece of string, and then exploiting this
mastery in various stimulating ways (such as elevator hopping, shaft
exploration, rat-racing, and the ever-popular drop experiments). Kids,
don't try this at home!

vanilla
================


**vanilla**: adj.

[from the default flavor of ice cream in the U.S.] Ordinary
`flavor <../F/flavor.html>`__, standard. When used of food, very often
does not mean that the food is flavored with vanilla extract! For
example, vanilla wonton soup means ordinary wonton soup, as opposed to
hot-and-sour wonton soup. Applied to hardware and software, as in
“Vanilla Version 7 Unix can't run on a vanilla 11/34.” Also used to
orthogonalize chip nomenclature; for instance, a 74V00 means what TI
calls a 7400, as distinct from a 74LS00, etc. This word differs from
`canonical <../C/canonical.html>`__ in that the latter means
‘default’, whereas vanilla simply means ‘ordinary’. For example, when
hackers go on a `great-wall <../G/great-wall.html>`__, hot-and-sour
soup is the `canonical <../C/canonical.html>`__ soup to get (because
that is what most of them usually order) even though it isn't the
vanilla (wonton) soup.



vanity domain
==================================

`Prev <vanilla.html>`__ 

V

 `Next <vannevar.html>`__

**vanity domain**: n.

[common; from ‘vanity plate’ as in car license plate] An Internet
domain, particularly in the .com or .org top-level domains, apparently
created for no reason other than boosting the creator's ego.



vannevar
==================





**vannevar**: /van'@·var/, n.

A bogus technological prediction or a foredoomed engineering concept,
esp. one that fails by implicitly assuming that technologies develop
linearly, incrementally, and in isolation from one another when in fact
the learning curve tends to be highly nonlinear, revolutions are common,
and competition is the rule. The prototype was Vannevar Bush's
prediction of ‘electronic brains’ the size of the Empire State Building
with a Niagara-Falls-equivalent cooling system for their tubes and
relays, a prediction made at a time when the semiconductor effect had
already been demonstrated. Other famous vannevars have included
magnetic-bubble memory, LISP machines, `videotex <videotex.html>`__,
and a paper from the late 1970s that computed a purported ultimate limit
on areal density for ICs that was in fact less than the routine
densities of 5 years later.



vaporware
===========================



**vaporware**: /vay´pr·weir/, n.

Products announced far in advance of any release (which may or may not
actually take place).



var
===========



**var**: /veir/, /var/, n.

Short for variable. Compare `arg <../A/arg.html>`__,
`param <../P/param.html>`__.



vaston
================================


**vaston**: n.

[Durham, UK] The unit of ‘load average’. A measure of how much work a
computer is doing. A meter displaying this as a function of time is
known as a vastometer. First used during a computing practical in
December 1996.


VAXen
===========================



**VAXen**: /vak´sn/, n.

[from ‘oxen’, perhaps influenced by ‘vixen’] (alt.: vaxen) The plural
canonically used among hackers for the `DEC <../D/DEC.html>`__ VAX
computers. “Our installation has four PDP-10s and twenty vaxen.” See
`boxen <../B/boxen.html>`__.



VAX
=======================================



**VAX**: /vaks/, n.

1. [from Virtual Address eXtension] The most successful minicomputer
design in industry history, possibly excepting its immediate ancestor,
the `PDP-11 <../P/PDP-11.html>`__. Between its release in 1978 and its
eclipse by `killer micro <../K/killer-micro.html>`__\ s after about
1986, the VAX was probably the hacker's favorite machine of them all,
esp. after the 1982 release of 4.2 BSD Unix (see
`BSD <../B/BSD.html>`__). Especially noted for its large,
assembler-programmer-friendly instruction set — an asset that became a
liability after the RISC revolution.

It is worth noting that the standard plural of VAX was ‘vaxen’ and that
VAX system operators were sometimes referred to as ‘vaxherds’

2. A major brand of vacuum cleaner in Britain. Cited here because its
sales pitch, “Nothing sucks like a VAX!” became a sort of battle-cry of
RISC partisans. It is even sometimes claimed that DEC actually entered a
cross-licensing deal with the vacuum-Vax people that allowed them to
market VAX computers in the U.K. in return for not challenging the
vacuum cleaner trademark in the U.S.

A rival brand actually pioneered the slogan: its original form was
“Nothing sucks like Electrolux”. It has apparently become a classic
example (used in advertising textbooks) of the perils of not knowing the
local idiom. But in 1996, the press manager of Electrolux AB, while
confirming that the company used this slogan in the late 1960s, also
tells us that their marketing people were fully aware of the possible
double entendre and intended it to gain attention.

And gain attention it did — the VAX-vacuum-cleaner people thought the
slogan a sufficiently good idea to copy it. Several British hackers
report that VAX's promotions used it in 1986--1987, and we have one
report from a New Zealander that the infamous slogan surfaced there in
TV ads for the product in 1992.

vaxocentrism
==========================================


**vaxocentrism**: /vak\`soh·sen´trizm/, n.

[analogy with ‘ethnocentrism’] A notional disease said to afflict C
programmers who persist in coding according to certain assumptions that
are valid (esp. under Unix) on `VAXen <VAXen.html>`__ but false
elsewhere. Among these are:

#. The assumption that dereferencing a null pointer is safe because it
   is all bits 0, and location 0 is readable and 0. Problem: this may
   instead cause an illegal-address trap on non-VAXen, and even on VAXen
   under OSes other than BSD Unix. Usually this is an implicit
   assumption of sloppy code (forgetting to check the pointer before
   using it), rather than deliberate exploitation of a misfeature.

#. The assumption that characters are signed.

#. The assumption that a pointer to any one type can freely be cast into
   a pointer to any other type. A stronger form of this is the
   assumption that all pointers are the same size and format, which
   means you don't have to worry about getting the casts or types
   correct in calls. Problem: this fails on word-oriented machines or
   others with multiple pointer formats.

#. The assumption that the parameters of a routine are stored in memory,
   on a stack, contiguously, and in strictly ascending or descending
   order. Problem: this fails on many RISC architectures.

#. The assumption that pointer and integer types are the same size, and
   that pointers can be stuffed into integer variables (and vice-versa)
   and drawn back out without being truncated or mangled. Problem: this
   fails on segmented architectures or word-oriented machines with funny
   pointer formats.

#. The assumption that a data type of any size may begin at any byte
   address in memory (for example, that you can freely construct and
   dereference a pointer to a word- or greater-sized object at an odd
   char address). Problem: this fails on many (esp. RISC) architectures
   better optimized for `HLL <../H/HLL.html>`__ execution speed, and
   can cause an illegal address fault or bus error.

#. The (related) assumption that there is no padding at the end of types
   and that in an array you can thus step right from the last byte of a
   previous component to the first byte of the next one. This is not
   only machine- but compiler-dependent.

#. The assumption that memory address space is globally flat and that
   the array reference **foo[-1]** is necessarily valid. Problem: this
   fails at 0, or other places on segment-addressed machines like Intel
   chips (yes, segmentation is universally considered a
   `brain-damaged <../B/brain-damaged.html>`__ way to design machines
   (see `moby <../M/moby.html>`__), but that is a separate issue).

#. The assumption that objects can be arbitrarily large with no special
   considerations. Problem: this fails on segmented architectures and
   under non-virtual-addressing environments.

#. The assumption that the stack can be as large as memory. Problem:
   this fails on segmented architectures or almost anything else without
   virtual addressing and a paged stack.

#. The assumption that bits and addressable units within an object are
   ordered in the same way and that this order is a constant of nature.
   Problem: this fails on `big-endian <../B/big-endian.html>`__
   machines.

#. The assumption that it is meaningful to compare pointers to different
   objects not located within the same array, or to objects of different
   types. Problem: the former fails on segmented architectures, the
   latter on word-oriented machines or others with multiple pointer
   formats.

#. The assumption that an int is 32 bits, or (nearly equivalently) the
   assumption that **sizeof(int) == sizeof(long)**. Problem: this fails
   on `PDP-11 <../P/PDP-11.html>`__\ s, 286-based systems and even on
   386 and 68000 systems under some compilers (and on 64-bit systems
   like the Alpha, of course).

#. The assumption that **argv[]** is writable. Problem: this fails in
   many embedded-systems C environments and even under a few flavors of
   Unix.

Note that a programmer can validly be accused of vaxocentrism even if he
or she has never seen a `VAX <VAX.html>`__. Some of these assumptions
(esp. 2--5) were valid on the `PDP-11 <../P/PDP-11.html>`__, the
original C machine, and became endemic years before the VAX. The terms
vaxocentricity and all-the-world's-a-VAX syndrome have been used
synonymously.


vdiff
========================





**vdiff**: /vee´dif/, v.,n.

Visual diff. The operation of finding differences between two files by
`eyeball search <../E/eyeball-search.html>`__. The term optical diff
has also been reported, and is sometimes more specifically used for the
act of superimposing two nearly identical printouts on one another and
holding them up to a light to spot differences. Though this method is
poor for detecting omissions in the ‘rear’ file, it can also be used
with printouts of graphics, a claim few if any diff programs can make.
See `diff <../D/diff.html>`__.

An interesting variant of the vdiff technique usable by anyone who has
sufficient control over the parallax of their eyeballs (e.g. those who
can easily view random-dot stereograms), is to hold up two paper
printouts and go cross-eyed to superimpose them. This invokes deep,
fast, built-in image comparison wetware (the same machinery responsible
for depth perception) and differences stand out almost immediately. This
technique is good for finding edits in graphical images, or for
comparing an image with a compressed version to spot artifacts.


veeblefester
========================================


**veeblefester**: /vee´b@l·fes\`tr/, n.

[from the *Born Loser* comix via Commodore; prob.: originally from *Mad*
Magazine's ‘Veeblefetzer’ parodies beginning in #15, 1954] Any obnoxious
person engaged in the (alleged) professions of marketing or management.
Antonym of `hacker <../H/hacker.html>`__. Compare
`suit <../S/suit.html>`__, `marketroid <../M/marketroid.html>`__.


velveeta
===========================================


**velveeta**: n.

[Usenet: by analogy with `spam <../S/spam.html>`__. The trade name
Velveeta is attached in the U.S. to a particularly nasty
processed-cheese spread.] Also knows as `ECP <../E/ECP.html>`__; a
message that is excessively cross-posted, as opposed to
`spam <../S/spam.html>`__ which is too frequently posted. This term is
widely recognized but not commonly used; most people refer to both kinds
of abuse as spam. Compare `jello <../J/jello.html>`__.



Venus flytrap
===========================================


**Venus flytrap**: n.

[after the insect-eating plant] See `firewall
machine <../F/firewall-machine.html>`__.



verbage
==========================



**verbage**: /ver´b@j/, n.

A deliberate misspelling and mispronunciation of
`verbiage <verbiage.html>`__ that assimilates it to the word
‘garbage’. Compare `content-free <../C/content-free.html>`__. More
pejorative than ‘verbiage’.



verbiage
===========


**verbiage**: n.

When the context involves a software or hardware system, this refers to
`documentation <../D/documentation.html>`__. This term borrows the
connotations of mainstream ‘verbiage’ to suggest that the documentation
is of marginal utility and that the motives behind its production have
little to do with the ostensible subject.



Version 7
=====================


**Version 7**: /vee´ se´vn/, n.

The first widely distributed version of `Unix <../U/Unix.html>`__,
released unsupported by Bell Labs in 1978. The term is used adjectivally
to describe Unix features and programs that date from that release, and
are thus guaranteed to be present and portable in all Unix versions
(this was the standard gauge of portability before the POSIX and IEEE
1003 standards). Note that this usage does *not* derive from the release
being the “seventh version of `Unix <../U/Unix.html>`__\ ”; research
`Unix <../U/Unix.html>`__ at Bell Labs has traditionally been numbered
according to the edition of the associated documentation. Indeed, only
the widely-distributed Sixth and Seventh Editions are widely known as
V[67]; the OS that might today be known as ‘V10’ is instead known in
full as “Tenth Edition Research Unix” or just “Tenth Edition” for short.
For this reason, “V7” is often read by cognoscenti as “Seventh Edition”.
See `BSD <../B/BSD.html>`__, `Unix <../U/Unix.html>`__. Some
old-timers impatient with commercialization and kernel bloat still
maintain that V7 was the Last True Unix.

vgrep
==================================



**vgrep**: /vee´grep/, v.,n.

Visual grep. The operation of finding patterns in a file optically
rather than digitally (also called an optical grep). See
`grep <../G/grep.html>`__; compare `vdiff <vdiff.html>`__.

videotex
======================================


**videotex**: n. obs.

An electronic service offering people the privilege of paying to read
the weather on their television screens instead of having somebody read
it to them for free while they brush their teeth. The idea bombed
everywhere it wasn't government-subsidized, because by the time videotex
was practical the installed base of personal computers could hook up to
timesharing services and do the things for which videotex might have
been worthwhile better and cheaper. Videotex planners badly
overestimated both the appeal of getting information from a computer and
the cost of local intelligence at the user's end. Like the `gorilla
arm <../G/gorilla-arm.html>`__ effect, this has been a cautionary tale
to hackers ever since. See also `vannevar <vannevar.html>`__.



video toaster
===================================================

`Prev <vi.html>`__ 

V

 `Next <videotex.html>`__

--------------

**video toaster**: n.

Historically, an Amiga fitted with a particular line of special video
effects hardware from NewTek — long a popular platform at
special-effects and video production houses. More generally, any
computer system designed specifically for video production and
manipulation. Compare `web toaster <../W/web-toaster.html>`__ and see
`toaster <../T/toaster.html>`__.

--------------

+-----------------------+----------------------------+-----------------------------+
| `Prev <vi.html>`__    | `Up <../V.html>`__         |  `Next <videotex.html>`__   |
+-----------------------+----------------------------+-----------------------------+
| vi                    | `Home <../index.html>`__   |  videotex                   |
+-----------------------+----------------------------+-----------------------------+

vi
====================

`Prev <vgrep.html>`__ 

V

 `Next <video-toaster.html>`__

--------------

**vi**: /V·I/, *not*, /vi:/, *never*, /siks/, n.

[from ‘Visual Interface’] A screen editor crufted together by Bill Joy
for an early `BSD <../B/BSD.html>`__ release. Became the de facto
standard Unix editor and a nearly undisputed hacker favorite outside of
MIT until the rise of `EMACS <../E/EMACS.html>`__ after about 1984.
Tends to frustrate new users no end, as it will neither take commands
while expecting input text nor vice versa, and the default setup on
older versions provides no indication of which mode the editor is in
(years ago, a correspondent reported that he has often heard the
editor's name pronounced /vi:l/; there is now a vi clone named vile).
Nevertheless vi (and variants such as vim and elvis) is still widely
used (about half the respondents in a 1991 Usenet poll preferred it),
and even EMACS fans often resort to it as a mail editor and for small
editing jobs (mainly because it starts up faster than the bulkier
versions of EMACS). See `holy wars <../H/holy-wars.html>`__.

--------------

+--------------------------+----------------------------+----------------------------------+
| `Prev <vgrep.html>`__    | `Up <../V.html>`__         |  `Next <video-toaster.html>`__   |
+--------------------------+----------------------------+----------------------------------+
| vgrep                    | `Home <../index.html>`__   |  video toaster                   |
+--------------------------+----------------------------+----------------------------------+

virgin
==================

`Prev <videotex.html>`__ 

V

 `Next <virtual.html>`__

--------------

**virgin**: adj.

Unused; pristine; in a known initial state. “Let's bring up a virgin
system and see if it crashes again.” (Esp.: useful after contracting a
`virus <virus.html>`__ through `SEX <../S/SEX.html>`__.) Also, by
extension, buffers and the like within a program that have not yet been
used.



virtual beer
==============================================

`Prev <virtual.html>`__ 

V

 `Next <virtual-Friday.html>`__

--------------

**virtual beer**: n.

Praise or thanks. Used universally in the Linux community. Originally
this term signified cash, after a famous incident in which some
Britishers who wanted to buy Linus a beer sent him money to Finland to
do so.



virtual Friday
================================================

`Prev <virtual-beer.html>`__ 

V

 `Next <virtual-reality.html>`__

--------------

**virtual Friday**: n.

(also logical Friday) The last day before an extended weekend, if that
day is not a ‘real’ Friday. For example, the U.S. holiday Thanksgiving
is always on a Thursday. The next day is often also a holiday or taken
as an extra day off, in which case Wednesday of that week is a virtual
Friday (and Thursday is a virtual Saturday, as is Friday). There are
also virtual Mondays that are actually Tuesdays, after the three-day
weekends associated with many national holidays in the U.S.

--------------

+---------------------------------+----------------------------+------------------------------------+
| `Prev <virtual-beer.html>`__    | `Up <../V.html>`__         |  `Next <virtual-reality.html>`__   |
+---------------------------------+----------------------------+------------------------------------+
| virtual beer                    | `Home <../index.html>`__   |  virtual reality                   |
+---------------------------------+----------------------------+------------------------------------+

virtual
========================

`Prev <virgin.html>`__ 

V

 `Next <virtual-beer.html>`__

--------------

**virtual**: adj.

[via the technical term virtual memory, prob.: from the term virtual
image in optics]

1. Common alternative to `logical <../L/logical.html>`__; often used
to refer to the artificial objects (like addressable virtual memory
larger than physical memory) simulated by a computer system as a
convenient way to manage access to shared resources.

2. Simulated; performing the functions of something that isn't really
there. An imaginative child's doll may be a virtual playmate. Oppose
`real <../R/real.html>`__.

--------------

+---------------------------+----------------------------+---------------------------------+
| `Prev <virgin.html>`__    | `Up <../V.html>`__         |  `Next <virtual-beer.html>`__   |
+---------------------------+----------------------------+---------------------------------+
| virgin                    | `Home <../index.html>`__   |  virtual beer                   |
+---------------------------+----------------------------+---------------------------------+

virtual reality
===============================

`Prev <virtual-Friday.html>`__ 

V

 `Next <virtual-shredder.html>`__

--------------

**virtual reality**: n.

1. Computer simulations that use 3-D graphics and devices such as the
Dataglove to allow the user to interact with the simulation. See
`cyberspace <../C/cyberspace.html>`__.

2. A form of network interaction incorporating aspects of role-playing
games, interactive theater, improvisational comedy, and ‘true
confessions’ magazines. In a virtual reality forum (such as Usenet's
"alt.callahans" newsgroup or the `MUD <../M/MUD.html>`__ experiments
on Internet), interaction between the participants is written like a
shared novel complete with scenery, foreground characters that may be
personae utterly unlike the people who write them, and common background
characters manipulable by all parties. The one iron law is that you may
not write irreversible changes to a character without the consent of the
person who ‘owns’ it. Otherwise anything goes. See
`bamf <../B/bamf.html>`__, `cyberspace <../C/cyberspace.html>`__,
`teledildonics <../T/teledildonics.html>`__.

--------------

+-----------------------------------+----------------------------+-------------------------------------+
| `Prev <virtual-Friday.html>`__    | `Up <../V.html>`__         |  `Next <virtual-shredder.html>`__   |
+-----------------------------------+----------------------------+-------------------------------------+
| virtual Friday                    | `Home <../index.html>`__   |  virtual shredder                   |
+-----------------------------------+----------------------------+-------------------------------------+

virtual shredder
==========================

`Prev <virtual-reality.html>`__ 

V

 `Next <virus.html>`__

--------------

**virtual shredder**: n.

The jargonic equivalent of the `bit bucket <../B/bit-bucket.html>`__
at shops using IBM's VM/CMS operating system. VM/CMS officially supports
a whole bestiary of virtual card readers, virtual printers, and other
phantom devices; these are used to supply some of the same capabilities
Unix gets from pipes and I/O redirection.

--------------

+------------------------------------+----------------------------+--------------------------+
| `Prev <virtual-reality.html>`__    | `Up <../V.html>`__         |  `Next <virus.html>`__   |
+------------------------------------+----------------------------+--------------------------+
| virtual reality                    | `Home <../index.html>`__   |  virus                   |
+------------------------------------+----------------------------+--------------------------+

virus
=======================================

`Prev <virtual-shredder.html>`__ 

V

 `Next <visionary.html>`__

--------------

**virus**: n.

[from the obvious analogy with biological viruses, via SF] A cracker
program that searches out other programs and ‘infects’ them by embedding
a copy of itself in them, so that they become `Trojan
horse <../T/Trojan-horse.html>`__\ s. When these programs are executed,
the embedded virus is executed too, thus propagating the ‘infection’.
This normally happens invisibly to the user. Unlike a
`worm <../W/worm.html>`__, a virus cannot infect other computers
without assistance. It is propagated by vectors such as humans trading
programs with their friends (see `SEX <../S/SEX.html>`__). The virus
may do nothing but propagate itself and then allow the program to run
normally. Usually, however, after propagating silently for a while, it
starts doing things like writing cute messages on the terminal or
playing strange tricks with the display (some viruses include nice
`display hack <../D/display-hack.html>`__\ s). Many nasty viruses,
written by particularly perversely minded
`cracker <../C/cracker.html>`__\ s, do irreversible damage, like
nuking all the user's files.

In the 1990s, viruses became a serious problem, especially among Windows
users; the lack of security on these machines enables viruses to spread
easily, even infecting the operating system (Unix machines, by contrast,
are immune to such attacks). The production of special anti-virus
software has become an industry, and a number of exaggerated media
reports have caused outbreaks of near hysteria among users; many
`luser <../L/luser.html>`__\ s tend to blame *everything* that doesn't
work as they had expected on virus attacks. Accordingly, this sense of
virus has passed not only into techspeak but into also popular usage
(where it is often incorrectly used to denote a
`worm <../W/worm.html>`__ or even a `Trojan
horse <../T/Trojan-horse.html>`__). See `phage <../P/phage.html>`__;
compare `back door <../B/back-door.html>`__; see also `Unix
conspiracy <../U/Unix-conspiracy.html>`__.





visionary
===================================

`Prev <virus.html>`__ 

V

 `Next <Visual-Fred.html>`__

--------------

**visionary**: n.

1. One who hacks vision, in the sense of an Artificial Intelligence
researcher working on the problem of getting computers to ‘see’ things
using TV cameras. (There isn't any problem in sending information from a
TV camera to a computer. The problem is, how can the computer be
programmed to make use of the camera information? See
`SMOP <../S/SMOP.html>`__, `AI-complete <../A/AI-complete.html>`__.)

2. [IBM] One who reads the outside literature. At IBM, apparently, such
a penchant is viewed with awe and wonder.

--------------

+--------------------------+----------------------------+--------------------------------+
| `Prev <virus.html>`__    | `Up <../V.html>`__         |  `Next <Visual-Fred.html>`__   |
+--------------------------+----------------------------+--------------------------------+
| virus                    | `Home <../index.html>`__   |  Visual Fred                   |
+--------------------------+----------------------------+--------------------------------+

Visual Fred
==============================

`Prev <visionary.html>`__ 

V

 `Next <VMS.html>`__

--------------

**Visual Fred**: n.

Pejorative hackerism for VB.NET (Visual Basic for the .NET framework).
VB.NET has been marketed by Microsoft as an updated version of the
previous Visual Basic on its .NET framework, but VB.NET is really just
C# with a slightly different syntax and fewer libraries. Migrating
existing code from Visual Basic to VB.NET is generally impractical
because VB.NET has a large number of unnecessary incompatibilities with
Visual Basic. Since VB.NET has essentially nothing to do with Visual
Basic, a well-known ex-Microserf suggested that VB.NET should have a
completely different name — Visual Fred. This rapidly caught on.

--------------

+------------------------------+----------------------------+------------------------+
| `Prev <visionary.html>`__    | `Up <../V.html>`__         |  `Next <VMS.html>`__   |
+------------------------------+----------------------------+------------------------+
| visionary                    | `Home <../index.html>`__   |  VMS                   |
+------------------------------+----------------------------+------------------------+

VMS
==================

`Prev <Visual-Fred.html>`__ 

V

 `Next <voice.html>`__

--------------

**VMS**: /V·M·S/, n.

`DEC <../D/DEC.html>`__'s proprietary operating system for its
`VAX <VAX.html>`__ minicomputer; one of the seven or so environments
that loom largest in hacker folklore. Many Unix fans generously concede
that VMS would probably be the hacker's favorite commercial OS if Unix
didn't exist; though true, this makes VMS fans furious. One major hacker
gripe with VMS concerns its slowness — thus the following limerick:

| 
|     There once was a system called VMS
|     Of cycles by no means abstemious.
|          It's chock-full of hacks
|          And runs on a VAX
|     And makes my poor stomach all squeamious.
|                                      — The Great Quux

See also `VAX <VAX.html>`__, `TOPS-10 <../T/TOPS-10.html>`__,
`TOPS-20 <../T/TOPS-20.html>`__, `Unix <../U/Unix.html>`__,
`runic <../R/runic.html>`__.

--------------

+--------------------------------+----------------------------+--------------------------+
| `Prev <Visual-Fred.html>`__    | `Up <../V.html>`__         |  `Next <voice.html>`__   |
+--------------------------------+----------------------------+--------------------------+
| Visual Fred                    | `Home <../index.html>`__   |  voice                   |
+--------------------------------+----------------------------+--------------------------+

voice
====================

`Prev <VMS.html>`__ 

V

 `Next <voice-net.html>`__

--------------

**voice**: vt.

To phone someone, as opposed to emailing them or connecting in `talk
mode <../T/talk-mode.html>`__. “I'm busy now; I'll voice you later.”

--------------

+------------------------+----------------------------+------------------------------+
| `Prev <VMS.html>`__    | `Up <../V.html>`__         |  `Next <voice-net.html>`__   |
+------------------------+----------------------------+------------------------------+
| VMS                    | `Home <../index.html>`__   |  voice-net                   |
+------------------------+----------------------------+------------------------------+

voice-net
=================================

`Prev <voice.html>`__ 

V

 `Next <voodoo-programming.html>`__

--------------

**voice-net**: n.

Hackish way of referring to the telephone system, analogizing it to a
digital network. Usenet `sig block <../S/sig-block.html>`__\ s not
uncommonly include the sender's phone next to a “Voice:” or “Voice-Net:”
header; common variants of this are “Voicenet” and “V-Net”. Compare
`paper-net <../P/paper-net.html>`__,
`snail-mail <../S/snail-mail.html>`__.

--------------

+--------------------------+----------------------------+---------------------------------------+
| `Prev <voice.html>`__    | `Up <../V.html>`__         |  `Next <voodoo-programming.html>`__   |
+--------------------------+----------------------------+---------------------------------------+
| voice                    | `Home <../index.html>`__   |  voodoo programming                   |
+--------------------------+----------------------------+---------------------------------------+

voodoo programming
=================================

`Prev <voice-net.html>`__ 

V

 `Next <VR.html>`__

--------------

**voodoo programming**: n.

[from George Bush Sr.'s “voodoo economics”]

1. The use by guess or cookbook of an `obscure <../O/obscure.html>`__
or `hairy <../H/hairy.html>`__ system, feature, or algorithm that one
does not truly understand. The implication is that the technique may not
work, and if it doesn't, one will never know why. Almost synonymous with
`black magic <../B/black-magic.html>`__, except that black magic
typically isn't documented and *nobody* understands it. Compare
`magic <../M/magic.html>`__, `deep magic <../D/deep-magic.html>`__,
`heavy wizardry <../H/heavy-wizardry.html>`__, `rain
dance <../R/rain-dance.html>`__, `cargo cult
programming <../C/cargo-cult-programming.html>`__, `wave a dead
chicken <../W/wave-a-dead-chicken.html>`__, `SCSI
voodoo <../S/SCSI-voodoo.html>`__.

2. Things programmers do that they know shouldn't work but they try
anyway, and which sometimes actually work, such as recompiling
everything.


VR
==============

`Prev <voodoo-programming.html>`__ 

V

 `Next <Vulcan-nerve-pinch.html>`__

--------------

**VR**: //, n.

On-line abbrev for `virtual reality <virtual-reality.html>`__, as
opposed to `RL <../R/RL.html>`__.


Vulcan nerve pinch

`Prev <VR.html>`__ 

V

 `Next <vulture-capitalist.html>`__

--------------

**Vulcan nerve pinch**: n.

[from the old *Star Trek* TV series via Commodore Amiga hackers] The
keyboard combination that forces a soft-boot or jump to ROM monitor (on
machines that support such a feature). On Amigas this is
<Ctrl>-<Left-Amiga>-<Right-Amiga>; on PC clones this is Ctrl-Alt-Del; on
Suns, L1-A; on Macintoshes, it is <Cmd>-<Power switch> or
<Cmd>-<Ctrl>-<Power>! On IRIX,
<Left-Ctrl><Left-Shift><F12><Keypad-Slash>, which kills and restarts the
X server, is sometimes called a vulcan nerve pinch. Also called
`three-finger salute <../T/three-finger-salute.html>`__ and Vulcan
death grip. At shops with a lot of Microsoft Windows machines, this is
often called the Microsoft Maneuver because of the distressing frequency
with which Microsoft's unreliable software requires it. Compare
`quadruple bucky <../Q/quadruple-bucky.html>`__.

--------------

+-----------------------+----------------------------+---------------------------------------+
| `Prev <VR.html>`__    | `Up <../V.html>`__         |  `Next <vulture-capitalist.html>`__   |
+-----------------------+----------------------------+---------------------------------------+
| VR                    | `Home <../index.html>`__   |  vulture capitalist                   |
+-----------------------+----------------------------+---------------------------------------+

vulture capitalist
======================

`Prev <Vulcan-nerve-pinch.html>`__ 



**vulture capitalist**: n.

Pejorative hackerism for ‘venture capitalist’, deriving from the common
practice of pushing contracts that deprive inventors of control over
their own innovations and most of the money they ought to have made from
them.


