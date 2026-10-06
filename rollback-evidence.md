# Rollback Evidence

## Purpose

This document records the rollback procedure for the Social Engineering Awareness project.

## Rollback Scenario

If an incorrect or unwanted change is committed to the repository, the project can be restored to a previous working version using Git history.

## Rollback Procedure

1. Open the GitHub repository.
2. Open the **Commits** section.
3. Identify the last known working commit.
4. Review the commit to confirm that it contains the correct project files.
5. Restore the repository to the required previous version using Git.
6. Verify that all project files are available and correct after the rollback.

## Evidence

The GitHub commit history provides a record of changes made to the project.

Each commit contains:

- Commit message
- Commit date
- Changed files
- Previous version reference

This commit history can be used to identify and verify the version that should be restored.

## Rollback Verification

After a rollback, verify the following files:

- `README.md`
- `social-engineering-awareness-guide.md`
- `deployment.md`
- `rollback-evidence.md`

The repository should contain the correct and expected version of the project after rollback.
