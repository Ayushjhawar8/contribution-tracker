# contribution-tracker

Generates weekly contribution overviews for tscircuit contributors. Check out all
the [contribution overviews here](./contribution-overviews/)

* All PRs in the tscircuit org are scanned/summarized via Claude Haiku
* Claude classifies each Diff/PR as a Major, Minor or Tiny contribution
* All the PRs, summaries, and classifications are organized into charts and tables

The current week is shown below. There are 3 major sections:

* [Contributor Overview](#contributor-overview)
* [PRs by Repository](#prs-by-repository)
* [PRs by Contributor](#changes-by-contributor)

## Current Week

<!-- START_CURRENT_WEEK -->

# Contribution Overview 2025-04-16

## PRs by Repository

```mermaid
pie
    "tscircuit/3d-viewer" : 3
    "tscircuit/core" : 4
    "tscircuit/schematic-viewer" : 3
    "tscircuit/pcb-viewer" : 3
    "tscircuit/circuit-json-util" : 1
    "tscircuit/circuit-json-to-gerber" : 1
    "tscircuit/tscircuit.com" : 6
    "tscircuit/circuit-json" : 1
    "tscircuit/props" : 1
    "tscircuit/contribution-tracker" : 1
    "tscircuit/runframe" : 1
    "tscircuit/cli" : 3
    "tscircuit/eval" : 1
```

## Contributor Overview

| Contributor | 🐳 Major | 🐙 Minor | 🐌 Tiny | ⭐ | Issues Created | Discussion Contributions |
|-------------|---------|---------|---------|-----|----------------|--------------------------|
| [seveibar](#seveibar) | 2 | 8 | 1 | ⭐⭐⭐ | 11 | 0🔹 0🔶 0💎 |
| [imrishabh18](#imrishabh18) | 1 | 4 | 0 | ⭐⭐ | 3 | 0🔹 0🔶 0💎 |
| [Abse2001](#Abse2001) | 2 | 3 | 0 | ⭐⭐ | 1 | 0🔹 0🔶 0💎 |
| [ArnavK-09](#ArnavK-09) | 1 | 5 | 0 | ⭐⭐ | 3 | 0🔹 0🔶 0💎 |
| [MustafaMulla29](#MustafaMulla29) | 0 | 1 | 0 | ⭐ | 1 | 0🔹 0🔶 0💎 |
| [tscircuitbot](#tscircuitbot) | 0 | 0 | 1 |  | 0 | 0🔹 0🔶 0💎 |

### Discussion Contribution Legend

- 🔹 Participating: Basic participation with minimal effort
- 🔶 Very Active: Thoughtful participation that adds value
- 💎 Extremely Active: Exceptional participation with high-quality content

## Review Table

[reviews-received-hover]: ## "Number of reviews received for PRs for this contributor"
[approvals-received-hover]: ## "Number of approvals received for PRs this contributor authored"
[rejections-received-hover]: ## "Number of rejections received for PRs this contributor authored"
[prs-opened-hover]: ## "Number of PRs opened by this contributor"
[issues-created-hover]: ## "Number of issues created by this contributor"
[bountied-issues-hover]: ## "Number of issues this contributor created with a bounty"
[bountied-issue-$-hover]: ## "Total bounty amount placed on issues authored by this contributor"

| Contributor | Reviews Received | Approvals Received | Rejections Received | Approvals | Rejections | PRs Opened | PRs Merged | Issues Created | Bountied Issues | Bountied Issue $ |
|---|---|---|---|---|---|---|---|---|---|---|
| [seveibar](#seveibar) | 2 | 1 | 0 | 14 | 4 | 16 | 11 | 11 | 8 | 178 |
| [imrishabh18](#imrishabh18) | 4 | 2 | 0 | 1 | 0 | 5 | 5 | 3 | 2 | 90 |
| [MustafaMulla29](#MustafaMulla29) | 3 | 1 | 2 | 0 | 1 | 3 | 1 | 1 | 1 | 5 |
| [Abse2001](#Abse2001) | 12 | 5 | 2 | 1 | 0 | 6 | 5 | 1 | 1 | 20 |
| [graphite-app[bot]](#graphite-app[bot]) | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| [ArnavK-09](#ArnavK-09) | 8 | 7 | 0 | 0 | 0 | 7 | 6 | 3 | 1 | 5 |
| [CodeMan62](#CodeMan62) | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 0 |
| [tscircuitbot](#tscircuitbot) | 0 | 0 | 0 | 0 | 0 | 8 | 1 | 0 | 0 | 0 |
| [yashksaini-coder](#yashksaini-coder) | 1 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 0 | 0 |

## Changes by Repository

### [tscircuit/3d-viewer](https://github.com/tscircuit/3d-viewer)

| PR # | Impact | Contributor | Description | Milestone Aligned |
|------|--------|-------------|-------------|-------------------|
| [#245](https://github.com/tscircuit/3d-viewer/pull/245) | 🐳 Major | seveibar | Introduces major performance improvements, fixes for board centering, trace drawings, and tooltip slowdown. | ✅ |
| [#252](https://github.com/tscircuit/3d-viewer/pull/252) | 🐳 Major | Abse2001 | Adds support for silkscreen text on the bottom layer and updates the text positioning and rotation behavior to match PCB-like behavior. | ✅ |
| [#251](https://github.com/tscircuit/3d-viewer/pull/251) | 🐳 Major | Abse2001 | Adds support for different board materials (FR1 and FR4) with corresponding color customization. | ✅ |

### [tscircuit/core](https://github.com/tscircuit/core)

| PR # | Impact | Contributor | Description | Milestone Aligned |
|------|--------|-------------|-------------|-------------------|
| [#747](https://github.com/tscircuit/core/pull/747) | 🐳 Major | seveibar | Use css-select for faster selectOne and selectAll queries, and cache the results to improve overall render times. | ✅ |
| [#741](https://github.com/tscircuit/core/pull/741) | 🐙 Minor | seveibar | The pull request updates the `@tscircuit/circuit-json-util` package to remove the dependency on `@tscircuit/soup-util`. | ✅ |
| [#739](https://github.com/tscircuit/core/pull/739) | 🐙 Minor | seveibar | Update checks and circuit JSON to connectivity net, a speculative fix for spurious DRC errors | ✅ |
| [#746](https://github.com/tscircuit/core/pull/746) | 🐙 Minor | Abse2001 | Adds a new "material" property to the Board component | ✅ |

### [tscircuit/schematic-viewer](https://github.com/tscircuit/schematic-viewer)

| PR # | Impact | Contributor | Description | Milestone Aligned |
|------|--------|-------------|-------------|-------------------|
| [#83](https://github.com/tscircuit/schematic-viewer/pull/83) | 🐙 Minor | seveibar | Revert a previous revert of the fix to update the center of a schematic component as per the last position. | ✅ |
| [#82](https://github.com/tscircuit/schematic-viewer/pull/82) | 🐙 Minor | imrishabh18 | Reverts a previous commit that fixed a bug in the schematic viewer. | ❌ |
| [#81](https://github.com/tscircuit/schematic-viewer/pull/81) | 🐙 Minor | imrishabh18 | Update the center position of a schematic component based on the last drag event | ❌ |

### [tscircuit/pcb-viewer](https://github.com/tscircuit/pcb-viewer)

| PR # | Impact | Contributor | Description | Milestone Aligned |
|------|--------|-------------|-------------|-------------------|
| [#235](https://github.com/tscircuit/pcb-viewer/pull/235) | 🐙 Minor | seveibar | Patch a regression in the `use-mouse-matrix` library, which broke the mouse pan functionality. | ❌ |
| [#231](https://github.com/tscircuit/pcb-viewer/pull/231) | 🐙 Minor | seveibar | Adding the `editCount` property to the `circuitJsonKey` to uniquely identify the circuit. | ✅ |
| [#234](https://github.com/tscircuit/pcb-viewer/pull/234) | 🐌 Tiny | seveibar | Update the version of the "use-mouse-matrix-transform" dependency to 1.3.3. | ✅ |

### [tscircuit/circuit-json-util](https://github.com/tscircuit/circuit-json-util)

| PR # | Impact | Contributor | Description | Milestone Aligned |
|------|--------|-------------|-------------|-------------------|
| [#31](https://github.com/tscircuit/circuit-json-util/pull/31) | 🐙 Minor | seveibar | Adds support for editCount on cju objects to enable smarter keying downstream | ✅ |

### [tscircuit/circuit-json-to-gerber](https://github.com/tscircuit/circuit-json-to-gerber)

| PR # | Impact | Contributor | Description | Milestone Aligned |
|------|--------|-------------|-------------|-------------------|
| [#28](https://github.com/tscircuit/circuit-json-to-gerber/pull/28) | 🐙 Minor | seveibar | Fix unsupported shape "rotated_rect" in the Gerber file generation. | ✅ |

### [tscircuit/tscircuit.com](https://github.com/tscircuit/tscircuit.com)

| PR # | Impact | Contributor | Description | Milestone Aligned |
|------|--------|-------------|-------------|-------------------|
| [#860](https://github.com/tscircuit/tscircuit.com/pull/860) | 🐳 Major | imrishabh18 | The pull request adds a fake endpoint for `order_quotes` that allows creating, retrieving, and creating all vendor quotes for a package release. | ❌ |
| [#865](https://github.com/tscircuit/tscircuit.com/pull/865) | 🐙 Minor | seveibar | Update the `circuit-json-to-gerber` dependency to fix issues with rotated rectangles. | ✅ |
| [#864](https://github.com/tscircuit/tscircuit.com/pull/864) | 🐙 Minor | imrishabh18 | Rename the "order_quote" directory to "order_quotes" | ✅ |
| [#859](https://github.com/tscircuit/tscircuit.com/pull/859) | 🐙 Minor | imrishabh18 | Fix the image preview in the package page. | ✅ |
| [#862](https://github.com/tscircuit/tscircuit.com/pull/862) | 🐙 Minor | ArnavK-09 | Fixes an error that occurs when trying to fork one's own package. | ✅ |
| [#861](https://github.com/tscircuit/tscircuit.com/pull/861) | 🐙 Minor | ArnavK-09 | Improve responsiveness and styling of the package header and code viewer components | ❌ |

### [tscircuit/circuit-json](https://github.com/tscircuit/circuit-json)

| PR # | Impact | Contributor | Description | Milestone Aligned |
|------|--------|-------------|-------------|-------------------|
| [#166](https://github.com/tscircuit/circuit-json/pull/166) | 🐙 Minor | Abse2001 | Added a new `material` field to the `PcbBoard` type, allowing users to specify the material of the PCB board as either "fr4" or "fr1". | ✅ |

### [tscircuit/props](https://github.com/tscircuit/props)

| PR # | Impact | Contributor | Description | Milestone Aligned |
|------|--------|-------------|-------------|-------------------|
| [#210](https://github.com/tscircuit/props/pull/210) | 🐙 Minor | Abse2001 | Added a new `material` prop to the `board` component with `fr4` as the default and `fr1` as an optional value. | ✅ |

### [tscircuit/contribution-tracker](https://github.com/tscircuit/contribution-tracker)

| PR # | Impact | Contributor | Description | Milestone Aligned |
|------|--------|-------------|-------------|-------------------|
| [#122](https://github.com/tscircuit/contribution-tracker/pull/122) | 🐳 Major | ArnavK-09 | Refactors the PR analysis feature by introducing a new `PrsTable` component to replace the deprecated `PRsByRepository` component, and adds support for fetching and processing PR analysis data, including grouping PRs by repository and contributor. | ✅ |

### [tscircuit/runframe](https://github.com/tscircuit/runframe)

| PR # | Impact | Contributor | Description | Milestone Aligned |
|------|--------|-------------|-------------|-------------------|
| [#473](https://github.com/tscircuit/runframe/pull/473) | 🐙 Minor | ArnavK-09 | Dynamically set the document title based on the package.json name or the guessed entrypoint from the file system map. | ✅ |

### [tscircuit/cli](https://github.com/tscircuit/cli)

| PR # | Impact | Contributor | Description | Milestone Aligned |
|------|--------|-------------|-------------|-------------------|
| [#170](https://github.com/tscircuit/cli/pull/170) | 🐙 Minor | ArnavK-09 | Update dependencies to the latest versions | ✅ |
| [#164](https://github.com/tscircuit/cli/pull/164) | 🐙 Minor | ArnavK-09 | Add a confirmation prompt to the `tsci init` command when no directory is provided. | ✅ |
| [#169](https://github.com/tscircuit/cli/pull/169) | 🐙 Minor | MustafaMulla29 | Fixed the instructions displayed after cloning a project. | ✅ |

### [tscircuit/eval](https://github.com/tscircuit/eval)

| PR # | Impact | Contributor | Description | Milestone Aligned |
|------|--------|-------------|-------------|-------------------|
| [#217](https://github.com/tscircuit/eval/pull/217) | 🐌 Tiny | tscircuitbot | Automated update of @tscircuit/core to v0.0.372. | ✅ |

## Changes by Contributor

### [seveibar](https://github.com/seveibar)

| PR # | Impact | Description | Milestone Aligned |
|------|--------|-------------|-------------------|
| [#245](https://github.com/tscircuit/3d-viewer/pull/245) | 🐳 Major | Introduces major performance improvements, fixes for board centering, trace drawings, and tooltip slowdown. | ✅ |
| [#747](https://github.com/tscircuit/core/pull/747) | 🐳 Major | Use css-select for faster selectOne and selectAll queries, and cache the results to improve overall render times. | ✅ |
| [#83](https://github.com/tscircuit/schematic-viewer/pull/83) | 🐙 Minor | Revert a previous revert of the fix to update the center of a schematic component as per the last position. | ✅ |
| [#235](https://github.com/tscircuit/pcb-viewer/pull/235) | 🐙 Minor | Patch a regression in the `use-mouse-matrix` library, which broke the mouse pan functionality. | ❌ |
| [#231](https://github.com/tscircuit/pcb-viewer/pull/231) | 🐙 Minor | Adding the `editCount` property to the `circuitJsonKey` to uniquely identify the circuit. | ✅ |
| [#31](https://github.com/tscircuit/circuit-json-util/pull/31) | 🐙 Minor | Adds support for editCount on cju objects to enable smarter keying downstream | ✅ |
| [#741](https://github.com/tscircuit/core/pull/741) | 🐙 Minor | The pull request updates the `@tscircuit/circuit-json-util` package to remove the dependency on `@tscircuit/soup-util`. | ✅ |
| [#739](https://github.com/tscircuit/core/pull/739) | 🐙 Minor | Update checks and circuit JSON to connectivity net, a speculative fix for spurious DRC errors | ✅ |
| [#28](https://github.com/tscircuit/circuit-json-to-gerber/pull/28) | 🐙 Minor | Fix unsupported shape "rotated_rect" in the Gerber file generation. | ✅ |
| [#865](https://github.com/tscircuit/tscircuit.com/pull/865) | 🐙 Minor | Update the `circuit-json-to-gerber` dependency to fix issues with rotated rectangles. | ✅ |
| [#234](https://github.com/tscircuit/pcb-viewer/pull/234) | 🐌 Tiny | Update the version of the "use-mouse-matrix-transform" dependency to 1.3.3. | ✅ |

### [imrishabh18](https://github.com/imrishabh18)

| PR # | Impact | Description | Milestone Aligned |
|------|--------|-------------|-------------------|
| [#860](https://github.com/tscircuit/tscircuit.com/pull/860) | 🐳 Major | The pull request adds a fake endpoint for `order_quotes` that allows creating, retrieving, and creating all vendor quotes for a package release. | ❌ |
| [#82](https://github.com/tscircuit/schematic-viewer/pull/82) | 🐙 Minor | Reverts a previous commit that fixed a bug in the schematic viewer. | ❌ |
| [#81](https://github.com/tscircuit/schematic-viewer/pull/81) | 🐙 Minor | Update the center position of a schematic component based on the last drag event | ❌ |
| [#864](https://github.com/tscircuit/tscircuit.com/pull/864) | 🐙 Minor | Rename the "order_quote" directory to "order_quotes" | ✅ |
| [#859](https://github.com/tscircuit/tscircuit.com/pull/859) | 🐙 Minor | Fix the image preview in the package page. | ✅ |

### [Abse2001](https://github.com/Abse2001)

| PR # | Impact | Description | Milestone Aligned |
|------|--------|-------------|-------------------|
| [#252](https://github.com/tscircuit/3d-viewer/pull/252) | 🐳 Major | Adds support for silkscreen text on the bottom layer and updates the text positioning and rotation behavior to match PCB-like behavior. | ✅ |
| [#251](https://github.com/tscircuit/3d-viewer/pull/251) | 🐳 Major | Adds support for different board materials (FR1 and FR4) with corresponding color customization. | ✅ |
| [#166](https://github.com/tscircuit/circuit-json/pull/166) | 🐙 Minor | Added a new `material` field to the `PcbBoard` type, allowing users to specify the material of the PCB board as either "fr4" or "fr1". | ✅ |
| [#210](https://github.com/tscircuit/props/pull/210) | 🐙 Minor | Added a new `material` prop to the `board` component with `fr4` as the default and `fr1` as an optional value. | ✅ |
| [#746](https://github.com/tscircuit/core/pull/746) | 🐙 Minor | Adds a new "material" property to the Board component | ✅ |

### [ArnavK-09](https://github.com/ArnavK-09)

| PR # | Impact | Description | Milestone Aligned |
|------|--------|-------------|-------------------|
| [#122](https://github.com/tscircuit/contribution-tracker/pull/122) | 🐳 Major | Refactors the PR analysis feature by introducing a new `PrsTable` component to replace the deprecated `PRsByRepository` component, and adds support for fetching and processing PR analysis data, including grouping PRs by repository and contributor. | ✅ |
| [#862](https://github.com/tscircuit/tscircuit.com/pull/862) | 🐙 Minor | Fixes an error that occurs when trying to fork one's own package. | ✅ |
| [#861](https://github.com/tscircuit/tscircuit.com/pull/861) | 🐙 Minor | Improve responsiveness and styling of the package header and code viewer components | ❌ |
| [#473](https://github.com/tscircuit/runframe/pull/473) | 🐙 Minor | Dynamically set the document title based on the package.json name or the guessed entrypoint from the file system map. | ✅ |
| [#170](https://github.com/tscircuit/cli/pull/170) | 🐙 Minor | Update dependencies to the latest versions | ✅ |
| [#164](https://github.com/tscircuit/cli/pull/164) | 🐙 Minor | Add a confirmation prompt to the `tsci init` command when no directory is provided. | ✅ |

### [tscircuitbot](https://github.com/tscircuitbot)

| PR # | Impact | Description | Milestone Aligned |
|------|--------|-------------|-------------------|
| [#217](https://github.com/tscircuit/eval/pull/217) | 🐌 Tiny | Automated update of @tscircuit/core to v0.0.372. | ✅ |

### [MustafaMulla29](https://github.com/MustafaMulla29)

| PR # | Impact | Description | Milestone Aligned |
|------|--------|-------------|-------------------|
| [#169](https://github.com/tscircuit/cli/pull/169) | 🐙 Minor | Fixed the instructions displayed after cloning a project. | ✅ |



<!-- END_CURRENT_WEEK -->
