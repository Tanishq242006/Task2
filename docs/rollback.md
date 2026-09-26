# Git Rollback Strategy

## Purpose

Git history allows previous versions of project files to be
reviewed and recovered when an unwanted change occurs.

## Rollback Process

1. Identify the required commit from Git history.
2. Review the changes in that commit.
3. Revert the unwanted change.
4. Test the restored version.
5. Commit and document the rollback.

## Useful Git Commands

git log --oneline

git show <commit-id>

git revert <commit-id>

git status

## Rollback Example

The rollback demonstration file was modified from Version 1
to Version 2. Git history preserves the previous Version 1,
allowing the earlier state to be reviewed and recovered.

## Benefit

Git rollback provides a safe recovery mechanism while
preserving the project's complete history.
