# SpecMetrics

## What is it for

SpecMetrics is a set of tools to help your team managing a growing test suite by providing analytics, metrics and other data-driven features around your test suite.

## Use cases

### Profiling

| Identifier | Description | Status |
| --- | --- | --- |
| #1 | Have an overview of the time spent in different spec directories (controllers, models...) | [Prototype](https://github.com/jobteaser/spec_metrics_dashboard)
| #2 | Drill down into spec profiling data to identify slow tests and possible causes (number of requests, SQL calls...) | [Prototype](https://github.com/jobteaser/spec_metrics_dashboard)
| #3 | Identifying recurring failing examples | [Prototype](https://github.com/jobteaser/spec_metrics_profiling_analysis) |
| #4 | Identify intersection of examples present before randomly failing examples | [Prototype](https://github.com/jobteaser/spec_metrics_profiling_analysis) |
| #5 | In-depth monitoring of tests duration over time | TODO |

### Coverage

| Identifier | Description | Status |
| --- | --- | --- |
| #1 | Regarding my current diff, which tests should I run? | [WIP](https://github.com/jobteaser/spec_metrics_coverage_analysis) |
| #2 | Given a feature test, can we estimate the feature complexity? | TODO |
| #3 | Dynamic visualization of code executed when running a specific test | TODO


## Status

SpecMetrics is currently under active development. It's still a prototype and should not be considered usable. Not all necessary components have been published yet.

It's currently being developed by JobTeaser Tech team, if you want to discuss about SpecMetrics, contact us [on Twitter](https://twitter.com/JobTeaserTech).

## Links

- [Introduction Article](https://medium.com/jobteaser-dev-team/introducing-specmetrics-1d6e61f67f13): introduces SpecMetrics (the profiling part)
- [SpecMetrics Dashboard](https://github.com/jobteaser/spec_metrics_dashboard): provides basic dashboard with analytics on the test suite.

## About this repo

This repo doesn't contain any code and is only the "parent" repository linking to the components of SpecMetrics's tools.
