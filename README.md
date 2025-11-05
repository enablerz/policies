# 🧾 Enablerz Policy Repository

### **Centralized Legal & Compliance Document Management**

This repository serves as the **single source of truth** for all legal, compliance, and policy documentation maintained by **Enablerz Digital Learning Pvt. Ltd.** It ensures consistent, version-controlled management of key policy documents such as:

* **Privacy Policy**
* **Terms & Conditions**
* **Disclaimer**
* **Cookie Policy**

The repository follows semantic versioning for each application and policy, starting with **MOAI**, Enablerz’s AI-powered digital coaching platform.

---

## 🏢 About Enablerz

**Enablerz Digital Learning Pvt. Ltd.** is a technology-driven learning and development organization building AI-based solutions for personalized coaching, leadership development, and corporate training.
Our products—including **MOAI**, **ENA**, and the **Enablerz Corporate Platform**—leverage AI, behavioral science, and data analytics to empower human growth at scale.

🌐 **Website:** [https://enablerz.co](https://www.enablerz.co)
📧 **Contact:** [privacy@enablerz.co](mailto:privacy@enablerz.co)

---

## 📂 Repository Structure

```
policies/
├── privacy-policy/
│   ├── moai/
│   │   └── v1.0.0.md
│   └── CHANGELOG.md
├── terms-and-conditions/
│   ├── moai/
│   │   └── v1.0.0.md
│   └── CHANGELOG.md
├── disclaimer/
│   ├── moai/
│   │   └── v1.0.0.md
│   └── CHANGELOG.md
├── cookie-policy/
│   ├── moai/
│   │   └── v1.0.0.md
│   └── CHANGELOG.md
version-map.json
CHANGELOG.md
.gitignore
README.md
```

Each document is versioned independently and organized by **application name** (e.g., `moai`, `ena`, `website`, `sso`).
Future updates will include policy sets for additional Enablerz applications.

---

## 🔢 Version Management

Version tracking is handled via [`version-map.json`](./version-map.json), which maintains the current release number for each app and policy type.

**Example:**

```json
{
  "moai": {
    "privacy-policy": "v1.0.0",
    "terms-and-conditions": "v1.0.0",
    "disclaimer": "v1.0.0",
    "cookie-policy": "v1.0.0"
  }
}
```

### **Versioning Convention**

We follow **Semantic Versioning (SemVer)**:

```
MAJOR.MINOR.PATCH
```

| Type      | Description                                                |
| --------- | ---------------------------------------------------------- |
| **MAJOR** | Structural or legal clause changes requiring re-acceptance |
| **MINOR** | Clarifications or new optional sections                    |
| **PATCH** | Typos, formatting, or minor wording corrections            |

---

## 🧱 Repository Standards

| Standard      | Description                                                                                 |
| ------------- | ------------------------------------------------------------------------------------------- |
| **Format**    | All documents use Markdown (`.md`) for compatibility and readability.                       |
| **Encoding**  | UTF-8 without BOM.                                                                          |
| **Naming**    | `vX.Y.Z.md` where X=Major, Y=Minor, Z=Patch.                                                |
| **Branching** | `main` is always the stable branch. Drafts or proposals should use `feature/policy-update`. |
| **Review**    | Each update must be reviewed by the Enablerz Compliance or Legal Officer before merging.     |

---

## 🪵 Changelog Protocol

All modifications must be recorded in both:

* The **global** [`CHANGELOG.md`](./CHANGELOG.md)

Each entry must include:

* Version number
* Date of release
* Summary of changes
* Reviewer/Approver initials

Example:

```markdown
## [v1.0.0] — 2025-11-05
- Updated Section 4 of Privacy Policy to include data retention clause.
- Revised Terms for SSO integration.
- Approved by Compliance Officer: [Name]
```

---

## 🔐 Security and Compliance

* All user data references follow principles of **lawfulness, fairness, and transparency**.
* Policies align with the **Indian IT Act (2000)**, **GDPR**, and **industry best practices**.
* Future versions will include signed digital hashes for document authenticity verification.

---

## 🧭 Roadmap

| Milestone | Description                                 | Status      |
| --------- | ------------------------------------------- | ----------- |
| v1.0.0    | Initial MOAI policy publication             | ✅ Completed |
| v1.0.0    | Add ENA policy set                          | ⏳ Planned   |
| v1.0.0    | Add Enablerz Website policy set              | ⏳ Planned   |
| v2.0.0    | Automate release tagging via GitHub Actions | 🔜 Future   |
| v2.1.0    | Introduce digital signature verification    | 🔜 Future   |

---

## 📞 Contact & Compliance

**Legal & Data Protection Office**
Enablerz Digital Learning Pvt. Ltd.
Mumbai, Maharashtra, India

📧 **[privacy@enablerz.co](mailto:privacy@enablerz.co)**
🌐 [https://enablerz.co](https://enablerz.co)