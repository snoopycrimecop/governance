# Charter for the NGFF Project Implementations

## Overview

This document formalizes the governance for the **OME-owned implementations** of the **NGFF (Next-Generation File Formats) Project**, an OME Registered Project (ORP). The **NGFF Project** encompasses two distinct but closely related components:

1. **The NGFF Specification**
   - The **NGFF Specification** defines the standards, formats, and protocols for next-generation bioimaging data. Its governance is outlined in the [NGFF Editorial Board Charter](https://ngff--559.org.readthedocs.build/rfc/10/index.html), which describes the decision-making process for the specification itself.

2. **OME-Owned Implementations**
   - The **OME-owned implementations** are software libraries, tools, and applications that enable the adoption and use of the **NGFF Specification**. These implementations are developed and maintained as a unified effort, currently focused on Python-based tools but with the flexibility to expand to other programming languages or platforms in the future. This charter governs the **OME-owned implementations**.

This document outlines the governance structure for the **OME-owned implementations**, ensuring alignment with the **NGFF Specification** and the broader OME ecosystem while providing flexibility for future growth.

---

## Aspiration to Completeness

The **OME-owned implementations** aspire to support every feature laid out by the **core NGFF Specification document**. The **Maintainers** and members of the **Project Steering Committee (PSC)** will meet periodically to review progress, ensure alignment with the **NGFF Specification**, and address any gaps or challenges in achieving this goal.

---

## Roles and Responsibilities

### Users

Users are members of the community who utilize the **OME-owned implementations** of the **NGFF Project**. Their contributions—such as providing feedback, reporting bugs, and evangelizing the project—are essential for shaping the purpose and direction of the implementations.

### Contributors

Contributors are community members who engage directly with the **OME-owned implementations** in concrete ways, such as:

- Proposing, discussing, or reviewing changes to code, documentation, or specifications via pull requests.
- Reporting issues through public channels.
- Assisting with documentation or project infrastructure.
- Supporting new users.

All community members are encouraged to contribute. Contributions must comply with the OME Project's [Code of Conduct](https://github.com/ome/governance/blob/master/code-of-conduct/README.md).

Requirements for code and documentation contributions are described in the OME Project's [code contribution policy](https://ome-contributing.readthedocs.io/en/latest/code-contributions.html) and [third-party contribution policy](https://ome-contributing.readthedocs.io/en/latest/third-party-policy.html). We strongly recommend reading these documents and seeking clarification before submitting contributions.

---

## Project Steering Committee (PSC)

### Function
The **Project Steering Committee (PSC)** serves as the governing body for the **OME-owned implementations** of the **NGFF Project**. It:
- Ensures alignment with the **NGFF Specification** and the broader OME ecosystem.
- Resolves conflicts or issues related to the implementations.
- Approves the addition of new repositories or projects.
- Manages administrative actions (e.g., adding/removing members) at the **project level**.
- Meets periodically to review the status of the **OME-owned implementations** as **complete implementations** and ensure progress toward supporting all features of the **NGFF Specification**.

### Authority
- The **PSC** is self-governing, and its membership is not overseen by the OME Management Group (OMG).
- The **PSC** may intervene in decisions if they conflict with the broader **NGFF Project** or OME ecosystem.
- The **PSC** ensures that the **OME-owned implementations** remain compatible with the **NGFF Specification**, but does not coordinate directly with the **NGFF Editorial Board** for day-to-day operations or governance.

### Membership
- **Merit-Based**: Any contributor to the **OME-owned implementations** is eligible to join the **PSC**.
  - **Nomination**: Existing **PSC** members can nominate new members based on sustained, quality contributions to the **OME-owned implementations**. Approval is subject to vote by the existing **PSC** (ideally consensus, but at minimum majority approval).
  - **Removal**: Inactive members can be removed via a majority vote of the existing **PSC**.

The **PSC** is currently defined as anyone with a `Maintainer` role in the **OME-owned implementations** as defined in the [NGFF Project roster](../roster/).

### PSC Chair
- The **Chair** acts as a coordinator and facilitator for the **PSC**.
- The Chair holds no additional authority over other **PSC** members.
- The current Chair is **[To Be Determined]**. The Chair role may be temporarily or permanently reassigned by agreement within the **PSC**, or by directive from the OMG if necessary.

---

## Relationship to NGFF and OME Governance

The **OME-owned implementations** operate as part of the **NGFF Project**, an [OME Registered Project (ORP)](../../README.md). They align with the broader governance framework of the **NGFF Project** and the OME ecosystem.

- The implementations contribute to and are supported by the **NGFF Project** and OME ecosystem.
- Coordination with the **NGFF PSC** and OME Management Group (OMG) occurs as needed.
- The implementations follow shared principles for openness, contribution, and sustainability.

The OME management group (OMG) provides oversight and strategic direction for the **OME-owned implementations** and the broader **NGFF Project**.
The OMG may provide additional steering by vetoing or reverse assignments to the **PSC** or project decisions as deemed necessary.

---


## Decision Making Process

### Consensus-Seeking and Voting

The **OME-owned implementations** aim for **consensus** among **PSC** members for all decisions. If consensus cannot be reached after discussion, decisions are resolved by a **majority vote** of the **PSC**.

#### Discussion Venues
Discussions primarily occur in the following venues, with a preference for public transparency:

1. **Publicly**: In GitHub pull requests, issues, and discussions.
2. **Semi-Publicly**: In OME project-wide meetings, which are [publicly minuted](https://ome-contributing.readthedocs.io/en/latest/team-communication.html#meetings).
3. **Semi-Privately**: In dedicated **NGFF Project** meetings, with minutes accessible to members of the OME Project.
4. **Privately**: Via the chat platforms or ad hoc meetings, as needed. Summaries of private discussions must be shared publicly.

### Lazy Consensus for Day-to-Day Operations

Lazy consensus is used for most day-to-day decisions within the **OME-owned implementations**, allowing contributions to proceed efficiently.

- **Minor Documentation Changes** (e.g., typo fixes): Require approval by a **Core Developer** and no disagreement or requested changes from any **Core Developer** within a reasonable time (e.g., one working day).
- **Code Changes and Major Documentation Changes**: Require agreement by one **Core Developer** and no disagreement or requested changes from any **Core Developer** within a reasonable time (e.g., a few working days).
- **Objections**: If a **Core Developer** raises an objection to a proposal under lazy consensus, the proposal is escalated to the **PSC** for a consensus-seeking discussion or majority vote.

A **Core Developer** or **Maintainer** may request additional reviews from individuals with other roles or from community members. These reviews should be taken seriously, and all reasonable attempts should be made to resolve disagreements. However, the final decision rests with the **PSC**.

---

## Code of Conduct

As an OME Registered Project, the **OME-owned implementations** of the **NGFF Project** adhere to the OME Project's [Code of Conduct](../../../code-of-conduct/). Contributors and community members are expected to comply with OME's [third-party contribution and communication policy](https://ome-contributing.readthedocs.io/en/latest/third-party-policy.html).

---

## Current Implementations

The **OME-owned implementations** contain the following subgroups:

### OME-Zarr in Python

The subgroup focuses on Python-based tools and libraries that support the **NGFF Specification**. These include:

- [ome-zarr-py](https://github.com/ome/ome-zarr-py/)
- [ome-zarr-models-py](https://github.com/ome-zarr-models/ome-zarr-models-py/)
- [napari-ome-zarr](https://github.com/ome/napari-ome-zarr/)

Additional implementations in other programming languages or platforms may be added in the future,
subject to approval by the **PSC**.

---

## Relationship to the NGFF Specification

The **OME-owned implementations** of the **NGFF Project** must align with the **NGFF Specification**, which is governed by the [NGFF Editorial Board](https://ngff--559.org.readthedocs.build/rfc/10/index.html). The **PSC** is responsible for ensuring that the implementations remain compatible with the **NGFF Specification**. However, the **OME-owned implementations** operate independently of the **Editorial Board** and do not coordinate with it for day-to-day operations or governance.

---

## License and Attribution

This governance document is adapted from the original **Zarr governance document** and the [Meritocratic Governance Model](http://oss-watch.ac.uk/resources/meritocraticgovernancemodel) by Ross Gardler and Gabriel Hanganu (licensed under a Creative Commons Attribution-ShareAlike 4.0 International License).

---