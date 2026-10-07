# Hi, I'm Mukhveer Kaur 👋

Computer Science graduate (University of Ottawa, 2026) based in Ottawa. I build and test software: backend APIs, automated test suites, and CI pipelines. Before software, I spent two years testing and verifying aerospace electronic systems and three years supporting a 5,000+ user IT environment, so I tend to think about how things fail and how to prove they work.

I'm looking for roles in **software development, QA / test automation, and technical systems**.

📫 [LinkedIn](https://www.linkedin.com/in/mukhveerkaur/) · 📍 Ottawa, ON

---

## 🔧 What I work with

| Area | Tools |
|---|---|
| **Languages** | Python, JavaScript, Java, SQL |
| **Testing & CI** | pytest, Jest (mocks, Supertest), GitHub Actions, Bash smoke tests, manual & functional testing |
| **Backend** | Node.js, Express.js, REST APIs, JWT auth, role-based access control, RabbitMQ |
| **Data** | PostgreSQL, Supabase, SQLite, pandas, scikit-learn |
| **Frontend** | React, React Router, Bootstrap, HTML/CSS |
| **Infrastructure** | Docker / Docker Compose, Linux, Git, networking (routing, VLANs, IPv6, TCP/IP, DNS, DHCP) |

---

## 🚀 Featured Projects

### [Order Events: Messaging System with Automated Test Suite](https://github.com/kaurmukhveer/rabbitmq-order-events)
`Python` `pytest` `Jest` `GitHub Actions` `Docker` `RabbitMQ` `Node.js` `SQLite`

A producer/consumer system with a secured REST API, built to learn asynchronous messaging and test automation end to end.
- **pytest** suite for the Python message-schema validator and **Jest** unit/API tests using a mocked broker and in-memory database
- **GitHub Actions** CI runs both suites on Linux and macOS, then starts RabbitMQ as a service container for an end-to-end smoke test
- JWT authentication with admin/customer roles, manual message acknowledgement, and Docker Compose deployment
- Built with AI-assisted coding; I reviewed, tested, and verified every component, and debugged the CI pipeline from failing to green

### [Mental Wellbeing Web Application (Honours Project)](https://github.com/kaurmukhveer/mental-wellbeing-chatbot-portfolio)
`Node.js` `Express` `PostgreSQL` `Supabase` `JWT` `React` `Netlify` `Render`

A full-stack AI chatbot app, built with a project partner and deployed to a live cloud environment. *Portfolio repo: architecture and engineering write-ups; source code is not public.*
- **My work:** backend authentication and API layer: JWT in HTTP-only cookies, bcrypt, auth middleware, REST endpoints
- Debugged a production cross-origin cookie issue (login 200, then 401) and fixed it with a same-origin API proxy
- Manually tested the partner-built RAG (retrieval-augmented generation) chatbot pipeline

### [YouBelong: Community Engagement Platform (Capstone)](https://github.com/Yash3842/You-Belong)
`React` `TypeScript` `React Router`

A front-end prototype built by a 7-member team across two universities with 5+ community organizations.
- Gathered requirements from community partners and translated them into specifications
- Built (AI-assisted) and manually tested the admin dashboard, user, event, and feedback management screens

### Front-end & UI/UX projects (individual)
- [**Bilingual Food Price Dashboard**](https://github.com/kaurmukhveer/food-price-dashboard): English/French data dashboard in React with full UI localization ([live](https://food-price-dashboard.vercel.app/))
- [**GreenCare Lawn Services**](https://github.com/kaurmukhveer/greencare-lawn-service): customer and admin booking flows with React Router ([live](https://greencare-lawn-service.vercel.app/))
- [**Portfolio Website**](https://github.com/kaurmukhveer/portfolio-website): component-based React portfolio ([live](https://portfolio-website-two-lyart-25.vercel.app/))
- **Bloom Memory**: persona-driven memory card game ([live](https://bloom-memory.vercel.app/)) · **TechNest**: e-commerce prototype ([live](https://technest-ecommerce-azure.vercel.app/))

### Academic team projects
- [**Software Requirements Engineering**](https://github.com/kaurmukhveer/software-requirements-engineering-project): stakeholder analysis, user stories, UML, requirements specification
- [**Hotel Booking: Relational Design**](https://github.com/kaurmukhveer/hotel-booking-relational-design) and [**Legacy Prototype**](https://github.com/kaurmukhveer/hotel-booking-legacy-prototype): ER modelling and a Java/Spring Boot booking prototype

---

## 💼 Background

- **Computer Technician Support**, University of Ottawa (2022–2026): network and system troubleshooting, SCCM/PXE workstation deployment across 8+ labs, Active Directory administration for 2,000+ users
- **Electronic Technician**, Star Navigation Systems (2020–2022): functional testing and hardware/software verification of aerospace electronics against acceptance criteria, root-cause analysis, test fixtures
- **Education:** B.Sc. Honours Computer Science, University of Ottawa · Electronics Engineering Technician Diploma, Sheridan College

---

## 📚 Currently learning

- Expanding test automation: API testing with pytest + `requests`, test reporting
- Optical networking fundamentals (DWDM, pluggable optics)
- Deeper Python and Java
