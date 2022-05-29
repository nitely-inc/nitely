# Nitely Source Access and Contributor Guidelines
*October 28, 2021*

# Contents

1. [Access to source code](#source-access)
1. [Reporting bugs](#reporting-bugs)
1. [Contributing code](#contributing)

# Introduction

Thank you for using Nitely!

Nitely is open source software that aims to allow power users download apps unavailable on the `APT` repositories.


Nitely is and will always remain free and openly available under the `GPL-v3.0` license.  It can be
used and modified in any way by anyone.

Nitely is maintained by the [Nitely Developers](https://github.com/nitely-developers).
Anyone can see the source, but only the Nitely Developers have commit access.

As the Nitely Developers, we're committed to
building communities that are welcoming and inclusive: environments where people
are encouraged to share ideas, treat each other with respect, and collaborate
towards the best solutions. To reinforce our commitment, Nitely
has adopted a slightly modified [Code of Conduct](https://github.com/Nitely-Developers/nitely/blob/master/docs/code_of_conduct.md)
for the Nitely project.

# <a name="source-access"></a>Access to source code

A public-access git repository is available on
[Github](https://github.com/nitely-developers/nitely).  This repository
contains all public-access branches. Upcoming updates can be viewed in
their current state at any time.  Short-lived development branches
contain unreviewed work in progress.

You can browse the source online via
[Github](https://github.com/nitely-developers/nitely/tree/master).

To clone the repository, use:

```bash
$ git clone https://github.com/nitely-developers/nitely.git
```

**OR**

```bash
$ git clone https://gitlab.com/C-EO/nitely.git
```


# <a name="reporting-bugs"></a>Reporting bugs

Reports of flaws in the Nitely package, including software bugs, errors
in the documentation, missing files in the tarball, suggested changes
or requests for new apps, etc., can be filed using
[Github issues](https://github.com/nitely-developers/nitely/issues).

Due to a large ticket backlog, we are sometimes slow to respond,
especially if a bug is cosmetic or if a suggestion is vague or
low in priority, but we try at least to acknowledge legitimate
bug reports within a week.

Nitely's Github system is publicly readable; however, you must have
an account to create a new issue..

## Reporting possible security issues

If you think you may be seeing a potential security vulnerability in Nitely
(for example, a crash with REQUIRE failure), please
report it immediately opening an [issue](https://github.com/nitely-developers/nitely/issues/new/choose) with the `Security Vulnerability` label. 

Do not discuss undisclosed security vulnerabilities on any public mailing list.
We as the Nitely Developers have a long history of handling reported vulnerabilities promptly and
effectively on many projects and we respect and acknowledge responsible reporters.

Our Security Vulnerability Disclosure Policy is documented on
[Github](https://github.com/nitely-developers/nitely/security/policy) under the `Security` tab.

# <a name="contributing"></a>Contributing code

Nitely is licensed under the
[GNU General Public License v3.0](https://github.com/nitely-developers/nitely/blob/tree/master/LICENSE.md).

### <a name="nitely-code"></a>Nitely code

Fixtures, app requests, or suggestions for Nitely may be submitted directly via pull requests on
[Nitely's Github](https://github.com/nitely-developers/pulls) or [issues](https://github.com/nitely-developers/nitely/issues).

Those wanting to write code for Nitely may be interested in the
[developer information](https://docs.nitely.vercel.app) website, which includes information
about Nitely design and coding apps for Nitely.

Every fixture submitted is reviewed by Nitely Developers following our
code review process before it is merged.

It may take considerable time to review fixture submissions.  If the fixture is a good
idea, we can and will do additional work to bring it up to par, but if
we're busy with other work, it may take us a long time to get to it.

To ensure your fixture is acted on as promptly as possible, please:

* Document your work, both in the issue and in the
  accompanying pull request. (Please note that the pull request may not be needed.)
* In fixtures that make non-trivial functional changes, include system
  tests if possible.

#### Documentation

Fixtures to improve existing documentation are also very welcome!

#### Thanks

Thank you for your interest in contributing to the ongoing development
of Nitely.
