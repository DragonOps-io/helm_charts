# How to release a new chart version
1. Update the `Chart.yaml` file with the new version.
2. Commit and push to main branch (a git hook will run to upgrade the version).
3. Update proto templates to reference the new version.
