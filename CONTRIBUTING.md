How to Contribute
=================

 This repository is owned by the [Accellera Systems Initiative][1] and
 is maintained by the [Universal Verification Methodology (UVM) Working Group][2] (LWG)
 according to the [Accellera Policies and Procedures][3].

 **Contributions to this reference implementation can only be
   accepted from Accellera members.**

### Join the Accellera UVM Language Working Group

 If you would like to contribute to the development of UVM and/or this
 reference implementation, have your company, organization, or university
 join Accellera and its working groups.
 Find out more information at http://www.accellera.org/about/join.
 If your company, organization or university is already an Accellera member,
 you can request to [join the UVM Working Group here][4].

### Join the UVM community

 If you are not an Accellera member, please join the **[UVM community
 forum][5]** to provide feedback, report bugs and join the general
 discussion around the evolution of UVM.

[1]: https://www.accellera.org
[2]: https://accellera.org/activities/working-groups/uvm
[3]: https://accellera.org/about/policies-and-procedures
[4]: https://workspace.accellera.org/workgroup/index
[5]: https://forums.accellera.org/forum/24-uvm-universal-verification-methodology

---------------------------------------------------------------------
Issue reporting
---------------------------------------------------------------------

Functional or Efficiency bugs may be posted via the [Issue Tracker][6].
When reporting bugs, please specify the following information (if applicable):

  1. UVM Version
  2. Platform, Compiler, Flags
  3. Description of the problem
  4. Steps to reproduce the problem, preferably a small code sample to demonstrate.
  5. Compile/runtime warnings and errors
  
> **Note**
> All bugs will only be tested against the latest publicly available
> version of the product.

> **Note**
> All C++ compilers and SystemVerilog simulators have bugs of different
> degree of severity.  We cannot fix those bugs.  Please report them to 
> the appropriate vendor.

> **Note**
> The [Issue Tracker][6] is only used to track functional and 
> efficiency bugs reported by the UVM community.  All requests for functional
> enhancements will be rejected.

Accellera WG members have access to the WG-internal issue tracking
at MantisHub, as described [here][6].

[6]: https://github.com/jrefice/wg_demo/issues
[7]: docs/DEVELOPMENT.md#issue-tracking

---------------------------------------------------------------------
Patch submission
---------------------------------------------------------------------

The following **sign-off procedure** is established to ensure that
patches submitted for inclusion into this Accellera reference
implementation are properly licensed under the
[Apache License Version 2.0](LICENSE).

The sign-off is a simple line at the end of the explanation for the
patch (or commit message), which certifies that you wrote it yourself
or otherwise have the right to pass it on as an open-source patch:

### Accellera Developer's Certificate of Origin

By making a signed-off contribution to this Accellera project,
I certify that:

 1. The contribution was created in whole or in part by me and I have
    the right to submit it under the Apache License Version 2.0
    (see LICENSE).

 2. The contribution was provided directly to me by some other person
    who certified (1) above, and I am forwarding it without
    modification.

 3. I understand and agree that this Accellera project and the
    contribution are public and that a record of the contribution
    (including all personal information I submit with it, including
    my sign-off) is maintained indefinitely and may be redistributed
    in accordance with this project or the Apache License Version 2.0.

If you can certify the above *Accellera Developer's Certificate of Origin*,
please use `git commit --signoff` to add a line of the form:
```
  Signed-off-by: Ima Contributor <ima@contributor.example.org>
```
using your real name (no pseudonyms or anonymous contributions).

> **Note**  
> For Accellera members, contributions are already bound by the
> [Accellera policies and procedures][3] and the sign-off is optional,
> but recommended.  For **non-Accellera** members, the sign-off is
> **mandatory** for consideration by the Accellera WGs.

When submitting a pull-request against the public repository, the
contribution may be considered by the Accellera WGs for inclusion.
An Accellera member may submit it to the private repository with their
own `Signed-off-by` line appended.  It stays under the sole governance
of the corresponding WGs to decide whether the proposal will be included
in the reference implementation (or future Accellera standards).

---------------------------------------------------------------------
Repository organization
---------------------------------------------------------------------

The central source code repository of the Accellera UVM implementation
is hosted in two repositories at [GitHub](http://github.com).  The main
repositories are **private** to the [`OSCI-WG` GitHub organization][7] and
can be found at:

 * https://github.com/OSCI-WG/uvm-core  (core UVM library)
 * https://github.com/OSCI-WG/uvm-tests (regression test suite)

A read-only, **public** version of these repositories can be found at

 * https://github.com/accellera-official/uvm-core  (core UVM library)
 * https://github.com/accellera-official/uvm-tests (regression test suite)

To obtain access to the repositories and the GitHub organization in general,
UVM members can contact the UVM chairs at <mailto:uvm-chair@lists.accellera.org>
including their GitHub account name.

[7]: https://github.com/osci-wg "Accellera WG GitHub organization"
