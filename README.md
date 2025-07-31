# 💼 Part time job finder for students(EarnEase)

**Connecting students with short-term gigs.**  
An intuitive platform where employers (Posters) can post temporary jobs and students (Finders) can discover, apply, and negotiate for those jobs — with wallet tracking and job completion confirmations.

---

## 🔗 Live Preview

🚀 [View Live App on Vercel](https://part-time-job-finder-for-students.vercel.app/)


A full-stack job marketplace platform connecting students (Finders) seeking part-time jobs with job Posters (Employers) who offer flexible, short-term gigs.

---

## 🚀 Features

### 🔵 For Posters (Employers)
- ✅ **Post Job**: Create and list jobs with details like title, description, location, and payment.
- 📋 **Manage Jobs**: Track and manage all previously posted jobs.
- 📥 **Applications**: View and approve/decline incoming applications from students.
- 💬 **Negotiation**: Handle negotiation requests from students regarding payment.
- 🤝 **Confirmed Jobs**: Track jobs that are confirmed and in progress.
- 🔔 **Notifications**: Get alerts on applications, negotiations, and completions.

### 🟢 For Finders (Students)
- 🔍 **Browse Jobs**: Explore available jobs from nearby posters.
- 📤 **Applied Jobs**: Track your job applications and their statuses.
- 💸 **Negotiation**: Send negotiation requests if you want better pay.
- 🤝 **Confirmed Jobs**: See jobs you’ve been selected for and are working on.
- 🕘 **Past Jobs**: View completed jobs.
- 💰 **Wallet**: Track your earnings and payments.
- 🔔 **Notifications**: Stay updated on job status and approvals.

---

## 🔁 Workflows

### ✅ Application Workflow
1. **Poster posts a job** → visible in **Finder’s Browse Jobs**.
2. Finder sends **accept request** → job moves to **Applied Jobs** (status: pending).
3. Poster views request in **Applications**, sees student details.
4. Poster **approves** → job moves to **Confirmed** in both dashboards.
5. After completion, Poster **marks as complete & makes payment** → job moves to:
   - **Past Jobs** (Finder)
   - **Manage Jobs** (Poster).

### 💬 Negotiation Workflow
1. **Poster posts a job** → visible in **Finder’s Browse Jobs**.
2. Finder sends **negotiation request** with updated amount → job moves to **Negotiation** (pending).
3. Poster views request in **Negotiation**, sees updated offer + student details.
4. Poster **approves** → price is updated in both dashboards, job moves to **Confirmed**.
5. Poster **marks as complete & makes payment** → job moves to:
   - **Past Jobs** (Finder)
   - **Manage Jobs** (Poster).

---

## 🛠 Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Supabase (for database + auth)
- **Deployment**: Vercel

---


---

## 📌 Notes

- Built entirely with client-side tech and Supabase.
- Mobile responsive UI for both Posters and Finders.
- Future enhancements may include:
  - Real-time chat 💬
  - Rating system ⭐
  - Enhanced wallet with transaction history 💳

---

## 🤝 Contributing

Feel free to fork this repository, raise issues, or submit pull requests!

---

## 📧 Contact

Made by **Hemanth Kumar**

GitHub: [@Hemanth-Kumar-Somana](https://github.com/Hemanth-Kumar-Somana)
