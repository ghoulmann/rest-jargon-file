===
M
===

macdink
===========

**macdink**: /mak´dink/, vt.

[from the Apple Macintosh, which is said to encourage such behavior] To
make many incremental and unnecessary cosmetic changes to a program or
file. Often the subject of the macdinking would be better off without
them. “When I left at 11PM last night, he was still macdinking the
slides for his presentation.” See also
`fritterware <./F.html#fritterware>`__, `window
shopping <./W.html#window-shopping>`__.

 

machoflops
==============

 

**machoflops**: /mach´oh·flops/, n.

[pun on megaflops, a coinage for ‘millions of FLoating-point Operations
Per Second’] Refers to artificially inflated performance figures often
quoted by computer manufacturers. Real applications are lucky to get
half the quoted speed. See `Your mileage may
vary <./Y.html#Your-mileage-may-vary>`__,
`benchmark <./B.html#benchmark>`__.



Macintoy
===========

 

**Macintoy**: /mak´in·toy/, n.

The Apple Macintosh, considered as a `toy <./T.html#toy>`__. Less
pejorative than `Macintrash <Macintrash>`__.



Macintrash
============

 

**Macintrash**: /mak´in·trash\`/, n.

The Apple Macintosh, as described by a hacker who doesn't appreciate
being kept away from the *real computer* by the interface. The term
`maggotbox <maggotbox>`__ has been reported in regular use in the
Research Triangle area of North Carolina. Compare
`Macintoy <Macintoy>`__. See also `beige
toaster <./B.html#beige-toaster>`__, `WIMP
environment <./W.html#WIMP-environment>`__, `point-and-drool
interface <./P.html#point-and-drool-interface>`__, `drool-proof
paper <./D.html#drool-proof-paper>`__,
`user-friendly <./U.html#user-friendly>`__.

 


macro-
===========

 

**macro-**: pref.

Large. Opposite of `micro- <micro->`__. In the mainstream and
among other technical cultures (for example, medical people) this
competes with the prefix `mega- <mega->`__, but hackers tend to
restrict the latter to quantification.

 



macro
============

 

**macro**: /mak´roh/, n.

[techspeak] A name (possibly followed by a formal
`arg <./A.html#arg>`__ list) that is equated to a text or symbolic
expression to which it is to be expanded (possibly with the substitution
of actual arguments) by a macro expander. This definition can be found
in any technical dictionary; what those won't tell you is how the
hackish connotations of the term have changed over time.

