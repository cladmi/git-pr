git-pr
======

Script to help using github pull requests from the command line.


Design
------

Pull requests are cloned to `pr/pr_number/readable_pr_description` local
branches.
There is no mechanism for security.


Usage
-----

    # Get help
    git pr -h

    # List local pull requests branches
    git pr

    # Create and switch to pull request <pr_number>
    git pr <githubremote> <pr_number>


Install
-------

Copy the script to your path and make it executable.
It will then be available both by `git-pr` but also `git pr`.
