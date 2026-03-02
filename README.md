<h1 align="center">
  MagazineHub 📰
</h1>

<p align="center">
  <strong>A comprehensive enterprise web platform for managing, collaborating, and publishing university faculty articles.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/.NET%208.0-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET 8" />
  <img src="https://img.shields.io/badge/React%2018-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white" alt="SQL Server" />
</p>

---

## 📖 About The Project

> Empowering academic contribution through seamless collaboration and robust management.

**MagazineHub** is an enterprise-level web application developed to streamline the process of managing and publishing articles within a university ecosystem. The platform bridges the gap between students (contributors) and faculty administration, providing a seamless workflow for article submission, review, feedback, and final publication. 

By categorizing access into distinct, hierarchical user roles, MagazineHub ensures that every contribution is properly vetted, securely stored, and elegantly showcased to the public, making it a definitive tool for academic content management.

---

## 👥 Team Members

| Name | UK Student ID | Vietnam Student ID |
| :--- | :--- | :--- |
| **Le Nguyen Khang** | 001391649 | GCS210650 |
| **Pham Xuan Trung** | 001391533 | GCS210791 |
| **Nguyen Hong Nhat** | 001391424 | GCS210149 |
| **Le Ngoc Phuong Anh** | 001395068 | GCS210156 |

---

## ✨ Key Features & User Roles

MagazineHub operates on a strict Role-Based Access Control (RBAC) system, ensuring data security and a tailored user experience for every stakeholder.

| Role | Responsibilities & Features |
| :--- | :--- |
| **🛡️ Admin** | **System Core Management:** Oversee the entire system structure.<br>**Entity Control:** Create and manage Faculties, Academic Periods, and overarching User Accounts (including role/faculty reassignment and deactivation). |
| **👔 Manager** | **Global Oversight:** View, search, filter, and sort all contributions across the entire university.<br>**Analytics & Export:** Access the Manager Dashboard for statistics and download all system contributions collectively via ZIP.<br>**Onboarding:** Create accounts for Faculty Coordinators. |
| **📋 Coordinator** | **Faculty Management:** Oversee articles specific to their assigned faculty.<br>**Workflow & Moderation:** Review submissions, provide detailed feedback, and Approve/Reject/Publish contributions.<br>**Analytics & Onboarding:** Access the Coordinator Dashboard and create accounts for Contributors. |
| **✍️ Contributor** | **Content Creation:** Submit new articles (documents & images) for specific academic periods.<br>**Contribution Tracking:** Track submission status, edit details, view feedback, and browse other approved faculty contributions. |
| **🌍 Guest** | **Public Access:** Browse, search, filter, and download publicly "Published" contributions without needing an account. |

*(All authenticated users can manage their profiles, update avatars, and securely reset their passwords).*

---

## 🛠️ Technology Stack

Our project utilizes a robust software stack to ensure optimal performance, maintainability, and scalability:

### 🎨 Front-End
- **Framework:** React 18.2 (Component-based architecture)
- **UI & Styling:** TailwindCSS (Utility-first styling) & HeadlessUI (Accessible modular components)

### ⚙️ Back-End
- **Framework:** .NET Core 8.0 (High-performance API foundation)
- **Documentation:** Swagger/OpenAPI

### ☁️ Database
- **Production:** Microsoft SQL Server (Robust data handling & integrity)
- **Development:** SQLite (Lightweight & portable for team collaboration)

---

## 🏗️ System Architecture

### 1. Entity-Relationship Diagram (ERD)
*Outlines the database schema, mapping the relationships between Users, Faculties, Periods, Contributions, and Roles.*
<p align="center">
  <img width="975" height="849" alt="image" src="https://github.com/user-attachments/assets/4a44cd20-4ac2-4346-99ed-a19e534c60a5" />
</p>