The term macro originated in early assemblers, which encouraged the use
of macros as a structuring and information-hiding device. During the
early 1970s, macro assemblers became ubiquitous, and sometimes quite as
powerful and expensive as `HLL <./H.html#HLL>`__\ s, only to fall
from favor as improving compiler technology marginalized assembler
programming (see `languages of
choice <./L.html#languages-of-choice>`__). Nowadays the term is most
often used in connection with the C preprocessor, LISP, or one of
several special-purpose languages built around a macro-expansion
facility (such as TeX or Unix's [nt]roff suite).

Indeed, the meaning has drifted enough that the collective macros is now
sometimes used for code in any special-purpose application control
language (whether or not the language is actually translated by text
expansion), and for macro-like entities such as the keyboard macros
supported in some text editors (and PC TSR or Macintosh INIT/CDEV
keyboard enhancers).



macrology
============

 

**macrology**: /mak·rol'@·jee/, n.

1. Set of usually complex or crufty macros, e.g., as part of a large
system written in `LISP <./L.html#LISP>`__,
`TECO <./T.html#TECO>`__, or (less commonly) assembler.

2. The art and science involved in comprehending a macrology in sense 1.
Sometimes studying the macrology of a system is not unlike archeology,
ecology, or `theology <./T.html#theology>`__, hence the sound-alike
construction. See also `boxology <./B.html#boxology>`__.

 


maggotbox
==============

 

**maggotbox**: /mag'@t·boks/, n.

See `Macintrash <Macintrash>`__. This is even more derogatory.

 


magic cookie
==============

 

**magic cookie**: n.

[Unix; common]

1. Something passed between routines or programs that enables the
receiver to perform some operation; a capability ticket or opaque
identifier. Especially used of small data objects that contain data
encoded in a strange or intrinsically machine-dependent way. E.g., on
non-Unix OSes with a non-byte-stream model of files, the result of
ftell(3) may be a magic cookie rather than a byte offset; it can be
passed to fseek(3), but not operated on in any meaningful way. The
phrase it hands you a magic cookie means it returns a result whose
contents are not defined but which can be passed back to the same or
some other program later.

2. An in-band code for changing graphic rendition (e.g., inverse video
or underlining) or performing other control functions (see also
`cookie <./C.html#cookie>`__). Some older terminals would leave a
blank on the screen corresponding to mode-change magic cookies; this was
also called a `glitch <./G.html#glitch>`__ (or occasionally a turd;
compare `mouse droppings <mouse-droppings>`__). See also
`cookie <./C.html#cookie>`__.



magic
=============

 

**magic**

1. adj. As yet unexplained, or too complicated to explain; compare
`automagically <./A.html#automagically>`__ and (Arthur C.) Clarke's
Third Law: “Any sufficiently advanced technology is indistinguishable
from magic.” “TTY echoing is controlled by a large number of magic
bits.” “This routine magically computes the parity of an 8-bit byte in
three instructions.”

2. adj. Characteristic of something that works although no one really
understands why (this is especially called `black
magic <./B.html#black-magic>`__).

3. n. [Stanford] A feature not generally publicized that allows
something otherwise impossible, or a feature formerly in that category
but now unveiled.

4. n. The ultimate goal of all engineering & development, elegance in
the extreme; from the first corollary to Clarke's Third Law: “Any
technology distinguishable from magic is insufficiently advanced”.

Parodies playing on these senses of the term abound; some have made
their way into serious documentation, as when a MAGIC directive was
described in the Control Card Reference for GCOS c.1978. For more about
hackish ‘magic’, see `Appendix A <../appendixa>`__. Compare `black
magic <./B.html#black-magic>`__, `wizardly <./W.html#wizardly>`__,
`deep magic <./D.html#deep-magic>`__, `heavy
wizardry <./H.html#heavy-wizardry>`__.

 


magic number
================
 

**magic number**: n.

[Unix/C; common]

1. In source code, some non-obvious constant whose value is significant
to the operation of a program and that is inserted inconspicuously
in-line (`hardcoded <./H.html#hardcoded>`__), rather than expanded in
by a symbol set by a commented **#define**. Magic numbers in this sense
are bad style.

2. A number that encodes critical information used in an algorithm in
some opaque way. The classic examples of these are the numbers used in
hash or CRC functions, or the coefficients in a linear congruential
generator for pseudo-random numbers. This sense actually predates and
was ancestral to the more common sense

3. Special data located at the beginning of a binary data file to
indicate its type to a utility. Under Unix, the system and various
applications programs (especially the linker) distinguish between types
of executable file by looking for a magic number. Once upon a time,
these magic numbers were `PDP-11 <./P.html#PDP-11>`__ branch
instructions that skipped over header data to the start of executable
code; 0407, for example, was octal for ‘branch 16 bytes relative’. Many
other kinds of files now have magic numbers somewhere; some magic
numbers are, in fact, strings, like the "!<arch>" at the beginning of
a Unix archive file or the "%!" leading PostScript files. Nowadays
only a `wizard <./W.html#wizard>`__ knows the spells to create magic
numbers. How do you choose a fresh magic number of your own? Simple —
you pick one at random. See? It's magic!

4. An input that leads to a computational boundary condition, where
algorithm behavior becomes discontinuous. Numeric overflows
(particularly with signed data types) and run-time errors (divide by
zero, stack overflows) are indications of magic numbers. The Y2K scare
was probably the most notorious magic number non-incident.

*The* magic number, on the other hand, is "7±2". See *The magical
number seven, plus or minus two: some limits on our capacity for
processing information* by George Miller, in the *Psychological Review*
63:81-97 (1956). This classic paper established the number of distinct
items (such as numeric digits) that humans can hold in short-term
memory. Among other things, this strongly influenced the interface
design of the phone system.



magic smoke
==============

 

**magic smoke**: n.

A substance trapped inside IC packages that enables them to function
(also called blue smoke; this is similar to the archaic phlogiston
hypothesis about combustion). Its existence is demonstrated by what
happens when a chip burns up — the magic smoke gets let out, so it
doesn't work any more. See `smoke test <./S.html#smoke-test>`__,
`let the smoke out <./L.html#let-the-smoke-out>`__.

Usenetter Jay Maynard tells the following story: “Once, while hacking on
a dedicated Z80 system, I was testing code by blowing EPROMs and
plugging them in the system, then seeing what happened. One time, I
plugged one in backwards. I only discovered that *after* I realized that
Intel didn't put power-on lights under the quartz windows on the tops of
their EPROMs — the die was glowing white-hot. Amazingly, the EPROM
worked fine after I erased it, filled it full of zeros, then erased it
again. For all I know, it's still in service. Of course, this is because
the magic smoke didn't get let out.” Compare the original phrasing of
`Murphy's Law <Murphys-Law>`__.

 


mailbomb
===============

 

**mailbomb**

(also mail bomb) [Usenet]

1. v. To send, or urge others to send, massive amounts of
`email <./E.html#email>`__ to a single system or person, esp. with
intent to crash or `spam <./S.html#spam>`__ the recipient's system.
Sometimes done in retaliation for a perceived serious offense.
Mailbombing is itself widely regarded as a serious offense — it can
disrupt email traffic or other facilities for innocent users on the
victim's system, and in extreme cases, even at upstream sites.

2. n. An automatic procedure with a similar effect.

3. n. The mail sent. Compare `letterbomb <./L.html#letterbomb>`__,
`nastygram <./N.html#nastygram>`__, `BLOB <./B.html#BLOB>`__
(sense 2), `list-bomb <./L.html#list-bomb>`__.

 


mailing list
=======================

 

**mailing list**: n.

(often shortened in context to list)

1. An `email <./E.html#email>`__ address that is an alias (or
`macro <macro>`__, though that word is never used in this
connection) for many other email addresses. Some mailing lists are
simple reflectors, redirecting mail sent to them to the list of
recipients. Others are filtered by humans or programs of varying degrees
of sophistication; lists filtered by humans are said to be moderated.

2. The people who receive your email when you send it to such an
address.

Mailing lists are one of the primary forms of hacker interaction, along
with `Usenet <./U.html#Usenet>`__. They predate Usenet, having
originated with the first UUCP and ARPANET connections. They are often
used for private information-sharing on topics that would be too
specialized for or inappropriate to public Usenet groups. Though some of
these maintain almost purely technical content (such as the Internet
Engineering Task Force mailing list), others (like the ‘sf-lovers’ list
maintained for many years by Saul Jaffe) are recreational, and many are
purely social. Perhaps the most infamous of the social lists was the
eccentric "bandykin" distribution; its latter-day progeny,
"lectroids" and "tanstaafl", still include a number of the oddest
and most interesting people in hackerdom.

Mailing lists are easy to create and (unlike Usenet) don't tie up a
significant amount of machine resources (until they get very large, at
which point they can become interesting torture tests for mail
software). Thus, they are often created temporarily by working groups,
the members of which can then collaborate on a project without ever
needing to meet face-to-face. Much of the material in this lexicon was
criticized and polished on just such a mailing list (called
‘jargon-friends’), which included all the co-authors of Steele-1983.

 



mail storm
==============

 

**mail storm**: n.

[from `broadcast storm <./B.html#broadcast-storm>`__, influenced by
*maelstrom*] What often happens when a machine with an Internet
connection and active users re-connects after extended downtime — a
flood of incoming mail that brings the machine to its knees. See also
`hairball <./H.html#hairball>`__.

 



mainframe
=============

 

**mainframe**: n.

Term originally referring to the cabinet containing the central
processor unit or ‘main frame’ of a room-filling `Stone
Age <./S.html#Stone-Age>`__ batch machine. After the emergence of
smaller minicomputer designs in the early 1970s, the traditional `big
iron <./B.html#big-iron>`__ machines were described as ‘mainframe
computers’ and eventually just as mainframes. The term carries the
connotation of a machine designed for batch rather than interactive use,
though possibly with an interactive timesharing operating system
retrofitted onto it; it is especially used of machines built by IBM,
Unisys, and the other great `dinosaur <./D.html#dinosaur>`__\ s
surviving from computing's `Stone Age <./S.html#Stone-Age>`__.

It has been common wisdom among hackers since the late 1980s that the
mainframe architectural tradition is essentially dead (outside of the
tiny market for `number-crunching <./N.html#number-crunching>`__
supercomputers having been swamped by the recent huge advances in IC
technology and low-cost personal computing. The wave of failures,
takeovers, and mergers among traditional mainframe makers in the early
1990s bore this out. The biggest mainframer of all, IBM, was compelled
to re-invent itself as a huge systems-consulting house. (See `dinosaurs
mating <./D.html#dinosaurs-mating>`__ and `killer
micro <./K.html#killer-micro>`__).

However, in yet another instance of the `cycle of
reincarnation <./C.html#cycle-of-reincarnation>`__, the port of Linux
to the IBM S/390 architecture in 1999 — assisted by IBM — produced a
resurgence of interest in mainframe computing as a way of providing huge
quantities of easily maintainable, reliable virtual Linux servers,
saving IBM's mainframe division from almost certain extinction.

 


main loop
==============

 

**main loop**: n.

The top-level control flow construct in an input- or event-driven
program, the one which receives and acts or dispatches on the program's
input. See also `driver <./D.html#driver>`__.

 



mainsleaze
==============

 

**mainsleaze**: n.

1. Spam emitted by a reputable, mainstream company (as opposed to
fly-by-night Viagra oeddlers and the like). Sometime this happens in
honest ignorance, but the reputation danage can take years to live down.

2. Occasionally used for a big-time spammer, with its own `fat
pipe <./F.html#fat-pipe>`__, their own mailservers, and a `pink
contract <./P.html#pink-contract>`__. Almost impossible to get shut
down.

 



malware
==================

 

**malware**: n.

[Common] Malicious software. Software intended to cause consequences the
unwitting user would not choose; especially used of
`virus <./V.html#virus>`__ or `Trojan
horse <./T.html#Trojan-horse>`__ software.

management
===========

 

**management**: n.

1. Corporate power elites distinguished primarily by their distance from
actual productive work and their chronic failure to manage (see also
`suit <./S.html#suit>`__). Spoken derisively, as in “\ *Management*
decided that ...”.

2. Mythically, a vast bureaucracy responsible for all the world's minor
irritations. Hackers' satirical public notices are often signed ‘The
Mgt’; this derives from the *Illuminatus* novels (see the
`Bibliography <../pt03.html#bibliography>`__ in Appendix C).



mandelbug
====================

 

**mandelbug**: /man´del·buhg/, n.

[from the Mandelbrot set] A bug whose underlying causes are so complex
and obscure as to make its behavior appear chaotic or even
non-deterministic. This term implies that the speaker thinks it is a
`Bohr bug <./B.html#Bohr-bug>`__, rather than a
`heisenbug <./H.html#heisenbug>`__. See also
`schroedinbug <./S.html#schroedinbug>`__.

 


manged
===================

 

**manged**: /mahnjd/, n.

[probably from the French ‘manger’ or Italian ‘mangiare’, to eat;
perhaps influenced by English ‘mange’, ‘mangy’] adj. Refers to anything
that is mangled or damaged, usually beyond repair. “The disk was manged
after the electrical storm.” Compare `mung <mung>`__.

 

mangled name
====================

 

**mangled name**: n.

A name, appearing in a C++ object file, that is a coded representation
of the object declaration as it appears in the source. Mangled names are
used because C++ allows multiple objects to have the same name, as long
as they are distinguishable in some other way, such as by having
different parameter types. Thus, the internal name must have that
additional information embedded in it, using the limited character set
allowed by most linkers. For instance, one popular compiler encodes the
standard library function declaration “memchr(const void\*,int,unsigned
int)” as “@memchr$qpxviui”.

 

mangle
================

 

**mangle**: vt.

1. Used similarly to `mung <mung>`__ or
`scribble <./S.html#scribble>`__, but more violent in its
connotations; something that is mangled has been irreversibly and
totally trashed.

2. To produce the `mangled name <mangled-name>`__ corresponding
to a C++ declaration.

 


mangler
=================
 

**mangler**: n.

[DEC] A manager. Compare `management <management>`__. Note that
`system mangler <./S.html#system-mangler>`__ is somewhat different in
connotation.

 



man page
=============

 

**man page**: n.

A page from the Unix Programmer's Manual, documenting one of Unix's many
commands, system calls, library subroutines, device driver interfaces,
file formats, games, macro packages, or maintenance utilities. By
extension, the term “man page” may be used to refer to documentation of
any kind, under any system, though it is most likely to be confined to
short on-line references.

As mentioned in `Chapter 11, *Other Lexicon
Conventions <../conventions>`__, there is a standard syntax for
referring to man page entries: the phrase “foo(n)” refers to the page
for “foo” in chapter n of the manual, where chapter 1 is user commands,
chapter 2 is system calls, etc.

The man page format is beloved, or berated, for having the same sort of
pithy utility as the rest of Unix. Man pages tend to be written as very
compact, concise descriptions which are complete but not forgiving of
the lazy or careless reader. Their stylized format does a good job of
summarizing the essentials: invocation syntax, options, basic
functionality. While such a concise reference is perfect for the
do-one-thing-and-do-it-well tools which are favored by the Unix
philosophy, it admittedly breaks down when applied to a command which is
itself a major subsystem.

 

+  +  +  ---+
| `Prev <malware>`__    | `Up <../M>`__         |  `Next <management>`__   |
+  +  +  ---+
| malware                    | `Home <../index>`__   |  management                   |
+  +  +  ---+

manularity
===============

 

**manularity**: /man\`yoo·la´ri·tee/, n.

[prob. fr. techspeak manual + granularity] A notional measure of the
manual labor required for some task, particularly one of the sort that
automation is supposed to eliminate. “Composing English on paper has
much higher manularity than using a text editor, especially in the
revising stage.” Hackers tend to consider manularity a symptom of
primitive methods; in fact, a true hacker confronted with an apparent
requirement to do a computing task `by hand <./B.html#by-hand>`__
will inevitably seize the opportunity to build another tool (see
`toolsmith <./T.html#toolsmith>`__).

 

+  +  +  ------+
| `Prev <mangler>`__    | `Up <../M>`__         |  `Next <marching-ants>`__   |
+  +  +  ------+
| mangler                    | `Home <../index>`__   |  marching ants                   |
+  +  +  ------+

marbles
================

 

**marbles**: pl.n.

[from mainstream “lost all his/her marbles”] The minimum needed to build
your way further up some hierarchy of tools or abstractions. After a bad
system crash, you need to determine if the machine has enough marbles to
come up on its own, or enough marbles to allow a rebuild from backups,
or if you need to rebuild from scratch. “This compiler doesn't even have
enough marbles to compile `hello world <./H.html#hello-world>`__.”

 

+  ------+  +  -+
| `Prev <marching-ants>`__    | `Up <../M>`__         |  `Next <marginal>`__   |
+  ------+  +  -+
| marching ants                    | `Home <../index>`__   |  marginal                   |
+  ------+  +  -+

marching ants
==================

 

**marching ants**

The animated dotted-line marquee that indicates a rectangle or item
select in Adobe Photoshop, the GIMP, and other similar image-editing
programs.

 

+  ---+  +  +
| `Prev <manularity>`__    | `Up <../M>`__         |  `Next <marbles>`__   |
+  ---+  +  +
| manularity                    | `Home <../index>`__   |  marbles                   |
+  ---+  +  +

marginal
==============

 

**marginal**: adj.

[common]

1. [techspeak] An extremely small change. “A marginal increase in
`core <./C.html#core>`__ can decrease `GC <./G.html#GC>`__ time
drastically.” In everyday terms, this means that it is a lot easier to
clean off your desk if you have a spare place to put some of the junk
while you sort through it.

2. Of little merit. “This proposed new feature seems rather marginal to
me.”

3. Of extremely small probability of `win <./W.html#win>`__\ ning.
“The power supply was rather marginal anyway; no wonder it fried.”

 

+  +  +  ---+
| `Prev <marbles>`__    | `Up <../M>`__         |  `Next <marginally>`__   |
+  +  +  ---+
| marbles                    | `Home <../index>`__   |  marginally                   |
+  +  +  ---+

marginally
============
 

**marginally**: adv.

Slightly. “The ravs here are only marginally better than at Small Eating
Place.” See `epsilon <./E.html#epsilon>`__.

 

+  -+  +  ---+
| `Prev <marginal>`__    | `Up <../M>`__         |  `Next <marketroid>`__   |
+  -+  +  ---+
| marginal                    | `Home <../index>`__   |  marketroid                   |
+  -+  +  ---+

marketroid
==============

 

**marketroid**: /mar´k@·troyd/, n.

alt.: marketing slime, marketeer, mar­ket­ing droid, marketdroid. A
member of a company's marketing department, esp. one who promises users
that the next version of a product will have features that are not
actually scheduled for inclusion, are extremely difficult to implement,
and/or are in violation of the laws of physics; and/or one who describes
existing features (and misfeatures) in ebullient, buzzword-laden
adspeak. Derogatory. Compare `droid <./D.html#droid>`__.

 

+  ---+  + -----------+
| `Prev <marginally>`__    | `Up <../M>`__         |  `Next <Mars>`__   |
+  ---+  + -----------+
| marginally                    | `Home <../index>`__   |  Mars                   |
+  ---+  + -----------+

Mars
===============

 

**Mars**: n.

A legendary tragic failure, the archetypal Hacker Dream Gone Wrong. Mars
was the code name for a family of PDP-10-compatible computers built by
Systems Concepts (now, The SC Group): the multi-processor SC-30M, the
small uniprocessor SC-25, and the never-built superprocessor SC-40.
These machines were marvels of engineering design; although not much
slower than the unique `Foonly <./F.html#Foonly>`__ F-1, they were
physically smaller and consumed less power than the much slower
`DEC <./D.html#DEC>`__ KS10 or Foonly F-2, F-3, or F-4 machines. They
were also completely compatible with the DEC KL10, and ran all KL10
binaries (including the operating system) with no modifications at about
2--3 times faster than a KL10.

When DEC cancelled the Jupiter project in 1983 (their followup to the
PDP-10), Systems Concepts should have made a bundle selling their
machine into shops with a lot of software investment in PDP-10s, and in
fact their spring 1984 announcement generated a great deal of excitement
in the PDP-10 world. TOPS-10 was running on the Mars by the summer of
1984, and TOPS-20 by early fall. Unfortunately, the hackers running
Systems Concepts were much better at designing machines than at mass
producing or selling them; the company allowed itself to be sidetracked
by a bout of perfectionism into continually improving the design, and
lost credibility as delivery dates continued to slip. They also
overpriced the product ridiculously; they believed they were competing
with the KL10 and `VAX <./V.html#VAX>`__ 8600 and failed to reckon
with the likes of Sun Microsystems and other hungry startups building
workstations with power comparable to the KL10 at a fraction of the
price. By the time SC shipped the first SC-30M to Stanford in late 1985,
most customers had already made the traumatic decision to abandon the
PDP-10, usually for VMS or Unix boxes. Most of the Mars computers built
ended up being purchased by CompuServe.

This tale and the related saga of `Foonly <./F.html#Foonly>`__ hold a
lesson for hackers: if you want to play in the `Real
World <./R.html#Real-World>`__, you need to learn Real World moves.

 

+  ---+  +  +
| `Prev <marketroid>`__    | `Up <../M>`__         |  `Next <martian>`__   |
+  ---+  +  +
| marketroid                    | `Home <../index>`__   |  martian                   |
+  ---+  +  +

martian
=============
 

**martian**: n.

A packet sent on a TCP/IP network with a source address of the test
loopback interface [127.0.0.1]. This means that it will come back
labeled with a source address that is clearly not of this earth. “The
domain server is getting lots of packets from Mars. Does that gateway
have a martian filter?” Compare `Christmas tree
packet <./C.html#Christmas-tree-packet>`__,
`Godzillagram <./G.html#Godzillagram>`__.

 

+ -----------+  +  +
| `Prev <Mars>`__    | `Up <../M>`__         |  `Next <massage>`__   |
+ -----------+  +  +
| Mars                    | `Home <../index>`__   |  massage                   |
+ -----------+  +  +

massage
==============
 

**massage**: vt.

[common] Vague term used to describe ‘smooth’ transformations of a data
set into a different form, esp. transformations that do not lose
information. Connotes less pain than `munch <munch>`__ or
`crunch <./C.html#crunch>`__. “He wrote a program that massages X
bitmap files into GIF format.” Compare `slurp <./S.html#slurp>`__.

 

+  +  +  -+
| `Prev <martian>`__    | `Up <../M>`__         |  `Next <math-out>`__   |
+  +  +  -+
| martian                    | `Home <../index>`__   |  math-out                   |
+  +  +  -+

math-out
==============

 

**math-out**: n.

[poss. from ‘white-out’ (the blizzard variety)] A paper or presentation
so encrusted with mathematical or other formal notation as to be
incomprehensible. This may be a device for concealing the fact that it
is actually `content-free <./C.html#content-free>`__. See also
`numbers <./N.html#numbers>`__, `social science
number <./S.html#social-science-number>`__.

|image0|

A `math-out <math-out>`__ approach to history.

(The next cartoon in the Crunchly saga is
`73-05-19 <./S.html#space-cadet-keyboard.html#crunchly73-05-19>`__. The
previous one is the `frontispiece <../lexicon.html#crunchly-1>`__.)

 

+  +  + -------------+
| `Prev <massage>`__    | `Up <../M>`__         |  `Next <Matrix>`__   |
+  +  + -------------+
| massage                    | `Home <../index>`__   |  Matrix                   |
+  +  + -------------+

.. |image0| image:: ../_static/73-05-18.png

Matrix
=============

 

**Matrix**: n.

[FidoNet]

1. What the Opus BBS software and sysops call
`FidoNet <./F.html#FidoNet>`__.

2. Fanciful term for a `cyberspace <./C.html#cyberspace>`__ expected
to emerge from current networking experiments (see `the
network <./T.html#the-network>`__). The name of the rather good 1999
`cypherpunk <./C.html#cypherpunk>`__ movie *The Matrix* played on
this sense, which however had been established for years before.

3. The totality of present-day computer networks (popularized in this
sense by John Quarterman; rare outside academic literature).

 

+  -+  +  ------------+
| `Prev <math-out>`__    | `Up <../M>`__         |  `Next <maximum-Maytag-mode>`__   |
+  -+  +  ------------+
| math-out                    | `Home <../index>`__   |  maximum Maytag mode                   |
+  -+  +  ------------+

maximum Maytag mode
====================
 

**maximum Maytag mode**: n.

What a `washing machine <./W.html#washing-machine>`__ or, by
extension, any disk drive is in when it's being used so heavily that
it's shaking like an old Maytag with an unbalanced load. If prolonged
for any length of time, can lead to disks becoming `walking
drives <./W.html#walking-drives>`__. In 1999 it's been some years
since hard disks were large enough to do this, but the same phenomenon
has recently been reported with 24X CD-ROM drives.

 

+ -------------+  +  ------+
| `Prev <Matrix>`__    | `Up <../M>`__         |  `Next <McQuary-limit>`__   |
+ -------------+  +  ------+
| Matrix                    | `Home <../index>`__   |  McQuary limit                   |
+ -------------+  +  ------+

McQuary limit
===============

 

**McQuary limit**

[from the name of the founder of "alt.fan.warlord"; see
`warlording <./W.html#warlording>`__.] 4 lines of at most 80
characters each, sometimes still cited on Usenet as the maximum
acceptable size of a `sig block <./S.html#sig-block>`__. Before the
great bandwidth explosion of the early 1990s, long sigs actually cost
people running Usenet servers significant amounts of money. Nowadays
social pressure against long sigs is intended to avoid waste of human
attention rather than machine bandwidth. Accordingly, the McQuary limit
should be considered a rule of thumb rather than a hard limit; it's best
to avoid sigs that are large, repetitive, and distracting. See also
`warlording <./W.html#warlording>`__.

 

+  ------------+  +  --+
| `Prev <maximum-Maytag-mode>`__    | `Up <../M>`__         |  `Next <meatspace>`__   |
+  ------------+  +  --+
| maximum Maytag mode                    | `Home <../index>`__   |  meatspace                   |
+  ------------+  +  --+

meatspace
============

 

**meatspace**: /meet´spays/, n.

The physical world, where the meat lives — as opposed to
`cyberspace <./C.html#cyberspace>`__. Hackers are actually more
willing to use this term than ‘cyberspace’, because it's not speculative
— we already have a running meatspace implementation (the universe).
Compare `RL <./R.html#RL>`__.

 

+  ------+  +  -+
| `Prev <McQuary-limit>`__    | `Up <../M>`__         |  `Next <meatware>`__   |
+  ------+  +  -+
| McQuary limit                    | `Home <../index>`__   |  meatware                   |
+  ------+  +  -+

meatware
=================

 

**meatware**: n.

Synonym for `wetware <./W.html#wetware>`__. Less common.

 

+  --+  + -------------+
| `Prev <meatspace>`__    | `Up <../M>`__         |  `Next <meeces>`__   |
+  --+  + -------------+
| meatspace                    | `Home <../index>`__   |  meeces                   |
+  --+  + -------------+

meeces
============

 

**meeces**: /mees'@z/, n.

[TMRC] Occasional furry visitors who are not
`urchin <./U.html#urchin>`__\ s. [That is, mice. This may no longer
be in live use; it clearly derives from the refrain of the early-1960s
cartoon character Mr. Jinks: “I hate meeces to *pieces*!” — ESR]

 

+  -+  + ----------+
| `Prev <meatware>`__    | `Up <../M>`__         |  `Next <meg>`__   |
+  -+  + ----------+
| meatware                    | `Home <../index>`__   |  meg                   |
+  -+  + ----------+

mega-
===========

 

**mega-**: /me´g@/, pref.

[SI] See `quantifiers <./Q.html#quantifiers>`__.

 

+ ----------+  +  --+
| `Prev <meg>`__    | `Up <../M>`__         |  `Next <megapenny>`__   |
+ ----------+  +  --+
| meg                    | `Home <../index>`__   |  megapenny                   |
+ ----------+  +  --+

megapenny
==============
 

**megapenny**: /meg'@·pen\`ee/, n.

$10,000 (1 cent \* "106"). Used semi-humorously as a unit in comparing
computer cost and performance figures.

 

+ ------------+  + -----------+
| `Prev <mega->`__    | `Up <../M>`__         |  `Next <MEGO>`__   |
+ ------------+  + -----------+
| mega-                    | `Home <../index>`__   |  MEGO                   |
+ ------------+  + -----------+

meg
=============

 

**meg**: /meg/, n.

See `quantifiers <./Q.html#quantifiers>`__.

 

+ -------------+  + ------------+
| `Prev <meeces>`__    | `Up <../M>`__         |  `Next <mega->`__   |
+ -------------+  + ------------+
| meeces                    | `Home <../index>`__   |  mega-                   |
+ -------------+  + ------------+

MEGO
=========

 

**MEGO**: /me´goh/, /mee´goh/

[“My Eyes Glaze Over”, often “Mine Eyes Glazeth (sic) Over”, attributed
to the futurologist Herman Kahn] Also MEGO factor.

1. n. A `handwave <./H.html#handwave>`__ intended to confuse the
listener and hopefully induce agreement because the listener does not
want to admit to not understanding what is going on. MEGO is usually
directed at senior management by engineers and contains a high
proportion of `TLA <./T.html#TLA>`__\ s.

2. excl. An appropriate response to MEGO tactics.

3. Among non-hackers, often refers not to behavior that causes the eyes
to glaze, but to the eye-glazing reaction itself, which may be triggered
by the mere threat of excessive technical detail as effectively as by an
actual excess of it.

 

+  --+  +  ----------+
| `Prev <megapenny>`__    | `Up <../M>`__         |  `Next <meltdown--network>`__   |
+  --+  +  ----------+
| megapenny                    | `Home <../index>`__   |  meltdown, network                   |
+  --+  +  ----------+

meltdown, network
====================

 

**meltdown, network**: n.

See `network meltdown <./N.html#network-meltdown>`__.

 

+ -----------+  + -----------+
| `Prev <MEGO>`__    | `Up <../M>`__         |  `Next <meme>`__   |
+ -----------+  + -----------+
| MEGO                    | `Home <../index>`__   |  meme                   |
+ -----------+  + -----------+

meme
=============
 

**meme**: /meem/, n.

[coined by analogy with ‘gene’, by Richard Dawkins] An idea considered
as a `replicator <./R.html#replicator>`__, esp. with the connotation
that memes parasitize people into propagating them much as viruses do.
Used esp. in the phrase meme complex denoting a group of mutually
supporting memes that form an organized belief system, such as a
religion. This lexicon is an (epidemiological) vector of the ‘hacker
subculture’ meme complex; each entry might be considered a meme.
However, meme is often misused to mean meme complex. Use of the term
connotes acceptance of the idea that in humans (and presumably other
tool- and language-using sophonts) cultural evolution by selection of
adaptive ideas has superseded biological evolution by selection of
hereditary traits. Hackers find this idea congenial for tolerably
obvious reasons.

 

+  ----------+  +  ----+
| `Prev <meltdown--network>`__    | `Up <../M>`__         |  `Next <meme-plague>`__   |
+  ----------+  +  ----+
| meltdown, network                    | `Home <../index>`__   |  meme plague                   |
+  ----------+  +  ----+

meme plague
================
 

**meme plague**: n.

The spread of a successful but pernicious `meme <meme>`__, esp.
one that parasitizes the victims into giving their all to propagate it.
Astrology, BASIC, and the other guy's religion are often considered to
be examples. This usage is given point by the historical fact that
‘joiner’ ideologies like Naziism or various forms of millennarian
Christianity have exhibited plague-like cycles of exponential growth
followed by collapses to small reservoir populations.

 

+ -----------+  +  -+
| `Prev <meme>`__    | `Up <../M>`__         |  `Next <memetics>`__   |
+ -----------+  +  -+
| meme                    | `Home <../index>`__   |  memetics                   |
+ -----------+  +  -+

memetics
==============

 

**memetics**: /me·met´iks/, n.

[from `meme <meme>`__] The study of memes. As of early 2003, this
is still an extremely informal and speculative endeavor, though the
first steps towards at least statistical rigor have been made by H.
Keith Henson and others. Memetics is a popular topic for speculation
among hackers, who like to see themselves as the architects of the new
information ecologies in which memes live and replicate.

 

+  ----+  +  -----+
| `Prev <meme-plague>`__    | `Up <../M>`__         |  `Next <memory-farts>`__   |
+  ----+  +  -----+
| meme plague                    | `Home <../index>`__   |  memory farts                   |
+  ----+  +  -----+

memory farts
=================

 

**memory farts**: n.

The flatulent sounds that some DOS box BIOSes (most notably AMI's) make
when checking memory on bootup.

 

+  -+  +  ----+
| `Prev <memetics>`__    | `Up <../M>`__         |  `Next <memory-leak>`__   |
+  -+  +  ----+
| memetics                    | `Home <../index>`__   |  memory leak                   |
+  -+  +  ----+

memory leak
==============

 

**memory leak**: n.

An error in a program's dynamic-store allocation logic that causes it to
fail to reclaim discarded memory, leading to eventual collapse due to
memory exhaustion. Also (esp. at CMU) called `core
leak <./C.html#core-leak>`__. These problems were severe on older
machines with small, fixed-size address spaces, and special “leak
detection” tools were commonly written to root them out. With the advent
of virtual memory, it is unfortunately easier to be sloppy about wasting
a bit of memory (although when you run out of memory on a VM machine, it
means you've got a *real* leak!). See `aliasing
bug <./A.html#aliasing-bug>`__, `fandango on
core <./F.html#fandango-on-core>`__, `smash the
stack <./S.html#smash-the-stack>`__, `precedence
lossage <./P.html#precedence-lossage>`__, `overrun
screw <./O.html#overrun-screw>`__, `leaky
heap <./L.html#leaky-heap>`__, `leak <./L.html#leak>`__.

 

+  -----+  +  -----+
| `Prev <memory-farts>`__    | `Up <../M>`__         |  `Next <memory-smash>`__   |
+  -----+  +  -----+
| memory farts                    | `Home <../index>`__   |  memory smash                   |
+  -----+  +  -----+

memory smash
=============

 

**memory smash**: n.

[XEROX PARC] Writing through a pointer that doesn't point to what you
think it does. This occasionally reduces your memory to a rubble of
bits. Note that this is subtly different from (and more general than)
related terms such as a `memory leak <memory-leak>`__ or
`fandango on core <./F.html#fandango-on-core>`__ because it doesn't
imply an allocation error or overrun condition.

 

+  ----+  +  -+
| `Prev <memory-leak>`__    | `Up <../M>`__         |  `Next <menuitis>`__   |
+  ----+  +  -+
| memory leak                    | `Home <../index>`__   |  menuitis                   |
+  ----+  +  -+

menuitis
=============

 

**menuitis**: /men\`yoo·i:´tis/, n.

Notional disease suffered by software with an obsessively simple-minded
menu interface and no escape. Hackers find this intensely irritating and
much prefer the flexibility of command-line or language-style
interfaces, especially those customizable via macros or a
special-purpose language in which one can encode useful hacks. See
`user-obsequious <./U.html#user-obsequious>`__, `drool-proof
paper <./D.html#drool-proof-paper>`__, `WIMP
environment <./W.html#WIMP-environment>`__, `for the rest of
us <./F.html#for-the-rest-of-us>`__.

 

+  -----+  +  -+
| `Prev <memory-smash>`__    | `Up <../M>`__         |  `Next <mess-dos>`__   |
+  -----+  +  -+
| memory smash                    | `Home <../index>`__   |  mess-dos                   |
+  -----+  +  -+

mess-dos
===============
 

**mess-dos**: /mes·dos/, n.

[semi-obsolescent now that DOS is] Derisory term for MS-DOS. Often
followed by the ritual banishing “Just say No!” See
`MS-DOS <MS-DOS>`__. Most hackers (even many MS-DOS hackers)
loathed MS-DOS for its single-tasking nature, its limits on application
size, its nasty primitive interface, and its ties to IBMness and
Microsoftness (see `fear and
loathing <./F.html#fear-and-loathing>`__). Also mess-loss, messy-dos,
mess-dog, mess-dross, mush-dos, and various combinations thereof. In
Ireland and the U.K. it is even sometimes called ‘Domestos’ after a
brand of toilet cleanser.

 

+  -+  + -----------+
| `Prev <menuitis>`__    | `Up <../M>`__         |  `Next <meta>`__   |
+  -+  + -----------+
| menuitis                    | `Home <../index>`__   |  meta                   |
+  -+  + -----------+

meta bit
=========

 

**meta bit**: n.

The top bit of an 8-bit character, which is on in character values
128--255. Also called `high bit <./H.html#high-bit>`__, `alt
bit <./A.html#alt-bit>`__. Some terminals and consoles (see
`space-cadet keyboard <./S.html#space-cadet-keyboard>`__) have a META
shift key. Others (including, *mirabile dictu*, keyboards on IBM
PC-class machines) have an ALT key. See also `bucky
bits <./B.html#bucky-bits>`__.

Historical note: although in modern usage shaped by a universe of 8-bit
bytes the meta bit is invariably hex 80 (octal 0200), things were
different on earlier machines with 36-bit words and 9-bit bytes. The MIT
and Stanford keyboards (see `space-cadet
keyboard <./S.html#space-cadet-keyboard>`__) generated hex 100 (octal
400) from their meta keys.

 

+ -----------+  +   -+
| `Prev <meta>`__    | `Up <../M>`__         |  `Next <metasyntactic-variable>`__   |
+ -----------+  +   -+
| meta                    | `Home <../index>`__   |  metasyntactic variable                   |
+ -----------+  +   -+

meta
===========

 

**meta**: /me´t@/, /may´t@/, /mee´t@/, pref.

[from analytic philosophy] One level of description up. A metasyntactic
variable is a variable in notation used to describe syntax, and
meta-language is language used to describe language. This is difficult
to explain briefly, but much hacker humor turns on deliberate confusion
between meta-levels. See `hacker humor <./H.html#hacker-humor>`__.

 

+  -+  +  -+
| `Prev <mess-dos>`__    | `Up <../M>`__         |  `Next <meta-bit>`__   |
+  -+  +  -+
| mess-dos                    | `Home <../index>`__   |  meta bit                   |
+  -+  +  -+

metasyntactic variable
========================
 

**metasyntactic variable**: n.

A name used in examples and understood to stand for whatever thing is
under discussion, or any random member of a class of things under
discussion. The word `foo <./F.html#foo>`__ is the
`canonical <./C.html#canonical>`__ example. To avoid confusion,
hackers never (well, hardly ever) use ‘foo’ or other words like it as
permanent names for anything. In filenames, a common convention is that
any filename beginning with a metasyntactic-variable name is a
`scratch <./S.html#scratch>`__ file that may be deleted at any time.

Metasyntactic variables are so called because (1) they are variables in
the metalanguage used to talk about programs etc; (2) they are variables
whose values are often variables (as in usages like “the value of
f(foo,bar) is the sum of foo and bar”). However, it has been plausibly
suggested that the real reason for the term “metasyntactic variable” is
that it sounds good. To some extent, the list of one's preferred
metasyntactic variables is a cultural signature. They occur both in
series (used for related groups of variables or objects) and as
singletons. Here are a few common signatures:

+         -----+                      ------------+
| `foo <./F.html#foo>`__, `bar <./B.html#bar>`__, `baz <./B.html#baz>`__, `quux <./Q.html#quux>`__, quuux, quuuux...:   | MIT/Stanford usage, now found everywhere (thanks largely to early versions of this lexicon!). At MIT (but not at Stanford), `baz <./B.html#baz>`__ dropped out of use for a while in the 1970s and '80s. A common recent mutation of this sequence inserts `qux <./Q.html#qux>`__\ before `quux <./Q.html#quux>`__.   |
+         -----+                      ------------+
| bazola, ztesch:                                                                                                                   | Stanford (from mid-'70s on).                                                                                                                                                                                                                                                                                                   |
+         -----+                      ------------+
| `foo <./F.html#foo>`__, `bar <./B.html#bar>`__, thud, grunt:                                                                | This series was popular at CMU. Other CMU-associated variables include `gorp <./G.html#gorp>`__.                                                                                                                                                                                                                            |
+         -----+                      ------------+
| `foo <./F.html#foo>`__, `bar <./B.html#bar>`__, bletch:                                                                     | Waterloo University. We are informed that the CS club at Waterloo formerly had a sign on its door reading “Ye Olde Foo Bar and Grill”; this led to an attempt to establish “grill” as the third metasyntactic variable, but it never caught on.                                                                                |
+         -----+                      ------------+
| `foo <./F.html#foo>`__, `bar <./B.html#bar>`__, fum:                                                                        | This series is reported to be common at XEROX PARC.                                                                                                                                                                                                                                                                            |
+         -----+                      ------------+
| `fred <./F.html#fred>`__, jim, sheila, `barney <./B.html#barney>`__:                                                        | See the entry for `fred <./F.html#fred>`__. These tend to be Britishisms.                                                                                                                                                                                                                                                   |
+         -----+                      ------------+
| `flarp <./F.html#flarp>`__:                                                                                                    | Popular at Rutgers University and among `GOSMACS <./G.html#GOSMACS>`__ hackers.                                                                                                                                                                                                                                             |
+         -----+                      ------------+
| zxc, spqr, wombat:                                                                                                                | Cambridge University (England).                                                                                                                                                                                                                                                                                                |
+         -----+                      ------------+
| shme                                                                                                                              | Berkeley, GeoWorks, Ingres. Pronounced /shme/ with a short /e/.                                                                                                                                                                                                                                                                |
+         -----+                      ------------+
| foo, bar, baz, bongo                                                                                                              | Yale, late 1970s.                                                                                                                                                                                                                                                                                                              |
+         -----+                      ------------+
| spam, eggs                                                                                                                        | `Python <./P.html#Python>`__ programmers.                                                                                                                                                                                                                                                                                   |
+         -----+                      ------------+
| snork                                                                                                                             | Brown University, early 1970s.                                                                                                                                                                                                                                                                                                 |
+         -----+                      ------------+
| `foo <./F.html#foo>`__, `bar <./B.html#bar>`__, zot                                                                         | Helsinki University of Technology, Finland.                                                                                                                                                                                                                                                                                    |
+         -----+                      ------------+
| blarg, `wibble <./W.html#wibble>`__                                                                                            | New Zealand.                                                                                                                                                                                                                                                                                                                   |
+         -----+                      ------------+
| toto, titi, tata, tutu                                                                                                            | France.                                                                                                                                                                                                                                                                                                                        |
+         -----+                      ------------+
| pippo, pluto, paperino                                                                                                            | Italy. Pippo /pee´po/ and Paperino /pa·per·ee'·no/ are the Italian names for Goofy and Donald Duck.                                                                                                                                                                                                                            |
+         -----+                      ------------+
| aap, noot, mies                                                                                                                   | The Netherlands. These are the first words a child used to learn to spell on a Dutch spelling board.                                                                                                                                                                                                                           |
+         -----+                      ------------+
| oogle, foogle, boogle; zork, gork, bork                                                                                           | These two series (which may be continued with other initial consonents) are reportedly common in England, and said to go back to Lewis Carroll.                                                                                                                                                                                |
+         -----+                      ------------+

Of all these, only foo and bar are universal (and
`baz <./B.html#baz>`__ nearly so). The compounds
`foobar <./F.html#foobar>`__ and foobaz also enjoy very wide
currency. Some jargon terms are also used as metasyntactic names;
`barf <./B.html#barf>`__ and `mumble <mumble>`__, for example.
See also `Commonwealth Hackish <./C.html#Commonwealth-Hackish>`__ for
discussion of numerous metasyntactic variables found in Great Britain
and the Commonwealth.

 

+  -+  + -----------+
| `Prev <meta-bit>`__    | `Up <../M>`__         |  `Next <MFTL>`__   |
+  -+  + -----------+
| meta bit                    | `Home <../index>`__   |  MFTL                   |
+  -+  + -----------+

MFTL
==========

 

**MFTL**: /M·F·T·L/

[abbreviation: ‘My Favorite Toy Language’]

1. adj. Describes a talk on a programming language design that is heavy
on the syntax (with lots of BNF), sometimes even talks about semantics
(e.g., type systems), but rarely, if ever, has any content (see
`content-free <./C.html#content-free>`__). More broadly applied to
talks — even when the topic is not a programming language — in which the
subject matter is gone into in unnecessary and meticulous detail at the
sacrifice of any conceptual content. “Well, it was a typical MFTL talk”.

2. n. Describes a language about which the developers are passionate
(often to the point of proselytic zeal) but no one else cares about.
Applied to the language by those outside the originating group. “He
cornered me about type resolution in his MFTL.”

The first great goal in the mind of the designer of an MFTL is usually
to write a compiler for it, then bootstrap the design away from
contamination by lesser languages by writing a compiler for it in
itself. Thus, the standard put-down question at an MFTL talk is “Has it
been used for anything besides its own compiler?” On the other hand, a
(compiled) language that cannot even be used to write its own compiler
is beneath contempt. (The qualification has become necessary because of
the increasing popularity of interpreted languages like
`Perl <./P.html#Perl>`__ and `Python <./P.html#Python>`__.) See
`break-even point <./B.html#break-even-point>`__. (On a related note,
Doug McIlroy once proposed a test of the generality and utility of a
language and the operating system under which it is compiled: “Is the
output of a FORTRAN program acceptable as input to the FORTRAN
compiler?” In other words, can you write programs that write programs?
(See `toolsmith <./T.html#toolsmith>`__.) Alarming numbers of
(language, OS) pairs fail this test, particularly when the language is
FORTRAN; aficionados are quick to point out that
`Unix <./U.html#Unix>`__ (even using FORTRAN) passes it handily. That
the test could ever be failed is only surprising to those who have had
the good fortune to have worked only under modern systems which lack
OS-supported and -imposed “file types”.)

 

+   -+  + -------------+
| `Prev <metasyntactic-variable>`__    | `Up <../M>`__         |  `Next <mickey>`__   |
+   -+  + -------------+
| metasyntactic variable                    | `Home <../index>`__   |  mickey                   |
+   -+  + -------------+

M
======

 

**M**: pref.

[SI] See `quantifiers <./Q.html#quantifiers>`__.

 

+ -----------+  + ---------+
| `Prev <../M>`__    | `Up <../M>`__         |  `Next <MS>`__   |
+ -----------+  + ---------+
| M                       | `Home <../index>`__   |  M$                   |
+ -----------+  + ---------+

mickey
==========

 

**mickey**: n.

The resolution unit of mouse movement. It has been suggested that the
disney will become a benchmark unit for animation graphics performance.

 

+ -----------+  +  -------------+
| `Prev <MFTL>`__    | `Up <../M>`__         |  `Next <mickey-mouse-program>`__   |
+ -----------+  +  -------------+
| MFTL                    | `Home <../index>`__   |  mickey mouse program                   |
+ -----------+  +  -------------+

mickey mouse program
=====================

 

**mickey mouse program**: n.

North American equivalent of a `noddy <./N.html#noddy>`__ (that is,
trivial) program. Doesn't necessarily have the belittling connotations
of mainstream slang “Oh, that's just mickey mouse stuff!”; sometimes
trivial programs can be very useful.

 

+ -------------+  + -------------+
| `Prev <mickey>`__    | `Up <../M>`__         |  `Next <micro->`__   |
+ -------------+  + -------------+
| mickey                    | `Home <../index>`__   |  micro-                   |
+ -------------+  + -------------+

MicroDroid
=========================

 

**MicroDroid**: n.

[Usenet] A Microsoft employee, esp. one who posts to various
operating-system advocacy newsgroups. MicroDroids post follow-ups to any
messages critical of Microsoft's operating systems, and often end up
sounding like visiting fundamentalist missionaries. See also
`astroturfing <./A.html#astroturfing>`__; compare
`microserf <microserf>`__.

 

+ -------------+  +  -------+
| `Prev <micro->`__    | `Up <../M>`__         |  `Next <microfortnight>`__   |
+ -------------+  +  -------+
| micro-                    | `Home <../index>`__   |  microfortnight                   |
+ -------------+  +  -------+

microfortnight
=================

 

**microfortnight**: n.

1/1000000 of the fundamental unit of time in the
Furlong/Firkin/Fortnight system of measurement; 1.2096 sec. (A furlong
is 1/8th of a mile; a firkin is 9 imperial gallons; the mass unit of the
system is taken to be a firkin of water). The VMS operating system has a
lot of tuning parameters that you can set with the SYSGEN utility, and
one of these is TIMEPROMPTWAIT, the time the system will wait for an
operator to set the correct date and time at boot if it realizes that
the current value is bogus. This time is specified in microfortnights!

Multiple uses of the millifortnight (about 20 minutes) and
`nanofortnight <./N.html#nanofortnight>`__ have also been reported.

 

+  ---+  +  ---+
| `Prev <MicroDroid>`__    | `Up <../M>`__         |  `Next <microLenat>`__   |
+  ---+  +  ---+
| MicroDroid                    | `Home <../index>`__   |  microLenat                   |
+  ---+  +  ---+

micro-
============

 

**micro-**: pref.

1. Very small; this is the root of its use as a quantifier prefix.

2. A quantifier prefix, calling for multiplication by "10-6" (see
`quantifiers <./Q.html#quantifiers>`__). Neither of these uses is
peculiar to hackers, but hackers tend to fling them both around rather
more freely than is countenanced in standard English. It is recorded,
for example, that one CS professor used to characterize the standard
length of his lectures as a microcentury — that is, about 52.6 minutes
(see also `attoparsec <./A.html#attoparsec>`__,
`nanoacre <./N.html#nanoacre>`__, and especially
`microfortnight <microfortnight>`__).

3. Personal or human-scale — that is, capable of being maintained or
comprehended or manipulated by one human being. This sense is
generalized from microcomputer, and is esp. used in contrast with macro-
(the corresponding Greek prefix meaning ‘large’).

4. Local as opposed to global (or `macro- <macro->`__). Thus a
hacker might say that buying a smaller car to reduce pollution only
solves a microproblem; the macroproblem of getting to work might be
better solved by using mass transit, moving to within walking distance,
or (best of all) telecommuting.

 

+  -------------+  +  ---+
| `Prev <mickey-mouse-program>`__    | `Up <../M>`__         |  `Next <MicroDroid>`__   |
+  -------------+  +  ---+
| mickey mouse program                    | `Home <../index>`__   |  MicroDroid                   |
+  -------------+  +  ---+

microLenat
=================

 

**microLenat**: /mi:\`·kroh·len'·@t/, n.

The unit of `bogosity <./B.html#bogosity>`__. Abbreviated µL or mL in
ASCII Consensus is that this is the largest unit practical for everyday
use. The microLenat, originally invented by David Jefferson, was
promulgated as an attack against noted computer scientist Doug Lenat by
a `tenured graduate student <./T.html#tenured-graduate-student>`__ at
CMU. Doug had failed the student on an important exam because the
student gave only “AI is bogus” as his answer to the questions. The slur
is generally considered unmerited, but it has become a running gag
nevertheless. Some of Doug's friends argue that *of course* a microLenat
is bogus, since it is only one millionth of a Lenat. Others have
suggested that the unit should be redesignated after the grad student,
as the microReid.

 

+  -------+  +  --+
| `Prev <microfortnight>`__    | `Up <../M>`__         |  `Next <microReid>`__   |
+  -------+  +  --+
| microfortnight                    | `Home <../index>`__   |  microReid                   |
+  -------+  +  --+

microReid
===========

 

**microReid**: /mi:´kroh·reed/, n.

See `microLenat <microLenat>`__.

 

+  ---+  +  --+
| `Prev <microLenat>`__    | `Up <../M>`__         |  `Next <microserf>`__   |
+  ---+  +  --+
| microLenat                    | `Home <../index>`__   |  microserf                   |
+  ---+  +  --+

microserf
=====================
 

**microserf**: /mi:´kro·s@rf/

[popularized, though not originated, by Douglas Coupland's book
*Microserfs*] A programmer at `Microsoft <#Microsoft>`__,
especially a low-level coder with little chance of fame or fortune.
Compare `MicroDroid <MicroDroid>`__.

 

+  --+  +  -----------+
| `Prev <microReid>`__    | `Up <../M>`__         |  `Next <Microsloth-Windows>`__   |
+  --+  +  -----------+
| microReid                    | `Home <../index>`__   |  Microsloth Windows                   |
+  --+  +  -----------+

Microsloth Windows
====================

 

**Microsloth Windows**: /mi:´kroh·sloth\` win´dohz/, n.

(Variants combine {Microshift, Macroshaft, Microsuck} with {Windoze,
WinDOS}. Hackerism(s) for ‘Microsoft Windows’. A thirty-two bit
extension and graphical shell to a sixteen-bit patch to an eight-bit
operating system originally coded for a four-bit microprocessor which
was written by a two-bit company that can't stand one bit of
competition. Also just called Windoze, with the implication that you can
fall asleep waiting for it to do anything; the latter term is extremely
common on Usenet. See `Black Screen of
Death <./B.html#Black-Screen-of-Death>`__ and `Blue Screen of
Death <./B.html#Blue-Screen-of-Death>`__; compare
`X <./X.html#X>`__, `sun-stools <./S.html#sun-stools>`__.

 

+  --+  +  --+
| `Prev <microserf>`__    | `Up <../M>`__         |  `Next <Microsoft>`__   |
+  --+  +  --+
| microserf                    | `Home <../index>`__   |  Microsoft                   |
+  --+  +  --+

Microsoft
===============
 

**Microsoft**

The new `Evil Empire <./E.html#Evil-Empire>`__ (the old one was
`IBM <./I.html#IBM>`__). The basic complaints are, as formerly with
IBM, that (a) their system designs are horrible botches, (b) we can't
get `source <./S.html#source>`__ to fix them, and (c) they throw
their weight around a lot. See also `Halloween
Documents <./H.html#Halloween-Documents>`__.

 

+  -----------+  +  -------+
| `Prev <Microsloth-Windows>`__    | `Up <../M>`__         |  `Next <micros-tilde-1>`__   |
+  -----------+  +  -------+
| Microsloth Windows                    | `Home <../index>`__   |  micros~1                         |
+  -----------+  +  -------+

micros~1
=============

 

**micros~1**

An abbreviation of the full name `Microsoft <Microsoft>`__
resembling the rather `bogus <./B.html#bogus>`__ way Windows 9x's
VFAT filesystem truncates long file names to fit in the MS-DOS 8+3
scheme (the real filename is stored elsewhere). If other files start
with the same prefix, they'll be called micros~2 and so on, causing lots
of problems with backups and other routine system-administration
problems. During the US Antitrust trial against Microsoft the names
Micros~1 and Micros~2 were suggested for the two companies that would
exist after a break-up.

 

+  --+  +  ------+
| `Prev <Microsoft>`__    | `Up <../M>`__         |  `Next <middle-endian>`__   |
+  --+  +  ------+
| Microsoft                    | `Home <../index>`__   |  middle-endian                   |
+  --+  +  ------+

middle-endian
===============

 

**middle-endian**: adj.

Not `big-endian <./B.html#big-endian>`__ or
`little-endian <./L.html#little-endian>`__. Used of perverse byte
orders such as 3-4-1-2 or 2-1-4-3, occasionally found in the
packed-decimal formats of minicomputer manufacturers who shall remain
nameless. See `NUXI problem <./N.html#NUXI-problem>`__. Non-US
hackers use this term to describe the American mm/dd/yy style of writing
dates (Europeans write little-endian dd/mm/yy, and Japanese use
big-endian yy/mm/dd for Western dates).

 

+  -------+  +   ----+
| `Prev <micros-tilde-1>`__    | `Up <../M>`__         |  `Next <middle-out-implementation>`__   |
+  -------+  +   ----+
| micros~1                          | `Home <../index>`__   |  middle-out implementation                   |
+  -------+  +   ----+

middle-out implementation
===========================

 

**middle-out implementation**

See `bottom-up implementation <./B.html#bottom-up-implementation>`__.

 

+  ------+  +  -----+
| `Prev <middle-endian>`__    | `Up <../M>`__         |  `Next <milliLampson>`__   |
+  ------+  +  -----+
| middle-endian                    | `Home <../index>`__   |  milliLampson                   |
+  ------+  +  -----+

milliLampson
==============

 

**milliLampson**: /mil'@·lamp\`sn/, n.

A unit of talking speed, abbreviated mL. Most people run about 200
milliLampsons. The eponymous Butler Lampson (a CS theorist and systems
implementor highly regarded among hackers) goes at 1000. A few people
speak faster. This unit is sometimes used to compare the (sometimes
widely disparate) rates at which people can generate ideas and actually
emit them in speech. For example, noted computer architect C. Gordon
Bell (designer of the `PDP-11 <./P.html#PDP-11>`__) is said, with
some awe, to think at about 1200 mL but only talk at about 300; he is
frequently reduced to fragments of sentences as his mouth tries to keep
up with his speeding brain.

 

+   ----+  +  -----+
| `Prev <middle-out-implementation>`__    | `Up <../M>`__         |  `Next <minor-detail>`__   |
+   ----+  +  -----+
| middle-out implementation                    | `Home <../index>`__   |  minor detail                   |
+   ----+  +  -----+

minor detail
===============

 

**minor detail**

Often used in an ironic sense about brokenness or problems that while
apparently major, are in principle solvable. “It works — the fact that
it crashes the system right after is a minor detail.” Compare
`SMOP <./S.html#SMOP>`__.

 

+  -----+  + -----------+
| `Prev <milliLampson>`__    | `Up <../M>`__         |  `Next <MIPS>`__   |
+  -----+  + -----------+
| milliLampson                    | `Home <../index>`__   |  MIPS                   |
+  -----+  + -----------+

MIPS
============

 

**MIPS**: /mips/, n.

[abbreviation]

1. A measure of computing speed; formally, ‘Million Instructions Per
Second’ (that's "106" per second, not "220"!); often rendered by
hackers as ‘Meaningless Indication of Processor Speed’ or in other
unflattering ways, such as ‘Meaningless Information Provided by
Salesmen’. This joke expresses an attitude nearly universal among
hackers about the value of most `benchmark <./B.html#benchmark>`__
claims, said attitude being one of the great cultural divides between
hackers and `marketroid <marketroid>`__\ s (see also
`BogoMIPS <./B.html#BogoMIPS>`__). The singular is sometimes ‘1 MIP’
even though this is clearly etymologically wrong. See also
`KIPS <./K.html#KIPS>`__ and `GIPS <./G.html#GIPS>`__.

2. Computers, especially large computers, considered abstractly as
sources of `computron <./C.html#computron>`__\ s. “This is just a
workstation; the heavy MIPS are hidden in the basement.”

3. The corporate name of a particular RISC-chip company, later acquired
by SGI.

4. Acronym for ‘Meaningless Information per Second’ (a joke, prob.: from
sense 1).

 

+  -----+  + -------------+
| `Prev <minor-detail>`__    | `Up <../M>`__         |  `Next <misbug>`__   |
+  -----+  + -------------+
| minor detail                    | `Home <../index>`__   |  misbug                   |
+  -----+  + -------------+

misbug
=============

 

**misbug**: /mis·buhg/, n.

[MIT; rare (like its referent)] An unintended property of a program that
turns out to be useful; something that should have been a
`bug <./B.html#bug>`__ but turns out to be a
`feature <./F.html#feature>`__. Compare `green
lightning <./G.html#green-lightning>`__. See
`miswart <miswart>`__.

 

+ -----------+  +  ---+
| `Prev <MIPS>`__    | `Up <../M>`__         |  `Next <misfeature>`__   |
+ -----------+  +  ---+
| MIPS                    | `Home <../index>`__   |  misfeature                   |
+ -----------+  +  ---+

misfeature
=============

 

**misfeature**: /mis·fee´chr/, /mis´fee\`chr/, n.

[common] A feature that eventually causes lossage, possibly because it
is not adequate for a new situation that has evolved. Since it results
from a deliberate and properly implemented feature, a misfeature is not
a bug. Nor is it a simple unforeseen side effect; the term implies that
the feature in question was carefully planned, but its long-term
consequences were not accurately or adequately predicted (which is quite
different from not having thought ahead at all). A misfeature can be a
particularly stubborn problem to resolve, because fixing it usually
involves a substantial philosophical change to the structure of the
system involved.

Many misfeatures (especially in user-interface design) arise because the
designers/implementors mistake their personal tastes for laws of nature.
Often a former feature becomes a misfeature because trade-offs were made
whose parameters subsequently change (possibly only in the judgment of
the implementors). “Well, yeah, it is kind of a misfeature that file
names are limited to six characters, but the original implementors
wanted to save directory space and we're stuck with it for now.”

 

+ -------------+  +  --------+
| `Prev <misbug>`__    | `Up <../M>`__         |  `Next <missile-address>`__   |
+ -------------+  +  --------+
| misbug                    | `Home <../index>`__   |  missile address                   |
+ -------------+  +  --------+

missile address
==================

 

**missile address**: n.

See `ICBM address <./I.html#ICBM-address>`__.

 

+  ---+  +  +
| `Prev <misfeature>`__    | `Up <../M>`__         |  `Next <MiSTing>`__   |
+  ---+  +  +
| misfeature                    | `Home <../index>`__   |  MiSTing                   |
+  ---+  +  +

MiSTing
============

 

**MiSTing**

[blogosphere] A variant of `fisking <./F.html#fisking>`__ patterned
on the protocol of Mystery Science Theater 3000, In a MiSTing, the
satire is spoken through characters purporting to be the MST3K robots or
other suitably bizarre characters, such as the Roman emperors Augustus
and Caligula.

 

+  --------+  +  +
| `Prev <missile-address>`__    | `Up <../M>`__         |  `Next <miswart>`__   |
+  --------+  +  +
| missile address                    | `Home <../index>`__   |  miswart                   |
+  --------+  +  +

miswart
===========

 

**miswart**: /mis·wort/, n.

[from `wart <./W.html#wart>`__ by analogy with
`misbug <misbug>`__] A `feature <./F.html#feature>`__ that
superficially appears to be a `wart <./W.html#wart>`__ but has been
determined to be the `Right Thing <./R.html#Right-Thing>`__. For
example, in some versions of the `EMACS <./E.html#EMACS>`__ text
editor, the ‘transpose characters’ command exchanges the character under
the cursor with the one before it on the screen, *except* when the
cursor is at the end of a line, in which case the two characters before
the cursor are exchanged. While this behavior is perhaps surprising, and
certainly inconsistent, it has been found through extensive
experimentation to be what most users want. This feature is a miswart.

 

+  +  + ----------+
| `Prev <MiSTing>`__    | `Up <../M>`__         |  `Next <MMF>`__   |
+  +  + ----------+
| MiSTing                    | `Home <../index>`__   |  MMF                   |
+  +  + ----------+

MMF
============

 

**MMF**: //

[Usenet; common] Abbreviation: “Make Money Fast”. Refers to any kind of
scheme which promises participants large profits with little or no risk
or effort. Typically, it is a some kind of multi-level marketing
operation which involves recruiting more members, or an illegal pyramid
scam. The term is also used to refer to any kind of spam which promotes
this. For more information, see the `Make Money Fast Myth
Page <http://www.stopspam.org/usenet/mmf/>`__.

 

+  +  + -----------+
| `Prev <miswart>`__    | `Up <../M>`__         |  `Next <mobo>`__   |
+  +  + -----------+
| miswart                    | `Home <../index>`__   |  mobo                   |
+  +  + -----------+

mobo
=========

 

**mobo**: /moh´bo/

Written and (rarely) spoken contraction of “motherboard”

 

+ ----------+  + -----------+
| `Prev <MMF>`__    | `Up <../M>`__         |  `Next <moby>`__   |
+ ----------+  + -----------+
| MMF                    | `Home <../index>`__   |  moby                   |
+ ----------+  + -----------+

moby
===========

 

**moby**: /moh´bee/

[MIT: seems to have been in use among model railroad fans years ago.
Derived from Melville's *Moby Dick* (some say from ‘Moby Pickle’). Now
common.]

1. adj. Large, immense, complex, impressive. “A Saturn V rocket is a
truly moby frob.” “Some MIT undergrads pulled off a moby hack at the
Harvard-Yale game.” (See `Appendix A <../appendixa>`__ for
discussion.)

2. n. obs. The maximum address space of a machine (see below). For a
680[234]0 or `VAX <./V.html#VAX>`__ or most modern 32-bit
architectures, it is 4,294,967,296 8-bit bytes (4 gigabytes).

3. A title of address (never of third-person reference), usually used to
show admiration, respect, and/or friendliness to a competent hacker.
“Greetings, moby Dave. How's that address-book thing for the Mac going?”

4. adj. In backgammon, doubles on the dice, as in moby sixes, moby ones,
etc. Compare this with `bignum <./B.html#bignum>`__ (sense 3): double
sixes are both bignums and moby sixes, but moby ones are not bignums
(the use of moby to describe double ones is sarcastic). Standard
emphatic forms: Moby foo, moby win, moby loss. Foby moo: a spoonerism
due to Richard Greenblatt.

5. The largest available unit of something which is available in
discrete increments. Thus, ordering a “moby Coke” at the local fast-food
joint is not just a request for a large Coke, it's an explicit request
for the largest size they sell.

This term entered hackerdom with the Fabritek 256K memory added to the
MIT AI PDP-6 machine, which was considered unimaginably huge when it was
installed in the 1960s (at a time when a more typical memory size for a
timesharing system was 72 kilobytes). Thus, a moby is classically 256K
36-bit words, the size of a PDP-6 or PDP-10 moby. Back when address
registers were narrow the term was more generally useful, because when a
computer had virtual memory mapping, it might actually have more
physical memory attached to it than any one program could access
directly. One could then say “This computer has 6 mobies” meaning that
the ratio of physical memory to address space is 6, without having to
say specifically how much memory there actually is. That in turn implied
that the computer could timeshare six ‘full-sized’ programs without
having to swap programs between memory and disk.

Nowadays the low cost of processor logic means that address spaces are
usually larger than the most physical memory you can cram onto a
machine, so most systems have much *less* than one theoretical ‘native’
moby of `core <./C.html#core>`__. Also, more modern memory-management
techniques (esp. paging) make the ‘moby count’ less significant.
However, there is one series of widely-used chips for which the term
could stand to be revived — the Intel 8088 and 80286 with their
incredibly `brain-damaged <./B.html#brain-damaged>`__
segmented-memory designs. On these, a moby would be the 1-megabyte
address span of a segment/offset pair (by coincidence, a PDP-10 moby was
exactly 1 megabyte of 9-bit bytes).

 

+ -----------+  +  ----+
| `Prev <mobo>`__    | `Up <../M>`__         |  `Next <mockingbird>`__   |
+ -----------+  +  ----+
| mobo                    | `Home <../index>`__   |  mockingbird                   |
+ -----------+  +  ----+

mockingbird
=============
 

**mockingbird**: n.

Software that intercepts communications (especially login transactions)
between users and hosts and provides system-like responses to the users
while saving their responses (especially account IDs and passwords). A
special case of `Trojan horse <./T.html#Trojan-horse>`__.

 

+ -----------+  + ----------+
| `Prev <moby>`__    | `Up <../M>`__         |  `Next <mod>`__   |
+ -----------+  + ----------+
| moby                    | `Home <../index>`__   |  mod                   |
+ -----------+  + ----------+

mode bit
===========

 

**mode bit**: n.

[common] A `flag <./F.html#flag>`__, usually in hardware, that
selects between two (usually quite different) modes of operation. The
connotations are different from `flag <./F.html#flag>`__ bit in that
mode bits are mainly written during a boot or set-up phase, are seldom
explicitly read, and seldom change over the lifetime of an ordinary
program. The classic example was the EBCDIC-vs.-ASCII bit (#12) of the
Program Status Word of the IBM 360.

 

+ -----------+  + -------------+
| `Prev <mode>`__    | `Up <../M>`__         |  `Next <modulo>`__   |
+ -----------+  + -------------+
| mode                    | `Home <../index>`__   |  modulo                   |
+ -----------+  + -------------+

mode
===========

 

**mode**: n.

[common] A general state, usually used with an adjective describing the
state. Use of the word ‘mode’ rather than ‘state’ implies that the state
is extended over time, and probably also that some activity
characteristic of that state is being carried out. “No time to hack; I'm
in thesis mode.” In its jargon sense, ‘mode’ is most often attributed to
people, though it is sometimes applied to programs and inanimate
objects. In particular, see `hack mode <./H.html#hack-mode>`__, `day
mode <./D.html#day-mode>`__, `night mode <./N.html#night-mode>`__,
`demo mode <./D.html#demo-mode>`__, `fireworks
mode <./F.html#fireworks-mode>`__, and `yoyo
mode <./Y.html#yoyo-mode>`__; also `talk
mode <./T.html#talk-mode>`__.

One also often hears the verbs enable and disable used in connection
with jargon modes. Thus, for example, a sillier way of saying “I'm going
to crash” is “I'm going to enable crash mode now”. One might also hear a
request to “disable flame mode, please”.

In a usage much closer to techspeak, a mode is a special state that
certain user interfaces must pass into in order to perform certain
functions. For example, in order to insert characters into a document in
the Unix editor **vi**, one must type the “i” key, which invokes the
“Insert” command. The effect of this command is to put vi into “insert
mode”, in which typing the “i” key has a quite different effect (to wit,
it inserts an “i” into the document). One must then hit another special
key, “ESC”, in order to leave “insert mode”. Nowadays, modeful
interfaces are generally considered `losing <./L.html#losing>`__ but
survive in quite a few widely used tools built in less enlightened
times.

 

+ ----------+  +  -+
| `Prev <mod>`__    | `Up <../M>`__         |  `Next <mode-bit>`__   |
+ ----------+  +  -+
| mod                    | `Home <../index>`__   |  mode bit                   |
+ ----------+  +  -+

mod
===========
 

**mod**: vt.,n.

[very common]

1. Short for ‘modify’ or ‘modification’. Very commonly used — in fact
the full terms are considered markers that one is being formal. The
plural ‘mods’ is used esp. with reference to bug fixes or minor design
changes in hardware or software, most esp. with respect to
`patch <./P.html#patch>`__ sets or a `diff <./D.html#diff>`__. See
also `case mod <./C.html#case-mod>`__.

2. Short for `modulo <modulo>`__ but used *only* for its
techspeak sense.

 

+  ----+  + -----------+
| `Prev <mockingbird>`__    | `Up <../M>`__         |  `Next <mode>`__   |
+  ----+  + -----------+
| mockingbird                    | `Home <../index>`__   |  mode                   |
+  ----+  + -----------+

modulo
===============

 

**modulo**: /mod´yu·loh/, prep.

Except for. An overgeneralization of mathematical terminology; one can
consider saying that 4 equals 22 except for the 9s ("4 =    22" mod
9). “Well, LISP seems to work okay now, modulo that
`GC <./G.html#GC>`__ bug.” “I feel fine today modulo a slight
headache.”

 

+  -+  +  -+
| `Prev <mode-bit>`__    | `Up <../M>`__         |  `Next <mojibake>`__   |
+  -+  +  -+
| mode bit                    | `Home <../index>`__   |  mojibake                   |
+  -+  +  -+

mojibake
============

 

**mojibake**: n., /mo´jee·ba·ke/

Japanese for “ghost characters”, the garbage that comes out when one
tries to display international character sets through software not
configured for them. There is a page on the topic at
`http://www.debian.or.jp/~kubota/mojibake/ <http://www.debian.or.jp/~kubota/mojibake/>`__.

 

+ -------------+  +  ----+
| `Prev <modulo>`__    | `Up <../M>`__         |  `Next <molly-guard>`__   |
+ -------------+  +  ----+
| modulo                    | `Home <../index>`__   |  molly-guard                   |
+ -------------+  +  ----+

molly-guard
===============

 

**molly-guard**: /mol´ee·gard/, n.

[University of Illinois] A shield to prevent tripping of some `Big Red
Switch <./B.html#Big-Red-Switch>`__ by clumsy or ignorant hands.
Originally used of the plexiglass covers improvised for the BRS on an
IBM 4341 after a programmer's toddler daughter (named Molly) frobbed it
twice in one day. Later generalized to covers over stop/reset switches
on disk drives and networking equipment. In hardware catalogues, you'll
see the much less interesting description “guarded button”.

 

+  -+  +   -----+
| `Prev <mojibake>`__    | `Up <../M>`__         |  `Next <Mongolian-Hordes-technique>`__   |
+  -+  +   -----+
| mojibake                    | `Home <../index>`__   |  Mongolian Hordes technique                   |
+  -+  +   -----+

Mongolian Hordes technique
===================================================
 

**Mongolian Hordes technique**: n.

[poss. from the Sixties counterculture expression Mongolian clusterfuck
for a public orgy] Development by `gang bang <./G.html#gang-bang>`__.
Implies that large numbers of inexperienced programmers are being put on
a job better performed by a few skilled ones (but see
`bazaar <./B.html#bazaar>`__). Also called Chinese Army technique;
see also `Brooks's Law <./B.html#Brookss-Law>`__.

 

+  ----+  +  --+
| `Prev <molly-guard>`__    | `Up <../M>`__         |  `Next <monkey-up>`__   |
+  ----+  +  --+
| molly-guard                    | `Home <../index>`__   |  monkey up                   |
+  ----+  +  --+

monkey, scratch
=========================
 

**monkey, scratch**: n.

See `scratch monkey <./S.html#scratch-monkey>`__.

 

+  --+  +  ----+
| `Prev <monkey-up>`__    | `Up <../M>`__         |  `Next <monstrosity>`__   |
+  --+  +  ----+
| monkey up                    | `Home <../index>`__   |  monstrosity                   |
+  --+  +  ----+

monkey up
==============
 

**monkey up**: vt.

To hack together hardware for a particular task, especially a one-shot
job. Connotes an extremely `crufty <./C.html#crufty>`__ and
consciously temporary solution. Compare `hack
up <./H.html#hack-up>`__, `kluge up <./K.html#kluge-up>`__, `cruft
together <./C.html#cruft-together>`__.

 

+   -----+  +  --------+
| `Prev <Mongolian-Hordes-technique>`__    | `Up <../M>`__         |  `Next <monkey--scratch>`__   |
+   -----+  +  --------+
| Mongolian Hordes technique                    | `Home <../index>`__   |  monkey, scratch                   |
+   -----+  +  --------+

monstrosity
=================
 

**monstrosity**

1. n. A ridiculously `elephantine <./E.html#elephantine>`__ program
or system, esp. one that is buggy or only marginally functional.

2. adj. The quality of being monstrous (see `the section called
“Overgeneralization” <../overgeneralization>`__ in the discussion
of jargonification). See also `baroque <./B.html#baroque>`__.

 

+  --------+  + ------------+
| `Prev <monkey--scratch>`__    | `Up <../M>`__         |  `Next <monty>`__   |
+  --------+  + ------------+
| monkey, scratch                    | `Home <../index>`__   |  monty                   |
+  --------+  + ------------+

monty
================

 

**monty**: /mon´tee/, n.

1. [US Geological Survey] A program with a ludicrously complex user
interface written to perform extremely trivial tasks. An example would
be a menu-driven, button clicking, pulldown, pop-up windows program for
listing directories. The original monty was an infamous
weather-reporting program, Monty the Amazing Weather Man, written at the
USGS. Monty had a widget-packed X-window interface with over 200
buttons; and all monty actually *did* was files off the network.

2. [Great Britain; commonly capitalized as Monty or as the Full Monty]
16 megabytes of memory, when fitted to an IBM-PC or compatible. A
standard PC-compatible using the AT- or ISA-bus with a normal BIOS
cannot access more than 16 megabytes of RAM. Generally used of a PC,
Unix workstation, etc. to mean fully populated with memory, disk-space
or some other desirable resource. See the World Wide Words article `“The
Full Monty” <http://www.worldwidewords.org/articles/monty.htm>`__ for
discussion of the rather complex etymology that may lie behind this
phrase. Compare American `moby <moby>`__.

 

+  ----+  + -----------+
| `Prev <monstrosity>`__    | `Up <../M>`__         |  `Next <Moof>`__   |
+  ----+  + -----------+
| monstrosity                    | `Home <../index>`__   |  Moof                   |
+  ----+  + -----------+

Moof
===============
 

**Moof**: /moof/

[Macintosh users]

1. n. The call of a semi-legendary creature, properly called the
`dogcow <./D.html#dogcow>`__. (Some previous versions of this entry
claimed, incorrectly, that Moof was the name of the *creature*.)

2. adj. Used to flag software that's a hack, something untested and on
the edge. On one Apple CD-ROM, certain folders such as “Tools & Apps
(Moof!)” and “Development Platforms (Moof!)”, are so marked to indicate
that they contain software not fully tested or sanctioned by the powers
that be. When you open these folders you cross the boundary into
hackerland.

3. v. On the Microsoft Network, the term ‘moof’ has gained popularity as
a verb meaning ‘to be suddenly disconnected by the system’. One might
say “I got moofed”.

 

+ ------------+  +  ---+
| `Prev <monty>`__    | `Up <../M>`__         |  `Next <Moores-Law>`__   |
+ ------------+  +  ---+
| monty                    | `Home <../index>`__   |  Moore's Law                  |
+ ------------+  +  ---+

Moore's Law
====================

 

**Moore's Law**: /morz law/, prov.

Any one of several similar folk theorems that fit computing capacity or
cost to a 2\ :sup:`t` exponential curve, with doubling time close to a
year. The most common fits component density to such a curve (previous
versions of this entry gave that form). Another variant asserts that the
dollar cost of constant computing power decreases on the same curve. The
original Moore's Law, first uttered in 1965 by semiconductor engineer
Gordon Moore (who co-founded Intel four years later), spoke of the
number of components on the lowest-cost silicon integrated circuits —
but Moore's own formulation varied somewhat over the years, and
reconstructing the meaning of the terminology he used in the original
turns out to be fraught with difficulties. Further variants were spawned
by Intel's PR department and various journalists.

It has been `shown <http://firstmonday.org/issues/issue7_11/tuomi/index.html>`__
that none of the variants of Moore's Law actually fit the data very well
(the price curves within DRAM generations perhaps come closest).
Nevertheless, Moore's Law is constantly invoked to set up expectations
about the next generation of computing technology. See also
`Parkinson's Law of Data <./P.html#Parkinsons-Law-of-Data>`__ and
`Gates's Law <./G.html#Gatess-Law>`__.

 

+ -----------+  + ------------+
| `Prev <Moof>`__    | `Up <../M>`__         |  `Next <moria>`__   |
+ -----------+  + ------------+
| Moof                    | `Home <../index>`__   |  moria                   |
+ -----------+  + ------------+

moria
===========

 

**moria**: /mor´ee·@/, n.

Like `nethack <./N.html#nethack>`__ and
`rogue <./R.html#rogue>`__, one of the large PD
Dungeons-and-Dragons-like simulation games, available for a wide range
of machines and operating systems. The name is from Tolkien's Mines of
Moria; compare `elder days <./E.html#elder-days>`__,
`elvish <./E.html#elvish>`__. The game is extremely addictive and a
major consumer of time better used for hacking. See also
`nethack <./N.html#nethack>`__, `rogue <./R.html#rogue>`__,
`Angband <./A.html#Angband>`__.

 

+  ---+  + ------------+
| `Prev <Moores-Law>`__    | `Up <../M>`__         |  `Next <MOTAS>`__   |
+  ---+  + ------------+
| Moore's Law                   | `Home <../index>`__   |  MOTAS                   |
+  ---+  + ------------+

MOTAS
===========

 

**MOTAS**: /moh·tahz/, n.

[Usenet: Member Of The Appropriate Sex, after `MOTOS <MOTOS>`__
and `MOTSS <MOTSS>`__] A potential or (less often) actual sex
partner. See also `SO <./S.html#SO>`__.

 

+ ------------+  + ------------+
| `Prev <moria>`__    | `Up <../M>`__         |  `Next <MOTOS>`__   |
+ ------------+  + ------------+
| moria                    | `Home <../index>`__   |  MOTOS                   |
+ ------------+  + ------------+

MOTOS
===========

 

**MOTOS**: /moh·tohs/, n.

[acronym from the 1970 U.S. census forms via Usenet: Member Of The
Opposite Sex] A potential or (less often) actual sex partner. See
`MOTAS <MOTAS>`__, `MOTSS <MOTSS>`__,
`SO <./S.html#SO>`__. Less common than MOTSS or
`MOTAS <MOTAS>`__, which has largely displaced it.

 

+ ------------+  + ------------+
| `Prev <MOTAS>`__    | `Up <../M>`__         |  `Next <MOTSS>`__   |
+ ------------+  + ------------+
| MOTAS                    | `Home <../index>`__   |  MOTSS                   |
+ ------------+  + ------------+

MOTSS
==============

 

**MOTSS**: /mots/, /M·O·T·S·S/, n.

[from the 1970 U.S. census forms via Usenet] Member Of The Same Sex,
esp. one considered as a possible sexual partner. The gay-issues
newsgroup on Usenet is called "soc.motss". See
`MOTOS <MOTOS>`__ and `MOTAS <MOTAS>`__, which derive from
it. See also `SO <./S.html#SO>`__.

 

+ ------------+  +  ----+
| `Prev <MOTOS>`__    | `Up <../M>`__         |  `Next <mouse-ahead>`__   |
+ ------------+  +  ----+
| MOTOS                    | `Home <../index>`__   |  mouse ahead                   |
+ ------------+  +  ----+

mouse ahead
================

 

**mouse ahead**: vi.

Point-and-click analog of type ahead. To manipulate a computer's
pointing device (almost always a mouse in this usage, but not
necessarily) and its selection or command buttons before a computer
program is ready to accept such input, in anticipation of the program
accepting the input. Handling this properly is rare, but it can help
make a `WIMP environment <./W.html#WIMP-environment>`__ much more
usable, assuming the users are familiar with the behavior of the user
interface.

 

+ ------------+  +  ---+
| `Prev <MOTSS>`__    | `Up <../M>`__         |  `Next <mouse-belt>`__   |
+ ------------+  +  ---+
| MOTSS                    | `Home <../index>`__   |  mouse belt                   |
+ ------------+  +  ---+

mouse belt
=============
 

**mouse belt**: n.

See `rat belt <./R.html#rat-belt>`__.

 

+  ----+  +  --------+
| `Prev <mouse-ahead>`__    | `Up <../M>`__         |  `Next <mouse-droppings>`__   |
+  ----+  +  --------+
| mouse ahead                    | `Home <../index>`__   |  mouse droppings                   |
+  ----+  +  --------+

mouse droppings
===================

 

**mouse droppings**: n.

[MS-DOS] Pixels (usually single) that are not properly restored when the
mouse pointer moves away from a particular location on the screen,
producing the appearance that the mouse pointer has left droppings
behind. The major causes for this problem are programs that write to the
screen memory corresponding to the mouse pointer's current location
without hiding the mouse pointer first, and mouse drivers that do not
quite support the graphics mode in use.

 

+  ---+  +  ----+
| `Prev <mouse-belt>`__    | `Up <../M>`__         |  `Next <mouse-elbow>`__   |
+  ---+  +  ----+
| mouse belt                    | `Home <../index>`__   |  mouse elbow                   |
+  ---+  +  ----+

mouse elbow
================

 

**mouse elbow**: n.

A tennis-elbow-like fatigue syndrome resulting from excessive use of a
`WIMP environment <./W.html#WIMP-environment>`__. Similarly, mouse
shoulder; GLS reports that he used to get this a lot before he taught
himself to be ambimoustrous.

 

+  --------+  +  -----+
| `Prev <mouse-droppings>`__    | `Up <../M>`__         |  `Next <mouse-pusher>`__   |
+  --------+  +  -----+
| mouse droppings                    | `Home <../index>`__   |  mouse pusher                   |
+  --------+  +  -----+

mouse pusher
=================

 

**mouse pusher**

[common] A person that prefers a mouse over a keyboard; originally used
for Macintosh fans. The derogatory implication is that the person has
nothing but the most superficial knowledge of the software he/she is
employing, and is incapable of using or appreciating the full glory of
the command line.

 

+  ----+  + ------------+
| `Prev <mouse-elbow>`__    | `Up <../M>`__         |  `Next <mouso>`__   |
+  ----+  + ------------+
| mouse elbow                    | `Home <../index>`__   |  mouso                   |
+  ----+  + ------------+

mouso
==============

 

**mouso**: /mow´soh/, n.

[by analogy with ‘typo’] An error in mouse usage resulting in an
inappropriate selection or graphic garbage on the screen. Compare
`thinko <./T.html#thinko>`__, `braino <./B.html#braino>`__.

 

+  -----+  + -------------+
| `Prev <mouse-pusher>`__    | `Up <../M>`__         |  `Next <MS-DOS>`__   |
+  -----+  + -------------+
| mouse pusher                    | `Home <../index>`__   |  MS-DOS                   |
+  -----+  + -------------+

MS-DOS
==============

 

**MS-DOS**: /M·S·dos/, n.

[MicroSoft Disk Operating System] A `clone <./C.html#clone>`__ of
`CP/M <./C.html#CP-M>`__ for the 8088 crufted together in 6 weeks by
hacker Tim Paterson at Seattle Computer Products, who called the
original QDOS (Quick and Dirty Operating System) and is said to have
regretted it ever since. Microsoft licensed QDOS in order to have
something to demo for IBM on time, and the rest is history. Numerous
features, including vaguely Unix-like but rather broken support for
subdirectories, I/O redirection, and pipelines, were hacked into
Microsoft's 2.0 and subsequent versions; as a result, there are two or
more incompatible versions of many system calls, and MS-DOS programmers
can never agree on basic things like what character to use as an option
switch or whether to be case-sensitive. The resulting appalling mess is
now the highest-unit-volume OS in history. Often known simply as DOS,
which annoys people familiar with other similarly abbreviated operating
systems (the name goes back to the mid-1960s, when it was attached to
IBM's first disk operating system for the 360). The name further annoys
those who know what the term `operating
system <./O.html#operating-system>`__ does (or ought to) connote; DOS
is more properly a set of relatively simple interrupt services. Some
people like to pronounce DOS like “dose”, as in “I don't work on dose,
man!”, or to compare it to a dose of brain-damaging drugs (a slogan
button in wide circulation among hackers exhorts: “MS-DOS: Just say
No!”). See `mess-dos <mess-dos>`__.

 

+ ------------+  + ---------+
| `Prev <mouso>`__    | `Up <../M>`__         |  `Next <mu>`__   |
+ ------------+  + ---------+
| mouso                    | `Home <../index>`__   |  mu                   |
+ ------------+  + ---------+

M$
======

 

**M$**

Common net abbreviation for Microsoft, everybody's least favorite
monopoly.

 

+ --------+  +  +
| `Prev <M>`__    | `Up <../M>`__         |  `Next <macdink>`__   |
+ --------+  +  +
| M                    | `Home <../index>`__   |  macdink                   |
+ --------+  +  +

muddie
=============

 

**muddie**: n.

Syn. `mudhead <mudhead>`__. More common in Great Britain,
possibly because system administrators there like to mutter “bloody
muddies” when annoyed at the species.

 

+ ----------+  +  +
| `Prev <MUD>`__    | `Up <../M>`__         |  `Next <mudhead>`__   |
+ ----------+  +  +
| MUD                    | `Home <../index>`__   |  mudhead                   |
+ ----------+  +  +

mudhead
============

 

**mudhead**: n.

Commonly used to refer to a `MUD <MUD>`__ player who eats,
sleeps, and breathes MUD. Mudheads have been known to fail their
degrees, drop out, etc., with the consolation, however, that they made
wizard level. When encountered in person, on a MUD, or in a chat system,
all a mudhead will talk about is three topics: the tactic, character, or
wizard that is supposedly always unfairly stopping him/her from becoming
a wizard or beating a favorite MUD; why the specific game he/she has
experience with is so much better than any other; and the MUD he or she
is writing or going to write because his/her design ideas are so much
better than in any existing MUD. See also
`wannabee <./W.html#wannabee>`__.

To the anthropologically literate, this term may recall the Zuni/Hopi
legend of the mudheads or *koyemshi*, mythical half-formed children of
an unnatural union. Figures representing them act as clowns in Zuni
sacred ceremonies. Others may recall the ‘High School Madness’ sequence
from the Firesign Theatre album *Don't Crush That Dwarf, Hand Me the
Pliers*, in which there is a character named “Mudhead”.

 

+ -------------+  + -------------+
| `Prev <muddie>`__    | `Up <../M>`__         |  `Next <muggle>`__   |
+ -------------+  + -------------+
| muddie                    | `Home <../index>`__   |  muggle                   |
+ -------------+  + -------------+

MUD
=========
 

**MUD**: /muhd/, n.

[acronym, Multi-User Dungeon; alt.: Multi-User Dimension]

1. A class of `virtual reality <./V.html#virtual-reality>`__
experiments accessible via the Internet. These are real-time chat forums
with structure; they have multiple ‘locations’ like an adventure game,
and may include combat, traps, puzzles, magic, a simple economic system,
and the capability for characters to build more structure onto the
database that represents the existing world.

2. vi. To play a MUD. The acronym MUD is often lowercased and/or verbed;
thus, one may speak of going mudding, etc.

Historically, MUDs (and their more recent progeny with names of MU-
form) derive from a hack by Richard Bartle and Roy Trubshaw on the
University of Essex's DEC-10 in the early 1980s; descendants of that
game still exist today and are sometimes generically called
*BartleMUD*\ s. There is a widespread myth (repeated, unfortunately, by
earlier versions of this lexicon) that the name MUD was trademarked to
the commercial MUD run by Bartle on British Telecom (the motto: “You
haven't *lived* 'til you've *died* on MUD!”); however, this is false —
Richard Bartle explicitly placed ‘MUD’ in the public domain in 1985. BT
was upset at this, as they had already printed trademark claims on some
maps and posters, which were released and created the myth.

Students on the European academic networks quickly improved on the MUD
concept, spawning several new MUDs (VAXMUD, AberMUD, LPMUD). Many of
these had associated bulletin-board systems for social interaction.
Because these had an image as ‘research’ they often survived
administrative hostility to BBSs in general. This, together with the
fact that Usenet feeds were often spotty and difficult to get in the
U.K., made the MUDs major foci of hackish social interaction there.

AberMUD and other variants crossed the Atlantic around 1988 and quickly
gained popularity in the U.S.; they became nuclei for large hacker
communities with only loose ties to traditional hackerdom (some
observers see parallels with the growth of Usenet in the early 1980s).
The second wave of MUDs (TinyMUD and variants) tended to emphasize
social interaction, puzzles, and cooperative world-building as opposed
to combat and competition (in writing, these social MUDs are sometimes
referred to as ‘MU\*’, with ‘MUD’ implicitly reserved for the more
game-oriented ones). By 1991, over 50% of MUD sites were of a third
major variety, LPMUD, which synthesizes the combat/puzzle aspects of
AberMUD and older systems with the extensibility of TinyMud. In 1996 the
cutting edge of the technology is Pavel Curtis's MOO, even more
extensible using a built-in object-oriented language. The trend toward
greater programmability and flexibility will doubtless continue.

The state of the art in MUD design is still moving very rapidly, with
new simulation designs appearing (seemingly) every month. Around 1991
there was an unsuccessful movement to deprecate the term
`MUD <MUD>`__ itself, as newer designs exhibit an exploding
variety of names corresponding to the different simulation styles being
explored. It survived. See also `bonk/oif <./B.html#bonk-oif>`__,
`FOD <./F.html#FOD>`__, `link-dead <./L.html#link-dead>`__,
`mudhead <mudhead>`__, `talk mode <./T.html#talk-mode>`__.

 

+ ---------+  + -------------+
| `Prev <mu>`__    | `Up <../M>`__         |  `Next <muddie>`__   |
+ ---------+  + -------------+
| mu                    | `Home <../index>`__   |  muddie                   |
+ ---------+  + -------------+

muggle
============

 

**muggle**

[from J.K. Rowling's *Harry Potter* books, 1998] A
non-`wizard <./W.html#wizard>`__. Not as disparaging as
`luser <./L.html#luser>`__; implies vague pity rather than contempt.
In the universe of Rowling's enormously (and deservedly) popular
children's series, muggles and wizards inhabit the same modern world,
but each group is ignorant of the commonplaces of the others' existence
— most muggles are unaware that wizards exist, and wizards (used to
magical ways of doing everything) are perplexed and fascinated by muggle
artifacts.

In retrospect it seems completely inevitable that hackers would adopt
this metaphor, and in hacker usage it readily forms compounds such as
muggle-friendly. Compare `luser <./L.html#luser>`__,
`mundane <mundane>`__, `chainik <./C.html#chainik>`__,
`newbie <./N.html#newbie>`__.

 

+  +  +  +
| `Prev <mudhead>`__    | `Up <../M>`__         |  `Next <Multics>`__   |
+  +  +  +
| mudhead                    | `Home <../index>`__   |  Multics                   |
+  +  +  +

mu
================
 

**mu**: /moo/

The correct answer to the classic trick question “Have you stopped
beating your wife yet?”. Assuming that you have no wife or you have
never beaten your wife, the answer “yes” is wrong because it implies
that you used to beat your wife and then stopped, but “no” is worse
because it suggests that you have one and are still beating her.
According to various Discordians and Douglas Hofstadter the correct
answer is usually “mu”, a Japanese word alleged to mean “Your question
cannot be answered because it depends on incorrect assumptions”. Hackers
tend to be sensitive to logical inadequacies in language, and many have
adopted this suggestion with enthusiasm. The word ‘mu’ is actually from
Chinese, meaning ‘nothing’; it is used in mainstream Japanese in that
sense. In Chinese it can also mean “have not” (as in “I have not done
it”), or “lack of”, which may or may not be a definite, complete
'nothing'). Native speakers of Japanese do not recognize the Discordian
question-denying use, which almost certainly derives from
overgeneralization of the answer in the following well-known Rinzai Zen
`koan <./K.html#koan>`__:

    A monk asked Joshu, “Does a dog have the Buddha nature?” Joshu
    retorted, “Mu!”

See also `has the X nature <./H.html#has-the-X-nature>`__, `Some AI
Koans <../koans>`__, and Douglas Hofstadter's *Gödel, Escher, Bach:
An Eternal Golden Braid* (pointer in the
`Bibliography <../pt03.html#bibliography>`__ in Appendix C.

 

+ -------------+  + ----------+
| `Prev <MS-DOS>`__    | `Up <../M>`__         |  `Next <MUD>`__   |
+ -------------+  + ----------+
| MS-DOS                    | `Home <../index>`__   |  MUD                   |
+ -------------+  + ----------+

Multics
=============
 

**Multics**: /muhl´tiks/, n.

[from “MULTiplexed Information and Computing Service”] An early
timesharing `operating system <./O.html#operating-system>`__
co-designed by a consortium including MIT, GE, and Bell Laboratories as
a successor to `CTSS <./C.html#CTSS>`__. The design was first
presented in 1965, planned for operation in 1967, first operational in
1969, and took several more years to achieve respectable performance and
stability.

Multics was very innovative for its time — among other things, it
provided a hierarchical file system with access control on individual
files and introduced the idea of treating all devices uniformly as
special files. It was also the first OS to run on a symmetric
multiprocessor, and the only general-purpose system to be awarded a B2
security rating by the NSA (see `Orange
Book <./O.html#Orange-Book>`__).

Bell Labs left the development effort in 1969 after judging that
`second-system effect <./S.html#second-system-effect>`__ had bloated
Multics to the point of practical unusability. Honeywell commercialized
Multics in 1972 after buying out GE's computer group, but it was never
very successful: at its peak in the 1980s, there were between 75 and 100
Multics sites, each a multi-million dollar mainframe.

One of the former Multics developers from Bell Labs was Ken Thompson,
and `Unix <./U.html#Unix>`__ deliberately carried through and
extended many of Multics' design ideas; indeed, Thompson described the
very name ‘Unix’ as “a weak pun on Multics”. For this and other reasons,
aspects of the Multics design remain a topic of occasional debate among
hackers. See also `brain-damaged <./B.html#brain-damaged>`__ and
`GCOS <./G.html#GCOS>`__.

MIT ended its development association with Multics in 1977. Honeywell
sold its computer business to Bull in the mid 80s, and development on
Multics was stopped in 1988. Four Multics sites were known to be still
in use as late as 1998, but the last one (a Canadian military site) was
decommissioned in November 2000. There is a Multics page at
`http://www.stratus.com/pub/vos/multics/tvv/multics.html <http://www.stratus.com/pub/vos/multics/tvv/multics>`__.

 

+ -------------+  +  --+
| `Prev <muggle>`__    | `Up <../M>`__         |  `Next <multitask>`__   |
+ -------------+  +  --+
| muggle                    | `Home <../index>`__   |  multitask                   |
+ -------------+  +  --+

multitask
===============
 

**multitask**: n.

Often used of humans in the same meaning it has for computers, to
describe a person doing several things at once (but see
`thrash <./T.html#thrash>`__). The term multiplex, from
communications technology (meaning to handle more than one channel at
the same time), is used similarly.

 

+  +  +  -+
| `Prev <Multics>`__    | `Up <../M>`__         |  `Next <mumblage>`__   |
+  +  +  -+
| Multics                    | `Home <../index>`__   |  mumblage                   |
+  +  +  -+

mumblage
===========
 

**mumblage**: /muhm´bl@j/, n.

The topic of one's mumbling (see `mumble <mumble>`__). “All that
mumblage” is used like “all that stuff” when it is not quite clear how
the subject of discussion works, or like “all that crap” when ‘mumble’
is being used as an implicit replacement for pejoratives.

 

+  --+  + -------------+
| `Prev <multitask>`__    | `Up <../M>`__         |  `Next <mumble>`__   |
+  --+  + -------------+
| multitask                    | `Home <../index>`__   |  mumble                   |
+  --+  + -------------+

mumble
===========

 

**mumble**: interj.

1. Said when the correct response is too complicated to enunciate, or
the speaker has not thought it out. Often prefaces a longer answer, or
indicates a general reluctance to get into a long discussion. “Don't you
think that we could improve LISP performance by using a hybrid
reference-count transaction garbage collector, if the cache is big
enough and there are some extra cache bits for the microcode to use?”
“Well, mumble ... I'll have to think about it.”

2. [MIT] Expression of not-quite-articulated agreement, often used as an
informal vote of consensus in a meeting: “So, shall we dike out the
COBOL emulation?” “Mumble!”

3. Sometimes used as an expression of disagreement (distinguished from
sense 2 by tone of voice and other cues). “I think we should buy a
"VAX <./V.html#VAX>`__ <./V.html#VAX>`__.” “Mumble!” Common
variant: mumble frotz (see `frotz <./F.html#frotz>`__; interestingly,
one does not say ‘mumble frobnitz’ even though ‘frotz’ is short for
‘frobnitz’).

4. Yet another `metasyntactic
variable <metasyntactic-variable>`__, like
`foo <./F.html#foo>`__.

5. When used as a question (“Mumble?”) means “I didn't understand you”.

6. Sometimes used in ‘public’ contexts on-line as a placefiller for
things one is barred from giving details about. For example, a poster
with pre-released hardware in his machine might say “Yup, my machine now
has an extra 16M of memory, thanks to the card I'm testing for
Mumbleco.”

7. A conversational wild card used to designate something one doesn't
want to bother spelling out, but which can be
`glark <./G.html#glark>`__\ ed from context. Compare
`blurgle <./B.html#blurgle>`__.

8. [XEROX PARC] A colloquialism used to suggest that further discussion
would be fruitless.

 

+  -+  + ------------+
| `Prev <mumblage>`__    | `Up <../M>`__         |  `Next <munch>`__   |
+  -+  + ------------+
| mumblage                    | `Home <../index>`__   |  munch                   |
+  -+  + ------------+

munch
============

 

**munch**: vt.

[often confused with `mung <mung>`__, q.v.] To transform
information in a serial fashion, often requiring large amounts of
computation. To trace down a data structure. Related to
`crunch <./C.html#crunch>`__ and nearly synonymous with
`grovel <./G.html#grovel>`__, but connotes less pain.

 

+ -------------+  +  -+
| `Prev <mumble>`__    | `Up <../M>`__         |  `Next <munching>`__   |
+ -------------+  +  -+
| mumble                    | `Home <../index>`__   |  munching                   |
+ -------------+  +  -+

munching
============

 

**munching**: n.

Exploration of security holes of someone else's computer for thrills,
notoriety, or to annoy the system manager. Compare
`cracker <./C.html#cracker>`__. See also `hacked
off <./H.html#hacked-off>`__.

 

+ ------------+  +  ---------+
| `Prev <munch>`__    | `Up <../M>`__         |  `Next <munching-squares>`__   |
+ ------------+  +  ---------+
| munch                    | `Home <../index>`__   |  munching squares                   |
+ ------------+  +  ---------+

munching squares
=================

 

**munching squares**: n.

A `display hack <./D.html#display-hack>`__ dating back to the PDP-1
(ca. 1962, reportedly discovered by Jackson Wright), which employs a
trivial computation (repeatedly plotting the graph Y = X XOR T for
successive values of T — see `HAKMEM <./H.html#HAKMEM>`__ items
146--148) to produce an impressive display of moving and growing squares
that devour the screen. The initial value of T is treated as a
parameter, which, when well-chosen, can produce amazing effects. Some of
these, later (re)discovered on the LISP machine, have been christened
munching triangles (try AND for XOR and toggling points instead of
plotting them), munching w's, and munching mazes. More generally,
suppose a graphics program produces an impressive and ever-changing
display of some basic form, foo, on a display terminal, and does it
using a relatively simple program; then the program (or the resulting
display) is likely to be referred to as munching foos. [This is a good
example of the use of the word `foo <./F.html#foo>`__ as a
`metasyntactic variable <metasyntactic-variable>`__.]

 

+  -+  +  -+
| `Prev <munching>`__    | `Up <../M>`__         |  `Next <munchkin>`__   |
+  -+  +  -+
| munching                    | `Home <../index>`__   |  munchkin                   |
+  -+  +  -+

munchkin
===========

 

**munchkin**: /muhnch´kin/, n.

[from the squeaky-voiced little people in L. Frank Baum's *The Wizard of
Oz*] A teenage-or-younger micro enthusiast hacking BASIC or something
else equally constricted. A term of mild derision — munchkins are
annoying but some grow up to be hackers after passing through a `larval
stage <./L.html#larval-stage>`__. The term
`urchin <./U.html#urchin>`__ is also used. See also
`wannabee <./W.html#wannabee>`__, `bitty
box <./B.html#bitty-box>`__.

 

+  ---------+  +  +
| `Prev <munching-squares>`__    | `Up <../M>`__         |  `Next <mundane>`__   |
+  ---------+  +  +
| munching squares                    | `Home <../index>`__   |  mundane                   |
+  ---------+  +  +

mundane
===========

 

**mundane**: n.

[from SF fandom]

1. A person who is not in science fiction fandom.

2. A person who is not in the computer industry. In this sense, most
often an adjectival modifier as in “in my mundane life....” See also
`Real World <./R.html#Real-World>`__, `muggle <muggle>`__.

 

+  -+  + -----------+
| `Prev <munchkin>`__    | `Up <../M>`__         |  `Next <mung>`__   |
+  -+  + -----------+
| munchkin                    | `Home <../index>`__   |  mung                   |
+  -+  + -----------+

munge
=========
 

**munge**: /muhnj/, vt.

1. [derogatory] To imperfectly transform information.

2. A comprehensive rewrite of a routine, data structure or the whole
program.

3. To modify data in some way the speaker doesn't need to go into right
now or cannot describe succinctly (compare `mumble <mumble>`__).

4. To add `spamblock <./S.html#spamblock>`__ to an email address.

This term is often confused with `mung <mung>`__, which probably
was derived from it. However, it also appears the word munge was in
common use in Scotland in the 1940s, and in Yorkshire in the 1950s, as a
verb, meaning to munch up into a masticated mess, and as a noun, meaning
the result of munging something up (the parallel with the
`kluge <./K.html#kluge>`__/`kludge <./K.html#kludge>`__ pair is
amusing). The OED reports “munge” as an archaic verb meaning “to wipe (a
person's nose)”.

 

+ -----------+  +  ----+
| `Prev <mung>`__    | `Up <../M>`__         |  `Next <Murphys-Law>`__   |
+ -----------+  +  ----+
| mung                    | `Home <../index>`__   |  Murphy's Law                  |
+ -----------+  +  ----+

mung
============
 

**mung**: /muhng/, vt.

[in 1960 at MIT, “Mash Until No Good”; sometime after that the
derivation from the `recursive
acronym <./R.html#recursive-acronym>`__ “Mung Until No Good” became
standard; but see `munge <munge>`__]

1. To make changes to a file, esp. large-scale and irrevocable changes.
See `BLT <./B.html#BLT>`__.

2. To destroy, usually accidentally, occasionally maliciously. The
system only mungs things maliciously; this is a consequence of
`Finagle's Law <./F.html#Finagles-Law>`__. See
`scribble <./S.html#scribble>`__, `mangle <mangle>`__,
`trash <./T.html#trash>`__, `nuke <./N.html#nuke>`__. Reports from
`Usenet <./U.html#Usenet>`__ suggest that the pronunciation /muhnj/
is now usual in speech, but the spelling ‘mung’ is still common in
program comments (compare the widespread confusion over the proper
spelling of `kluge <./K.html#kluge>`__).

3. In the wake of the `spam <./S.html#spam>`__ epidemics of the
1990s, mung is now commonly used to describe the act of modifying an
email address in a sig block in a way that human beings can readily
reverse but that will fool an `address
harvester <./A.html#address-harvester>`__. Example:
johnNOSPAMsmith@isp.net.

4. The kind of beans the sprouts of which are used in Chinese food.
(That's their real name! Mung beans! Really!)

Like many early hacker terms, this one seems to have originated at
`TMRC <./T.html#TMRC>`__; it was already in use there in 1958. Peter
Samson (compiler of the original TMRC lexicon) thinks it may originally
have been onomatopoeic for the sound of a relay spring (contact) being
twanged. However, it is known that during the World Wars, ‘mung’ was
U.S.: army slang for the ersatz creamed chipped beef better known as
‘SOS’, and it seems quite likely that the word in fact goes back to
Scots-dialect `munge <munge>`__.

Charles Mackay's 1874 book *Lost Beauties of the English Language*
defined “mung” as follows: “Preterite of ming, to ming or mingle; when
the substantive meaning of mingled food of bread, potatoes, etc. thrown
to poultry. In America, ‘mung news’ is a common expression applied to
false news, but probably having its derivation from mingled (or mung)
news, in which the true and the false are so mixed up together that it
is impossible to distinguish one from another.”

 

+  +  + ------------+
| `Prev <mundane>`__    | `Up <../M>`__         |  `Next <munge>`__   |
+  +  + ------------+
| mundane                    | `Home <../index>`__   |  munge                   |
+  +  + ------------+

Murphy's Law
=================

 

**Murphy's Law**: prov.

The correct, *original* Murphy's Law reads: “If there are two or more
ways to do something, and one of those ways can result in a catastrophe,
then someone will do it.” This is a principle of defensive design, cited
here because it is usually given in mutant forms less descriptive of the
challenges of design for `luser <./L.html#luser>`__\ s. For example,
you don't make a two-pin plug symmetrical and then label it “THIS WAY
UP”; if it matters which way it is plugged in, then you make the design
asymmetrical (see also the anecdote under `magic
smoke <magic-smoke>`__).

Edward A. Murphy, Jr. was one of McDonnell-Douglas's test engineers on
the rocket-sled experiments that were done by the U.S. Air Force in 1949
to test human acceleration tolerances (USAF project MX981). One
experiment involved a set of 16 accelerometers mounted to different
parts of the subject's body. There were two ways each sensor could be
glued to its mount, and somebody methodically installed all 16 in a
replacement set the wrong way around. Murphy then made the original form
of his pronouncement, which the test subject (Major John Paul Stapp)
mis-quoted (apparently in the more general form “Whatever can go wrong,
*will* go wrong)” at a news conference a few days later.

Within months ‘Murphy's Law’ had spread to various technical cultures
connected to aerospace engineering. Before too many years had gone by
variants had passed into the popular imagination, changing as they went.
Most of these are variants on “Anything that can go wrong, will”; this
is more correctly referred to as `Finagle's
Law <./F.html#Finagles-Law>`__. The memetic drift apparent in these
mutants clearly demonstrates Murphy's Law acting on itself!

 

+ ------------+  + ------------+
| `Prev <munge>`__    | `Up <../M>`__         |  `Next <music>`__   |
+ ------------+  + ------------+
| munge                    | `Home <../index>`__   |  music                   |
+ ------------+  + ------------+

music
=================

 

**music**: n.

A common extracurricular interest of hackers (compare `science-fiction
fandom <./S.html#science-fiction-fandom>`__, `oriental
food <./O.html#oriental-food>`__; see also
`filk <./F.html#filk>`__). Hackish folklore has long claimed that
musical and programming abilities are closely related, and there has
been at least one large-scale statistical study that supports this.
Hackers, as a rule, like music and often develop musical appreciation in
unusual and interesting directions. Folk music is very big in hacker
circles; so is electronic music, and the sort of elaborate instrumental
jazz/rock that used to be called ‘progressive’ and isn't recorded much
any more. The hacker's musical range tends to be wide; many can listen
with equal appreciation to (say) Talking Heads, Yes, Gentle Giant, Pat
Metheny, Scott Joplin, Tangerine Dream, Dream Theater, King Sunny Ade,
The Pretenders, Screaming Trees, or the Brandenburg Concerti. It is also
apparently true that hackerdom includes a much higher concentration of
talented amateur musicians than one would expect from a similar-sized
control group of `mundane <mundane>`__ types.

 

+  ----+  + -------------+
| `Prev <Murphys-Law>`__    | `Up <../M>`__         |  `Next <mutter>`__   |
+  ----+  + -------------+
| Murphy's Law                   | `Home <../index>`__   |  mutter                   |
+  ----+  + -------------+

mutter
========
 

**mutter**: vt.

To quietly enter a command not meant for the ears, eyes, or fingers of
ordinary mortals. Often used in “mutter an
`incantation <./I.html#incantation>`__\ ”. See also
`wizard <./W.html#wizard>`__.

 

+ ------------+  + -----------+
| `Prev <music>`__    | `Up <../M>`__         |  `Next <../N>`__   |
+ ------------+  + -----------+
| music                    | `Home <../index>`__   |  N                      |
+ ------------+  + -----------+

