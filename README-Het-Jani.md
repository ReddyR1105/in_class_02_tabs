# README - Het Jani

## Reflection Questions

### 1. What surprised you most about how the widget tree, state, or lifecycle actually behaves once you saw it applied in the app?
What surprised me was how one small thing like the `TabController` length has to match the tabs and the `TabBarView`. Before this activity I thought adding another tab would just mean adding another widget, but I saw that different parts of the tree depend on each other.

### 2. Which concept took the longest to click for you, and what finally made it make sense?
Controllers and lifecycle took the longest for me. `initState()` and `dispose()` felt random at first, but it clicked when I understood that I create the `TabController` when the screen starts and I should clean it up when that screen is removed.

### 3. What part of the GitHub workflow felt least familiar, and how did you work through it?
Branches were probably the least familiar part for me. At one point I literally tried to `cd` into my branch because I was thinking of it like a folder, and that helped me realize that a branch is really a separate version of the project, not a directory.

### 4. If you rebuilt this activity from scratch tomorrow, what would you do differently?
I would create my branch first and run `git branch` and `git status` before I touch any files. I spent extra time checking whether I was on `main` or `het-notes`, so next time I would verify that first and then start working.

## Peer Feedback & Reflection

### 5. Describe one specific contribution from your teammate that you found genuinely helpful, and why.
My teammate created the GitHub repository and added me as a collaborator, which made the setup easier for me. Once I accepted it and cloned the repo, I could focus on making my branch and doing my part of the work.

### 6. Share one piece of constructive feedback that could help your teammate collaborate even more effectively next time.
I think next time we should agree on our branch names, file names, and who is doing each part before we start. That would make the workflow less confusing and also reduce the chance of us changing the same file at the same time.

### 7. What is one thing you learned from watching how your teammate approached a problem?
I learned that setting up the shared repository correctly before doing any coding actually matters a lot. Once the repo, collaborator access, and branches were set up correctly, everything else became much easier to manage.

### 8. How did the two of you resolve any disagreements or merge conflicts, and what would you try differently next time?
We did not have a major merge conflict because we were mostly working on separate branches. Next time I would still pull the newest `main` before starting and communicate before merging so we do not accidentally create a conflict.