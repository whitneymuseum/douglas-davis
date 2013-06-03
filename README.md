*A contest to help the Whitney Museum recover a web-based work of art from the 1990s*
===================================================================================



In 1995, Douglas Davis's *The World's First Collaborative Sentence* (1994) was
exhibited at the first Gwangju Biennale, where visitors were able to contribute to the piece using machines provided
by Samsung. Most contributed text in their native languages, and as a result, approximately 40% of the
*Sentence* is in Korean. Unfortunately, before the work was donated to the
Whitney Museum, the files sustained some form of encoding damage. All of the
Korean text input by visitors at the 1995 Gwangju Biennale is now illegible.

**For example:** what once would have been seen as: 광주비엔낱레여 (which Google
translates to "Gwangju Biennale open"), is now rendered as ±Ûç…¼–À£Òøá. Some
modern browsers attempt and fail to automatically detect the encoding. This is
not a simple matter of the text being in an obsolete character encoding, but
rather, it would appear that the text was inadvertently converted between
character encodings. This could have been through some act of copy and paste,
but the details of how or when this damage occurred are unknown.



The challenge:
--------------

The Whitney Museum has conducted initial research and experiments in encoding
mapping and conversions, and has assembled all available evidence here in this
repository. We're not sure if complete recovery is possible, and in any case it
is beyond our area of expertise. Here's where you come in.



**The challenge:** Repair the damaged character encoding to its original
state.\*


\*It is required that your results be reproducible. We ask that you produce
technical documentation of your process and solution, explaining the "how" and "why"
of what you did.



Your Tools:
-----------

1.  The **Evidence** directory contains a PDF containing the ONLY remaining
    evidence of the correct rendering of the Korean text. We have also included
    a snippet of the source files to which this excerpt corresponds.

2.  The **Research** directory contains correspondence between Ken Lunde (author
    of [CJKV Computing][1] [from O'Reily]) and Ben Fino-Radin, in which they
    discuss the root of the problem, and potential solutions.

3.  The **Source Files** directory contains all pages of "The Sentence." Most of
    the Korean text deriving from the Gwangju Biennale can be found in files
    sentence5.html – through – sentence13.html

[1]: <http://shop.oreilly.com/product/9780596514471.do>





To respond to the challenge:
---------------------------

1.  Fork the repository

2.  Do your magic

3.  Email a link to your solution and documentation to: decoding.davis@gmail.com



It's worth it.
--------------

If you are able to repair this encoding damage, this will be the first time
these characters have been properly seen by anyone in at least 15 years.
