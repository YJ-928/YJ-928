# Open-source contributions

A record of my work on open-source projects. Maintainer of [zigflow/zigflow](https://github.com/zigflow/zigflow) since October 2026.

Generated daily by [upstream-ledger](https://github.com/YJ-928/upstream-ledger).

**9 merged pull requests** across **1 repository**, and **3 issues** reported. Took part in **4 discussions**.

## [zigflow/zigflow](https://github.com/zigflow/zigflow)

### Pull requests

| PR | Status | Title | Fixes |
|---|---|---|---|
| [#623](https://github.com/zigflow/zigflow/pull/623) | Merged 2026-10-11 | fix(deps): bump golang.org/x/net to v0.60.0 for CVE-2026-78669 |  |
| [#622](https://github.com/zigflow/zigflow/pull/622) | Merged 2026-10-11 | test: resolve the temp dir symlink in the working-directory test |  |
| [#615](https://github.com/zigflow/zigflow/pull/615) | Merged 2026-10-08 | fix: resolve activity inputs in the workflow before scheduling | [#462](https://github.com/zigflow/zigflow/issues/462) |
| [#609](https://github.com/zigflow/zigflow/pull/609) | Merged 2026-09-30 | fix(run): pass run.workflow.input to the child workflow | [#608](https://github.com/zigflow/zigflow/issues/608) |
| [#592](https://github.com/zigflow/zigflow/pull/592) | Merged 2026-09-22 | feat(validate): warn about nested do tasks mixed with executable tasks | [#585](https://github.com/zigflow/zigflow/issues/585) |
| [#591](https://github.com/zigflow/zigflow/pull/591) | Merged 2026-09-18 | fix(fork): wait for branches to be cancelled before the fork returns |  |
| [#586](https://github.com/zigflow/zigflow/pull/586) | Merged 2026-09-17 | fix(listen): report a listen timeout as the Zigflow timeout error |  |
| [#574](https://github.com/zigflow/zigflow/pull/574) | Merged 2026-09-10 | fix(http): encode the request body for the declared Content-Type |  |
| [#568](https://github.com/zigflow/zigflow/pull/568) | Merged 2026-09-08 | fix(utils): honour io.Writer contract in LogWriter.Write |  |

### Issues reported

| Issue | Opened | Title | Outcome |
|---|---|---|---|
| [#608](https://github.com/zigflow/zigflow/issues/608) | 2026-09-29 | run.workflow.input is ignored: the child workflow receives the parent's input | Completed 2026-09-30 |
| [#587](https://github.com/zigflow/zigflow/issues/587) | 2026-09-17 | Cancelling a workflow does not stop it: remaining tasks run and it completes | Completed 2026-09-17 |
| [#493](https://github.com/zigflow/zigflow/issues/493) | 2026-06-21 | DoTaskBuilder incorrectly drops sibling DoTask after ForTask causing "next target specified but not found" | Closed as not planned |

### Discussions

| Issue | Title | Status |
|---|---|---|
| [#585](https://github.com/zigflow/zigflow/issues/585) | Validator should flag nested do workflow definitions in mixed task lists | Completed 2026-09-22 |
| [#525](https://github.com/zigflow/zigflow/issues/525) | `for` and `try` blocks compile to child workflows — fan-in read/lock amplification on hot parents at scale | Open |
| [#491](https://github.com/zigflow/zigflow/issues/491) | Enforce `document.dsl` Version Validation | Open |
| [#462](https://github.com/zigflow/zigflow/issues/462) | Activity inputs should be expression-evaluated before scheduling activities | Completed 2026-10-08 |
