Delete the most recent commit, keeping the work you've done.

    git reset --soft HEAD~1

Delete the most recent commit, destroying the work you've done.

    git reset --hard HEAD~1

Remove a file from the repo without deleting local copy of the file.

    git rm --cached filename

Remove a directory from the repo without deleting local copy of the directory.

    git rm --cached -r dirname

Download repository branch packed up in an archive.

    git archive --output=dest_filename.zip --format=zip --remote=git@bitbucket.org:username/reponame.git master
