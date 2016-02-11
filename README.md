# mergepdf
Merge 2 PDF from a non-recto/verso scan

# How
It use pdftk to split and concatenate the PDFs, it's the only dependancy (and
standard GNU tools).

    $ ./mergepdf
    ./mergepdf recto.pdf verso.pdf output.pdf

Where :
- "recto.pdf" is the PDF containing all recto pages,
- "verso.pdf" is the one containing all verso pages and
- "output.pdf"... Well, the file you want to get.

# Why
I have a scanner that can scan multiple pages and output it in PDF, but I can
only scan one side of the page per scan. This script just reorganize this mess
in seconds.
