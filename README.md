## Objectives

- Test your understanding of git commands

???

# Git Quiz

?: Which of the following is the correct way to initialize a new Git repository?

( )`git add .` (X)`git init` ( )`git commit`

?: Which of the following commands will create a new branch called `brand_new` and also check it out?

( )`git branch brand_new` ( )`git checkout brand_new` (X)`git checkout -b brand_new`

?: Which of the following commands will delete the branch `brand_new`

(X)`git branch -d brand_new` ( )`git delete brand_new`

?: How do you check the state of your local git repository since your last commit?

(X)`git status`
( )`git commit`
( )`git diff`
( )`git check`

?: How do you check the untracked differences within your local git repository?

( )`git status`
( )`git commit`
(X)`git diff`
( )`git check`

?: You can type `git status` at any point while in a git controlled directory to check the status of your files.

(X)True ( )False

?: Which of the following commands will stage your entire directory and every non-empty directory inside your current directory?

( )`git status all`
( )`git commit all`
(X)`git add .`

?: We've just created a new file called `index.html`. Which of the following will stage this one file so we can commit it?

(X)`git add index.html`
( )`git add new`
( )`git commit index.html`

?: We've made many changes to the `index.html` but only want to stage some lines towards the middle of the file. Which of the following commands will enable you to partially stage your changes?

( )`git commit -p index.html`
( )`git add . index.html`
( )`git add -m index.html`
(X)`git add -p index.html`
( )`git commit --partial-staging index.html`

?: `git status` returns:

```bash
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

  new file:   index.html
```

How would you commit this with the subject "Add index.html" and a description of "I ran into some complications listing authors and instead am listing copywriters."

( )`git commit -m "I ran into some complications listing authors and instead am listing copywriters." "Add index.html"`
( )`git commit -m "Add index.html" "I ran into some complications listing authors and instead am listing copywriters."`
( )`git commit -m "Add index.html" -p "I ran into some complications listing authors and instead am listing copywriters."`
(X)`git commit -m "Add index.html" -m "I ran into some complications listing authors and instead am listing copywriters."`
( )`git commit -m "Add index.html" & "I ran into some complications listing authors and instead am listing copywriters."`

?: What's the git command that downloads your repository from GitHub to your computer?

( )`git push`
( )`git fork`
(X)`git clone`
( )`git commit`

?: How do you create a copy of a lab under your own GitHub account?

( )`git fork`
( )`git clone`
( )`git pull-request`
(X) Forking it via the GitHub interface.

?: What command would you use to add more staged changes into your last commit?

( )`git add --amend`
(X)`git commit --amend`
( )`git add --more`
( )`git commit --more`

?: You go to push up your work and your shell outputs this:

```bash
$ git push origin toggle-branch
To github.com:powerforeva/nitro.git
 ! [rejected]        toggle-branch -> toggle-branch (non-fast-forward)
error: failed to push some refs to 'git@github.com:powerforeva/nitro.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
```

This makes sense because you just amended your last commit (and rewrote history). What do you do to push up your changes?

(X)`git push origin toggle-branch --force-with-lease`
( )`git push origin toggle-branch --amend`
( )`git push origin toggle-branch --force`
( )`git push origin toggle-branch --do-it`

?: You want to move back to a previous commit on your branch. What command should you use?

( )`git exchange`
( )`git moveback`
( )`git checkout`
(X)`git reset`

?: What command prints a history of local git commits?

( )`git list`
(X)`git log`
( )`git pull`
( )`git bisect`

?: You want to move back to the 2nd to last commit on your branch. What command should you use?

( )`git checkout HEAD^2`
( )`git moveback HEAD^2`
(X)`git reset HEAD^2`
( )`git checkout other_branch`

?: You want to move back to the last commit on your branch and throw out all changes from the last commit. What command should you use?

( )`git reset --mixed HEAD^1`
( )`git reset --soft HEAD^1`
(X)`git reset --hard HEAD^1`

?: You want to point to 4 commits earlier on your branch. Which of these are valid references to that commit?

[X]`HEAD^4`
[ ]`HEAD*4`
[X]`HEAD~4`
[ ]`HEAD#4`

?: `git log` returns:

```
commit 4c8560845c8bc02c003732291e5dc762d0d0d520 (HEAD -> master, origin/master, origin/HEAD)
Author: Kevin Skilton <kevin.skilton@powerhrg.com>
Date:   Wed Oct 18 14:35:37 2017 -0200

    Keep master as reference

commit c926e26e9c1ac9be1adfca1e53aca85d481647d6
Author: Leila Weiss <leila.weiss@powerhrg.com>
Date:   Fri May 19 11:38:52 2017 -0300

    Update search to work with files
```

What commands would point your local master branch to the commit with the subject `"Update search to work with files"`?

[X]`git reset c926e26e9c1ac9be1adfca1e53aca85d481647d6`
[X]`git reset c926e26`
[ ]`git reset "Update search to work with files"`
[X]`git reset HEAD~1`

?: You have added some changes you would like to move back to untracked. What command will do this?

(X)`git reset`
( )`git untracked`
( )`git rewind`

???

## Does this need an update?

Please open a [GitHub issue](https://github.com/powerhome/phrg-advanced-git-quiz/issues). Provide a detailed description that explains the issue you have found or the change you are proposing. Then "@" mention your instructor on the issue, and send them a link via Connect.
