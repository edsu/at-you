to-deray
========

This repository is a work in progress for analyzing and characterizing tweets
that have been directed at [DeRay Mckesson](https://twitter.com/deray). 
We want to help shine a light on the types of harrassment that #BlackLivesMatter
activists like DeRay have to deal with on social media. 

The dataset we are working with consists of 12,014 tweets that were sent to 
@deray between May 23 and June 1, 2015. Twitter's Terms of Service do not
allow us to distribute the raw data of this dataset. However they do allow the
tweet identifers to be distributed. You can find our initial set as part of this
repository. If you want you should be able to obtain the dataset by 
"hydrating" the ids with [twarc](http://github.com/edsu/twarc).

    twarc.py --hydrate to-deray-ids.txt > to-deray.json

Check back soon for more details on our approach and findings. Don't hesitate 
to get in touch using the [issues](https://github.com/edsu/to-deray/issues) 
queue, or via email using the addresses below.

## Team

* Dan Chudnov: [dchud@email.gwu.edu](mailto:dchud@email.gwu.edu)
* Bergis Jules: [bergis.jules@ucr.edu](mailto:bergis.jules@ucr.edu) 
* Ed Summers: [ehs@pobox.com](mailto:ehs@pobox.com)
