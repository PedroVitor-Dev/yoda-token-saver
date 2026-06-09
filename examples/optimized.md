# Optimized Response Example

## User request

Explain how to fix a Git push rejected error.

## Optimized response

Remote has commits you do not have.

Run:

```bash
git pull --rebase origin main
git push origin main
```

If conflicts appear, fix them, commit, then push again.

## Token efficiency note

This response keeps the meaning while removing unnecessary explanation.
