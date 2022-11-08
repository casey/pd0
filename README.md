# PD0

Disclaimer: I am not a lawyer, this is not legal advice.

The Fedora project has recently changed the classification of the CC0 license
to `allowed-content` only, and will not accept CC0-licensed software going
forward.

This is due to paragraph 4(a) of the CC0:

> No trademark or patent rights held by Affirmer are waived, abandoned,
> surrendered, licensed or otherwise affected by this document.

Such a clause may strengthen the case of a party that releases software under
the CC0 that infringes a software patent that they hold, and attepts to sue
those who use the software they release for patent infringement.

Software patents are deeply harmful to free and open-source software, and such
a clause makes the CC0 less suitable for use with software.

In the interest of preserving the value of the CC0, I propose a minimally
modified version with the following changes:

- Rename the license to `PD0` to avoid confusion
- Remove all references to Creative Commons, since it is no longer a Creative
  Commons license
- Remove paragraph 4(a)

The modified license is in [PD0](PD0). Each change of the above changes been
made in a separate commit to this repository for ease of auditing.
