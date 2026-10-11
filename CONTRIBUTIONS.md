# Open-source contributions

A record of my work on open-source projects, newest first within each section.

## [zigflow/zigflow](https://github.com/zigflow/zigflow)

Declarative YAML workflows on Temporal. **Maintainer since October 2026.**

### Pull requests

| PR | Merged | Change | Fixes |
|---|---|---|---|
| [#623](https://github.com/zigflow/zigflow/pull/623) | 2026-10-11 | Bumped `golang.org/x/net` to v0.60.0 for CVE-2026-78669. This unblocked the image scan that had failed `main` and every open PR since 2026-10-10. | |
| [#622](https://github.com/zigflow/zigflow/pull/622) | 2026-10-11 | Resolve the temp-dir symlink in the working-directory test, so it passes on macOS. | |
| [#615](https://github.com/zigflow/zigflow/pull/615) | 2026-10-08 | Resolve activity inputs in the workflow before scheduling. | [#462](https://github.com/zigflow/zigflow/issues/462) |
| [#609](https://github.com/zigflow/zigflow/pull/609) | 2026-09-30 | Pass `run.workflow.input` to the child workflow. | [#608](https://github.com/zigflow/zigflow/issues/608) |
| [#592](https://github.com/zigflow/zigflow/pull/592) | 2026-09-22 | The validator warns about nested `do` tasks mixed with executable tasks. | [#585](https://github.com/zigflow/zigflow/issues/585) |
| [#591](https://github.com/zigflow/zigflow/pull/591) | 2026-09-18 | A fork waits for its branches to be cancelled before it returns. | [#587](https://github.com/zigflow/zigflow/issues/587) (with #588) |
| [#586](https://github.com/zigflow/zigflow/pull/586) | 2026-09-17 | A `listen` timeout is reported as the Zigflow timeout error. | |
| [#574](https://github.com/zigflow/zigflow/pull/574) | 2026-09-10 | `call: http` encodes the request body for the declared `Content-Type`. | |
| [#568](https://github.com/zigflow/zigflow/pull/568) | 2026-09-08 | `LogWriter.Write` honours the `io.Writer` contract. | |

### Issues reported

| Issue | Opened | Outcome |
|---|---|---|
| [#608](https://github.com/zigflow/zigflow/issues/608) | 2026-09-29 | `run.workflow.input` was ignored. Fixed by #609. |
| [#587](https://github.com/zigflow/zigflow/issues/587) | 2026-09-17 | Cancelling a workflow did not stop it. Fixed by #588 and #591. |
| [#493](https://github.com/zigflow/zigflow/issues/493) | 2026-06-21 | Sibling `do` task dropped after a `for` task. Closed as not planned. |

### Design discussions

| Issue | Contribution |
|---|---|
| [#525](https://github.com/zigflow/zigflow/issues/525) | `for`/`try` as inline execution: agreed to drop workflow-versioning gates in favour of a breaking-change policy. |
| [#491](https://github.com/zigflow/zigflow/issues/491) | `document.dsl` holds the Zigflow DSL version; validation lands with v1. |
| [#462](https://github.com/zigflow/zigflow/issues/462) | Design for resolving activity inputs in the workflow, implemented in #615. |
| [#585](https://github.com/zigflow/zigflow/issues/585) | Validator rule for nested `do` definitions, implemented in #592. |
