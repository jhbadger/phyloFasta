PhyloFasta
==========

Phylogenetic programs have the annoying feature of typically requiring
awkward formats for data input, while most people using modern
alignment programs like MUSCLE typically keep their alignments in
straight-forward aligned FASTA files. So I've written wrappers around
various phylogenetic programs to take in aligned FASTA alignments and
convert them to whatever the program needs. Plus I have tried to keep
arguments consistent across programs to make running various programs
on the same alignment convenient. I use the Trollop option parser so
that the programs are self-documenting by simply running them without
any arguments.

Requirements
============

While each wrapper obviously requires the phylogenetic program in
question, there are several Ruby gems that are required:
bio trollop newick-ruby fpdf

The programs will report if any gems or programs are missing.

1.00 Initial Commit

License
=======
(The MIT License)

Copyright © 2014 Jonathan Badger

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the ‘Software’), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED ‘AS IS’, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
