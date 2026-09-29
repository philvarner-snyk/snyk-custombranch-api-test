# Branch fingerprint: main (default branch)

This file exists so a human can tell at a glance which branch they are looking at.

The machine-readable fingerprint is the manifest layout. Each branch carries a
manifest in a directory that exists on that branch only:

| branch                | unique manifest path          |
| --------------------- | ----------------------------- |
| `main` (default)      | `main-only/requirements.txt`  |
| `custombranch-test`   | `branch-only/requirements.txt`|

A Snyk import therefore reveals which branch it actually read, regardless of what
branch metadata the API reports back.
