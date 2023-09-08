answer1 = 
    git version 2.34.1

answer2 = 
    user.name=nf843222
    user.email=nf843222@ohio.edu

answer3 = 
    A list of file contents pops up including synopsis' a description of what your looking at. 
    There are a total of 260 lines and in order to get back the terminal press "q" to quit.

answer4 = 
    On branch master

    No commits yet

    Untracked files:
        (use "git add <file>..." to include in what will be committed)
            README.md
            answers.md

        nothing added to commit but untracked files present (use "git add" to track)

answer5 =
    On branch master

    No commits yet

    Changes to be committed:
        (use "git rm --cached <file>..." to unstage)
            new file:   README.md

    Untracked files:
        (use "git add <file>..." to include in what will be committed)
            answers.md

answer6 =
    On branch master

    No commits yet

    Changes to be committed:
        (use "git rm --cached <file>..." to unstage)
            new file:   README.md
            new file:   answers.md

answer7 =
    [master (root-commit) 83396b8] Initial commit
    2 files changed, 20 insertions(+)
    create mode 100644 README.md
    create mode 100644 answers.md

answer8 =
    commit 83396b85c63b8bfe826f57d5893b3a5532c78a75 (HEAD -> master)
    Author: nf843222 <nf843222@ohio.edu>
    Date:   Fri Sep 8 14:35:40 2023 -0400

        Initial commit

answer9 = 
    Enumerating objects: 4, done.
    Counting objects: 100% (4/4), done.
    Delta compression using up to 16 threads
    Compressing objects: 100% (3/3), done.
    Writing objects: 100% (4/4), 600 bytes | 600.00 KiB/s, done.
    Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
    To https://github.com/nf843222/git-lab.git
    * [new branch]      main -> main
    Branch 'main' set up to track remote branch 'main' from 'origin'.

    git status
        On branch main
        Your branch is up to date with 'origin/main'.

        Changes not staged for commit:
            (use "git add <file>..." to update what will be committed)
            (use "git restore <file>..." to discard changes in working directory)
                modified:   answers.md

    no changes added to commit (use "git add" and/or "git commit -a")
    
answer10 = 
    There were no changes made to the README.md

answer11 = 
    To https://github.com/nf843222/git-lab.git
     ! [rejected]        main -> main (fetch first)
    error: failed to push some refs to 'https://github.com/nf843222/git-lab.git'
    hint: Updates were rejected because the remote contains work that you do
    hint: not have locally. This is usually caused by another repository pushing
    hint: to the same ref. You may want to first integrate the remote changes
    hint: (e.g., 'git pull ...') before pushing again.
    hint: See the 'Note about fast-forwards' in 'git push --help' for details.
    -----------DID NOT ACCEPT CHANGES IN GIT-HUB----------
answer12 =
    remote: Enumerating objects: 5, done.
    remote: Counting objects: 100% (5/5), done.
    remote: Compressing objects: 100% (3/3), done.
    remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
    Unpacking objects: 100% (3/3), 736 bytes | 245.00 KiB/s, done.
    From https://github.com/nf843222/git-lab
        83396b8..eb55f0a  main       -> origin/main
    Updating 83396b8..eb55f0a
    Fast-forward
        README.md | 5 ++++-
        1 file changed, 4 insertions(+), 1 deletion(-)
    ---- CHANGES WERE MADE TO THE README.md FILE ---

answer13 =
    .  ..  .git  .gitignore  README.md
    ------CREATED A NEW PATH WITH FILES------------
answer14 = 
    git commit -m "Sending update program from Virtual Code Studio"
    [main 9e12bcb] Sending update program from Virtual Code Studio
    1 file changed, 18 insertions(+)
    create mode 100644 git-lab-program.cc

    Enumerating objects: 4, done.
    Counting objects: 100% (4/4), done.
    Delta compression using up to 16 threads
    Compressing objects: 100% (3/3), done.
    Writing objects: 100% (3/3), 574 bytes | 574.00 KiB/s, done.
    Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
    To https://github.com/nf843222/git-lab.git
        eb55f0a..9e12bcb  main -> main
 -----IT SENT THE INFORMATION TO BE COLLECTED ON GIT-HUB. -------------
