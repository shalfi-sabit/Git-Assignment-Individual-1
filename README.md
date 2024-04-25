## Describing 3 types of reset options
  - `--soft:` Only removes the commit. But, staging area and working directory remains untouched.
  - `--mixed:` Only removes the commit and unstages the files. But, working directory remains untouched.
  - `--hard:` Changes commit, staging and working directory to that exact state of the mentioned commit.

## Squashing commits
  - Combines one or more commits together so that unnecessary commits messages can be merged into a single message.
  - As we can remove the noise the combining multiple commits together, the history remains clean and informative. <br> Hence, improves the readability of the commit.
