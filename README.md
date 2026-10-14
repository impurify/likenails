# “When all that you have is a hammer, everything looks like a nail.”

*By [impurify](https://impurify.com/).*

> **Warning:** Do not attempt to use the dirty hack that I hereby attempted with rebasing a public branch!  It will break your Github Pages deployment, and waste you an hour to fix your site with more dirty hacks.
>
> I did this, and all I got was ~~this lousy T-shirt~~ *perhaps a future blog post*.

This `git` repository is a kludge to hold blobby web resources that I don’t want to check into other repos, and to make them deletable with `git rebase` without rewriting other repos’ histories.

I have a design in mind to retain a permanent history of what I checked in, but make the actual blobs deletable with a weird branching strategy.

I first thought of this idea on 2026-10-10.

This repository is named `likenails`, so as to reserve the word `nails` in my git repo namespace.  However, when adding it as a submodule, it should be placed in the `nails` path (absent any local namespace conflict).
