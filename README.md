PhD thesis data
=============================================

This thesis is generated based on the [Lyx PhD Template](https://github.com/chaosct/LyxPhDTemplateUPF).
The pdf is generated with XeTex in [LyX](http://www.lyx.org/). 


Setup
-----

You will need LyX, a functional Latex installation, LibreOffice.


How to use generate/modify this thesis
------------------------

The master document is `PhDThesis_Georgi_Knowledge_based_Lyrics_Tracking`. It includes all the material there. You can edit any subdocument as you would normally do in Lyx. This means that only by generating the pdf (`xetex` option) in this document you will get the whole thing correctly.

Some modifications of the [original Lyx PhD Template](https://github.com/chaosct/LyxPhDTemplateUPF) to take into account:


1. The publications appendix isn't generated automatically in the master document. You need to edit `publications.bib`, open `publications.lyx` and save the generated pdf as `publications.pdf` (this is the default). The resulting pdf is also automatically imported when generating the master document.
2. The bibliography is generated with the chicago-ff.bst style file following the 13th edition of the Chicago Manual of Style. I have modified http://kinglab.eeb.lsa.umich.edu/pub/biblios/bst/ to have full author names like [this](https://tex.stackexchange.com/questions/324728/how-to-do-chicago-style-citation-where-author-last-name-first-name-appear-in-fu)
3. The abbreviations list is generated adding the `\usepackage[automake]{glossaries}` to the LaTex preamble following the last comment [here](https://tex.stackexchange.com/questions/12346/use-a-quality-glossary-and-acronym-list-in-lyx)

License
-------

If you modify this thesis as a template for yours, you don't have to thank me in your manuscript. Use as please. I'm not responsible if you lose all your manuscript because of Lyx, or this thesis, or if the final PDF gets rejected because of the formatting, etc.
