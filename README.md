# Justification of Text in Haskell

A common type of text alignment in print media is "justification", where the spaces between words, are stretched or compressed to align both the left and right ends of each line of text. In this problem we'll be implementing a text justification function for a monospaced terminal output (i.e. fixed width font where every letter has the same width).

Alignment is achieved by inserting blanks and hyphenating the words. For example, given a text:

"He who controls the past controls the future. He who controls the present controls the past."

we want to be able to align it like this (to a width of say, 15 columns):

        He who controls
        the  past cont-
        rols  the futu-
        re. He  who co-
        ntrols the pre-
        sent   controls
        the past.


*part 1,2,3,4,5(1) are running smooth

