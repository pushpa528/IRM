# IPA overview

IPA is an Intelligent Processor Framework for executing workflows through event-driven processing, scalable processors, and integrations. This guide explains its architecture and provides instructions for creating, configuring, and securing workflows in InSight DXP.

## Prerequisites

Before you create and configure nodes in IPA, ensure that you:

- Have access to the [InSight DXP Environments](https://irm-rmaas.atlassian.net/wiki/spaces/CCI/pages/2881224706/Environme) page.
- Understand the basic **IPA workflow and node concepts**.
- Define the **task or processing requirement** for the node.
- Identify the appropriate **node category** for the task.
- Identify the **repository** that corresponds to the selected node category when creating a solution-based node.
- Have the required **credentials** available if the node accesses an authenticated service.
- Identify task-specific settings, such as **wait timeout**, **parallel processing**, or **sub-workflows**, where applicable.
- Ensure that the **processor image supports the actions** you configure for the node.
- Platform engineers Identify the required advanced settings, such as **Form Type**, **Node Type**, **Category**, **Classification**, **Worker Name**, **Simple Conductor Type**, and **node availability**, when configuring platform-level nodes.
