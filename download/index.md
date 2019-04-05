---
layout: archive
title: ""
date:
modified:
excerpt:
image:
  feature:
  teaser:
  thumb:
ads: false
---

## Download and installation
To download the Flypitch project, use any of the releases listed at the [project repository](https://github.com/flypitch/flypitch). To compile the Flypitch project, you will need [Lean 3.4.2](https://leanprover.github.io/download/). Installation instructions for Lean (using `elan`) can be found [here](https://github.com/leanprover-community/mathlib/blob/master/docs/elan.md).

### Building the project
After cloning the repository to `flypitch`, navigate to `flypitch` and run

	leanpkg configure
	leanpkg build

The `leanpkg.toml` file points to a certain commit of `mathlib`,[^1] which, during the build, will be cloned into the project directory.

## Viewing the project
To view the project, we recommend the use of a Lean-aware editor like [Emacs](https://github.com/leanprover/lean-mode) or [VSCode](https://github.com/leanprover/vscode-lean). Among other things, like typing information, such editors can display the _proof state_ inside a tactic block, making it easier to understand how theorems are being proved.

## Navigating the project

A summary of the main results can be found in `/src/summary.lean`, containing `#print` statements of important definitions and duplicated proofs of the main theorems. From there, one may use their editor's jump-to-definition feature to trace the dependencies of the definitions and proofs. A more detailed summary can be found at the [project repository](https://github.com/flypitch/flypitch).

[^1]: `mathlib` is Lean's community-maintained [mathematical components library](https://github.com/leanprover-community/mathlib/)
