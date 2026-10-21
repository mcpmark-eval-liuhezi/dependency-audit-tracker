# Dependency audit tracker

Quarterly tracker for the dependency and security advisory review.

Scope: npm lodash, pip requests

## How this tracker works

Each quarterly review pulls critical and high severity advisories from
GitHub's security advisory database for the packages in scope. Qualifying
advisories are filed as sub-issues under the parent audit issue for this
review cycle.

## CI

A minimal workflow runs on every push as a smoke check that the repository
and its tooling are reachable. CI logs are not retained on tracker
repositories.
