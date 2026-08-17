# 🎥 Interview Connect Platform

<p align="center">
  <strong>A modern video interview platform designed to make online interviews simple, secure, and collaborative.</strong>
</p>

<p align="center">
  Built with Next.js, TypeScript, Stream, Convex, Clerk, Tailwind CSS, and Shadcn UI.
</p>

---

## 📌 Overview

**Interview Connect Platform** is a full-stack web application for conducting professional online interviews.

The platform provides real-time video communication along with features such as screen sharing, screen recording, authentication, interview management, and a modern responsive interface.

It is designed to provide a smooth experience for both interviewers and candidates.

---

## ✨ Key Features

- 🎥 **Video Calling** – Conduct real-time video interviews
- 🖥️ **Screen Sharing** – Share your screen during technical or collaborative interviews
- 🎬 **Screen Recording** – Record interview sessions when required
- 🔐 **Authentication & Authorization** – Secure user authentication and protected access
- 👤 **Interview Management** – Manage and participate in interview sessions
- ⚡ **Real-Time Communication** – Powered by Stream
- 🗄️ **Database & Backend** – Convex for backend data management
- 🎨 **Modern UI** – Built with Tailwind CSS and Shadcn UI
- 📱 **Responsive Design** – Works across different screen sizes
- 🚀 **Next.js App Router** – Uses modern Next.js architecture
- 🧩 **Server & Client Components** – Combines server-side and client-side functionality

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **Next.js** | Full-stack React framework |
| **TypeScript** | Type-safe application development |
| **Stream** | Video calling and real-time communication |
| **Convex** | Backend and database |
| **Clerk** | Authentication and user management |
| **Tailwind CSS** | Styling and responsive UI |
| **Shadcn UI** | Reusable UI components |

---

## 🏗️ Application Architecture

```text
                         ┌──────────────────────┐
                         │   Interview Connect  │
                         │      Platform        │
                         └──────────┬───────────┘
                                    │
                 ┌──────────────────┼──────────────────┐
                 │                  │                  │
                 ▼                  ▼                  ▼
          ┌─────────────┐    ┌─────────────┐    ┌─────────────┐
          │   Next.js   │    │    Clerk    │    │    Convex   │
          │  Frontend   │    │    Auth     │    │   Backend   │
          └──────┬──────┘    └─────────────┘    └──────┬──────┘
                 │                                      │
                 └──────────────────┬───────────────────┘
                                    ▼
                            ┌───────────────┐
                            │     Stream    │
                            │ Video Calling │
                            └───────────────┘
```

---

## 📂 Project Structure

```text
Interview-Connect-Platform/
│
├── app/
├── components/
├── convex/
├── public/
├── lib/
├── hooks/
├── actions/
├── .env.local
├── package.json
├── tsconfig.json
└── README.md
```

> The exact structure may vary depending on the current implementation.

---

# ⚙️ Getting Started

## 1. Clone the Repository

```bash
git clone https://github.com/msr23cs8059-ux/Interview-Connect-Platform.git
cd Interview-Connect-Platform
```

## 2. Install Dependencies

```bash
npm install
```

---

## 🔐 3. Configure Environment Variables

Create a `.env.local` file in the project root.

Add the required credentials:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=

NEXT_PUBLIC_STREAM_API_KEY=
STREAM_SECRET_KEY=
```

### Environment Variables

| Variable | Purpose |
|---|---|
| `NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY` | Clerk public authentication key |
| `CLERK_SECRET_KEY` | Clerk server-side authentication key |
| `CONVEX_DEPLOYMENT` | Convex deployment configuration |
| `NEXT_PUBLIC_CONVEX_URL` | Convex backend URL |
| `NEXT_PUBLIC_STREAM_API_KEY` | Stream public API key |
| `STREAM_SECRET_KEY` | Stream server-side secret |

> **Important:** Never commit `.env.local` or expose secret keys publicly.

---

## 🗄️ 4. Configure Convex

After configuring your environment variables, initialize/start the Convex development environment according to your project configuration.

Typically:

```bash
npx convex dev
```

Keep the Convex process running while developing locally if your application requires it.

---

## 🚀 5. Run the Application

Start the Next.js development server:

```bash
npm run dev
```

Open your browser and visit:

```text
http://localhost:3000
```

---

# 🎥 Core Functionality

### Video Interviews

Interviewers and candidates can join real-time video sessions for conducting online interviews.

### 🖥️ Screen Sharing

Participants can share their screen during technical interviews, coding discussions, presentations, or collaborative sessions.

### 🎬 Screen Recording

Interview sessions can be recorded when recording functionality is enabled and permitted.

### 🔒 Authentication

Clerk provides secure authentication and user management, allowing protected application features to be accessed by authenticated users.

### ⚡ Real-Time Communication

Stream powers the real-time video communication experience, providing reliable audio/video functionality for interview sessions.

---

# 🎨 UI & Design

The platform uses:

- Tailwind CSS for styling
- Shadcn UI for reusable components
- Responsive layouts
- Modern dashboard-style interfaces
- Reusable React components

The interface is designed to keep the interview experience focused and easy to navigate.

---

# 🚧 Future Improvements

Potential enhancements include:

- 📅 Interview scheduling
- 📧 Email notifications
- 📝 Collaborative coding editor
- 🤖 AI-powered interview feedback
- 📊 Interview performance analytics
- 🧠 Automated candidate evaluation
- 📄 Resume integration
- 💬 In-interview chat
- 🌐 Multi-language support
- 📱 Improved mobile experience

---

# 🎯 Project Highlights

**Interview Connect Platform** demonstrates the integration of modern web technologies to build a real-time interview experience.

The project combines:

**Next.js + TypeScript + Stream + Convex + Clerk + Tailwind CSS + Shadcn UI**

to create a scalable platform for conducting online technical and professional interviews.

---

## 👩‍💻 Author

**msr23cs8059-ux**

---

<p align="center">
  <strong>🎥 Connect. Interview. Evaluate. 🚀</strong>
</p>
