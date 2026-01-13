# CI-CD-Pipeline (GitHub Pages Implementation)

This repository demonstrates a lightweight CI/CD approach using **GitHub Pages** and **GitHub Actions**. It is designed as the "Platform as a Service" (PaaS) baseline to compare against an IaaS-based AWS implementation.

## 📁 Repository Structure
* `.github/workflows/`: Contains the YAML files for automated deployment.
* `index.html`: The main entry point for the static site.

## 🚀 The Pipeline
1.  **Trigger:** On every `push` to the `main` branch.
2.  **Action:** GitHub Actions runner initializes.
3.  **Deploy:** Automatically pushes the build artifacts to the `gh-pages` branch/environment.

---

## ⚖️ Comparison: GitHub Pages vs. AWS

| Feature | GitHub Pages (PaaS) | AWS Implementation (IaaS) |
| :--- | :--- | :--- |
| **Primary Use** | Static Sites, Documentation, Portfolios. | Enterprise Applications, APIs, Microservices. |
| **Setup Time** | < 5 Minutes. | ~1-2 Hours (initial setup). |
| **Security** | Managed by GitHub. | Managed by User (IAM, Security Groups). |
| **Maintenance** | Zero maintenance. | High (Patching, monitoring instances). |
| **Integration** | Built-in to GitHub ecosystem. | Requires cross-platform authentication. |

**Conclusion:** This repo demonstrates the "Developer Experience" (DX) advantage of GitHub Pages for rapid frontend deployment where server management is unnecessary.
