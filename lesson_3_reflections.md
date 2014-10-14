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
