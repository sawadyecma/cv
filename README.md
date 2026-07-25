# CV

## Personal Summary

I was born and raised in Japan.
I'm curious about working with people who have various nationalities and cultures.
Through them, I believe that I can realize my own identities.
From 2024 to 2026, I stayed in Australia on a working holiday, going back and forth between Australia and Japan while continuing to work remotely as an engineer. (TOEIC 890)

I'm usually a calm person. As a professional, I cherish keeping my motivation.

In terms of programming, also I love to find an abstract way to think.
For example, the way to write a readable and reusable code, the new discovery on the business domain.
This is why I love programming.

In the end of this section, I love third wave coffee, impressionism arts and alternative/indie band's songs.


## Skills

- Bachelor's degree in computer science, software engineering
- 7+ years’ experience in Front End such as React/jQuery
- Work as a full stack engineer, covering frontend, backend and infrastructure
- Work in an Agile environment, and contribute to stabilizing the team's velocity
- Use AI coding agents (Claude Code) for implementation, review, research, design and CI integration, and share the practices within the team
- Eliminate technology debt
- Collaborate with backend engineers, mobile engineers, product managers and UI/UX designers
- Build a Design System with UI/UX designers
- Develop new product
- Create basic codes and Deciding a policy of writing codes
- Discuss API specification with backend engineers
- Read the internals of OSS libraries to solve performance issues and difficult bugs

And I have listed up the skills which I used in my practical works below.

### Main Skills

| name | years |
|------------|----|
| TypeScript | 7 |
| React.js | 7.5 |
| AWS | 4.5 |
| Go | 2 |
| Rust | 1 |


### Sub Skills

|name|items|
|---|---|
|Js Related|Next.js, Nest.js, Hono, TypeOrm, jQuery, fabric.js, yjs, Node.js, Express, SWR, zod, Material UI, Ant Design, ApolloClient, emotion, styled-component ,dnd-kit, Vite, Vitest, Jest, Redux, redux-toolkit, React Select|
|Go Related|Gorm, Echo|
|AWS|VPC, S3, API Gateway, Lambda, EC2, ECS, ECR, Fargate, ALB, Route53, IAM, Cognito, RDS(MySQL|PostgreSQL), DynamoDB, Appsync, SES, Cloud Formation, Cloud Watch Logs, Cloud Watch Event, Sage Maker, CodePipeline, ElastiCache for Redis, CDK, SAM|
|GCP|GCS, IAM, Speech To Text, Vision API, Route Optimization API|
|Database| MySQL, PostgreSQL, MongoDB, DynamoDB |
|ML and Analysis| Python, Keras, Tensorflow, OpenCV, MeCab, Numpy|
|Other|Claude Code, WebAssembly, Twilio, Swagger, GraphQL, GitHub, GitHub Actions, Docker, Nginx, Apache, Ruby on Rails |


## Experiences

### 2026.02 - current | Mobility / MaaS (Freelance)

- **Role**: Full stack engineer (frontend : backend : infrastructure = 4 : 4 : 2)
- **Team**: Scrum team / 1 PO, 1 scrum master and 4 engineers (all of whom are full stack)
- **Skills**: TypeScript, React, Hono, AWS Lambda, Google Route Optimization API

**Responsibilities and Achievements**

- Work on an AI on-demand ride-sharing service and autonomous driving services for local communities. There is almost no boundary between roles in the team.
- Develop 3 applications cross-sectionally: the app for passengers, the app for drivers and the internal admin console for operation management.
- Lead the route optimization area using Google Route Optimization API, and also lead the team in understanding and organizing the specifications.
- Contribute to stabilizing the velocity of the scrum team.
  - Change the agenda of the daily scrum from each member's individual progress report to reviewing the progress of each PBI together as a team.
  - Spread the mindset of prioritizing flow efficiency over resource efficiency.
- Use Claude Code across implementation, review, research, design and CI integration. We teach each other how to use it in the retrospective, and the team's development speed has roughly doubled.

---

### 2025.04 - 2025.08 | EdTech SaaS (Freelance)

- **Role**: Frontend engineer (a member of the team, and the most leading position in the fabric.js and yjs areas)
- **Team**: 4 frontend engineers and a similar number of backend engineers
- **Skills**: TypeScript, React, Next.js, styled-components, fabric.js, yjs

**Responsibilities and Achievements**

