# The records this agent must leave

This is the contract. The agent leaves the following behind, on
every run.

- the prettier command run for the task, word for word, with its exit code — at `*/commands.txt`
- every file delivered, listed in pieces.json in the job folder

An agent that leaves less than this does not do this job,
whatever else it does well.
