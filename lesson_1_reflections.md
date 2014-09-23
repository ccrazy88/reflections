> How did viewing a diff between two version of a file help you see the bug
> that was introduced?

It was easy to see that something was misspelled in one version of the file,
and, once the misspelling was spotted, it was easy to see that it was in the
new file, the one that doesn't work.

> How could having easy access to the entire history of a file make you a more
> efficient programmer in the long term?

It would allow you to track the progress of a project, revert to old versions
of your files, and more. It also allows for better collaboration, since other
programmers will be able to see exactly how their proposed versions of files
differ from yours.

> What do you think are the pros and cons of manually choosing when to create a
> commit, like you do in Git, versus having versions automatically saved, like
> Google Docs does?

Manually choosing when to create a commit allows you to control its size,
whether size is measured in lines, logical changes, time, or something else
entirely. Google Docs ensures that a change is (hopefully) never lost, which
Git doesn't, but you can't really control how detailed/granular your history
is, which makes files with long histories difficult to work with.

> Why do you think some version control systems, like Git, allow saving
> multiple files in one commit, while others, like Google Docs, treat each file
> separately?

A logical change may span multiple files, so allowing one commit to span
multiple files allows a programmer to organize their commit history in an
easier-to-understand manner, especially once projects grow.

> How can you use the commands git log and git diff to view the history of
> files?

The git log command lists commit IDs, which can be used in the git diff command
to pull up differences between two different commits.

> How might using version control make you more confident to make changes that
> could break something?

Going back in time is easy, and, assuming a clean commit history, finding the
first occurrence of a bug can be done, if necessary, as well.

> Now that you have your workspace set up, what do you want to try using Git
> for?

Everything!