- Develop a web digital note system provided by a major Japanese stationery manufacturer for educational institutions.
- The purpose of the product is to digitalize the communication between teachers and students. It consists of a note-taking system for students and a management / correction system for teachers.
- Read the internals of fabric.js deeply in order to implement the drawing requirements.
  - Improve rendering performance by optimizing image processing and the transparency handling of objects.
  - Investigate and fix difficult bugs around rendering.
- Implement realtime synchronization with yjs (CRDT).

---

### 2024.01 - 2026.01 | Working Holiday in Australia

- Stayed in Australia on a working holiday, going back and forth between Australia and Japan.
- Worked in agriculture as a seasonal worker in various regions and roles, in a multinational environment.
- Continued to work remotely on the software engineering projects above during the same period.
- TOEIC 890.

---

### 2023.10 - 2024.08 | Real Estate Start-up (Freelance)

- **Role**: Frontend lead
- **Team**: Small scrum team / deploying once a week
- **Skills**: TypeScript, React(v18), Rust, WebAssembly

**Responsibilities and Achievements**

- Work in a start-up running a private lodging service.
- Lead the frontend development, including deciding the coding conventions.
- Introduce testing tools to improve the quality of the code, which enables to test hooks with api stubbing.
- Separate modules into appropriate responsibilities and sizes to make it easy to test.
- Experience backend development with Rust, and embed my own programming language into both frontend and backend via WebAssembly.

---

### 2022.10 - 2023.09 | Fintech / Inheritance Solution (Freelance)

- **Role**: Frontend engineer (launching the development from the beginning)
- **Skills**: TypeScript, React(v18), Next.js

**Responsibilities and Achievements**

- Join a company having solution business to a Japanese huge bank, and develop and launch the service to assist mass customers’ inheritance tasks.
- Make a basic code on the application such as rpc client, web storage manager and common error handling flow.
- Develop 3 applications cross-sectionally: customer service, service for advertiser and management service.
- At the beginning of the development, encourage the team to decide which technologies we should use, and make policies for programming.
- Collaborate with the UI/UX designer team to build a design system and user-friendly pages.
- Implement frontend cache design in order to reduce server load and adjust the life cycles of resources.
- Create library for the common process including domain logic, and consider efficient way to commonize and separate the responsibility of modules.
- Introduce appropriate tools and directory structures for monorepo.

---

### 2020.04 - 2022.09 | Dental Health SaaS

- **Role**: Lead engineer (frontend : backend : infrastructure : machine learning = 4 : 4 : 1.5 : 0.5)
- **Skills**: Go, React, Python, AWS, PHP (see the table below)

**Responsibilities and Achievements**

- To improve the Japanese dental health, work in a company providing a SaaS for dental offices.
- Work on the following products cross-sectionally.

|Feature|Responsibility|Skills|
|------------|-------|---------|
| Web Interview | Design GraphQL Schema and implement frontend application.| React / ApolloClient / useContext / AWS Appsync / AWS DynamoDB |
| Web Reservation | Replace php to Go as a backend engineer | Go / echo / gorm / AWS ECS |
| Patient's Image Storage | Replace php to Go. Deploy API and batch process infrastructure. Design and implement authentication and authorization. | Go / echo / gorm / AWS ECS / AWS S3 / AWS CodePipeline |
| Examination Record Tool | PoC design and make handwriting text recognition model for examination. | Python / Keras / Swagger |
| User Management | Design Rest API and develop and deploy backend server | Go / AWS ECS / AWS Cognito / AWS CodePipeline / AWS ElastiCache for Redis |
| Model Development Distinguishing Oral Images | PoC, Collect processing training data and create model. | Python / Tensorflow |
| Electric Karte System | Design and develop GUI frontend application made by fabric.js. | React / redux-toolkit / fabric.js |

---

### 2019.07 - 2020.03 | M&A Fintech Start-up

- **Role**: Engineer (frontend : backend : data analysis = 4 : 5 : 1)

**Responsibilities and Achievements**

- To deal with a business inheritance issue in Japan, join a start-up company providing a SaaS related M&A.
- Develop the features such as OCR for financial reports, valuation calculator for private companies and tool to assist for making contracts.

---

### 2014.04 - 2019.03 | Hokkaido University

- **Research Field**: Natural language processing and machine learning

**Activities**

- Learn computer science, especially natural language processing and machine learning.
- Develop the CNN model which can distinguish whether an input text is dajare or not. (Dajare is a kind of Japanese play of words)


## Recent Interests

- Improving the development process with AI agents
- Route optimization and combinatorial optimization
- Rust
- Competitive programming