### 2. Use Case Diagram
*Visualizes the functional interactions and permission boundaries between Admins, Managers, Coordinators, Contributors, and Guests.*
<p align="center">
 <img width="975" height="832" alt="image" src="https://github.com/user-attachments/assets/faccb372-6da3-4d59-9c0d-73fe13f81dc1" />
</p>

---

## 🔑 Test Accounts

For evaluation and testing purposes, you can use the following pre-configured accounts:

| Role | Email / Username | Password | Description |
| :--- | :--- | :--- | :--- |
| **Admin** | `admin@gmail.com` | `Abcd@1234` | Super admin of the website |
| **Manager** | `manager@gmail.com` | `Abcd@1234` | Marketing manager |
| **Coordinator** | `it@gmail.com` | `Abcd@1234` | Coordinator of IT faculty |
| **Contributor** | `contributorit1@gmail.com` | `Abcd@1234` | Contributor of IT faculty |

---

## 📸 User Interface Showcase

*A comprehensive visual tour of the MagazineHub platform across all distinct modules and user roles.*

### 🔌 API & System 
<table align="center">
  <tr>
    <td align="center" width="100%">
      <img width="914" height="609" alt="image" src="https://github.com/user-attachments/assets/fc4fa264-3ea9-4875-8d7e-0cc741624434" />
      <br/><b>Fig 31: Swagger API Documentation for Back-End</b>
    </td>
  </tr>
</table>

### 🔐 Authentication & Profile Management
<table align="center">
  <tr>
    <td align="center" width="50%">
       <img width="975" height="455" alt="image" src="https://github.com/user-attachments/assets/ecd13e4c-37b7-44f0-9598-041c071f710f" />
      <br/><b>Fig 32: Login Screen</b>
    </td>
    <td align="center" width="50%">
       <img width="813" height="379" alt="image" src="https://github.com/user-attachments/assets/dc7758ff-238a-4da5-86bc-57766e6c7b5a" />
      <br/><b>Fig 33: First-Time Login (Granted Account)</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img width="975" height="362" alt="image" src="https://github.com/user-attachments/assets/5d8a2a66-fba5-4c59-af4d-d592980b142b" />
      <br/><b>Fig 34: Change Initial Password</b>
    </td>
    <td align="center" width="50%">
      <img width="1025" height="351" alt="image" src="https://github.com/user-attachments/assets/ef6c6426-1ebc-4ed8-8a0a-4dc8c3fbb42d" />
      <br/><b>Fig 35: Change Initial Password Successfully</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img width="975" height="305" alt="image" src="https://github.com/user-attachments/assets/87e502be-ab91-43da-8ccf-da970ea7ea8c" />
      <br/><b>Fig 36: Reset Password (Step 1)</b>
    </td>
    <td align="center" width="50%">
      <img width="933" height="352" alt="image" src="https://github.com/user-attachments/assets/39b52e6b-d7a1-40c3-ab64-db3fc38fd396" />
      <br/><b>Fig 37: Reset Password (Step 2)</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img width="803" height="277" alt="image" src="https://github.com/user-attachments/assets/fd0f7ccf-68f1-43a1-aaf1-73b3a355b8b0" />
      <br/><b>Fig 38: Reset Password OTP Email</b>
    </td>
    <td align="center" width="50%">
     <img width="614" height="367" alt="image" src="https://github.com/user-attachments/assets/1dfc062a-8742-46b0-bba3-79940fd2427a" />
      <br/><b>Fig 39: Reset Password Successfully</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
       <img width="975" height="395" alt="image" src="https://github.com/user-attachments/assets/e18ec669-e51c-452c-8da2-4308a7d5b175" />
      <br/><b>Fig 40: Update Profile (Step 1)</b>
    </td>
    <td align="center" width="50%">
      <img width="975" height="447" alt="image" src="https://github.com/user-attachments/assets/c3442a85-2137-4bcc-84d0-ef76816f3245" />
      <br/><b>Fig 41: Update Profile (Step 2)</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img width="938" height="345" alt="image" src="https://github.com/user-attachments/assets/dfbf5609-a5b0-4ce7-804c-c30f929a67d4" />
      <br/><b>Fig 42: Update Profile Successfully</b>
    </td>
    <td align="center" width="50%">
      </td>
  </tr>
