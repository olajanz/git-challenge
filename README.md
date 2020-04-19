# Git Challenge

This is an exercise to practice git branches and merging.

Start by creating a fork of this project.

For each task create a new branch and

## Getting Started

- Fork the project
- Clone the fork
- Create a develop branch
- For each story create a new feature branch (choose a short but descriptive name in kebap-case). Always branch out from the develop branch
- Implement the feature and tick it off in this Readme
- When you have completed all stories from a sprint, merge them one by one into the develop branch.
  - Before you merge do a `rebase --interactive` on the develop branch. That's a chance to clean up your commit messages, squash commits, etc... and it ensures that there won't be any forks in the develop log.
  - If you encounter conflicts during the rebase, fix and stage them using `git add` and then run `git rebase --continue`
- When all feature branches from a sprint are merged, merge the develop branch into the master.

## Sprint 1

- [ ] Change the title of the page to Git Summary
- [ ] Fix the typo in the **Configure** heading
- [ ] Add the commit section from <https://gist.github.com/yodra/c1c95f8c2cd94811d988d97640a5da45#file-git-command-summary-md>

## Sprint 2

- [ ] Add a stylesheet file
- [ ] Change the font to Open Sans (import from Google Fonts)
- [ ] Set the maximum width of the body to 800px and center the text on the page

## Sprint 3

- [ ] Improve the table layout to have some better spacing and a consistent column width throughout the page
- [ ] Change the code font to Fira Mono
- [ ] Add more sections from <https://gist.github.com/yodra/c1c95f8c2cd94811d988d97640a5da45#file-git-command-summary-md>
