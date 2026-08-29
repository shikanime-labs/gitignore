<!-- owner: shikanime | zone: internal | purpose: contribution and release flow -->

# Runbook

## Contribute

1. Fork or branch from `main`.
2. Edit/add a `<Tool>.gitignore`.
3. Open a pull request; one template per PR keeps review trivial.

## Release

There is no packaged release. Templates are consumed directly from the
repository by other shikanime repos that reference them. No CI publish step
exists.

## Branch protection

- 1 approving review, linear history, signed commits, squash+rebase only
  (consistent with the other shikanime-labs repos).
