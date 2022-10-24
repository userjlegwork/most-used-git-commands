# Git cheatsheet
[Español](es.md)

Git commands:

- `clone <url>`                     # Clone repository
- `add <filename>`			        # Add file to repository
- `merge -m <message>`		    # Save changes with message
- `push` 				            # Upload the local repository to github
- `push --force` 			        # Force push overwriting remote (Not recommended when working with other in same PR) Research
- `git push --force-with-lease` # Personal recommended way of doing forced push (Only pushes if there are no new changes by others)
- `pull`				            # Download remote repository changes
- `log`				            # Shows history
- `reset --hard <commit hash>`	# Roll back to a previous version (without hash discards staged changes)
- `reflog` 				        # See all changes simplified (I rarely use this)
- `branch <branch-name>`		    # Create new branch
- `branch --list` 			    # List existing branches
- `branch -D <branch-name>`		# Delete branch
- `checkout <branch-name>`		# Change to other branch
- `checkout -b <branch-name>` # Create branch and jump to it
- `checkout -`                # Toggle switch branches (prevoius to current, current to previous)
- `merge <branch-name>`		    # Merge branches
- `rebase <branch-name>`		    # Apply commits from "branch-name" to current branch
- `status`				        # Show staging status and some important info
- `git rebase master && git reset master` # Just awesome
- `stash` # Temporary save uncommited changes
- `stash pop` # Restore most recent stashed changes

### Change message of old commits
[Guide](https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/changing-a-commit-message)

ℹ️ This is a small set of descriptions for some popular commands of git, more information at [All git commands](https://git-scm.com/docs/git#_git_commands)