</table>

### 🌍 Guest View & Public Portal
<table align="center">
  <tr>
    <td align="center" width="50%">
      <img width="975" height="651" alt="image" src="https://github.com/user-attachments/assets/b5db8558-1216-461a-b131-69299a729e2c" />
      <br/><b>Fig 43: Home Page (Section 1)</b>
    </td>
    <td align="center" width="50%">
      <img width="842" height="399" alt="image" src="https://github.com/user-attachments/assets/1e2493e7-b185-4823-beb6-9f973ae3e657" />
      <br/><b>Fig 44: Home Page (Section 2)</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
     <img width="489" height="504" alt="image" src="https://github.com/user-attachments/assets/847862ba-aba8-471e-a976-ad84c38aa2f1" />
      <br/><b>Fig 45: Home Page Responsiveness</b>
    </td>
    <td align="center" width="50%">
      <img width="975" height="462" alt="image" src="https://github.com/user-attachments/assets/66f2bba4-b4f4-4dc5-8b1a-0b4b7849866e" />
      <br/><b>Fig 46: Exploring Published Contributions</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
       <img width="504" height="615" alt="image" src="https://github.com/user-attachments/assets/eb830629-8dc1-461e-8cbd-d9396d79fdfe" />
      <br/><b>Fig 47: Explore Page Responsiveness</b>
    </td>
    <td align="center" width="50%">
      </td>
  </tr>
</table>

### ✍️ Contributor Hub
<table align="center">
  <tr>
    <td align="center" width="50%">
    <img width="464" height="322" alt="image" src="https://github.com/user-attachments/assets/35be0f49-7d0c-46cb-acb8-59ea51729ce6" />
      <br/><b>Fig 48: Contributor Page Access</b>
    </td>
    <td align="center" width="50%">
      <img width="1038" height="314" alt="image" src="https://github.com/user-attachments/assets/1b9ee98a-45ff-4aef-9de4-72285d45dd09" />
      <br/><b>Fig 49: Submit Contribution (Select Period)</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
     <img width="955" height="369" alt="image" src="https://github.com/user-attachments/assets/2bcadf5a-b279-4ece-8519-d2c57c5f06ef" />
      <br/><b>Fig 50: Submit Contribution (Details)</b>
    </td>
    <td align="center" width="50%">
     <img width="975" height="367" alt="image" src="https://github.com/user-attachments/assets/8f8d17f4-730d-4b16-931f-48e2fc513661" />
      <br/><b>Fig 51: Submit Contribution (Confirm)</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img width="784" height="352" alt="image" src="https://github.com/user-attachments/assets/aad00c8a-9dcb-4240-8d3e-1895bbc14088" />
    </td>
    <td align="center" width="50%">
     <img width="975" height="201" alt="image" src="https://github.com/user-attachments/assets/b5988ae3-3971-4d0b-afa0-36c25b53d3e6" />
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img width="975" height="463" alt="image" src="https://github.com/user-attachments/assets/f9b82278-84fb-4276-9624-45538d39854b" />
      <br/><b>Fig 54: View My Contributions</b>
    </td>
    <td align="center" width="50%">
      <img width="838" height="328" alt="image" src="https://github.com/user-attachments/assets/a08593ca-4a41-41ae-9344-c4cd260233c3" />
      <br/><b>Fig 55: Update Available Contribution</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img width="975" height="396" alt="image" src="https://github.com/user-attachments/assets/4d3725a3-84f1-42d9-8577-eb4c0b7498f9" />
      <br/><b>Fig 56: Update Processed Contribution</b>
    </td>
    <td align="center" width="50%">
      <img width="975" height="387" alt="image" src="https://github.com/user-attachments/assets/d279a71b-2ed1-4d95-942e-a8418e139514" />
      <br/><b>Fig 57: Status Reverted to Processing</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img width="975" height="257" alt="image" src="https://github.com/user-attachments/assets/f53c580d-eb1a-43c7-b4e0-d767dd4f7fce" />
      <br/><b>Fig 58: Update Notification Email</b>
    </td>
    <td align="center" width="50%">
   <img width="975" height="460" alt="image" src="https://github.com/user-attachments/assets/31c44f26-48c0-49b0-8c20-85ebaf809103" />
      <br/><b>Fig 59: View Faculty's Approved Articles (1)</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
  <img width="975" height="462" alt="image" src="https://github.com/user-attachments/assets/6cc7ee69-9cf8-41d2-9048-a2db56dda818" />
      <br/><b>Fig 60: View Faculty's Approved Articles (2)</b>
    </td>
    <td align="center" width="50%">
      </td>
  </tr>
