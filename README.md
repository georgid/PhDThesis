PhD thesis data
=============================================

This thesis is generated based on the (Lyx PhD Template )[github.com/chaosct/LyxPhDTemplateUPF].
The pdf is generated with XeTex in LyX. 


Setup
-----

You will need LyX, a functional Latex installation, LibreOffice.


How to use generate/modify this thesis
------------------------

The master document is `PhDThesis_Georgi_Knowledge_based_Lyrics_Tracking`. It includes all the material there. You can edit any subdocument as you would normally do in Lyx. This means that only by generating the pdf (`pdf(pdflatex)` option) in this document you will get the whole thing correctly.

Some modifications of the original tamplate to take into account:


2. The publications appendix isn't generated automatically in the master document. You need to edit `publications.bib`, open `publications.lyx` and save the generated pdf as `publications.pdf` (this is the default). The resulting pdf is also automatically imported when generating the master document.
3. The bibliography is generated with the chicago-ff.bst style file following the 13th edition of the Chicago Manual of Style. I have modified http://kinglab.eeb.lsa.umich.edu/pub/biblios/bst/ to have full author names like (this)[https://tex.stackexchange.com/questions/324728/how-to-do-chicago-style-citation-where-author-last-name-first-name-appear-in-fu]

License
-------

You don't have to thank me in your manuscript. Use as please. I'm not responsible if you lose all your manuscript because of Lyx, or this template, or if the final PDF gets rejected because of the formatting, etc.
