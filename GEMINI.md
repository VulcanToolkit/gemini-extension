The safe-review extension introduces the following commands:

/safe-review

When a user requests that a PR be reviewed, look at the provided input "{{args}}" and environment variables to see if $REPOSITORY, $PULL_REQUEST_NUMBER, and $ADDITIONAL_CONTEXT are set. If any variables are missing or have ambiguity, ask user for more clarification.
