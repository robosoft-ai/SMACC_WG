# SMACC Working Group

This document defines the scope and governance of the SMACC Working Group (SMACC WG).

Mission: The SMACC Working Group's mission is to advance the current state of the art in robotic applications, by utilizing the SMACC state machine library for ROS and ROS2.

We will be focused on…

 * The creation of new SMACC state machine examples that demonstrate advanced autonomy capabilities.
 * The creation of new SMACC clients that will enable the utilization of SMACC on platforms with different peripherals.
 * Improvements to the core SMACC library, bug-fixes, new features, etc.
 * Improving the documentation of the library.
 * Surveying the community interest in using SMACC for particular use cases in ROS 2 and Gazebo.
 * Producing demonstrations with real robots that utilize SMACC to meet their application requirements.


## Governance

### Meetings

Meeting will generally happen once a month or more often. Meetings will be announced on ROS Discourse and minutes will be kept.

  * [Proposal for the SMACC Working Group](https://discourse.ros.org/t/proposal-for-smacc-wg/27331)
  * [Rolling Agenda and Minutes](https://docs.google.com/document/d/1vizP6lzpi6iwjjmCyGV2VlArftpxNB7oAu5f76Ofpxw/edit#heading=h.koswsc4mb967)

### Communication Channels

  * Meeting invite group: [smacc-wg@googlegroups.com](smacc-wg@googlegroups.com)
  * Working Group Github repo: [SMACC_WG](https://github.com/robosoft-ai/SMACC_WG)
  * Discourse tag: [wg-smacc](https://discourse.ros.org/tag/wg-smacc)

### Backlog Management

Backlog management is performed using Github Issues & Projects on the following repos:

  * [SMACC Repository for ROS1](https://github.com/robosoft-ai/SMACC)
  * [SMACC2 Repository for ROS2](https://github.com/robosoft-ai/SMACC2)
  * [SMACC Working Group Repository](https://github.com/robosoft-ai/SMACC_WG)

### Membership, Roles and Organization Management

Working Group members may act in one or more of the following roles:

* **Member**
  * Prerequisite: Attend at least one out of the last three Working Group meetings
  * Responsible for triaging issues
* **Reviewer**
  * All reviewers are members
  * Prerequisite: Proven track record of high-quality reviews to WG Subprojects
  * Responsible for reviewing pull requests
* **Approver**
  * All approvers are reviewers
  * Prerequisite: Proven track record of high-quality contributions and reviews to WG Subprojects
  * Responsible for approving and merging pull requests
  * Responsible for vetting and accepting new projects into the Working Group
* **Lead**
  * TSC member or their delegate
  * Responsible for organizing and moderating working group meetings
  * Responsible for posting meeting materials (minutes, recordings, etc.)
  * Responsible for breaking ties

To become a member or change role, create an issue in this repository using the appropriate issue template.
Such applications are accepted upon unanimous agreement from Approvers, and are typically based on the applicant's history with the subprojects of the Working Group.

The Lead role cannot be applied for, as it is an appointee of the ROS 2 TSC.

### Modifying this governance document

Changes to this document will be made via Pull Request.
The PR will be merged on unanimous agreement from Approvers.
