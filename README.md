Demo of how to setup a workflow which runs on two different OSes:
- RL8 is always run
- RL9 runs if either:
  - it's ticked when manually-triggering a run
  - the PR's branch starts with 'rl9'

Note that the RL9 run won't happen on merge to main, even from a 'rl9' branch. Whether
this is the desired behaviour or not is questionable.
