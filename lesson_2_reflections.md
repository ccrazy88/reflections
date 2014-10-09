> What happens when you initialize a repository? Why do you need to do it?

A folder containing all of the Git metadata, .git, is created. We need to do it
because otherwise, there's no way for Git to track all of the history, the
status, and everything else that it needs to track in order to make it work as
a version control system

> How is the staging area different from the working directory and the
> repository? What value do you think it offers?

It's where things that are inside the working directory are placed in order to
be committed to the repository. It allows the user to control exactly which
files apply to a certain commit.

> How can you use the staging area to make sure you have one commit per logical
> change?

Only stage the files that are relevant to a logical change, and then commit
them.

> What are some situations when branches would be helpful in keeping your
> history organized? How would branches help?

If there are certain features that are being added that aren't quite ready for
primetime.
