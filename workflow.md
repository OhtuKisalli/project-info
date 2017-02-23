## Workflow guide
_Please follow this guideline during the project_

### What's happend?
* Check [slack](https://ohtu-k.slack.com/messages/general/) messages
* Check taskboard [trello](https://trello.com/b/Llh06XVS/ohtu-kisalli)
* Check new commits from git repos:
  * [frontend](https://github.com/OhtuKisalli/ohtukisalli.github.io/commits/master)
  * [backend](https://github.com/OhtuKisalli/kisallioppiminen.server/commits/master)

### Start working
* **Tag a task** from trello and drag the card to _In progress_
* Code + git
* [branching practices etc.](https://github.com/agis-/git-style-guide)

### Task done
* `git push origin branch` your commits
  * `feature/dev/personal` -branch **OR**
  * `master` if ready for staging server
* Drag card to _DONE_
* **Mark working hours** _(task)_ to card comments
* Write new cards
  * _After finishing a task you'll probably notice something that should/could be done next.. Now is a great time to write them down for other to see_
  * _Write notes on card comments can also be very useful. Perhaps copy them to a appropriate slack channel_

### Story done
* Working hours
  * Count working hours from tasks
  * Mark time used on story to backlog
  * Mark "Done sprint" in backlog

### End working
* `git push` your commits
  * `feature/dev/personal` -branch if unfinished
  * `master` if ready for staging server
* **[Mark](https://docs.google.com/spreadsheets/d/180-vFs-bMMX5TbqWguWX8CcJY1d9pP2HliAgFIHWH1I/edit) your hours** _(all day)_ and what you've been working on
  * Everybody + personal tabs!

## Sprint meeting

[Check steps for sprint planning meeting](https://github.com/OhtuKisalli/project-info/blob/master/Sprint-planning-memo.md)

## Git workflow
* `git pull origin master`
* `git checkout -b branch-name-here`
* _work work work work_
* `git add -a /-p`
* `git commit -m "Commit message"`
* Push
  * Ready for sharing to team:
    * share/save your `feature/dev/personal` -branch
    * `git push ?? ??`
  * Ready for staging:
    * `git checkout master`
    * `git pull`
    * `git merge branch-name-here`
    * `git push ?? ??`
  * Ready for production:
    * _todo_
