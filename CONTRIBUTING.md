# Contributing

We encourage community contributions to this repository. Feel free to open an issue or provide a pull request.

This repository is a fork of the ROS 2 port of Cartographer. A fix that is not specific to Duatic's use
is also worth contributing upstream (see the [README](./README.md)).

## Licensing

Any contribution to this repository will be under the [Apache License 2.0](./LICENSE), as stated in its
section 5 (Submission of Contributions).

## Pull requests

The pull request title must follow [Conventional Commits](https://www.conventionalcommits.org/), for
example `fix(mapping): handle empty range data`. Pull requests are squash-merged, so the title becomes
the commit message.

Please keep changes to upstream code minimal and in the existing style. Avoid reformatting lines you do
not otherwise change, so that upstream fixes keep merging cleanly.

## Tooling

Please make sure for any pull request that it passes the `pre-commit` checks.
