# DroneOps: Aerial Survey and Fleet Management System

Group project for Web Technologies (Lab).

DroneOps keeps an organisation's drone work in one place. Pilots request flights, technicians record the condition of every drone, a dispatcher approves or denies each flight request, and a safety officer watches damage reports and pilot licenses.

## Group

| No. | Name | Student ID | Module |
|-----|------|------------|--------|
| 1 | Akib Osmani | 23-52996-3 | Login, registration and pilot profile; flight planning |
| 2 | Nashid Jamil Kanchon | 23-54572-3 | Drone hardware and maintenance |
| 3 | Amana Siddika | 24-56234-1 | Dispatcher panel |
| 4 | Rafisa Lam-Mim Sarker | 23-53859-3 | Safety and compliance |

## How to open

Open `index.html` in a web browser. It links to every page.

## Pages

| Page | File | Member |
|------|------|--------|
| Home | `index.html` | Akib |
| Login | `pages/auth/login.html` | Akib |
| Pilot Registration | `pages/auth/register.html` | Akib |
| Pilot Dashboard and Profile | `pages/auth/profile.html` | Akib |
| New Flight Plan | `pages/pilot/flight_request.html` | Akib |
| My Flights | `pages/pilot/my_flights.html` | Akib |
| Drone Grid | `pages/tech/drones.html` | Nashid |
| Maintenance Update | `pages/tech/maintenance.html` | Nashid |
| Flight Schedule | `pages/admin/flights.html` | Amana |
| Fleet Management | `pages/admin/fleet.html` | Amana |
| User Management | `pages/admin/users.html` | Amana |
| Safety Dashboard | `pages/safety/dashboard.html` | Rafisa |
| Grounding & Damage Audit | `pages/safety/groundings.html` | Rafisa |
| Pilot Compliance | `pages/safety/pilots.html` | Rafisa |
| Compliance Notices | `pages/safety/notices.html` | Rafisa |

## Design

All pages share one style sheet, `public/css/style.css`. It has one section per part:

| Section | Member | What it styles |
|---------|--------|----------------|
| 1 | Akib Osmani | Colours, page layout, navigation bar, footer |
| 2 | Akib Osmani | Forms and fields |
| 3 | Nashid Jamil Kanchon | Drone grid, dashboard numbers, status labels |
| 4 | Amana Siddika | Buttons, tables, dispatcher controls |
| 5 | Rafisa Lam-Mim Sarker | Safety pages: extra status colours, shortcut buttons |

Light cream background, dark text, no boxes or shadows. Flexbox lays out the navigation bar and buttons; CSS Grid lays out the drone grid and the two-column form rows. Pages also fit a phone screen.
