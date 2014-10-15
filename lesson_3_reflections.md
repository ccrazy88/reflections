> When would you want to use a remote repository rather than keeping all your
> work local?

If you want to store your work in a safe place, a remote repository located on
a server that is tailored to storing them securely and redundantly will help to
mitigate issues involving data loss on your local machine (i.e. your computer
and/or hard drive dying).

Working collaboratively with others is also much easier with a remote
repository. Local repositories on each developer's machine can interact with
the remote repository, which will act as a de facto master copy.

> Why might you want to always pull changes manually rather than having Git
> automatically stay up-to-date with your remote repository?

Sometimes, automatically staying up-to-date with a remote repository might be
more hassle than it's worth. If a branch you're working on is completely
separate from what is being updated in the remote repository, then you don't
gain anything from being current with the remote repository.

> Describe the differences between forks, clones, and branches. When would you
> use one instead of another?

Branches are pointers to commits and can be used to start adding new features
in your repository or to represent a new area of work without inadvertently
messing up a clean version of your project, which can be referred to via a
different branch (i.e. master). Clones are copies of an entire repository and
can be used in order to facilitate collaboration with others. Rather than being
parts of a repository, like branches, clones are done at the repository level.
Forks are clones of repositories that are located in GitHub that allow people
to trace a project back to its original author. Whereas clones are usually used
on work that is either your own or your teammates' work (or a combination of
the two), a fork is usually done if the originator of the repository wants to
maintain their version of the code and you want to modify it in some way and/or
take it in a different direction, while maintaining a reference to the original
source.

> What is the benefit of having a copy of the last known state of the remote
> stored locally?

This makes merging your new code, presumably stored locally in your repository
on a new branch, into the origin/master branch, less painful by allowing you to
merge changes on the latest version of the remote that you could possibly have
had access to. The ability to have this copy of the last known state without it
merged into what you're working on allows for a lot of flexibility.

