---
title: OMERO.web charter
permalink: /governance/projects/omero-web/charter/
description: Charter for OME OMERO.web
---

# Charter for OMERO.web

## **Overview**

This document formalizes the default governance for the OMERO.web OME
Registered Project (ORP). It is a meritocratic, consensus-based, and
self-governing process, akin to the Apache model. The primary goal is to
empower developers, streamline the development process, and maintain the
project's stability and continuity while adhering to the overarching principles
of the overall OME Project.

## **Roles and Responsibilities**

### **Users**

Users are members of the community who utilize the project. Their
contributions, such as providing feedback, reporting bugs, and general
evangelism, are essential for the project's purpose and direction.

### **Contributors**

Contributors are community members who engage directly with the project in concrete ways, such as:

- Proposing, discussing, or reviewing a change to the code, documentation, or specification via a pull request.
- Reporting issues through public channels.
- Assisting with documentation or project infrastructure.
- Supporting new users.

All community members are encouraged to contribute. Contributions should be
made in compliance with the OME Project's
[Code of Conduct](https://github.com/ome/governance/blob/master/code-of-conduct/README.md).

Requirements for code and documentation contributions are
described in the OME Project's [code contribution policy](https://ome-contributing.readthedocs.io/en/latest/code-contributions.html)
and [third party contribution policy](https://ome-contributing.readthedocs.io/en/latest/third-party-policy.html).
We strongly recommend reading these documents and seeking clarification if needed before
submitting test data or proposing a code or documentation change.

A list of all code and documentation contributors (as of the most recent release) is
maintained on the [OME website](https://www.openmicroscopy.org/contributors/).

### **Project Steering Committee (PSC)**

The Project Steering Committee (PSC) serves as the governing and administrative
body for the individual Registered Project. It is equivalent to the Project
Management Committee (PMC) in an Apache-governed project.

- Function: The PSC have administrative rights and make decisions, such as
  accepting or rejecting pull requests, and managing administrative actions
  within the project's repositories (e.g. adding/removing members). The PSC
  is currently defined as anyone with a `Maintainer` role as defined in the
  [OMERO.web roster](../roster/README.md).
- Authority: The PSC is self-governing and its membership is not overseen by
  the OME Management Group (OMG). The PSC
  is currently defined as anyone with a `Maintainer` role as defined in the
  [OMERO.web roster](../roster/README.md).
- Membership is Merit-Based: Any contributor is eligible to join the PSC.
  - Nomination: Existing PSC members can nominate new members. Nominations must
    be based on clear evidence of sustained, quality contribution to the
    project. Approval is subject to vote by the existing PSC (ideally
    consensus, but at minimum majority approval).
  - Removal: PSC members who become inactive can and should be removed via a
    majority vote of the existing PSC.

### **PSC Chair**

The Chair's role is to act as a
coordinator and facilitator for the group's activities and discussions. The
Chair holds no additional authority over other PSC members. 

The current Chair is [Andreas Knab (Glencoe Software)](https://github.com/knabar).
The Chair role may be temporarily passed to anyone else on the PSC due to extended absence,
by agreement within the PSC. Permanent changes may be made by agreement within the PSC,
or, if that is not possible, directive from the OMG.

## **Decision Making Process**

Decisions should be made in accordance with the mission and values of the OME
Project. Decisions are primarily made through consensus-seeking as described below,
and are discussed as publicly as possible. Given the foundational nature of the
Bio-Formats project, decisions may impact other ORPs (in particular, Core Model,
NGFF, and OMERO server). When making decisions that impact other ORPs, all
reasonable effort should be made to work with the PSC and/or maintainers of those ORPs
to reach a mutually agreeable decision.

### **Consensus-Seeking and Voting**

The project aims for consensus among PSC members for all decisions. If
consensus cannot be reached after discussion, decisions will be resolved by
falling back on a majority vote of the PSC.

Discussions primarily occur:

- publicly, in GitHub pull requests and issues
- semi-publicly, in OME project-wide meetings which are [publicly minuted](https://ome-contributing.readthedocs.io/en/latest/team-communication.html#meetings)
- semi-privately, in dedicated weekly meetings which span OMERO.web and related plugins,
  with minutes accessible to members of the OME Project
- privately, via Slack or ad hoc meetings as needed

Preference is given to public discussion. In the case of private and semi-private discussions,
a summary of discussion and outcome is to be shared publicly.

### **Lazy Consensus for Day-to-Day Operations**

Lazy Consensus is used for most day-to-day decisions, allowing the majority of
contributions to proceed efficiently.

- Minor Documentation Changes (e.g. typo fixes): Require approval by a Core
  Developer and no disagreement or requested changes from any Core Developer
  within a reasonable time (e.g. one working day).
- Code Changes and Major Documentation Changes: Require agreement by one Core
  Developer and no disagreement or requested changes from any Core Developer
  within a reasonable time (e.g. a few working days).
- Objections: If a Core Developer raises an objection to a proposal under lazy
  consensus, the proposal is escalated to the full group for a
  consensus-seeking discussion or a majority vote.

A Core Developer or Maintainer may request additional reviews from individuals
with other roles, and in some cases from community members who are not currently listed
on an ORP roster. These reviews should be taken seriously (if submitted), and all
reasonable attempts should be made to resolve disagreements between reviewers with
any role. However, it is ultimately up to an agreement within the PSC whether a
requested change or the absence of a review blocks a proposed change.

## **Code of Conduct**

All Registered Projects must adhere to the OME Project's
[Code of Conduct](https://github.com/ome/.github/blob/master/CODE_OF_CONDUCT.md).
The OMERO.web project and prospective contributors are expected to adhere
to OME's [third party contribution and communication policy](https://ome-contributing.readthedocs.io/en/latest/third-party-policy.html).

## **License and Attribution**

This governance document is adapted from the original Zarr governance document
and the [Meritocratic governance model](http://oss-watch.ac.uk/resources/meritocraticgovernancemodel)
by Ross Gardler and Gabriel Hanganu (licensed under a Creative Commons
Attribution-ShareAlike 4.0 International License).
