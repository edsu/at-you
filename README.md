to-deray
========

This repository is a work in progress for analyzing and characterizing tweets
that have been directed at [DeRay Mckesson](https://twitter.com/deray).  We want
to help shine a light on deployment of online harrassment that 
[BlackLivesMatter](https://en.wikipedia.org/wiki/Black_Lives_Matter) activists 
like DeRay have to deal with when working in public social media spaces. This 
work was large a response to DeRay's 
[tweet](https://twitter.com/deray/status/604782399906418688)
about how many people he has had to block on Twitter.

The initial dataset we are working with consists of 12,014 tweets that were sent
to @deray between May 23 and June 1, 2015. Twitter's Terms of Service do not
allow us to distribute the raw data of this dataset. However Twitter does 
allow the tweet identifers to be distributed. You can find our initial set 
as part of this repository. If you want you should be able to obtain the 
full dataset by "hydrating" the ids with [twarc](http://github.com/edsu/twarc).

    twarc.py --hydrate to-deray-ids.txt > to-deray.json

Check back soon for more details on our approach and findings. Please don't 
hesitate to get in touch using the 
[issues](https://github.com/edsu/to-deray/issues) queue, or via email using
the addresses below.

## Team

* Dan Chudnov: [dchud@email.gwu.edu](mailto:dchud@email.gwu.edu)
* Bergis Jules: [bergis.jules@ucr.edu](mailto:bergis.jules@ucr.edu) 
* Ed Summers: [ehs@pobox.com](mailto:ehs@pobox.com)
