
## On Windows

This kitchen runs on Windows, where two things above don't. `tc` is a bash tool, so there is no `--slot`: give a cook that writes code its own checkout with `git worktree add <dir> -b <kitchen>/<cook>` in the repo, and hire it with `--project <dir>`. `kitchen restart sous` isn't on Windows yet: once a new channel's credential is in place, ask the head chef to end this session with `/exit` and run `kitchen open --resume` in its pane.
