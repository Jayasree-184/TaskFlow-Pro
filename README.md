A full-stack Team Task Management Web Application built with React, Node.js, and Express. It allows teams to create projects, assign tasks, track progress, and collaborate with role-based access control.

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React 18, CSS Animations |
| Backend | Node.js, Express.js |
| Deployment | Railway |

## Authentication

- Login and Register system
- Role-based access — **Admin** and **Member**
- Session-based persistent login
- Form validation with error handling
- Password show/hide toggle

## Admin vs Member Access

Admin can:
- Create, edit, delete projects
- Create, assign, delete tasks
- View all projects and tasks
- Delete any comment
- Access full analytics dashboard

Member can:
- View their assigned tasks
- Update task status
- Add comments on tasks
- Update their own profile

## Dashboard

- Stat cards — Total Projects, Tasks Done, In Progress, Overdue
- Animated number counters on load
- Tasks by Status bar chart
- Priority split (Low, Medium, High, Critical)
- Recent projects list with progress bars
- Overdue task alert banner

## Project Management

- Create, edit, delete projects
- Status — Planning, Active, On Hold, Completed
- Priority — Low, Medium, High
- Color picker for project cards
- Auto-calculated progress from tasks
- Deadline tracking
- Search and filter by status

## Task Management

- Create, edit, delete tasks
- Assign tasks to team members
- Priority — Low, Medium, High, Critical
- Status — To Do, In Progress, Review, Completed
- Due dates with overdue detection
- Labels and tags
- Comments section per task
- Click any task to open detail panel

## Kanban Board

- Drag and drop tasks between columns
- 4 columns — To Do, In Progress, Review, Completed
- Add tasks directly from any column
- Progress auto-updates when tasks move
- Visual highlight on drag over

## UI & Animations

- Dark mode and Light mode toggle
- Fully responsive — Mobile, Tablet, Desktop
- Page transitions on every navigation
- Animated stat number counters
- Progress bars animate from 0 to value
- Card hover lift and glow effect
- Spring bounce modal open animation
- Toast notifications — success, error, warning
- Logo floating animation
- Notification bell pulse ring
- Task card left border accent on hover
- Stat card icons tilt on hover

## Responsive Design

- Collapsible sidebar on desktop
- Hamburger menu on mobile
- Kanban board stacks vertically on mobile
- Stat grid changes from 4 columns to 2 to 1
- Touch-friendly buttons and inputs

## Demo Credentials

| Role | Email | Password |
|------|-------|----------|
| Admin | admin@taskflow.com | admin123 |
| Member | sarah@taskflow.com | member123 |
