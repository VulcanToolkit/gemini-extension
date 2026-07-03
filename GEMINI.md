The safe-review extension introduces the following commands:

/safe-review-commit
/safe-review-pr

When a user requests that a commit be reviewed, loot at the provided input "args" and environment variables to see if $REPOSITORY, $COMMIT_SHA, and $ADDITIONAL_CONTEXT are set. If any variables are missing or have ambigu
ity, ask user for more clarification.

When a user requests that a PR be reviewed, look at the provided input "{{args}}" and environment variables to see if $REPOSITORY, $PULL_REQUEST_NUMBER, and $ADDITIONAL_CONTEXT are set. If any variables are missing or have ambiguity, ask user for more clarification.