</table>

### 📋 Coordinator Workflow
<table align="center">
  <tr>
    <td align="center" width="50%">
       <img width="975" height="280" alt="image" src="https://github.com/user-attachments/assets/879720e6-8e7d-46e6-ab39-68c8acbe1ee4" />
      <br/><b>Fig 61: Create Contributor Account</b>
    </td>
    <td align="center" width="50%">
      <img width="975" height="366" alt="image" src="https://github.com/user-attachments/assets/46d4b29a-83cd-4aba-96bf-c0b2412d922c" />
      <br/><b>Fig 62: Contributor Account Details Email</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img width="975" height="463" alt="image" src="https://github.com/user-attachments/assets/cea71d2d-0f33-41ae-877b-1cb8dbc74363" />
      <br/><b>Fig 63: View Faculty Contributions</b>
    </td>
    <td align="center" width="50%">
    <img width="975" height="351" alt="image" src="https://github.com/user-attachments/assets/18f2f18e-7578-40cb-86a2-54bb7b37ed5b" />
      <br/><b>Fig 64: Provide Feedback</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img width="975" height="294" alt="image" src="https://github.com/user-attachments/assets/ad4723f5-e8c2-4d38-a2a9-8bc20bb1d30d" />
      <br/><b>Fig 65: Approve/Reject Contribution</b>
    </td>
    <td align="center" width="50%">
       <img width="975" height="232" alt="image" src="https://github.com/user-attachments/assets/3eedb3f5-c811-4dea-afeb-99b3efe71b45" />
      <br/><b>Fig 66: Approval Email Notification</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img width="975" height="304" alt="image" src="https://github.com/user-attachments/assets/c5457a1e-3af7-4b2c-9132-65f759391997" />
      <br/><b>Fig 67: Publish/Unpublish Contribution</b>
    </td>
    <td align="center" width="50%">
    <img width="898" height="238" alt="image" src="https://github.com/user-attachments/assets/ecf3e479-fa68-42a9-bc3e-551b3d60c3ed" />
      <br/><b>Fig 68: Published Email Notification</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img width="975" height="423" alt="image" src="https://github.com/user-attachments/assets/8ac5c321-4f4f-41f3-8487-5aa617f1c8b2" />
      <br/><b>Fig 69: Coordinator Dashboard</b>
    </td>
    <td align="center" width="50%">
      </td>
  </tr>
</table>

