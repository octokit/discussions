# Octokit Requirements

> Provide a first class experience for platform developers in their preferred programming languages

Octokit strives to offer complete and officially supported SDKs, quick starts, code samples, and copy/paste-able examples for the GitHub Platform in the most popular languages.

Each Octokit will work towards meeting these requirements:

|                                 | JavaScript | Ruby | .NET |
| ------------------------------- | ---------- | ---- | ---- |
| [Complete](#complete)           | 🌔         | 🌔   | 🌔   |
| → REST                          | ✅         | ✅   | ✅   |
| → GraphQL                       | 🌑         | 🌑   | 🌑   |
| → GitHub Apps                   | 🌑         | 🌑   | 🌑   |
| → OAuth                         | 🌑         | 🌑   | 🌑   |
| → Webhooks                      | 🌑         | 🌑   | 🌑   |
| [Decomposable](#decomposable)   | 🌑         | 🌑   | 🌑   |
| [Generated](#generated)         | 🌑         | 🌑   | 🌑   |
| [Native](#native)               | 🌑         | 🌑   | 🌑   |
| [Documented](#documented)       | 🌑         | 🌑   | 🌑   |
| [Tested](#tested)               | 🌑         | 🌑   | 🌑   |
| [Friendly](#friendly)           | 🌑         | 🌑   | 🌑   |
| [Prescriptive](#prescriptive)   | 🌑         | 🌑   | 🌑   |
| [Supported](#supported)         | 🌑         | 🌑   | 🌑   |
| [Maintained](#maintained)       | 🌑         | 🌑   | 🌑   |
| [Collaborative](#collaborative) | 🌑         | 🌑   | 🌑   |

Key: 🌑 Not started — 🌔 In progress —  ✅ Meets requirements

## Complete

The SDK includes support for all platform features:

- REST - by offering a generic HTTP request library and a wrapper method for each endpoint
- GraphQL - by offering a generic GraphQL client that is pre-configured and optimized for GitHub
- GitHub Apps - by implementing all REST endpoints for GitHub Apps as well as JWT authentication
- OAuth - by offering middleware in the most popular web framework for performing the OAuth exchange
- Webhooks - by offering middleware in the most popular web framework for validating webhooks

## Decomposable

Each feature is available both as individual packages and one monolithic meta-package that includes all components pre-wired.

## Generated

Any part of the SDK that varies based on the target GitHub instance should be generated from a common schema.

This currently applies to the REST API, webhooks, and any GraphQL wrappers.

## Native

The SDK feels native to the language or platform it is designed for. This includes using native idioms, and following patterns used in other popular SDK libraries for that language.

## Documented

The SDK is uniformly documented, including generated API reference documentation, and getting started guides for using every platform feature.

## Tested

The SDK is well-tested, including thorough unit tests with 100% code coverage and a shared integration test suite that includes VCR-style fixtures.

It is easy to write well-tested applications that use the SDKs.

## Friendly

The SDK anticipates most common issues, gives friendly errors, and points users to help documentation when they run into issues.

## Prescriptive

The SDK follows best practices, such as handling throttling and rate limiting. Where possible, the SDK transparently implements these best practices.

## Supported

New features are supported in a stable release of the SDK at the time of the feature being released.

Developers will receive code-level technical support on client libraries from GitHub.

## Maintained

The SDK is open source, has a community maintainer on contract, and a GitHub employee to oversee the work.

GitHub will:

- Provide advance notice to maintainers for all platform improvements and features (at least 1 week notice for incremental improvements, at least 4 weeks notice for all major features)
- Invite maintainers to any relevant events hosted by GitHub

The community maintainer is expected to:

- Help maintain an Octokit SDK that strives to meet all the requirements
- Acknowledge all opened Issues and Pull Requests within 72 hours
- Implement support for all improvements and new features by launch day
- Let your GitHub buddy know when you are going to be unavailable so they can take over your duties.
- Be a classy representative of GitHub

The GitHub employee is expected to:

- Respond to any requests for review or feedback from the community maintainer
- Raise any concerns or issues with the client or maintainer

## Collaborative

The SDK shares as many resources and tools as possible with other SDKs, such as [routes](https://github.com/octokit/routes), [fixtures](https://github.com/octokit/fixtures), and release tooling.


The maintainer has access to GitHub's ecosystem and documentation teams, there is a process for communicating new APIs, and opportunities to give feedback on unreleased features.
