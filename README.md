# Hi, I'm Aniruddha Fale

### Full-Stack Developer | React • Python • Flask • Docker • ML Integration

I'm a full-stack developer passionate about building scalable web applications, integrating machine learning models into production systems, and deploying containerized solutions. My experience spans from production platforms serving live users to experimental projects exploring mobile development and ML pipelines. Take a look at my projects and what tech stack i learnt from each one of them. 

---

## Featured Projects

### [Brandlytical](https://brandlytical.in/) - Production Influencer Marketing Platform
**Internship @ Propell Action | Live Product Serving Real Users**

Built an end-to-end influencer marketing platform from initial architecture through production deployment. Demonstrates enterprise-level development with complex multi-role workflows, real-time data synchronization, and scalable cloud infrastructure.

**Tech Stack:**
- **Frontend:** React.js, React Router DOM, Tailwind CSS, Ant Design
- **Database:** Supabase (PostgreSQL with built-in auth, row-level security, auto-generated APIs)
- **Features:** Multi-role dashboards (Admin/Brand/Agency), JWT authentication, real-time sync, campaign management, CSV bulk imports, approval workflows, reporting

**Key Achievements:**
- Designed and implemented full application architecture from scratch
- Built complex role-based access control systems
- Integrated real-time data synchronization across multiple dashboards
- Deployed to production with live users
- Leveraged Supabase's serverless architecture to eliminate custom backend development while maintaining enterprise security

**Note:** Code is proprietary to Propell Action. [Live Website](https://brandlytical.in/)

---

### [RecipeMatching (Nutrient Pro)](https://github.com/aniruddha1607/RecipeMatching) - ML-Powered Recipe Recommendation System
**Focus: ML Integration • REST APIs • Docker Containerization**

Full-stack recipe search and recommendation app that bridges machine learning with web development. Trained a custom K-Nearest Neighbors model on 3000+ recipes and integrated it into a production-ready web application using Docker.

**Tech Stack:**
- **Backend:** Python (Flask), scikit-learn (KNN)
- **Frontend:** React.js, Tailwind CSS
- **Database:** MongoDB
- **DevOps:** Docker, Docker Compose
- **Data Source:** EDAMAM Recipe API

**What I Built:**
1. **ML Pipeline:** Created custom dataset by iteratively calling EDAMAM API → preprocessed 3000+ recipes (handled duplicates, normalized nutrients) → trained KNN model → serialized with pickle for production use

2. **REST API Development:**
   - `/find` endpoint: Nutrient-based filtering (protein, fats, carbs, energy, fiber) with MongoDB queries
   - `/predict` endpoint: ML model inference returning 10 nutritionally similar recipes
   - Successfully integrated pickled ML model with JSON APIs consumed by React frontend

3. **Docker & Containerization:**
   - Learned Docker from scratch
   - Wrote custom Dockerfiles for frontend and backend
   - Used Docker Compose to orchestrate 3 containers (Flask, React, MongoDB)
   - Configured service dependencies, environment variables, persistent volumes
   - One-command deployment: `docker-compose up --build`

4. **Full-Stack Development:**
   - React component-based architecture (RecipeCard, RecipeDetailCard)
   - Real-time ML-powered recipe suggestions
   - Responsive UI with Tailwind CSS

**Learning Outcome:** Productionizing ML models—not just training in notebooks, but exposing them through APIs that real applications consume. Docker taught me containerization beyond "works on my machine."

**[GitHub Repository](https://github.com/aniruddha1607/RecipeMatching)** | Includes API docs, Docker setup, ML notebook

---

### [APSIT-COMMUNITY](https://github.com/aniruddha1607/APSIT-COMMUNITY) - Campus Services Web App
**Focus: Flask • ORM • Authentication • Email Integration**

Built a comprehensive campus services platform handling user authentication, event management, grievances, lost & found, and canteen ordering with email notifications.

**Tech Stack:**
- **Backend:** Python (Flask)
- **Database:** SQLite with SQLAlchemy ORM
- **Frontend:** HTML, Bootstrap, Jinja2 templating

**What I Built:**
- User authentication and session management
- Event posting and management system
- Grievance submission and tracking
- Lost & found item registry
- Canteen order system with email notifications
- Full CRUD operations using SQLAlchemy ORM

**Learning Outcome:** Mastered Flask fundamentals—routing, templating, ORM, forms, and authentication. These core concepts directly map to Django (which adds conventions and built-in features). Flask's lightweight approach taught me the fundamentals from the ground up.

**[GitHub Repository](https://github.com/aniruddha1607/APSIT-COMMUNITY)** | Includes setup docs and working SQLite DB

---

### [Expense Tracker](https://github.com/aniruddha1607/expense-tracker) - Cross-Platform Mobile App
**Focus: React Native • Mobile UI/UX • AsyncStorage**

Built a mobile expense tracking app to explore React Native and cross-platform development for iOS and Android.

**Tech Stack:**
- **Framework:** React Native & Expo
- **Language:** JavaScript/React
- **Storage:** AsyncStorage (local device storage)
- **Navigation:** React Navigation

**Features:**
- Add, edit, and delete expenses with calendar date picker
- View recent or all expenses with filtering
- Local data persistence on device
- Cross-platform compatibility (iOS & Android)

**Learning Outcome:** This was a learning project focused on mobile UI/UX development and understanding React Native fundamentals. Used local storage to demonstrate core concepts. For full-stack backend integration, see APSIT-COMMUNITY or RecipeMatching.

**[GitHub Repository](https://github.com/aniruddha1607/expense-tracker)**

---

## What I Bring to the Table

**Full-Stack Development:**
- Frontend: React.js, React Native, Tailwind CSS, Bootstrap
- Backend: Python (Flask), REST API design
- Database: PostgreSQL (Supabase), MongoDB, SQLite with ORMs

**ML Integration & DevOps:**
- Integrating ML models (scikit-learn) into production web apps
- Docker containerization and multi-container orchestration
- API design for serving ML predictions
- Data preprocessing and model deployment

**Production Experience:**
- Built live platform serving real users (Brandlytical)
- End-to-end development: architecture → implementation → deployment
- Real-time data sync and complex multi-role workflows
- Scalable cloud infrastructure (Supabase, Docker)

---

## What I'm Looking For

Full-Stack Developer roles where I can:
- Build scalable web applications with modern frameworks
- Bridge machine learning/data science with practical web development
- Work with cloud infrastructure and containerized deployments
- Contribute to production systems serving real users

---

## Let's Connect

I'm open to opportunities in **Software Development**, especially roles involving ML integration, cloud platforms, or web/mobile app development.

**GitHub:** [aniruddha1607](https://github.com/aniruddha1607)

---
