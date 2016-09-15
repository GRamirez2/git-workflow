#notes from deliberate git
http://rakeroutes.com/blog/deliberate-git/
https://vimeo.com/72762735

## commits are the what & why
  - state the change
    - subject is clear, imperative and short / short & direct === what
  - then explain the change
    - followed by detailed body === why

  - they are not a histroical log, they are actions of what your code does if you merge it
  - body: it describes the to-do item
    - explain as if you're writing a message of the changes you're making

  - WIP (with a shorthand reference)
  - make lots of small commits
    - code / commit / rewrite


re-writing commits ======
## git rebase
  - allows you to re-write commits you've already made
    - git rebase -i

  - use `git log` to find the commit before the first commit you want to change (the stable point)
  - `git rebase -i [that commit's hash]
