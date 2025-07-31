# 💼 WorkHop / PocketJob / EarnEase

**Connecting students with short-term gigs.**  
An intuitive platform where employers (Posters) can post temporary jobs and students (Finders) can discover, apply, and negotiate for those jobs — with wallet tracking and job completion confirmations.

---

## 🔗 Live Preview

🚀 [View Live App on Vercel](https://part-time-job-finder-for-students.vercel.app/)

---

## 🌟 Project Overview

**WorkHop** enables:
- 👨‍🎓 **Students (Finders)** to browse and apply for part-time jobs.
- 🧑‍💼 **Employers (Posters)** to post jobs, manage applications, and track completion.

---

## 🔐 Authentication & Role Management

- 🔑 Secure login/signup with role selection:
  - `Finder (Student)`
  - `Poster (Employer)`
- Role determines dashboard access and privileges.

### ✅ Verification

| Role    | Method                                             |
| ------- | -------------------------------------------------- |
| Finder  | Aadhaar/DL upload (masked), admin verification     |
| Poster  | OTP verification + optional business verification  |

---

## 🧭 Navigation & Layout

### 🌐 Top Navigation

| Role    | Sections                                           |
| ------- | -------------------------------------------------- |
| Finder  | Find a Job, Application Status, Past Jobs, Wallet  |
| Poster  | Post a Job, Application Status, Past Jobs          |

Each user sees only relevant features.

---

## 🎓 Finder Dashboard

### 🔍 Find a Job
- Browse job cards with:
  - Title, Pay, Distance, Timings, Negotiation status
- View full job details & apply or negotiate

### 📋 Application Status
- Track status of applied/negotiated jobs:
  - `Pending`, `Accepted`, `Rejected`, `Negotiating`
- View status messages and history

### 📁 Past Jobs
- View completed job history:
  - Pay, Date, Employer, Rating

### 💼 Wallet
- Total earned, pending payments, job list
- Filter by `Paid` / `Pending`
- Sort by `Date`, `Pay`, `Duration`

---

## 🧑‍💼 Poster Dashboard

### 📤 Post a Job
- Post job with:
  - Title, Domain, Description, Pay (negotiable), Skills, Preferences, Address

### 📬 Application & Negotiation Status
- Accept/Reject applications
- View & respond to negotiation requests
- Confirm selected student & agreed pay

### 📁 Past Posted Jobs
- Full job posting history with details

---

## 🔁 Use Cases

### ✅ Direct Job Application
1. Poster posts job
2. Finder applies directly
3. Poster accepts/rejects
4. Application status updates for both

### ✅ Negotiated Application
1. Finder makes pay offer
2. Poster accepts/rejects
3. If accepted, pay is locked and job is confirmed

---

## ✅ Completion & Payment Flow

- Poster marks job complete
- Wallet is updated for Finder
- Notification sent:  
  > “🎉 Job marked complete. ₹600 added to wallet.”

---

## 🔔 Notifications

| User    | Triggered On                                      |
| ------- | -------------------------------------------------- |
| Finder  | Application/Negotiation accepted/rejected, Payment |
| Poster  | New applications, Negotiation requests, Reminders  |

---

## 🗂️ Database Schema (Essentials)

### `users`
- `user_id`, `name`, `role`, `email`, `verified`, `aadhaar_masked`

### `jobs`
- `job_id`, `poster_id`, `title`, `domain`, `skills`, `pay`, `negotiable`, `timing`, `location`, `duration`, `instructions`

### `applications`
- `application_id`, `student_id`, `job_id`, `status`, `agreed_pay`

### `negotiations`
- `negotiation_id`, `student_id`, `job_id`, `requested_pay`, `status`

### `wallet_entries`
- `entry_id`, `student_id`, `job_id`, `amount`, `status`, `duration`, `created_at`

---

## 🗓️ MVP Development Timeline

| Week | Deliverable                             |
|------|-----------------------------------------|
| 1    | UI Design + Wireframes                  |
| 2    | Auth + Role-Based Login                 |
| 3    | Job Posting Flow                        |
| 4    | Finder Job Discovery + Apply/Negotiate  |
| 5    | Notifications + Job Completion Logic    |
| 6    | Wallet Integration                      |
| 7    | Full Dashboard UX + Filters             |
| 8    | Final QA and Launch 🚀                  |

---

## 🛠️ Tech Stack

| Layer     | Technology                        |
|----------|-----------------------------------|
| Frontend | `Next.js`, `Tailwind CSS`, `Vercel` |
| Backend  | `Node.js`, `Express` *(optional)* |
| DB       | `MongoDB` / `PostgreSQL` *(planned)* |
| Auth     | Role-based login + Aadhaar/OTP     |
| Storage  | Cloudinary / Firebase *(optional)* |
| Maps     | Google Maps API                    |

---

## 📃 License

MIT License. See `LICENSE` file for details.

---

## 🙋‍♂️ Maintainer

**Hemanth Kumar Somana**  
📧 `hemanthkumarsomana@gmail.com`  
🔗 GitHub: [@Hemanth-Kumar-Somana](https://github.com/Hemanth-Kumar-Somana)

