# iik
Insurance Innovation Kit (IIK)

# Insurance Innovation Kit (IIK)
<p align="center">
  <img src="https://img.shields.io/badge/Status-Actively%20Developing-blue.svg" alt="Project Status: Actively Developing">
  <img src="https://img.shields.io/github/license/iik/iik.svg" alt="License: MIT">
</p>

## Accelerating InsurTech Innovation

The **Insurance Innovation Kit (IIK)** is an open-source collection of structured data standards, modular schemas, and technical blueprints designed to drive innovation within the insurance space.

This project addresses the industry's common challenge where **business knowledge** and **technical expertise** often operate in silos. The IIK provides a shared, structured foundation that enables both domain experts to build and explore.

---

## The Modular Kit Collection

The IIK is structured as a **Monorepo** containing distinct, independent Kits. Each kit is a standalone module, allowing users to **select and integrate only the components required** for their specific needs.

### Available Kits:

| Kit | Description | Key Components | Status | Link |
| :--- | :--- | :--- | :--- | :--- |
| **IIK-PAS** | **Policy Administration System Core.** Defines the fundamental data model and process flows for the policy lifecycle (New Business, Endorsements, Renewals). | Core Policy, Customer, Risk Schemas. | **Alpha** | [kits/iik-policy-admin/](kits/iik-pas/) |
| **IIK-Submission** | **Submission Intake Process.** Focuses on the pre-policy process, including intake, data validation, and automated underwriting referral rules. | Submission, Quote, Referral Schemas. | **Planning** | [kits/iik-submission/](kits/iik-subm/) |
| **IIK-Brokerage** | **Brokerage Management.** Schema and APIs for managing brokers, agencies, commissions, and performance tracking. | Broker, Commission Schemas. | **Planning** | [kits/iik-brokerage/](kits/iik-brokerage/) |

---

## Contribution and Collaboration

The IIK is a community-driven project that relies on expertise from across the insurance and technology sectors. We actively encourage contributions:

### 1. Domain Experts
Help us refine the core accuracy of the kits. We need input on industry standards, entities, and workflow logic.
* Review schemas and definitions in the **`core/`** directory.
* Suggest process improvements or necessary entities via **GitHub Issues**.

### 2. Engineers
Help us build out the technical implementation and tooling.
* Contribute Data Definition Language (DDL/SQL) and configuration files.
* Develop reference implementations and test suites.

Please consult the **[CONTRIBUTING.md](CONTRIBUTING.md)** file for guidelines on how to get started.

---

## 📄 License

This project is licensed under the MIT License - see the **[LICENSE](LICENSE)** file for details.
