# Enterprise Learning Management System (LMS)

A **modern enterprise-grade LMS** built with Next.js, Node.js, and AWS. Instructors can create and manage courses, while students can seamlessly purchase, enroll, and learn through an intuitive platform.

---

## 🚀 Features

* 🔑 **Authentication & Roles** – Secure login with Clerk, role-based access for students and instructors
* 🎓 **Course Management** – Create and manage complete courses with videos and resources
* 📂 **Cloud Storage** – Upload and manage course content in AWS S3
* 🎥 **Video Learning** – Smooth video streaming with progress tracking
* 💳 **Payments & Enrollment** – Secure checkout and auto-enrollment with Stripe
* 📡 **Serverless Backend** – Powered by AWS Lambda + API Gateway for scalability
* ⚡ **Database** – High-performance NoSQL storage with DynamoDB
* 🌍 **Global Delivery** – Optimized content delivery via CloudFront CDN
* 🎨 **Modern UI/UX** – Built with Next.js, Tailwind CSS, and ShadCN components

---

## 🛠 Tech Stack

* **Frontend:** - Next.js (TypeScript), Tailwind, ShadCN, Redux Toolkit, React Hook Form, Zod, Framer Motion
* **Backend:** - Node.js, Express, AWS Lambda, DynamoDB, S3, CloudFront, Docker
* **Auth & Payments:** - Clerk, Stripe
* **Deployment:** - Vercel (frontend), AWS (backend)

---

## 📐 Architecture

The LMS follows a **modular and scalable architecture**:

* **Frontend** – Next.js (server-side rendered + client-side hydration)
* **Backend** – Serverless functions (Lambda) for course, auth, and payment APIs
* **Database** – DynamoDB for course data, users, and progress tracking
* **Storage** – AWS S3 for video and static content
* **Delivery** – CloudFront CDN for global, low-latency delivery
---
![Image](https://github.com/user-attachments/assets/a6ec1643-99a9-4bda-b2f0-7058a43ffcd7)

---
