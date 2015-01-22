




======================
Hacker Writing Style
======================

We've already seen that hackers often coin jargon by overgeneralizing
grammatical rules. This is one aspect of a more general fondness for
form-versus-content language jokes that shows up particularly in hackish
writing. One correspondent reports that he consistently misspells
‘wrong’ as ‘worng’. Others have been known to criticize glitches in
Jargon File drafts by observing (in the mode of Douglas Hofstadter)
“This sentence no verb”, or “Too repetetetive”, or “Bad speling”, or
“Incorrectspa cing.” Similarly, intentional spoonerisms are often made
of phrases relating to confusion or things that are confusing; ‘dain
bramage’ for ‘brain damage’ is perhaps the most common (similarly, a
hacker would be likely to write “Excuse me, I'm cixelsyd today”, rather
than “I'm dyslexic today”). This sort of thing is quite common and is
enjoyed by all concerned.

Hackers tend to use quotes as balanced delimiters like parentheses, much
to the dismay of American editors. Thus, if “Jim is going” is a phrase,
and so are “Bill runs” and “Spock groks”, then hackers generally prefer
to write: “Jim is going”, “Bill runs”, and “Spock groks”. This is
incorrect according to standard American usage (which would put the
continuation commas and the final period inside the string quotes);
however, it is counter-intuitive to hackers to mutilate literal strings
with characters that don't belong in them. Given the sorts of examples
that can come up in discussions of programming, American-style quoting
can even be grossly misleading. When communicating command lines or
small pieces of code, extra characters can be a real pain in the neck.

Consider, for example, a sentence in a `vi <V/vi.html>`__ tutorial
that looks like this::

    Then delete a line from the file by typing “dd”.

Standard usage would make this::

    Then delete a line from the file by typing “dd.”

but that would be very bad — because the reader would be prone to type
the string d-d-dot, and it happens that in vi(1), dot repeats the last
command accepted. The net result would be to delete *two* lines!

The Jargon File follows hackish usage throughout.

Interestingly, a similar style is now preferred practice in Great
Britain, though the older style (which became established for
typographical reasons having to do with the aesthetics of comma and
quotes in typeset text) is still accepted there. *Hart's Rules* and the
*Oxford Dictionary for Writers and Editors* call the hacker-like style
‘new’ or ‘logical’ quoting. This returns British English to the style
many other languages (including Spanish, French, Italian, Catalan, and
German) have been using all along.

Another hacker habit is a tendency to distinguish between ‘scare’ quotes
and ‘speech’ quotes; that is, to use British-style single quotes for
marking and reserve American-style double quotes for actual reports of
speech or text included from elsewhere. Interestingly, some authorities
describe this as correct general usage, but mainstream American English
has gone to using double-quotes indiscriminately enough that hacker
usage appears marked [and, in fact, I thought this was a personal quirk
of mine until I checked with Usenet —ESR] One further permutation that
is definitely *not* standard is a hackish tendency to do marking quotes
by using apostrophes (single quotes) in pairs; that is, ’like this’.
This is modelled on string and character literal syntax in some
programming languages (reinforced by the fact that many character-only
terminals display the apostrophe in typewriter style, as a vertical
single quote).

One quirk that shows up frequently in the `email <E/email.html>`__
style of Unix hackers in particular is a tendency for some things that
are normally all-lowercase (including usernames and the names of
commands and C routines) to remain uncapitalized even when they occur at
the beginning of sentences. It is clear that, for many hackers, the case
of such identifiers becomes a part of their internal representation (the
‘spelling’) and cannot be overridden without mental effort (an
appropriate reflex because Unix and C both distinguish cases and
confusing them can lead to `lossage <L/lossage.html>`__). A way of
escaping this dilemma is simply to avoid using these constructions at
the beginning of sentences.

There seems to be a meta-rule behind these nonstandard hackerisms to the
effect that precision of expression is more important than conformance
to traditional rules; where the latter create ambiguity or lose
information they can be discarded without a second thought. It is
notable in this respect that other hackish inventions (for example, in
vocabulary) also tend to carry very precise shades of meaning even when
constructed to appear slangy and loose. In fact, to a hacker, the
contrast between ‘loose’ form and ‘tight’ content in jargon is a
substantial part of its humor!

Hackers have also developed a number of punctuation and emphasis
conventions adapted to single-font all-ASCII communications links, and
these are occasionally carried over into written documents even when
normal means of font changes, underlining, and the like are available.

One of these is that TEXT IN ALL CAPS IS INTERPRETED AS ‘LOUD’, and this
becomes such an ingrained synesthetic reflex that a person who goes to
caps-lock while in `talk mode <T/talk-mode.html>`__ may be asked to
“stop shouting, please, you're hurting my ears!”.

Also, it is common to use bracketing with unusual characters to signify
emphasis. The asterisk is most common, as in “What the \*hell\*?” even
though this interferes with the common use of the asterisk suffix as a
footnote mark. The underscore is also common, suggesting underlining
(this is particularly common with book titles; for example, “It is often
alleged that Joe Haldeman wrote \_The\_Forever\_War\_ as a rebuttal to
Robert Heinlein's earlier novel of the future military,
\_Starship\_Troopers\_.”). Other forms exemplified by “=hell=”,
“\\hell/”, or “/hell/” are occasionally seen (it's claimed that in the
last example the first slash pushes the letters over to the right to
make them italic, and the second keeps them from falling over). On
FidoNet, you might see #bright# and ^dark^ text, which was actually
interpreted by some reader software. Finally, words may also be
emphasized L I K E T H I S, or by a series of carets (^) under them on
the next line of the text.

There is a semantic difference between \*emphasis like this\* (which
emphasizes the phrase as a whole), and \*emphasis\* \*like\* \*this\*
(which suggests the writer speaking very slowly and distinctly, as if to
a very young child or a mentally impaired person). Bracketing a word
with the ‘\*’ character may also indicate that the writer wishes readers
to consider that an action is taking place or that a sound is being
made. Examples: \*bang\*, \*hic\*, \*ring\*, \*grin\*, \*kick\*,
\*stomp\*, \*mumble\*.

One might also see the above sound effects as <bang>, <hic>, <ring>,
<grin>, <kick>, <stomp>, <mumble>. This use of angle brackets to mark
their contents originally derives from conventions used in
`BNF <B/BNF.html>`__, but since about 1993 it has been reinforced by
the HTML markup used on the World Wide Web.

Angle-bracket enclosure is also used to indicate that a term stands for
some `random <R/random.html>`__ member of a larger class (this is
straight from `BNF <B/BNF.html>`__). Examples like the following are
common::

    So this <ethnic> walks into a bar one day...

There is also an accepted convention for 'writing under erasure'; the
text>

    Be nice to this fool^H^H^H^Hgentleman, he's visiting from corporate
    HQ.

reads roughly as “Be nice to this fool, er, gentleman...”, with irony
emphasized. The digraph ^H is often used as a print representation for a
backspace, and was actually very visible on old-style printing
terminals. As the text was being composed the characters would be echoed
and printed immediately, and when a correction was made the backspace
keystrokes would be echoed with the string ‘^H’. Of course, the final
composed text would have no trace of the backspace characters (or the
original erroneous text).

Accidental writing under erasure occurs when using the Unix **talk**
program to chat interactively to another user. On a PC-style keyboard
most users instinctively press the backspace key to delete mistakes, but
this may not achieve the desired effect, and merely displays a ^H
symbol. The user typically presses backspace a few times before their
brain realises the problem — especially likely if the user is a
touch-typist — and since each character is transmitted as soon as it is
typed, Freudian slips and other inadvertent admissions are (barring
network delays) clearly visible for the other user to see.

Deliberate use of ^H for writing under erasure parallels (and may have
been influenced by) the ironic use of ‘slashouts’ in science-fiction
fanzines.

A related habit uses editor commands to signify corrections to previous
text. This custom faded in email as more mailers got good editing
capabilities, only to take on new life on IRCs and other line-based chat
systems::                                                        

     charlie: I've seen that term used on alt.foobar often.               
     lisa: Send it to Erik for the File.                                  
     lisa: Oops...s/Erik/Eric/.                                                                                                                    



The s/Erik/Eric/ says “change Erik to Eric in the preceding”. This
syntax is borrowed from the Unix editing tools **ed** and **sed**, but
is widely recognized by non-Unix hackers as well.

In a formula, * signifies multiplication but two asterisks in a row are
a shorthand for exponentiation (this derives from FORTRAN, and is also
used in Ada). Thus, one might write 2 ** 8 = 256.

Another notation for exponentiation one sees more frequently uses the
caret (^, ASCII 1011110); one might write instead 2^8 = 256. This goes
all the way back to Algol-60, which used the archaic ASCII ‘up-arrow’
that later became the caret; this was picked up by Kemeny and Kurtz's
original BASIC, which in turn influenced the design of the bc(1) and
dc(1) Unix tools, which have probably done most to reinforce the
convention on Usenet. (TeX math mode also uses ^ for exponention.) The
notation is mildly confusing to C programmers, because ^ means bitwise
exclusive-or in C. Despite this, it was favored 3:1 over \*\* in a
late-1990 snapshot of Usenet. It is used consistently in this lexicon.

In on-line exchanges, hackers tend to use decimal forms or improper
fractions (‘3.5’ or ‘7/2’) rather than ‘typewriter style’ mixed
fractions (‘3-1/2’). The major motive here is probably that the former
are more readable in a monospaced font, together with a desire to avoid
the risk that the latter might be read as ‘three minus one-half’. The
decimal form is definitely preferred for fractions with a terminating
decimal representation; there may be some cultural influence here from
the high status of scientific notation.

Another on-line convention, used especially for very large or very small
numbers, is taken from C (which derived it from FORTRAN). This is a form
of ‘scientific notation’ using ‘e’ to replace '\*10^'; for example, one
year is about 3e7 (that is, 3 × 10 :sup: '7') seconds long.

The tilde (~) is commonly used in a quantifying sense of
‘approximately’; that is, "~50" means ‘about fifty’.

On Usenet and in the `MUD <M/MUD.html>`__ world, common C boolean,
logical, and relational operators such as "|", "&", "||", "&&",
"!", "==", "!=", ">", "<", ">=", and "<=" are often
combined with English. The Pascal not-equals, "<>", is also
recognized, and occasionally one sees "/=" for not-equals (from Ada,
Common Lisp, and Fortran 90). The use of prefix ‘!’ as a loose synonym
for ‘not-’ or ‘no-’ is particularly common; thus, ‘!clue’ is read
‘no-clue’ or ‘clueless’.

A related practice borrows syntax from preferred programming languages
to express ideas in a natural-language text. For example, one might see
the following::
                                                                         
      In <jrh578689@thudpucker.com> J. R. Hacker wrote:                     
      <I recently had occasion to field-test the Snafu                      
      <Systems 2300E adaptive gonkulator.  The price was                    
      <right, and the racing stripe on the case looked                      
      <kind of neat, but its performance left something                     
      <to be desired.                                                       
                                                                            
      Yeah, I tried one out too.                                            
                                                                            
      #ifdef FLAME                                                          
      Hasn't anyone told those idiots that you can't get                    
      decent bogon suppression with AFJ filters at today's                  
      net volumes?                                                          
      #endif /* FLAME */                                                    
                                                                            
      I guess they figured the price premium for true                       
      frame-based semantic analysis was too high.                           
      Unfortunately, it's also the only workable approach.                  
      I wouldn't recommend purchase of this product unless                  
      you're on a *very* tight budget.                                      
                                                                            
      #include <disclaimer.h>                                               
                                                                          
                       == Frank Foonly (Fubarco Systems)                                                                                            


In the above, the "#ifdef"/"#endif" pair is a conditional
compilation syntax from C; here, it implies that the text between (which
is a `flame <F/flame.html>`__) should be evaluated only if you have
turned on (or defined on) the switch FLAME. The "#include" at the end
is C for “include standard disclaimer here”; the ‘standard disclaimer’
is understood to read, roughly, “These are my personal opinions and not
to be construed as the official position of my employer.”

The top section in the example, with < at the left margin, is an example
of an inclusion convention we'll discuss below.

More recently, following on the huge popularity of the World Wide Web,
pseudo-HTML markup has become popular for similar purposes:
                                                                        
      <flame>                                                               
      Your mother was a hamster and your father smelt of elderberries!      
      </flame>                                                                                                                                       


You'll even see this with an HTML-style attribute modifier:                                                       
                                                                            
      <flame intensity="100%">                                              
      You seem well-suited for a career in government.                      
      </flame>                                                                                                                                       

Another recent (late 1990s) construction now common on Usenet seems to
be borrowed from Unix shell syntax or Perl. It consists of using a
dollar sign before an uppercased form of a word or acronym to suggest
any `random <R/random.html>`__ member of the class indicated by the
word. Thus: ‘$PHB’ means “any random member of the class ‘Pointy-Haired
Boss’”.

Hackers also mix letters and numbers more freely than in mainstream
usage. In particular, it is good hackish style to write a digit sequence
where you intend the reader to understand the text string that names
that number in English. So, hackers prefer to write ‘1970s’ rather than
‘nineteen-seventies’ or ‘1970's’ (the latter looks like a possessive).

It should also be noted that hackers exhibit much less reluctance to use
multiply-nested parentheses than is normal in English. Part of this is
almost certainly due to influence from LISP (which uses deeply nested
parentheses (like this (see?)) in its syntax a lot), but it has also
been suggested that a more basic hacker trait of enjoying playing with
complexity and pushing systems to their limits is in operation.

Finally, it is worth mentioning that many studies of on-line
communication have shown that electronic links have a de-inhibiting
effect on people. Deprived of the body-language cues through which
emotional state is expressed, people tend to forget everything about
other parties except what is presented over that ASCII link. This has
both good and bad effects. A good one is that it encourages honesty and
tends to break down hierarchical authority relationships; a bad one is
that it may encourage depersonalization and gratuitous rudeness. Perhaps
in response to this, experienced netters often display a sort of
conscious formal *politesse* in their writing that has passed out of
fashion in other spoken and written media (for example, the phrase “Well
said, sir!” is not uncommon).

Many introverted hackers who are next to inarticulate in person
communicate with considerable fluency over the net, perhaps precisely
because they can forget on an unconscious level that they are dealing
with people and thus don't feel stressed and anxious as they would face
to face.

Though it is considered gauche to publicly criticize posters for poor
spelling or grammar, the network places a premium on literacy and
clarity of expression. It may well be that future historians of
literature will see in it a revival of the great tradition of personal
letters as art.



