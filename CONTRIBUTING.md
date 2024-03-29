# How to Contribute

We love Pull Requests! Your contributions help make ChooseALicense.com great.

Contributions to this project are released to the public under the project's open source license.

Please note that this project is released with a Contributor Code of Conduct. By participating in this project you agree to abide by its terms.

## Getting Started

So you want to contribute to ChooseALicense. Great! We welcome any help we can get. But first, please make sure you understand what this site is all about. It’s not a comprehensive list of all possible licenses.

## Adding a license

Choosealicense.com is intended to demystify license choices, not present or catalog all of them. As such, only a small number are highlighted on the home page or https://choosealicense.com/licenses, and there are several requirements for a license to be cataloged on the site:

The license must have an SPDX identifier. If your license isn't registered with SPDX, please request that it be added.
The license must be listed on one of the following approved lists of licenses:
List of OSI approved licenses
GNU's list of free licenses (note: the license must be listed in one of the three "free" categories)
Open Definition's list of conformant licenses (non-code)
A GitHub code search must reveal at least 1,000 public repositories using the license.
3 notable projects using the license must be identified. These must have straightforward LICENSE files which serve as examples newcomers can follow and that could be detected by licensee if it knew about the license.
If your proposed license meets the above criteria, here's a few other things to keep in mind as you propose the license's addition:

Is the license already cataloged? See https://choosealicense.com/appendix/ for a list of all of the licenses known by the site.
Licenses live in the /_licenses folder.
The license files should be in the format of _licenses/[lowercased-spdx-id].txt (e.g., _licenses/mit.txt)
Each license has both required and optional metadata that should be included.
The text of the license should be wrapped to a 78 character width.
The text of the license should match the corresponding text found in spdx/license-list-data. If there are errors there, please fix them in spdx/license-list-XML (from which the plain text version is generated) so as to minimize license text variation and make it easier for choosealicense.com to eventually consume license texts directly from SPDX.
The body of the file should be the text of the license in plain text.
## Making Changes

The easiest way to make a change is to simply edit a file from your browser. When you click the edit button, it will fork the repository under your account. Note what issue/issues your patch fixes in the commit message.

For example, to change this file, find it in the GitHub repository. Then click the Edit button. Make your changes, type in a commit message, and click the Propose File Change button. That’s it!

For more advanced changes, check out the bootstrap instructions in the project's readme.

## Testing

HTML::Proofer is set up to validate all links within the project. You can run this locally to ensure that your changes are valid:
