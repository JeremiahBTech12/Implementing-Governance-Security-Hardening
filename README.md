# Implementing Governance & Security Hardening in Azure

![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Entra ID](https://img.shields.io/badge/Microsoft_Entra_ID-RBAC-0078D4?style=flat)
![Azure Policy](https://img.shields.io/badge/Azure_Policy-Cost_Management-555?style=flat)

In this lab I act as a Cloud Administrator. Instead of being the "Owner" who can do everything, I restrict what other people can do. I create a new user in **Microsoft Entra ID**, give them limited permissions with **RBAC**, enforce rules with **Azure Policy** to block expensive deployments, and set up a **budget** that alerts me on spending.

## What I configured

| Control | Purpose |
|---|---|
| Entra ID user | A separate identity for a non-admin team member |
| RBAC role assignment | Least-privilege access instead of Owner |
| Azure Policy | Prevents expensive resource deployments |
| Cost Management budget | Alerts me when spending crosses a threshold |

## Build steps

1. Created a new user in Microsoft Entra ID.
2. Assigned the user a limited RBAC role and verified that access outside that role was denied.
3. Assigned an Azure Policy that blocks expensive deployments and verified that it was enforced.
4. Created a Cost Management budget with a spending alert.

## Video walkthroughs (Loom)

- [Project introduction](https://www.loom.com/share/e4c0767586f54f51808b99622dfdbae7)
- [Role-based access control and verifying denial of access](https://www.loom.com/share/9349697ab70144349134765e0c83f040)
- [Azure Policy configuration and verification, plus Cost Management budget setup](https://www.loom.com/share/63ebc716b17d41ecb40cc4dd3da31732)
- [Project outro](https://www.loom.com/share/ba966037f46d451cb15742176cedf989)
