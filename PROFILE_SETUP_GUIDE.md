# 🚀 GitHub Profile Setup & Verification Guide

This guide provides instructions to finalize your GitHub profile setup, configure account metadata, set repository pins, and inspect the verification report.

---

## 1. GitHub Account Settings & Profile Photo Configuration

### A. Setting Your Profile Avatar
GitHub does not permit 3rd-party bots or automated tools to change account profile photos via the API for security reasons. Your cropped high-resolution headshot has been saved directly to your Desktop and in this repository:

1. Open **[GitHub Profile Settings](https://github.com/settings/profile)** in your browser.
2. In the **Profile picture** section on the top right, click **Edit** &rarr; **Upload a photo...**.
3. Select the photo saved on your Desktop:
   `c:\Users\vpnna\OneDrive\Desktop\github-profile-photo.jpg`
4. Adjust the circular crop if desired and click **Set new profile picture**.

---

### B. Account Metadata Settings

On the same **[GitHub Settings &rarr; Public Profile](https://github.com/settings/profile)** page, fill out these fields:

| Field | Recommended Value | Why |
| :--- | :--- | :--- |
| **Name** | `Nagendra Vannempalli` | Ensures full real name appears cleanly on GitHub search and profile headers. |
| **Public Email** | `vpnnagendra@gmail.com` | Verified communication channel for recruiters and hiring managers. |
| **Bio** | `Python AI Developer \| Backend Engineer • Engineering high-throughput MySQL pipelines & intelligent LLM-driven applications.` | Consistent 160-character elevator pitch matching your profile banner. |
| **URL (Website)** | `https://github.com/vpnnagendra-a11y/job-nex-project2` | Directly routes profile visitors to your flagship full-stack system. |
| **Location** | `Bengaluru, India` | Sets correct hiring market context. |
| **Timezone** | `Asia/Kolkata` (`IST`, `UTC+05:30`) | Clarifies working hours for global and local teams. |

---

## 2. Six Recommended Pinned Repositories

On your main profile page (**[github.com/vpnnagendra-a11y](https://github.com/vpnnagendra-a11y)**), click **"Customize your pins"** and select these 6 repositories in this exact order:

1. 📌 **`job-nex-project2`**  
   *Justification*: Your flagship full-stack system demonstrating FastAPI REST APIs, JWT role-based access control (Admin & Recruiter modules), MySQL database schema design, and candidate-matching algorithms.
2. 📌 **`jobnex_analgonex_product`**  
   *Justification*: The core algorithmic analysis engine showcasing semantic resume-to-job matching, skill extraction, gap identification, and database persistence.
3. 📌 **`algonex_intern_management_system`**  
   *Justification*: Enterprise backend workflow application exhibiting complex relational schema modeling, database triggers, and stored procedures.
4. 📌 **`ALGONEX_PAYMENT_SYSYTEM2`**  
   *Justification*: Backend financial and transaction tracking system demonstrating state-machine validation, audit logging, and SQL data integrity.
5. 📌 **`Data-Structure-Algorithm`**  
   *Justification*: Demonstrates fundamental algorithmic competency, computational efficiency, data structure implementations, and optimization.
6. 📌 **`-loops-and-conditions`**  
   *Justification*: Core logic architecture testbed illustrating clean Python coding conventions, iteration benchmarks, and automated condition testing.

---

## 3. How to Push the Profile to GitHub

The repository is already cloned at `c:\Users\vpnna\OneDrive\Desktop\vpnnagendra-a11y`. To push all changes directly:

```bash
cd "c:\Users\vpnna\OneDrive\Desktop\vpnnagendra-a11y"
git add .
git commit -m "Build professional animated profile with 3D monogram, verified achievements, and responsive assets"
git push origin main
```

---

## 4. Verification & QA Report

| Test Item | Status | Verification Detail |
| :--- | :---: | :--- |
| **Hero Animation (Desktop)** | ✅ **PASS** | 6.0-second calm sinusoidal loop featuring isometric 3D "NV" monogram, rotating orbital particle ring, and gradient light sweep. |
| **Mobile Responsiveness** | ✅ **PASS** | `<picture>` media query automatically switches to `assets/animated-hero-mobile.svg` on viewports &le; 600px with stacked typography. |
| **Reduced Motion Fallback** | ✅ **PASS** | Detects `@media (prefers-reduced-motion: reduce)` in both SVG and HTML, falling back to `assets/hero-static.svg`. |
| **Asset Localization** | ✅ **PASS** | All animation assets (`assets/`) and editable vector sources (`design/`) are committed directly inside the repository. |
| **Working Links** | ✅ **PASS** | Portfolio link points to `job-nex-project2`, LinkedIn points to `linkedin.com/in/nagendra-vannempalli`, Email points to `mailto:vpnnagendra@gmail.com`. |
| **Verified Information** | ✅ **PASS** | Uses strictly real experience metrics (R² &gt; 0.85, 30% pipeline speedup, 40% query throughput, 20+ scripts at Algonex IT Solutions). Zero fabricated awards or skills. |
| **GitHub Actions Automation** | ✅ **PASS** | `.github/workflows/profile-stats.yml` created with daily cron schedule and asset integrity checks. |

