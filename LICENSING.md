# Project IMACE Licensing

<p align="center">
  <em>Repository-level licensing for an open, multidisciplinary research ecosystem</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Code-Apache%202.0-blue?style=for-the-badge" alt="Apache 2.0" />
  <img src="https://img.shields.io/badge/Code-BSD%20%2F%20GPL%20%2F%20MIT-purple?style=for-the-badge" alt="Code Licenses" />
  <img src="https://img.shields.io/badge/Docs-CC%20BY--SA%204.0-orange?style=for-the-badge" alt="CC BY-SA 4.0" />
  <img src="https://img.shields.io/badge/Policy-Project%20Specific-green?style=for-the-badge" alt="Project Specific" />
</p>

<p align="center">
  Project IMACE (Integrated Modular Architecture for Cognitive Emulation) uses a repository-level licensing model.
</p>

> **Key principle:** different Project IMACE repositories may use different open-source licenses depending on technical, research, and distribution requirements.  
> Licensing must remain clear, open, attributed, and consistent with governance.

---

## 🧭 Licensing Decision Tree

```text
Is the repository code?
├─ Yes → choose a code license
│  ├─ Broad reuse / adoption / clear legal framework → Apache 2.0
│  ├─ Minimal permissive reuse → BSD 2-Clause
│  ├─ Permissive + name-use protection → BSD 3-Clause
│  ├─ Strong copyleft / derivatives stay open → GPL v3.0
│  ├─ Legacy copyleft compatibility → GPL v2.0
│  ├─ Library-level copyleft → LGPL v3.0
│  └─ Minimal permissive fallback → MIT
└─ No → is it documentation / research text?
   ├─ Yes → CC BY-SA 4.0
   └─ No → declare the repository-specific policy clearly
