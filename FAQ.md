**1. What is Time-Manager?**
Time-Manager is a full-stack employee attendance and workforce management application designed to manage:
employee clock-in/out
attendance tracking
planning & scheduling
KPI dashboards
role-based access systems
It supports Admin, Manager, and Employee roles. (GitHub)

**2. What technologies are used in this project?**
Frontend
Vue.js 3
Vite
Chart.js
Axios
Backend
Node.js
Express.js
Prisma ORM
MariaDB
JWT Authentication
Infrastructure
Docker
Docker Compose
Nginx reverse proxy
(GitHub)

**3. What problem does this project solve?**
The system helps organizations:
track employee attendance
manage working hours
monitor lateness
improve scheduling
centralize workforce analytics

**4. Does the application support role-based access control?**
Yes.
The application supports:
Admin
Manager
Employee
Each role has different permissions and access restrictions. (GitHub)

**5. How does the clock in/out system work?**
Employees can:
clock in
clock out
automatically calculate work duration
The backend stores attendance records and computes working hours for dashboards and KPI tracking.

**6. Why was Vue.js chosen for the frontend?**
Vue.js provides:
reactive UI rendering
lightweight architecture
fast component development
excellent dashboard experience
Vite further improves development speed using hot-module replacement.

**7. Why was Prisma ORM used?**
Prisma simplifies:
database schema management
SQL querying
migrations
type-safe backend development
It also integrates well with Node.js applications.

**8. Does this project support Docker deployment?**
Yes.
The repository includes:
Dockerfile
docker-compose.yml
This allows quick deployment of:
frontend
backend
database
reverse proxy
inside isolated containers. (GitHub)

**9. What KPIs can the dashboard track?**
The dashboard can track:
employee lateness
total working hours
attendance metrics
team performance
planning schedules
using charts and real-time statistics. (GitHub)

**10. Can this project be expanded for enterprise HR systems?**
Yes.
Potential future upgrades:
payroll integration
leave management
biometric authentication
AI attendance analytics
facial recognition
mobile app support
notification systems
cloud deployment
RBAC audit logging
This project already provides a strong foundation for enterprise workforce management systems.
