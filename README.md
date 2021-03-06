
<!-- README.md is generated from README.Rmd. Please edit that file -->

# ThreadTone

<!-- badges: start -->

<!-- badges: end -->

The goal of ThreadTone is to reproduce the ThreadTone (aka.knit
portrait) effect from [Petros
Vrellis](http://artof01.com/vrellis/works/knit.html) in R.

[Fang, Lin & Shamir](https://arxiv.org/pdf/1802.04706.pdf) have
described an algorithmic method for producing this type of work.

[Hackaday provides some detail of the underlying
method](https://hackaday.com/2016/07/28/computer-designed-portraits-knit-by-hand/).

> “He assigned darker pixels in the original image a higher score, and
> ran the string to the opposing pin that maximizes the sum of the
> pixels passed through. With each string, he subtracted off a bit of
> darkness from all of the pixels along the string’s path, and repeated,
> starting each time at the new pin location. Each string has “only” 200
> choices to make times 3000-4000 passes, so a computer should be done
> in no time. Tuning this algorithm to work just right, and look good
> with real string is probably just about as easy as it sounds. For
> instance, he had to include code to break ties."

This has also been [implemented in python by Tommy
Clausner](https://github.com/TommyClausner/knit-portrait)