### 👔 Manager Overview
<table align="center">
  <tr>
    <td align="center" width="50%">
      <img width="913" height="325" alt="image" src="https://github.com/user-attachments/assets/b7b8e34a-147a-43b3-bef9-f272b8311160" />
      <br/><b>Fig 70: Create Coordinator Account</b>
    </td>
    <td align="center" width="50%">
     <img width="975" height="399" alt="image" src="https://github.com/user-attachments/assets/d713fbf4-4ba5-4092-ab8c-88e697111ecd" />
      <br/><b>Fig 71: Coordinator Account Details Email</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
     <img width="975" height="461" alt="image" src="https://github.com/user-attachments/assets/dc61c453-8dd1-4175-8db7-d9702cac8e28" />
      <br/><b>Fig 72: Global Contributions View</b>
    </td>
    <td align="center" width="50%">
     <img width="975" height="462" alt="image" src="https://github.com/user-attachments/assets/05354a81-7a99-4bb2-a4a6-04829bf79ed4" />
      <br/><b>Fig 73: Download Contributions as ZIP</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
  <img width="936" height="442" alt="image" src="https://github.com/user-attachments/assets/807aa0fe-e72b-4b50-9b2e-da1e33f7a146" />
      <br/><b>Fig 74: Manager Dashboard (Overview)</b>
    </td>
    <td align="center" width="50%">
     <img width="975" height="465" alt="image" src="https://github.com/user-attachments/assets/68437803-64b9-4eec-93e2-af9dcf0a7d4b" />
      <br/><b>Fig 75: Manager Dashboard (Detailed)</b>
    </td>
  </tr>
</table>

### 🛡️ Admin Control Panel
<table align="center">
  <tr>
    <td align="center" width="50%">
     <img width="975" height="460" alt="image" src="https://github.com/user-attachments/assets/3e964287-987b-4709-8d41-e60b3e4be8d0" />
      <br/><b>Fig 76: Admin User Management Table</b>
    </td>
    <td align="center" width="50%">
    <img width="975" height="269" alt="image" src="https://github.com/user-attachments/assets/82734299-9873-4971-8126-ee9dcecf3686" />
      <br/><b>Fig 77: Modify User Role</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
     <img width="975" height="316" alt="image" src="https://github.com/user-attachments/assets/311645db-64e6-4399-9c38-04d91b55a426" />
      <br/><b>Fig 78: Modify User Faculty</b>
    </td>
    <td align="center" width="50%">
     <img width="975" height="393" alt="image" src="https://github.com/user-attachments/assets/295a0392-547b-4501-a95e-522c8cb92174" />
      <br/><b>Fig 79: Academic Periods Management</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
     <img width="975" height="393" alt="image" src="https://github.com/user-attachments/assets/8e87bab6-36e5-40db-8547-cc6f49d776f4" />
      <br/><b>Fig 80: Create New Period</b>
    </td>
    <td align="center" width="50%">
    <img width="975" height="385" alt="image" src="https://github.com/user-attachments/assets/a0d43ec7-8bce-4c23-85fd-c89cb25fe1b4" />
      <br/><b>Fig 81: Update Existing Period</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
     <img width="975" height="281" alt="image" src="https://github.com/user-attachments/assets/0a0c274f-cd54-4eea-a303-fdebeabb504b" />
      <br/><b>Fig 82: Faculty Management Dashboard</b>
    </td>
    <td align="center" width="50%">
      <img width="975" height="353" alt="image" src="https://github.com/user-attachments/assets/5e0d23e1-2641-4f2f-8437-a8f26a2ddd20" />
      <br/><b>Fig 83: Create New Faculty</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img width="975" height="341" alt="image" src="https://github.com/user-attachments/assets/2eb9085c-68ea-4401-aace-cb7ae43d6e83" />
      <br/><b>Fig 84: Update Existing Faculty</b>
    </td>
    <td align="center" width="50%">
<img width="975" height="414" alt="image" src="https://github.com/user-attachments/assets/c00aaa67-a0a5-448b-b642-c4cedd588c7e" />
      <br/><b>Fig 85: Global Account Creation Tool</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="100%" colspan="2">
      <img width="975" height="398" alt="image" src="https://github.com/user-attachments/assets/2cb79587-05b0-45fd-a185-2fc11820d71e" />
      <br/><b>Fig 86: Account Credentials Dispatch Email</b>
    </td>
  </tr>
</table>

---

## 🚀 Getting Started

To explore the codebase or run MagazineHub locally, clone the repository:

```bash
git clone https://github.com/khangln2111/Greenwich-COMP1640-EWSD-MagazineHub.git
