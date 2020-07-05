# Changelog

All notable changes to this project will be documented in this file
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.0] - YYYY-MM-DD
### Added


[unreleased]: https://github.com/olivierlacan/keep-a-changelog/compare/v1.1.0...HEAD
[0.2.0]: https://github.com/olivierlacan/keep-a-changelog/compare/v1.0.0...v1.1.0
[0.1.0]: https://github.com/olivierlacan/keep-a-changelog/compare/v0.3.0...v1.0.0


### Usage Guide
`Unreleased` Section 
- located at the very top
- lets people see what changes they might expect in upcoming release

Releases are marked by version number and release date 
Each release has a link to the specific version for easy reference and use


#### Types of changes to document are:
- `Added` for new features.
- `Changed` for changes in existing functionality.
- `Deprecated` for soon-to-be removed features.
- `Removed` for now removed features.
- `Fixed` for any bug fixes.
- `Security` in case of vulnerabilities.

#### Guiding Principles
- Changelogs are for humans, not machines.
- There should be an entry for every single version.
- The same types of changes should be grouped.
- Versions and sections should be linkable.
- The latest version comes first.
- The release date of each version is displayed.
- Dates are formatted as YYYY-MM-DD following the [ISO standard](https://www.iso.org/iso-8601-date-and-time-format.html).
- Use semantic versioning to clearly communicate breaking changes.

### Semantic Versioning 
Project versions are numbered as MAJOR.MINOR.PATCH, e.g., 1.0.0, 0.12.1, or 0.2.5
1. MAJOR version when you make incompatible changes,
2. MINOR version when you add functionality in a backwards compatible manner, and
3. PATCH version when you make backwards compatible bug fixes.

#### Implementing Semantic Versioning
- For the initial release start at 0.1.0 and then increment the minor version for each subsequent release.
- Once your project is being used in production or has many users depending on it, you should be 1.0.0. 
- As soon as you realize that you’ve broken the Semantic Versioning spec by releasing a backwards incompatible change, retract teh version, fix the problem, and release a new minor version that corrects the problem and restores backwards compatibility. Even under this circumstance, it is unacceptable to modify versioned releases. If it’s appropriate, document the offending version and inform your users of the problem so that they are aware of the offending version.  

