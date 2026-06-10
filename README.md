# Omar Alomar
**Full-Stack & Desktop Application Engineer**  
**Email:** oa6090449@gmail.com | **Location:** Türkiye  
**Profiles:** [GitHub](https://github.com/Omar-05-ino) 

---

## 🎯 Professional Summary
Software engineer focused on building integrated systems across web, desktop, and backend environments. I approach software engineering with a growth mindset, treating complex technical challenges as valuable opportunities to learn and develop. I have hands-on experience bridging mathematical logic and algorithmic calculations with stable database architectures, alongside a practical focus on CI/CD automation to streamline software delivery.

---

## 🛠️ Technical Stack & Skills

* **Frontend & Desktop:** React 19, TypeScript (Strict Mode), Electron, Vite, Zustand, TanStack React Query, Tailwind CSS v4, MUI, Radix UI.
* **Backend:** Python, Django, Django REST Framework (DRF), Gunicorn, Poetry (Dependency Management).
* **Databases:** PostgreSQL, SQLite, complex relationship management, and query optimization.
* **Automation & DevOps:** GitHub Actions (CI/CD), Docker, Docker Compose, Git, Black (Formatting), Flake8 (Linting).
* **Algorithms & Solvers:** Cyclic Coordinate Descent, Topological Sorting, Graph Dependencies.

---

## 💻 Featured Projects

### **KulaLac Suite**
*An integrated formulation system designed for nutritional blending and industrial compliance.*  
A comprehensive system linking international quality standards with actual manufacturing Bill of Materials (BOM) in factories. Developed both core layers of the application:

* **Frontend & Desktop Application:**
  * Developed a responsive, high-performance interface for both web and desktop environments using **React 19**, **Electron**, and **TypeScript** (Strict Mode) to eliminate runtime type errors.
  * Managed client-side state and server synchronization using **Zustand** and **React Query**.
  * Implemented local algorithmic engines including:
    * **Macro Blend Solver:** Utilizes a *Cyclic Coordinate Descent* approach to calculate primary source weights with minimal error margins.
    * **Mineral Network Solver:** Maps nutrient dependencies into a *Dependency Graph* and resolves calculations sequentially using *Topological Sorting* to prevent nutrient ratio conflicts.
  * Automated instant Bill of Materials (BOM) exports to Excel and PDF formats.

* **Backend Server & Architecture:**
  * Designed a **Modular Architecture** adhering to the separation of concerns principle, isolating core calculation logic within a dedicated service layer (`services/`) to achieve thin, clean views.
  * Secured data integrity by utilizing **UUIDs** as primary keys and implemented stateless authentication using **Simple JWT**.
  * Generated automated API documentation using **drf-spectacular (OpenAPI/Swagger)**.

---

## ⚙️ DevOps & CI/CD Experience
Practical experience shifting manual local operations into automated cloud workflows:
* **GitHub Actions:** Configured workflows to trigger code quality checks (linting/formatting) automatically on every push or pull request.
* **Automated Release Compilation:** Built automated multi-platform compilation pipelines for the Electron desktop application to package and release Windows installers (**NSIS Installers**) directly to GitHub Releases.
* **Environment Consistency:** Utilized **Poetry** to isolate dependencies, preventing environmental drifts between local development and production.

---

## 🧠 Technical Problems I Can Solve

* **Code Tangling & Bloated Controllers:** I eliminate code bloat in web frameworks by isolating complex computations entirely into a clean **Service Layer**, keeping controllers thin, maintainable, and straightforward to unit-test.
* **Database Performance Bottlenecks (N+1 Queries):** Experienced in auditing database query logs and resolving redundant querying patterns using Django’s `select_related` and `prefetch_related` to minimize server overhead.
* **Cascading & Interdependent Logic:** When mathematical calculations depend on cascading variables (e.g., adjusting trace minerals based on values inherited from primary protein sources), I resolve them by building a directed **Dependency Graph** and applying a **Topological Sort** to ensure accurate sequential evaluation.
* **Partial Data Failures (Data Corruption):** I safeguard multi-step batch modifications by executing them inside **Atomic Transactions**, guaranteeing that data blocks either commit fully or rollback safely upon failure.
* **Slow Manual Release Pipelines:** I eliminate manual packaging errors and environment-specific bugs by moving the entire desktop build and compilation sequence into secure, cloud-based automation pipelines.

---

## 🎓 Education & Continuous Learning
* **Academic Background:** University Student in Software Engineering.
* **Current Focus:** Deepening knowledge in scalable system architectures, containerization (Docker), and exploring advanced algorithmic applications to resolve practical business and industrial logic problems.
