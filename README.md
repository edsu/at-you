at-you
======

This repository is a work in progress for analyzing and characterizing tweets
that have been directed at [DeRay Mckesson](https://twitter.com/deray) and 
[Johnetta Elzie](https://twitter.com/Nettaaaaaaaa). We want to help shine a 
light on the networks of online harrassment that 
[BlackLivesMatter](https://en.wikipedia.org/wiki/Black_Lives_Matter) activists 
have to deal with when working in public social media spaces. This 
work was largely a response to DeRay's 
[tweet](https://twitter.com/deray/status/604782399906418688)
about the number of people he has had to block on Twitter.

The initial datasets we are working with consist of 12,014 tweets that were 
sent to @deray, and 1,537 tweets that were sent to @Nettaaaaaaaa between May 
23 and June 1, 2015. They were collected on June 1st with
[twarc](http://github.com/edsu/twarc) using the following command:

    twarc.py --search to:deray
    twarc.py --search to:Nettaaaaaaaa

While Twitter's Terms of Service do not allow us to distribute the complete 
JSON dataset we obtained from Twitter's API, they do allow us to distribute the
tweet identifers. You can find our initial sets of ids in the data directory
in this repository. You should be able to obtain the full JSON dataset by 
"hydrating" the ids with [twarc](http://github.com/edsu/twarc).

One significant caveat is that if a tweet has been deleted since our initial 
collection you will not be able to hydrate it, since Twitter's API will not 
make it available.

Please don't hesitate to get in touch using the 
[issues](https://github.com/edsu/to-deray/issues) queue, or via Twitter.
This is a collaborative project. If you'd like to get involved let us know and
we'll let you know when we are meeting.

* [Dan Chudnov](https://twitter.com/dchud)
* [Bergis Jules](https://twitter.com/bergisjules)
* [Ed Summers](https://twitter.com/edsu)
