# OME NGFF Project Implementations — Roster

## 1. Overview

The **OME-owned implementations** of the **NGFF (Next-Generation File Formats) Project** are a unified effort to develop and maintain software libraries, tools, and applications that enable the adoption and use of the **NGFF Specification**. This roster documents the current contributors and maintainers of the **OME-owned implementations**, along with their roles and responsibilities.

Participation in this roster reflects **sustained and substantial contributions** aligned with the goals of the **NGFF Project** and the broader OME mission.

---

## 2. Scope of the Implementations

### Primary Focus
The **OME-owned implementations** are responsible for developing and maintaining tools and libraries that support the **NGFF Specification**. This includes:

- **Key Responsibilities:**
  - Developing and maintaining the [`ome-zarr-py`](https://github.com/ome/ome-zarr-py/) library for reading, writing, and manipulating OME-Zarr files.
  - Developing and maintaining the [`ome-zarr-models-py`](https://github.com/ome-zarr-models/ome-zarr-models-py/) library for validating and working with OME-Zarr metadata models.
  - Developing and maintaining the [`napari-ome-zarr`](https://github.com/ome/napari-ome-zarr/) plugin for visualizing OME-Zarr files in the **napari** image viewer.
  - Ensuring compatibility and interoperability with the **NGFF Specification** and OME standards.
  - Maintaining documentation, examples, and tutorials for users and developers.
  - Managing the distribution of release artifacts and Docker images (where applicable) through centralized packaging hubs.

- **Out of Scope:**
  - Extensions or tools that do not directly relate to the **NGFF Specification** or its ecosystem.
  - Core infrastructure or tools maintained by other **NGFF** or OME teams (e.g., Bio-Formats, OMERO.server).

---

## 3. Roles and Responsibilities

Roles within the **OME-owned implementations** are aligned with the GitHub permissions model and reflect increasing levels of responsibility and trust. Assignment of roles is based on **sustained and substantial contributions**, as well as demonstrated reliability in supporting the project.

### 3.1 Core Dev
Individuals with the *Core Dev* role support the organization and flow of contributions by:
- Reviewing and labeling issues and pull requests.
- Helping prioritize work and identify duplicates.
- Assisting contributors with initial feedback and guidance.
- Submitting and updating pull requests.
- Contributing code, documentation, or specifications.
- Collaborating with maintainers on implementation details.

This role reflects consistent contribution and familiarity with project practices.

### 3.2 Maintainer
Individuals with the *Maintain* role are responsible for the ongoing development and direction of the **OME-owned implementations**. This includes:
- Reviewing and merging pull requests.
- Guiding technical direction and roadmap.
- Ensuring alignment with the **NGFF Specification** and OME standards.
- Facilitating discussions and decision-making.

This role corresponds to a **maintainer-level responsibility**, requiring sustained engagement and stewardship of the project.

### 3.3 Admin
Administrative authority reflects responsibility for the long-term success and sustainability of the **OME-owned implementations**. Individuals with *Admin* access provide structural and operational support for the repositories and project. This includes:

- Managing repository settings, permissions, and integrations.
- Supporting release processes and infrastructure.
- Ensuring continuity and stability of project operations.
- **Admin Rights for Packaging and Distribution**: Admin rights to package hubs (e.g., PyPI, conda-forge, Docker Hub) are conveyed through access to a **common admin account**, which centralizes all packaging and distribution operations. Access to this account is restricted to a subset of **Admins** and managed by the **PSC** to ensure security and consistency.

Admin responsibilities are assigned sparingly and typically overlap with experienced maintainers or members coordinating across the broader OME ecosystem. While many Administrators emerge through sustained technical contribution, the project may also appoint individuals whose responsibilities primarily relate to leadership, stewardship, funding, operations, community coordination, or institutional commitments.

---

## 3.4 Current Roster

### Subgroups

The following table summarizes the current roster of contributors and maintainers for the **OME-owned implementations** of the **NGFF Project**, organized by subgroup.

| Role | OME-Zarr in Python |
|:-----|:-------------------|
| Admin | [Jean-Marie Burel](https://github.com/jburel), [Josh Moore](https://github.com/joshmoore) |
| Maintainer | [Will Moore](https://github.com/will-moore), [Johannes Soltwedel](https://github.com/jo-mueller), [Kevin Yamauchi](https://github.com/kevinyamauchi) |
| Contributor (Core Dev) | [Wouter-Michiel Vierdag](https://github.com/melonora), [Juan Nunez-Iglesias](https://github.com/jni), [Draga Doncila Pop](https://github.com/dragadoncila) |


The following table summarizes the repositories currently governed by this charter,
along with their respective responsibilities and governance structure.

| Repository | Governance |
|:-----------|:------|
| [ome-zarr-py](https://github.com/ome/ome-zarr-py/) | All (see above) |
| [ome-zarr-models-py](https://github.com/ome-zarr-models/ome-zarr-models-py/) | All (see above) |
| [napari-ome-zarr](https://github.com/ome/napari-ome-zarr/) | All (see above) |

---

## 4. Membership Expectations

Membership in the roles outlined above is open to individuals who wish to contribute. Becoming part of the roster (e.g., Core Dev or Maintainer) is based on:
- Sustained and meaningful contributions.
- Alignment with project goals.
- Demonstrated reliability and collaboration.

These roles within the project are not fixed and may evolve over time:
- Contributors may become Maintainers through sustained engagement.
- Maintainers are expected to remain active and responsive.

To ensure continued progress:
- Individuals who become inactive may be moved to an inactive or alumni status.
- Responsibilities may be reassigned as needed to maintain momentum.

---

## 5. Expansion of Governed Repositories
As the NGFF Project grows, additional repositories or projects may be brought under the governance of this charter. When new projects are added:

- Existing Maintainers: The maintainers of the newly governed project repositories retain their Maintainer or Admin roles, ensuring continuity and expertise in the project's development.
- Coordination with PSC: While these maintainers retain their day-to-day autonomy, they agree to coordinate strategic decisions (e.g., major architectural changes, alignment with the NGFF Specification, or cross-project dependencies) with the Project Steering Committee (PSC).
- Lazy Coordination: For day-to-day operations, maintainers of newly governed projects will follow the lazy consensus model outlined in this charter, ensuring efficient collaboration while maintaining alignment with the broader NGFF Project.

This approach ensures that new projects integrate smoothly into the OME-owned implementations while preserving their existing momentum and expertise.

## 6. Maintenance of This Document

This roster is maintained by the project Maintainers and updated as needed to reflect:
- Changes in participation.
- Role transitions.
- Project evolution.

| Version History |                          |
| :-------------- | :----------------------- |
| Date            | Description              |
| [Insert Date]   | Initial draft            |

---