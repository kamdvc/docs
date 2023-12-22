# Feature name

* Proposal: [SE-NNNN](NNNN-filename.md)
* Authors: [Author 1](https://github.com/N3v1), [Author 2](https://github.com/N3v1)
* Review Manager: TBD
* Status: **Awaiting implementation** or **Awaiting review**
* Bug: *if applicable* [ScribbleLabApp/ScribbleLab#NNNNN](https://github.com/ScribbleLabApp/ScribbleLab/issues/NNNNN)
* Implementation: [ScribbleLabApp/ScribbleLab#NNNNN](https://github.com/ScribbleLabApp/ScribbleLab/pull/NNNNN)
* Previous Proposal: *if applicable* [SE-XXXX](XXXX-filename.md)

When filling out this template, you should delete or replace all of
the text except for the section headers and the header fields above.
For example, you should delete everything from this paragraph down to
the Introduction section below.

As a proposal author, you should fill out all of the header fields
except `Review Manager`.  The review manager will set that field and
change several others as part of initiating the review.  Delete any
header fields marked *if applicable* that are not applicable to your
proposal.

When sharing a link to the proposal while it is still a PR, be sure
to share a live link to the proposal, not an exact commit, so that
readers will always see the latest version when you make changes.
On GitHub, you can find this link by browsing the PR branch: from the
PR page, click the "username wants to merge ... from username:my-branch-name"
link and find the proposal file in that branch.

`Status` should reflect the current implementation status while the
proposal is still a PR.  The proposal cannot be reviewed until an
implementation is available, but early readers should see the correct
status.

`Bug` should be used when this proposal is fixing a bug with significant
discussion in the bug report.  It is not necessary to link bugs that do
not contain significant discussion or that merely duplicate discussion
linked somewhere else.  Do not link bugs from private bug trackers.

`Implementation` should link to the PR(s) implementing the feature.
If the proposal has not been implemented yet, or if it simply codifies
existing behavior, just say that.  If the implementation has already
been committed to the main branch (as an experimental feature), say
that and specify the experimental feature flag.  If the implementation
is spread across multiple PRs, just link to the most important ones.

`Previous Proposal` should be used when there is a specific line of
succession between this proposal and another proposal.  For example,
this proposal might have been removed from a previous proposal so
that it can be reviewed separately, or this proposal might supersede
a previous proposal in some way that was felt to exceed the scope of
a "revision".  Include text briefly explaining the relationship,
such as "Supersedes SE-1234" or "Extracted from SE-01234".  If possible,
link to a post explaining the relationship, such as a review decision
that asked for part of the proposal to be split off.  Otherwise, you
can just link to the previous proposal.

`Review` is a history of all discussion threads about this proposal,
in chronological order.  Use these standardized link names: `pitch`
`review` `revision` `acceptance` `rejection`.  If there are multiple
such threads, spell the ordinal out: `first pitch` `second review` etc.

## Introduction

A short description of what the feature is. Try to keep it to a
single-paragraph "elevator pitch" so the reader understands what
problem this proposal is addressing.

## Motivation

Describe the problems that this proposal seeks to address. If the
problem is that some common pattern is currently hard to express, show
how one can currently get a similar effect and describe its
drawbacks. If it's completely new functionality that cannot be
emulated, motivate why this new functionality would help Swift
developers create better Swift code.

## Proposed solution

Describe your solution to the problem. Provide examples and describe
how they work. Show how your solution is better than current
workarounds: is it cleaner, safer, or more efficient?

This section doesn't have to be comprehensive.  Focus on the most
important parts of the proposal and make arguments about why the
proposal is better than the status quo.

## Detailed design

Describe the design of the solution in detail. If it involves new
syntax in the language, show the additions and changes to the Swift
grammar. If it's a new API, show the full API and its documentation
comments detailing what it does. The detail in this section should be
sufficient for someone who is *not* one of the authors to be able to
reasonably implement the feature.

## Source compatibility

Describe the impact of this proposal on source compatibility.  As a
general rule, all else being equal, Swift code that worked in previous
releases of the tools should work in new releases.  That means both that
it should continue to build and that it should continue to behave
dynamically the same as it did before.  Changes that cannot satisfy
this must be opt-in, generally by requiring a new language mode.

This is not an absolute guarantee, and the Language Workgroup will
consider intentional compatibility breaks if their negative impact
can be shown to be small and the current behavior is causing
substantial problems in practice.

For proposals that affect parsing, consider whether existing valid
code might parse differently under the proposal.  Does the proposal
reserve new keywords that can no longer be used as identifiers?

For proposals that affect type checking, consider whether existing valid
code might type-check differently under the proposal.  Does it add new
conversions that might make more overload candidates viable?  Does it
change how names are looked up in existing code?  Does it make
type-checking more expensive in ways that might run into implementation
limits more often?

For proposals that affect the standard library, consider the impact on
existing clients.  If clients provide a similar API, will type-checking
find the right one?  If the feature overloads an existing API, is it
problematic that existing users of that API might start resolving to
the new API?

## Alternatives considered

Describe alternative approaches to addressing the same problem.
This is an important part of most proposal documents.  Reviewers
are often familiar with other approaches prior to review and may
have reasons to prefer them.  This section is your first opportunity
to try to convince them that your approach is the right one, and
even if you don't fully succeed, you can help set the terms of the
conversation and make the review a much more productive exchange
of ideas.

You should be fair about other proposals, but you do not have to
be neutral; after all, you are specifically proposing something
else.  Describe any advantages these alternatives might have, but
also be sure to explain the disadvantages that led you to prefer
the approach in this proposal.

You should update this section during the pitch phase to discuss
any particularly interesting alternatives raised by the community.
You do not need to list every idea raised during the pitch, just
the ones you think raise points that are worth discussing.  Of course,
if you decide the alternative is more compelling than what's in
the current proposal, you should change the main proposal; be sure
to then discuss your previous proposal in this section and explain
why the new idea is better.

## Acknowledgments

If significant changes or improvements suggested by members of the 
community were incorporated into the proposal as it developed, take a
moment here to thank them for their contributions. Swift evolution is a 
collaborative process, and everyone's input should receive recognition!

Generally, you should not acknowledge anyone who is listed as a
co-author or as the review manager.