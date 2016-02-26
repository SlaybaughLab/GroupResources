# Reproducible and Open Science

Very closely related to reproducibility and openness is [Licensing](./Licenses.md)

> "Open science is a movement that seeks to ensure that the results and the
> data of scientific research are, and continue to be, available to all."
>
> --from An Open Science Peer Review Oath
>
> "Reproducibility and open science are about providing evidence that you are
> right, not just claiming that you are right."
>
> --Philip Stark


Our group strives to do science as reproducibly and openly as we can. We
recognize that there can be limitations in nuclear because of export control
and occasional non-disclosure agreements, but within those confines we will
follow these practices:

*   Version control work in a (usually git) repository, hosted on openly GitHub
    or BitBucket if possible.
*   Conduct analysis with version-controlled scripts; post the scripts in the
    repository with the code.
*   Include clear documentation about code and script use with the code(s) and
    script(s).
*   Ensure that codes have appropriate tests associated with them (unit tests
    at a minimum, system and integration tests if applicable).
*   Store data (for us results) in an open access repository like [figshare](http://figshare.com/) 
    or [Zenodo](http://zenodo.org), possibly as soon as it's collected,
    and give that data its own [Digital Object Identifier](https://en.wikipedia.org/wiki/Digital_object_identifier) (DOI).
    We might instead store published data somewhere like [Dryad](http://datadryad.org/).
*   Use an open repository for publications associated with the work.
*   When happy with the state of the publication, post a preprint version to 
    [arXiv](http://arxiv.org/) or some other preprint server to invite feedback 
    from peers (incorporate feedback as necessary).
*   The published paper includes links to the preprint
    and code and data repositories.

Some things to think about in terms of reproducibility that are useful to
document:
* What versions of third party libraries and support software were required?
* What operating system did you use?
* Make sure to version control output or include timestamps so it can be mapped
  to exact code versions.  

---
Other resources:
* [This short article](http://www.bitss.org/2015/12/31/science-is-show-me-not-trust-me/) 
by [Philip Stark] (http://www.stat.berkeley.edu/~stark/) provides a good
checklist for guiding the reproducibility of your work.
* [This short guide](https://guides.github.com/activities/citable-code/) from
GitHub explains how to create a Digital Object Identifier (DOI) for your code,
 your papers, or anything else hosted in a version control repository.
* BIDS Working Group on [Reproducibility and Open
Science](http://bids.berkeley.edu/working-groups/reproducibility-and-open-science)

---
Journal Selection and Reviews:

"Peer review is an important gatekeeper and key component of scientific
discourse."

Everyone in our group is encouraged to read
[An Open Science Peer Review Oath](http://f1000research.com/articles/3-271/v2)
In light of this, I [Rachel
Slaybaugh](https://www.nuc.berkeley.edu/people/rachel-slaybaugh) pledge:

> Principle 1: I will sign my name to my review
>
> Principle 2: I will review with integrity
>
> Principle 3: I will treat the review as a discourse with you; in particular, I
> will provide constructive criticism
> 
> Principle 4: I will be an ambassador for the practice of open science
> 

Discussions in our group about journal selection will include considering
degree of open access. It is possible we will pledge something stronger in the
future...at the least we will make all preprint publications openly available. 

