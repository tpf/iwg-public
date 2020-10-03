# So you want the IWG to run a service…

⚠️  This document is maintained by the IWG and is likely to change as we learn
from the process of actually carrying out our mandate.

## What does "run a service" mean?

The IWG has a few roles in running services:

1. It holds administrative keys and delegates access to the current active
   admins, if needed.
2. It keeps services running, monitors availability, performs security updates,
   and does other "keep the lights on" tasks.
3. It identifies breakages caused by upstream changes and attempts to have them
   fixed.  The IWG does not perform development tasks (like rewriting custom
   software).  See "[When Things Break](#When Things Break)" below.
4. It writes internal documentation (playbooks) for how to manage services.
   This covers generic documentation of the hosting platform and
   service-specific troubleshooting steps.

The IWG expressly *does not* do the following:

1. moderate user content
2. develop new features
3. fix non-trivial bugs
4. write documentation for users

## What kind of services does IWG run?

There are two categories of system run by IWG:

1. **TPF services**: those being used for the direct benefit of TPF; for
   example: its mail hosting, web hosting, and GitHub organization
2. **community services**: those being used for the benefit of the Perl and
   Raku communities

## Enrollment of TPF Services

IWG administrates all TPF services unless there is a compelling reason for
other accomodations.

## Enrollment of Community Services

Before any service can be hosted by the IWG, its current maintainer(s) and the
IWG must agree to this arrangement.  Here are a number of guidelines about how
the IWG decides what to host:

* Services must have a significant ongoing value to the community.
* Services must have a minimum level of reliability (or, alternatively,
  hosting it must fall below some maximum level of hassle).
* The IWG must have full ownership of the hosting and deployment environment.
* The IWG will establish an official hosting platform.  ("We host everything on
  such and such OS and are comfortable with managing the following services.")
  Deviation from the official platform is treated as a hassle and judged
  accordingly.
* Services must be hosted at a domain controlled by the IWG.
* Custom code must be hosted at GitHub, in an organization administrated by
  IWG.

## When Things Break

The IWG will establish internal procedures for dealing with routine monitoring
and incident response.

The larger question is what happens when a service's custom code is broken by
changes to the standard deployment environment.  If the IWG is unable to make
a fix easily, they will make a prominent call for assistance.  If the problem
isn't fixed, the service may be taken down and replaced by a page describing
the problem.  Fixes provided by the public will be tested and, if they're
effective, deployed.

