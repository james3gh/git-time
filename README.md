
# Squash and Regret 🙂

## Issue Description:

First make two commits in your info.md file each having respective answers to the questions. Commit title of each commit should be `<GitHub-username>-one` and `<GitHub-username>-two`. No commit description is required.

**Q1** - Explain objects and refs folder inside ./git. Where git commits are stored in ./git folder?

**Q2** - Differentiate between tree and blob in git? What they represent?

Then squash both the commits into one. Title of squash commit can be anything.

### NOTE: After cloning, one can use only 3 git commands uptil squashing the commits. (Even git status will get count)

Now make a `new_Branch`. Delete the squash commit from that branch. 
Now recover back the changes made in the commit 1 and 2 **individually** by cherry picking. i.e. first cherry-pick the 1st commit `<GitHub-username>-one`, then cherry-pick the 2nd commit `<GitHub-username>-two` into the `new_Branch`. Solve merge-conflicts if any.

Now make a PR from this `new_Branch`.

#### NOTE: The total number of commits on the PR should be 2 only and only one PR is allowed

