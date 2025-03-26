**Ticket Type:** Task  
**Title:** Configure Terraform and the GitHub Provider  
**Project:** Version Control System Deployment  
**Assignee:** You  
**Reporter:** Derek Morgan  
**Priority:** High  
**Labels:** Terraform, GitHub, Providers  
**Epic Link:** GitHub Expansion  
**Sprint:** Sprint 01/Providers

**Description:**

As part of our code consolidation strategy, we need to configure and initialize Terraform to ensure that any minor version above Terraform 1.0 (1.1, 1.2, etc.) is used and ensure GitHub Provider version 6.2.0 and its **patch** versions, except 6.2.1, are allowed: e.g. 6.2.0, 6.2.2 are all fine, but not 6.2.1, 6.3.0, or 6.4.1.

**Implementation Notes:**

> **Important:** If the `terraform validate` command fails, all tasks in the lab will fail!

- <a href="https://registry.terraform.io/providers/integrations/github/latest/docs" target="_blank">GitHub Provider Documentation</a>  
- <a href="https://developer.hashicorp.com/terraform/language/resources" target="_blank">Terraform Resources Documentation</a>  
- <a href="https://developer.hashicorp.com/terraform/language/providers/configuration" target="_blank">Terraform Provider Configuration</a>  
- <a href="https://developer.hashicorp.com/terraform/language/providers/requirements" target="_blank">Terraform Provider Requirements</a>  
- <a href="https://developer.hashicorp.com/terraform/cli/commands/init" target="_blank">Terraform Init Command</a>
