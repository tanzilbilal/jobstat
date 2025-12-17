# JobStat

JobStat is a full‑stack job application tracking platform that helps users manage, track, and visualize their job applications efficiently. It provides a clean, responsive interface to monitor application status, view analytics, and stay organized throughout the job‑search process.

---

## 🚀 Features

* **Job Tracking** – Add and manage job applications with details like company, role, and location
* **Status Management** – Update application status (Applied, Interview, Rejected, Offer, etc.)
* **Analytics Dashboard** – Visualize applications with charts and monthly statistics
* **Dark Mode** – Optimized UI for low‑light environments
* **Responsive Design** – Works seamlessly on desktop, tablet, and mobile devices

---

## 🛠 Tech Stack

* **Frontend:** Next.js, React, TypeScript
* **Backend:** Next.js API Routes
* **Database:** PostgreSQL (via Prisma ORM)
* **Styling:** Tailwind CSS
* **Charts:** Chart.js / Recharts
* **ORM:** Prisma
* **Deployment:** Vercel (recommended)

---

## 📂 Project Structure

```
JobStat/
├── app/
├── components/
├── prisma/
│   ├── schema.prisma
│   ├── seed.js
├── utils/
├── public/
├── README.md
└── package.json
```

---

## ⚙️ Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/tanzilbilal/jobstat.git
cd jobstat
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Configure environment variables

Create a `.env` file:

```env
DATABASE_URL=your_database_url
```

### 4️⃣ Setup database

```bash
npx prisma generate
npx prisma migrate dev
npx prisma db seed
```

### 5️⃣ Run the application

```bash
npm run dev
```

Open `http://localhost:3000` in your browser.

---

## 📸 Screenshots

Below are some screenshots showcasing the main features of JobStat:

* Dashboard view showing tracked job applications
* Analytics view with monthly statistics
* Dark mode interface for better readability

> You can add screenshots by placing image files in the root or `public/` folder and referencing them like:
> `![Dashboard](image-1.png)`

---

## 🎯 Use Case

JobStat is ideal for students and professionals who are actively applying to jobs and want a centralized, visual way to track applications and progress.

---

## 🔮 Future Enhancements

* Authentication (NextAuth)
* Resume upload per application
* Email reminders for follow‑ups
* Advanced analytics & filters

---

## 👤 Author

**Tanzil Bilal Mohammed**
Master’s in Computer Science
Aspiring Software Engineer

---

⭐ If you find this project useful, feel free to star the repository!

