# Nguyen The Tam

Backend Developer focused on Node.js, NestJS, PostgreSQL, REST APIs, real-time systems, and practical AI workflow integration.

Location: Bac Tu Liem, Hanoi  
Email: [thetam2103@gmail.com](mailto:thetam2103@gmail.com)  
Phone: 0386 312 564  
LinkedIn: [linkedin.com/in/nguyenthetam](https://www.linkedin.com/in/nguyenthetam/)  
GitHub: [github.com/tam130103](https://github.com/tam130103)  
Portfolio: [tam130103.github.io](https://tam130103.github.io)

## Resume

- [Backend CV](./Nguyen_The_Tam_CV_Backend_HN.pdf)
- [AI Engineer Intern CV](./Nguyen_The_Tam_CV_AI_HN.pdf)

## Technical Skills

| Area | Skills |
| --- | --- |
| Backend | TypeScript, Node.js, NestJS, Hono, Express.js, RESTful API Design, Clean Architecture, JWT Authentication, RBAC, Socket.IO |
| Database | PostgreSQL, MongoDB, Drizzle ORM, TypeORM, Mongoose |
| AI and Integrations | Dify AI, chatbot workflows, AI agents, prompt engineering, fallback strategy, Stripe API |
| Tools and DevOps | Docker, Docker Compose, Git/GitHub, Swagger/OpenAPI, Postman, Cloudflare Workers, Vercel, Render, Cloudinary, Playwright |
| Familiar | React 18, Next.js, Tailwind CSS, Python |
| Languages | English technical reading and writing, Japanese JLPT N5 |

## Experience

### Back-end Developer Intern, CONG TY CO PHAN ESG TECH

Nov 2025 - Apr 2026

- Contributed to backend API development using the Hono framework on Cloudflare Workers for an ESG Reporting platform that converts raw environmental, social, and governance data into XBRL-compliant reports.
- Worked with PostgreSQL via Drizzle ORM to manage data models for GRI metric mapping, organization data, and report generation workflows.
- Integrated Dify AI workflows to automate GRI standard mapping and qualitative assessment scoring inside the data processing pipeline.

## Featured Projects

### [DATN Social - Real-time Edu-Social Platform](https://github.com/tam130103/datn)

Stack: NestJS 11, TypeScript, PostgreSQL, TypeORM, Socket.IO, Dify AI, Docker Compose, Cloudinary, Swagger/OpenAPI, Vercel, Render

- Architected a modular backend with NestJS 11 and Clean Architecture across 11 feature modules, backed by 17 PostgreSQL entities and documented via Swagger/OpenAPI.
- Designed and implemented 81 RESTful API endpoints with JWT authentication and 3-tier RBAC for user, admin, and system roles.
- Built dual Socket.IO gateways for real-time 1-1 messaging and push notification delivery, including joinConversation, sendMessage, markAsRead, typing, and leaveConversation events.
- Integrated 3 Dify AI workflows: caption generation, content chatbot, and toxic content detection with fallback-to-Gemini on timeout.
- Wrote 7 unit test suites covering auth, post, chat, engagement, admin, and AI service modules.

Demo: [datn-mu-six.vercel.app](https://datn-mu-six.vercel.app/)

### [Food Delivery Website - Full-stack E-commerce Application](https://github.com/tam130103/DACN)

Stack: Node.js, Express.js, MongoDB, Mongoose, Stripe API, JWT, Bcrypt, Cloudinary, Docker Compose, Vercel, Render

- Built 14 RESTful API endpoints across user, food, order, and cart route groups with JWT authentication and Bcrypt password hashing.
- Added role-based middleware to separate customer and admin access.
- Implemented Stripe Checkout session creation and server-side payment verification by cross-checking payment_status against order state.
- Developed an Admin Dashboard for order management, food catalog CRUD with Cloudinary image upload, and business monitoring.
- Containerized the application with Docker Compose and deployed it across Vercel and Render.

## Education

Hanoi University of Mining and Geology  
B.S. Information Technology, 2021 - 2026  
Expected graduation: 2026
