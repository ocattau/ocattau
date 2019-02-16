---
layout: post
title: First Tracks of Geoduck Genome
date: '2019-02-16'
---

We are working on last steps of getting a genome together including annoation. As of now we are working with [version 070](http://owl.fish.washington.edu/halfshell/genomic-databank/Pgenerosa_v070.fa) (via Phase Genomics, with Hi-C added to 10X, further improved with 10k MP library alignment) with about 300k scaffolds. And reduced versions limited to scaffolds greater than 10k bp [version 071](http://owl.fish.washington.edu/halfshell/genomic-databank/Pgenerosa_v071.fasta) and greater than 10k bp [version 073](http://owl.fish.washington.edu/halfshell/genomic-databank/Pgenerosa_v073.fasta), with 14014 and 1350 scaffolds respectively.


Maker is currently running on version 070 and 071. Using blast I have created a crude expressed gene track using [transcriptome version 4 - larval transcriptome](https://sr320.github.io/Geoduck-larval-transcriptome/) and version 071. Some [code](https://github.com/sr320/nb-2019/blob/master/P_generosa/03-Simple-gene-track.ipynb) and the [resulting gff](https://d.pr/f/ZBix9V) with ~15M regions. In addition, [taking a intermediate maker output](https://github.com/sr320/nb-2019/blob/master/P_generosa/02-Exploring-early-070-maker.ipynb) from version 070 I generated [a gff](https://d.pr/f/9T87e5) with about 130k gene regions.
