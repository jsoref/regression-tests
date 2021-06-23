# Regression Tests

This repository is designed to host regression tests.

## Design Plan

There will be a series of commits that point to a branch, e.g. `HEAD`.

A base commit will be checked out and amended to replace `HEAD` with a specified full sha of the action.

A series of commits will be cherry-picked and pushed on top of that base commit.
