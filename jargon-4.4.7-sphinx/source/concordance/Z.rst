=====
Z
=====

zap
===


**zap**

1. n. Spiciness.

2. vt. To make food spicy.

3. vt. To make someone ‘suffer’ by making his food spicy. (Most hackers
love spicy food. Hot-and-sour soup is considered wimpy unless it makes
you wipe your nose for the rest of the meal.) See
`zapped <Z.html#zapped>`__.

4. vt. To modify, usually to correct; esp. used when the action is
performed with a debugger or binary patching tool. Also implies surgical precision. “Zap the debug level to 6 and run it again.” In the IBM mainframe world, binary patches are applied to programs or to the OS with a program called ‘superzap’, whose file name is ‘IMASPZAP’ (possibly contrived from I M A SuPerZAP).

5. vt. To erase or reset.

6. To `fry <F.html#fry>`__ a chip with static electricity. “Uh oh —
I think that lightning strike may have zapped the disk controller.”



zapped
======



**zapped**: adj.

Spicy. This term is used to distinguish between food that is hot (in
temperature) and food that is *spicy*-hot. For example, the Chinese
appetizer Bon Bon Chicken is a kind of chicken salad that is cold but
zapped; by contrast, `vanilla <V.thml#vanilla>`__ wonton soup is
hot but not zapped. See also `oriental
food <O.html#oriental-food>`__, `laser
chicken <L.html#laser-chicken>`__. See `zap <#zap>`__, senses
1 and 2.


Zawinski's Law
================



**Zawinski's Law**

“Every program attempts to expand until it can read mail. Those programs
which cannot so expand are replaced by ones which can.” Coined by Jamie
Zawinski (who called it the “Law of Software Envelopment”) to express
his belief that all truly useful programs experience pressure to evolve
into toolkits and application platforms (the mailer thing, he says, is
just a side effect of that). It is commonly cited, though with widely
varying degrees of accuracy.


zbeba
======



**zbeba**: n.

[USENET] The word ‘moron’ in `rot13 <R.html#rot13>`__. Used to
describe newbies who are behaving with especial cluelessness.





zen
========


**zen**: vt.

To figure out something by meditation or by a sudden flash of
enlightenment. Originally applied to bugs, but occasionally applied to
problems of life in general. “How'd you figure out the buffer allocation
problem?” “Oh, I zenned it.” Contrast `grok <G.html#grok>`__, which
connotes a time-extended version of zenning a system. Compare `hack
mode <H.html#hack-mode>`__. See also `guru <G.html#guru>`__.

zero-content
===================


**zero-content**: adj.

Syn. `content-free <C.html#content-free>`__.



zero
======


**zero**: vt.

1. To set to 0. Usually said of small pieces of data, such as bits or
words (esp. in the construction zero out).

2. To erase; to discard all data from. Said of disks and directories,
where ‘zeroing’ need not involve actually writing zeroes throughout the
area being zeroed. One may speak of something being logically zeroed
rather than being physically zeroed. See
`scribble <S.html#scribble>`__.




Zero-One-Infinity Rule
==========================



**Zero-One-Infinity Rule**: prov.

“Allow none of `foo <F.html#foo>`__, one of
`foo <F.html#foo>`__, or any number of `foo <F.html#foo>`__.”
A rule of thumb for software design, which instructs one to not place
`random <./R.html#random>`__ limits on the number of instances of a
given entity (such as: windows in a window system, letters in an OS's
filenames, etc.). Specifically, one should either disallow the entity
entirely, allow exactly one instance (an “exception”), or allow as many
as the user wants — address space and memory permitting.

The logic behind this rule is that there are often situations where it
makes clear sense to allow one of something instead of none. However, if
one decides to go further and allow N (for N > 1), then why not N+1? And
if N+1, then why not N+2, and so on? Once above 1, there's no excuse not
to allow any N; hence, `infinity <I.html/infinity>`__.

Many hackers recall in this connection Isaac Asimov's SF novel *The Gods
Themselves* in which a character announces that the number 2 is
impossible — if you're going to believe in more than one universe, you
might as well believe in an infinite number of them.


zeroth
==========

**zeroth**: /zee´rohth/, adj.

First. Among software designers, comes from C's and LISP's 0-based
indexing of arrays. Hardware people also tend to start counting at 0
instead of 1; this is natural since, e.g., the 256 states of 8 bits
correspond to the binary numbers 0, 1, ..., 255 and the digital devices
known as counters count in this way.

