# BlenderHub LMS & 3D Asset Marketplace — Digital Asset Distribution & E-Learning Platform

[![PHP Version](https://img.shields.io/badge/PHP-8.2%2B-777bb4?style=for-the-badge&logo=php&logoColor=white)](https://php.net)
[![3D Pipeline](https://img.shields.io/badge/3D%20Engine-Blender%20%7C%20GLTF%20%7C%20FBX-F5792A?style=for-the-badge&logo=blender&logoColor=white)](https://blender.org)
[![MySQL](https://img.shields.io/badge/MySQL-8.0%2B-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://mysql.com)
[![Status](https://img.shields.io/badge/Build-Production%20Hardened-success?style=for-the-badge)](https://github.com/RG-Creators)

> **Public Showcase Repository**: This repository provides high-level architectural documentation, system workflow diagrams, and specifications for the **BlenderHub LMS & 3D Asset Marketplace**. Full underlying source code and proprietary creator payout modules are held securely in a private production repository.

---

## 🏗️ System Architecture & Digital Asset Pipeline

```
+-------------------------------------------------------------------------------+
|                            COMMUNITY & CREATOR TIER                           |
|   - 3D Artists submit models (.blend, .fbx, .obj) & course curricula         |
|   - Creator Verification & Portfolio Audit Portal (`pages/applyforcreator`)  |
+---------------------------------------|---------------------------------------+
                                        v
+-------------------------------------------------------------------------------+
|                        ADMINISTRATIVE CURATION ENGINE                         |
|   - Content Moderation & Topology Quality Checks (`admin/views/`)             |
|   - Asset Pricing Approval & Royalty Tiering (`admin/`)                       |
+---------------------------------------|---------------------------------------+
                                        v
+-------------------------------------------------------------------------------+
|                         MARKETPLACE & LEARNING SUITE                          |
|   - Asset Storefront (`pages/assets.php`): Filter by polycount, textures      |
|   - Interactive Course Player: Multi-module structured video lessons          |
|   - On-Demand Commission Engine: Custom 3D Model RFQs & Bidding System        |
|   - SharePay Transaction Gate: Cryptographic OTP authorization                |
+---------------------------------------|---------------------------------------+
                                        v
+-------------------------------------------------------------------------------+
|                         CREATOR MONETIZATION & PAYOUTS                        |
|   - Real-time creator revenue ledger (`user/creator-panel.php`)               |
|   - Automated payout accounting & purchase history auditing                   |
+-------------------------------------------------------------------------------+
```

---

## ⚡ Core Platform Highlights

### 1. 3D Digital Asset Distribution Hub
- Comprehensive metadata management: Polycount, vertex count, PBR texture maps, rigged/animated status, and file format compatibility (`.blend`, `.fbx`, `.obj`, `.gltf`).
- Protected direct download links with tokenized access authorization.

### 2. Comprehensive LMS Video Course Suite
- Structured multi-tier curriculum: Courses partitioned into Modules, Topics, and Subtopics with progress tracking.
- Dedicated student library (`pages/my_library.php`) with persistent access privileges.

### 3. Creator Economy & Commission Engine
- **Custom Model RFQs (`model_requests`)**: Users submit specific 3D model requirements with budget and reference imagery.
- **Competitive Bidding (`model_bids`)**: Verified creators place competitive proposals on open commissions.
- **Creator Dashboard (`user/creator-panel.php`)**: Live sales analytics, download counters, and payout disbursement tracking.

---

## 🛠️ Tech Stack

- **Backend**: Core PHP 8.2+ (Modular Architecture, MySQLi Prepared Statements, Session Protection)
- **Frontend**: Responsive CSS Grid / Flexbox, SweetAlert2 Dialogs, FontAwesome 6, Modern Typography
- **Database**: MySQL 8.0+ / MariaDB (Relational Model with Foreign Keys and B-Tree Performance Indexes)

---

## 🔒 Proprietary Code Notice
The underlying codebase, creator licensing algorithms, and payment verification mechanisms are privately maintained. For commercial partnerships, white-label inquiries, or architectural reviews, please contact:
- **Developer**: RG
- **Email**: [rgcreatorsofficial@gmail.com](mailto:rgcreatorsofficial@gmail.com)
- **Portfolio**: [rgcreators.netlify.app](https://rgcreators.netlify.app/)
