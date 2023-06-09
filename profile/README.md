# Welcome to the _Open Portfolio Project_!

The _Open Portfolio Project_ is part of the [_OpenAlloc_](https://github.com/openalloc/) family of applications and re-useable libraries.

## Portfolio App Project

Apps for rebalancing a portfolio and tracking its value over time, for macOS.

These are available on the App Store as **free** downloads for macOS.

They are formerly proprietary applications now fully open-sourced as of August 2022. 

### Flow Allocator

A portfolio rebalancing tool.

* [Flow Allocator](https://open-portfolio.github.io/allocator/) - product website
* [Flow Allocator Project](https://github.com/open-portfolio/FlowAllocatorApp/) - Github site for the development project, including full source code

### Flow Worth

A tool for tracking the value and performance of a portfolio over time.

* [Flow Worth](https://open-portfolio.github.io/worth/) - product website
* [Flow Worth Project](https://github.com/open-portfolio/FlowWorthApp/) - Github site for the development project, including full source code

## Libraries

Swift libraries written principally to support the apps above, available as Swift Packages.

### Application Dependencies

* [FlowUI](https://github.com/open-portfolio/FlowUI) - shared UI support for the apps
* [FlowAllocHigh](https://github.com/open-portfolio/FlowAllocHigh) - high-level support for the _Flow Allocator_ app
* [FlowAllocLow](https://github.com/open-portfolio/FlowAllocLow) - low-level support for the _Flow Allocator_ app
* [FlowWorthLib](https://github.com/open-portfolio/FlowWorthLib) - support for the _Flow Worth_ app
* [FlowBase](https://github.com/open-portfolio/FlowBase) - shared support for the apps
* [FlowStats](https://github.com/open-portfolio/FlowStats) - shared stats support for the apps
* [FlowViz](https://github.com/open-portfolio/FlowViz) - shared visualization components for the apps
* [FlowXCT](https://github.com/open-portfolio/FlowXCT) - shared testing components for the apps

### Financial data import

The libraries which focus on importing financial data, such as exports from specific brokerages, are available independently for re-use.

* [AllocData](https://github.com/open-portfolio/AllocData) - standardized data formats for investing-focused apps and tools
* [FINporter](https://github.com/open-portfolio/FINporter) - library and command-line tool to transform various specialized finance-related formats to the standardized schema of AllocData

The rest of the _FINporter_ dependencies:

* [FINporterCLI](https://github.com/open-portfolio/FINporterCLI) - the command-line interface (CLI) incorporating supported importers
* [FINporterChuck](https://github.com/open-portfolio/FINporterChuck) - importers for the Schwab brokerage
* [FINporterFido](https://github.com/open-portfolio/FINporterFido) - importers for the Fidelity brokerage
* [FINporterAllocSmart](https://github.com/open-portfolio/FINporterAllocSmart) - importer for the Allocate Smartly service
* [FINporterTabular](https://github.com/open-portfolio/FINporterTabular) - importer for transforming the AllocData schema

## Your Participation is Essential

As an open source project, we depend on our community of users (and eventually developers) for support.

**The most important thing you can do now is to rate and review the apps in the App Store. Preferably favorably! :)**

(This will help to broaden the base of users, to find bugs and improve the apps.)

Future portfolio apps to add to the family are certainly possible, should good ideas emerge.

To report a bug or suggest a feature, add an Issue to the relevant Github project.

## XCode Setup

See the [Workspace](https://github.com/open-portfolio/Workspace) repository for a handy Xcode workspace that contains most of the repositories.

## See also

### OpenAlloc Libraries

Re-useable Swift libraries for multiple platforms.

* [_OpenAlloc Libraries_](https://openalloc.github.io/) - _OpenAlloc Libraries_ product website
* [_OpenAlloc Libraries_ Project](https://github.com/openalloc/) - Github site for the development project, including full source code

### Open Trackers

Fitness, nutrition, and productivity apps for iPhone, iPad, and Apple Watch.

* [_Open Trackers_](https://open-trackers.github.io/) - _Open Trackers_ product website
* [_Open Trackers_ Project](https://github.com/open-trackers/) - Github site for the development project, including full source code

### Open Portfolio

Investing apps for macOS.

* [_Open Portfolio_](https://open-portfolio.github.io/) - _Open Portfolio_ product website
* [_Open Portfolio_ Project](https://github.com/open-portfolio/) - Github site for the development project, including full source code

## License

Copyright 2021, 2022, 2023 OpenAlloc LLC

All application code is licensed under the [Mozilla Public License 2](https://www.mozilla.org/en-US/MPL/2.0/), except where noted in individual modules.

Re-useable library code may be under the [MPL-2.0](https://www.mozilla.org/en-US/MPL/2.0/) or the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0), except where noted in individual modules.

Copyright is held by [@reedes](https://github.com/reedes)’s OpenAlloc LLC, except where noted in individual modules.

## Contributing

Contributions are welcome. You are encouraged to submit pull requests to fix bugs, improve documentation, or offer new features. 

The pull request need not be a production-ready feature or fix. It can be a draft of proposed changes, or simply a test to show that expected behavior is buggy. Discussion on the pull request can proceed from there.

Contributions should ultimately have adequate test coverage. See tests for current entities to see what coverage is expected.

Your contributions can be under the your name or organization, but must have a compatible license, preferably MPL-2.0 (for app code) or Apache-2.0 (for re-usable library code).

(This should probably be expanded to a proper policy.)