Hackers and computer scientists often like to call the first chapter of
a publication ‘Chapter 0’, especially if it is of an introductory nature
(one of the classic instances was in the First Edition of
`K&R<K.html#K-ampersand-R>`__). In recent years this trait has
also been observed among many pure mathematicians (who have an
independent tradition of numbering from 0). Zero-based numbering tends
to reduce `fencepost errors <F.html#fencepost-error>`__, though
it cannot eliminate them entirely.


zigamorph
===============


**zigamorph**: /zig'@·morf/, n.

1. Hex FF (11111111) when used as a delimiter or
`fence <F.html#fence>`__ character. Usage: primarily at IBM shops.

2. [proposed] n. The Unicode non-character U+FFFF (1111111111111111), a
character code which is not assigned to any character, and so is usable
as end-of-string. (Unicode is a 16-bit character code intended to cover
all of the world's writing systems, including Latin, Greek, Cyrillic,
Chinese, hiragana, katakana, Devanagari, Thai, Laotian and many other
scripts — support for `elvish <E.html#elvish>`__ is planned for a
future release).


zip
=====



**zip**: vt.

[primarily MS-DOS/Windows] To create a compressed archive from a group
of files using PKWare's PKZIP or a compatible archiver. Its use is
spreading now that portable implementations of the algorithm have been
written. Commonly used as follows: “I'll zip it up and send it to you.”
See `tar and feather <T.html#tar-and-feather>`__.




zipperhead
===========



**zipperhead**: n.

[IBM] A person with a closed mind.


zombie
==========


**zombie**: n.

1. [Unix] A process that has died but has not yet relinquished its
process table slot (because the parent process hasn't executed a wait(2)
for it yet). These can be seen in ps(1) listings occasionally. Compare
`orphan <./O.html#orphan>`__.

2. A machine, especially someone's `home box <./H.html#home-box>`__,
that has been cracked and is being used as part of a second-stage attack
by miscreants trying to mask their home IP address. Especially used of
machines being exploited in large gangs for a mechanized
denial-of-service attack like Tribe Flood Network; the image that goes
with this is of a veritable army of zombies mindlessly doing the bidding
of a necromancer.


zorch
========



**zorch**: /zorch/

1. [TMRC] v. To attack with an inverse heat sink.

2. [TMRC] v. To travel, with "v" approaching "c" [that is, with
velocity approaching lightspeed —ESR].

3. [MIT] v. To propel something very quickly. “The new comm software is
very fast; it really zorches files through the network.”

4. [MIT] n. Influence. Brownie points. Good karma. The intangible and
fuzzy currency in which favors are measured. “I'd rather not ask him for
that just yet; I think I've used up my quota of zorch with him for the
week.”

5. [MIT] n. Energy, drive, or ability. “I think I'll
`punt <./P.html#punt>`__ that change for now; I've been up for 30
hours and I've run out of zorch.”

6. [MIT] v. To flunk an exam or course.

A track called *Zorch* was the B-side of a single called *Captain
Hideous*, released by novelty artist Nervous Norvous in 1955. Norvous
was heavily influemced by a radio comedian named Red Blanchard; the word
“zorch” appears to have been coined on Blanchard's show in the early
1950s. The word itself had no meaning, but there where compounds using
it that did — “zorch cow”, for example, was a variant of the
Chicago-area slang “black cow” for a root beer float.


Zork
======


**Zork**: /zork/, n.

The second of the great early experiments in computer fantasy gaming;
see `ADVENT <./A.html#ADVENT>`__. Originally written on MIT-DM during
1977-1979, later distributed with BSD Unix (as a patched, sourceless
RT-11 FORTRAN binary; see
`retrocomputing <./R.html#retrocomputing>`__) and commercialized as
‘The Zork Trilogy’ by `Infocom <./I.html#Infocom>`__. The FORTRAN
source was later rewritten for portability and released to Usenet under
the name “Dungeon”. Both FORTRAN “Dungeon” and translated C versions are
available at many FTP sites; the commercial Zork trilogy is available at
`http://www.ifarchive.org/ <http://www.ifarchive.org/>`__. See also
`grue <./G.html#grue>`__. You can play Zork via a `Java
Applet <http://www.forkexec.com/html/play-zork1>`__.


zorkmid
===============


**zorkmid**: /zork´mid/, n.

The canonical unit of currency in hacker-written games. This originated
in `Zork <Zork>`__ but has spread to
`nethack <./N.html#nethack>`__ and is referred to in several other
games.
