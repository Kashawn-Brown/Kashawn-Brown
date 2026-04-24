<!--
**Kashawn-Brown/Kashawn-Brown** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# Hi, I'm Kashawn Brown! 👋


### 📖 About Me

- 🎓 B.Sc. in Computer Science — Western University
- 💻 Full-Stack Software Engineer (Backend-leaning)
- ⚙️ Constantly learning and building with purpose
- 🚀 Turning ideas into real, shipped products
- 🔨 Always working on something new
- 🎮 Outside code: sports, gaming, and anime

---

### 🏆 Featured Projects

Current:   

**Circle Accountability (Expo · Go · Next.js · PostgreSQL · Clerk · GCP)**  
A group accountability app built around a single visual mechanic: a shared **ProgressRing** that fills as each member logs progress toward a shared goal. Small groups (gym partners, study squads, roommates) define a goal with cadence and target, invite members, and each member owns a slice of the ring. The circle only completes when everyone does their part. Built as a real product, not a portfolio piece: targeting App Store and Google Play release after MVP. Architected as a Turborepo monorepo with mobile-first delivery (Expo/React Native), web companion (Next.js 15 App Router), and a Go 1.23 backend using chi + pgx against PostgreSQL. Auth foundation (Clerk) is live across all three clients with a JWT-bridged user model, and CI is wired through GitHub Actions. Deploying to GCP Cloud Run + Neon.   
([🔗 Repo](https://github.com/Kashawn-Brown/CircleAccountability))

  
<br/>
Complete:    
<br/><br/>

**Career-Tracker (Next.js · Fastify · Postgres · OpenAI)**   
A production job application tracker built to replace spreadsheets: a fast **table-first dashboard**, **GCS document storage**, and a **connections system**. Includes a **5-tool AI suite** (JD extraction, compatibility scoring, resume advice, cover letter generation, and interview prep) backed by a monthly credit entitlement system. Auth is JWT with rotating hashed refresh sessions, Google OAuth with PKCE, CSRF protection, and Redis rate limiting throughout. GitHub Actions CI / Cloud Build CD, Vitest integration tests, k6 load tested.  
([🔗 Repo](https://github.com/Kashawn-Brown/Career-Tracker)) ([🌐 Website](https://career-tracker.ca))

**MicroFlix (Java 21 · Spring Boot · PostgreSQL · Next.js)**  
Microservices movie platform built as deliberate practice in production-style backend architecture. JWT-secured APIs through a Spring Cloud Gateway, per-service PostgreSQL with Flyway migrations, TMDb-seeded catalog, and cross-service auth via local JWT verification. End-to-end observability (Micrometer + Prometheus + Grafana) underpins measurement-driven performance work at both layers: EXPLAIN ANALYZE on hot query paths producing targeted Flyway indexes (~28× faster on the highest-leverage lookup), and k6 load testing against the gateway's aggregation endpoints that significantly collapsed browser round trips. A GitHub Actions CI/CD pipeline builds and pushes images to Docker Hub, with deploys explicitly ordered behind successful CI runs. The stack was deployed to AWS EC2 with Docker Compose; the deployment is currently retired, but the codebase is the source of truth for everything described here.  
([🔗 Repo](https://github.com/Kashawn-Brown/MicroFlix))
 
**PASS / WSPass (TypeScript · Next.js · Fastify · GitHub Actions · Zod · Claude)**  
An artifact-first agentic DevOps control plane built for the Wealthsimple AI Builder challenge. Converts PRDs into persisted, schema-validated planning artifacts (architecture pack + decomposition), then enforces a human stop-line before   syncing an approved backlog to GitHub. Includes encrypted integration tokens (AES-256-GCM) and LLM observability (token usage, redacted traces, cost estimates) so runs remain safe and diagnosable.  
([🔗 Repo](https://github.com/MatteoTanziCodes/WSPass)) ([🌐 Website](https://ws-pass-website.vercel.app/))

**Due For A Win (Python · FastAPI · React · Vite · The Odds API)**  
A +EV sports betting engine that strips the vig from 10+ sportsbooks via proportional devigging, builds a consensus fair-probability vector, and surfaces bets where FanDuel is mispriced. Applies Kelly Criterion sizing to recommend stake fractions. Covers NFL, NBA, MLB, NHL, and EPL across moneyline, spread, and totals markets.
Refactored 5 duplicate sport scripts into a 4-module backend (utils / odds_client / ev_engine / FastAPI). Built a multi-page React dashboard with JWT auth, a live picks feed, personal P&L tracker, and configurable engine settings. Mock data wired throughout — live fetch activates with a user-supplied Odds API key.  
([🔗 Repo](https://github.com/dkadiry/due_for_a_win))

**AI-Sudoku (React, FastAPI, PostgreSQL, Tailwind CSS v4, Docker, React Query)**  
A full-stack Sudoku game built as a collaborative project with Cursor AI to explore AI-assisted development. The game includes real-time move validation, a scoring system with difficulty multipliers, and a hint system (3 per game). The React frontend uses React Query for data fetching and Tailwind CSS v4 for responsive styling with light/dark mode. The FastAPI backend serves puzzles from PostgreSQL with difficulty filtering. The project is containerized with Docker Compose for development and production, and includes comprehensive documentation and code comments throughout. Built iteratively with Cursor AI for pair programming and rapid feature iteration, demonstrating modern full-stack development practices from local setup to containerized deployment.  
([🔗 Repo](https://github.com/Kashawn-Brown/AI-Sudoku))

**MovieVault (React · Express · Node · MongoDB · TMDb API)**  
Movie Discovery & Reviews: A full-stack app for exploring and reviewing movies with live TMDb integration. I used it to practice REST API design and a responsive, polished React UI—versioned endpoints, typed/request-response shapes, pagination/filtering, and explicit error contracts, with optimistic updates on the front end. Unlike MicroFlix (which centers your own lists/history), MovieVault is about open discovery in a clean, cohesive app.  
([🔗 Repo](https://github.com/Kashawn-Brown/MovieAPI))

**DataQuest Hackathon - Brescia Norton Classifier**  
Built a booking-cancellation classifier achieving 89% accuracy on held-out data (~10% over baseline). Compared SVC/KNN/MLP→XGBoost and chose XGBoost; Mutual Information–based feature selection reduced selection time by ~20%. Placed 3rd overall at a hackathon for model design + presentation.   
~ Developed in collaboration with Oluwadamilola Kadiri and Oladayo Ogunjimi.  
([🔗 Repo](https://github.com/dkadiry/BresciaNortonClassifier))

---

### 🛠️ Skills
**Languages:** Java, Python, JavaScript, SQL  
**Backend:** Spring Boot, Node.js, Fastify, Express, Django  
**Frontend:** React, Next.js, Tailwind, ShadCN   
**Databases:** PostgreSQL, MySQL, MongoDB, Redis, Firebase  
**Cloud/Tools:** Docker, Linux, AWS, GCP, Git    
**Other:** Microservices, RESTful APIs, OOP, Testing (JUnit 5, Mockito, PyTest), CI/CD, Agile, Algorithms & Data Structures  

---

### 📌 Current Focus
- Productionize & host my projects  
- Finding new problems to solve and more things to build
- Constant learning  
---

### 📫 Get in Touch
- LinkedIn: https://www.linkedin.com/in/kashawn-brown/
- Email: kashawnbrown@hotmail.com

---
> If something here resonates or you’d like a quick demo, feel free to reach out.
> Also open to new connections & opportunities!
