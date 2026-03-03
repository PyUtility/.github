<div align = "center">

# Contribution Guidelines
[![Org. Home](https://img.shields.io/badge/-PyUtility-black?logo=github&style=plastic)](https://github.com/PyUtility)

</div>

<div align = "justify">

First and foremost, 🙏 thank you for considering contributing to **`PyUtility`**. We are currently setting up the organization.
Stay tuned for more information! Actively looking for contributors!

## Issues

If you spot a problem with any of the functionalities/documentation, then first
[search if an issue already exists](https://docs.github.com/en/github/searching-for-information-on-github/searching-on-github/searching-issues-and-pull-requests#search-by-the-title-body-or-comments).
If a related issue doesn't exist, you can open a new issue using a relevant [issue form](https://github.com/github/docs/issues/new/choose).

## Pull Request Process

The product/project (repository) for the organization may have additional contributing guidelines. Please refer to the respective repository's README file or contact the administrator
and/or group administrator for more information. The general process is as follows:

1. Ensure any install or build dependencies are removed before the end of the layer when doing a  build.
2. Update the README.md with details of changes to the interface, which includes new environment  variables,
  exposed ports, useful file locations, and container parameters.
3. Increase the version numbers in any example files and the README.md to the new version that this
  Pull Request would represent. The versioning scheme we use eis ither [SemVer](http://semver.org/) or [PEP 440](https://peps.python.org/pep-0440/).
4. You may merge the Pull Request once you have the sign-off of two other developers, or if you 
  do not have permission to do that, you may request the second reviewer to merge it for you.

### Version Styling Guide

All the projects largely follows [`PEP 440`](https://peps.python.org/pep-0440/) versioning style, unless it is an explicit that
the project does not follow the Python programming language; it follows the [`SemVer`](http://semver.org/) versioning. All the
notable changes for a repository also follow any one of the styling guides; check the changelog header for the convention for
each repository; the same is followed in the *"Release Notes"* to publish packages.

<details>
<summary>Click to open <code>PEP 440</code> Styilng Guide</summary>

Packaging for `PyPI` follows the standard PEP0440 styling guide and is implemented by the **`packaging.version.Version`** class. The other
popular versioning scheme is [`semver`](https://semver.org/), but each build has different parts/mapping.
The following table gives a mapping between these two versioning schemes:

<div align = "center">

| `PyPI` Version | `semver` Version |
| :---: | :---: |
| `epoch` | n/a |
| `major` | `major` |
| `minor` | `minor` |
| `micro` | `patch` |
| `pre` | `prerelease` |
| `dev` | `build` |
| `post` | n/a |

</div>

One can use the **`packaging`** version to convert between PyPI to semver and vice-versa. For more information, check
this [link](https://python-semver.readthedocs.io/en/latest/advanced/convert-pypi-to-semver.html).

</details>

## Activity & Development

It is expected that an issue/PR needs a definite amount of time to resolve. To ensure we follow the stale/mothballed convention
when it is not resolved within a specified period.

For issues, the default is 85 days, and for PR it is 30 days of inactivity after which an issue is labeled as *"`issue/stale`"*
and PR is labeled as *"`pr/mothballed`"*. The label allows administrators to review and take necessary actions.

</div>
