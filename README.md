# actions

Currently:

- PRs get a [Danger JS run](https://github.com/orta/actions/blob/master/.github/danger-js.workflow)
- Get danger-swift working (kinda blocked on danger-js work, but the whole swift/process stuff works)
- Issue comments can trigger adding the label "merge on green" - [src](https://github.com/artsy/peril-settings/blob/master/org/markAsMergeOnGreen.ts)

- On a green status, merge if the label applies - [src](https://github.com/artsy/peril-settings/blob/master/org/mergeOnGreen.ts)

Does not work:

- Syncing workflows across many repos by sending PRs (no access to write to other repos)
