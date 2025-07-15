# 💸 AI-Powered Finance Management Platform

A full-stack personal finance application built with **Next.js**, **Tailwind CSS**, **Supabase**, and **Gemini AI**. This platform allows users to manage their income, expenses, and budgets with intelligent features like AI-powered **receipt scanning**, **smart categorization**, and **monthly financial insights**.

---

## 🚀 Features

- 🔐 **Authentication**: Secure sign-in/sign-up using [Clerk](https://clerk.dev)
- 📥 **Income & Expense Tracking**: Add and view transactions across accounts
- 🧠 **AI Receipt Scanning**: Upload receipts and auto-fill transactions using [Gemini API](https://deepmind.google/technologies/gemini/)
- 📊 **Smart Categorization**: Automatically detect expense categories with AI
- 📈 **Monthly Reports**: View financial summaries and visual insights
- 💰 **Budgeting & Alerts**: Set monthly budgets and receive alerts when overspending
- 🔁 **Recurring Transactions**: Handle monthly or weekly recurring payments
- 📧 **Email Notifications**: Send budget alerts and monthly reports via [Resend API](https://resend.com/)
- 🔒 **Secure & Responsive UI**: Built with Tailwind CSS and optimized for all devices

---

## 🧰 Tech Stack

| Frontend            | Backend              | AI & Tools          | Deployment |
|---------------------|----------------------|---------------------|------------|
| Next.js (React)     | Supabase (PostgreSQL)| Gemini API          | Vercel     |
| Tailwind CSS        | Prisma ORM           | Clerk (Auth)        | GitHub     |
| Recharts            |                      | Resend (Emails)     |            |

---

## 🛠️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/Wamiquemashhadi03/my-ai-financing.git
cd my-ai-financing
```


### 2. Install Dependencies

```bash
npm install
# or
yarn install
```

### 3. Create `.env.local` File

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_key
CLERK_SECRET_KEY=your_key
NEXT_PUBLIC_SUPABASE_URL=your_url
SUPABASE_SERVICE_ROLE_KEY=your_key
RESEND_API_KEY=your_key
GEMINI_API_KEY=your_key
```

### 4. Run the Development Server

```bash
npm run dev
```

---

## 🔄 Project Structure

```
/
├── app/                # App routes and layouts (Next.js App Router)
├── components/         # Reusable UI components
├── hooks/              # Custom React hooks
├── lib/                # Helpers and API integrations
├── prisma/             # Database schema and migrations
├── public/             # Static files (images, logos, etc.)
├── actions/            # Server-side API actions (e.g., for dashboard)
├── middleware.js       # Route protection and auth logic
├── tailwind.config.mjs # TailwindCSS config
├── next.config.mjs     # Next.js config
├── README.md

```


---

## 📦 Deployment

* 💻 Will soon be deployed on [Vercel](https://vercel.com/)
* Ensure all environment variables from `.env.local` are set in Vercel dashboard
* Enable **Clerk**, **Supabase**, and **Resend** production configs

---

## 🙋‍♂️ About the Developer

**Wamique Mashhadi**
🚀 Full-stack Developer | ☁️ Cloud & AI Enthusiast | 🔐 Cybersecurity Learner
📍 Based in Delhi, originally from Gaya
🌐 [Portfolio](https://wamique-mashhadi-portfolio.vercel.app/)

---

## ⭐ Credits

* [Gemini API](https://deepmind.google/technologies/gemini/)
* [Clerk Authentication](https://clerk.dev)
* [Supabase](https://supabase.com/)
* [Resend Email API](https://resend.com/)
* [Tailwind CSS](https://tailwindcss.com/)
* [Vercel](https://vercel.com/)

---

## 📜 License

This project is licensed under the MIT License.


