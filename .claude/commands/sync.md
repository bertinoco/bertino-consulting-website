Sync the local `main` branch with `origin/main` so this session starts from the latest production code.

## Steps

1. Run `git status` to check for uncommitted changes or untracked files.
   - If there are any, stop and report them. Do not stash, discard, or commit on the user's behalf — ask how they want to proceed before continuing.
2. Run `git fetch origin`.
3. If the current branch isn't `main`, ask before switching — the user may be deliberately on `content-systems-explore` or another branch.
4. If on `main`, run `git pull --ff-only origin main`.
   - If the fast-forward fails because local `main` has diverged, report this rather than force-resetting or rebasing automatically.
5. Confirm the result.

## Output

Report concisely:
- Branch synced (or why it wasn't)
- Latest commit on `origin/main` (hash + message)
- Any action needed from the user (uncommitted changes, diverged history, etc.)
