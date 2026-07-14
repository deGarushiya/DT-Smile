# DT Smile Dental Clinic  
## Patient Management System — Proposal Pack

![DT Smile Dental Clinic logo](assets/dt-smile-logo.png)

**Clinic:** DT Smile Dental Clinic  
**Dentist-owner:** Doc Shelay  
**Team:** Doc Shelay + 1 receptionist/assistant  
**Goal:** Replace Google Sheets with a simple, cloud clinic system

---

## The problem (why Sheets is hard)

Running the clinic on Google Sheets often means:

- Double-booking or missed appointments when two people edit at once  
- Patient history, X-rays, and billing scattered across tabs  
- No automatic email reminders → more no-shows  
- Hard to see who paid, who still owes, and daily revenue  
- Weak access control (everyone can see/edit everything)  
- Backup and security depend on whoever remembers to tidy the file  

You need something built for clinic work—not a spreadsheet pretending to be a database.

---

## What you get

A **cloud web app** you open on phone, tablet, or clinic PC:

| Module | Benefit |
|--------|---------|
| Appointment scheduling | Day/week calendar, chair/dentist slots, status tracking |
| Electronic patient records | Profile, visit notes, simple dental chart, file uploads |
| Billing & payments | Invoices, Cash/GCash/bank/card recording, balances |
| Prescriptions | Create, print/PDF, history per patient |
| Email appointment reminders | Auto email reminders before appointments |
| Reports dashboard | Revenue, no-shows, outstanding balances |
| Multi-user access | **Dentist** (full) + **Reception** (front desk) |
| Cloud storage & backup | DigitalOcean hosting with database + file backups |
| Technical support | Optional monthly retainer after go-live |

---

## Who uses it

| Role | Typical use |
|------|-------------|
| **Dentist (Doc Shelay)** | Charting, visit notes, prescriptions, reports, users/settings |
| **Reception** | Book/check-in patients, update profiles, collect payments |

---

## Price snapshot (PHP)

**Family / first-client rate** (cousin + portfolio build — not agency pricing):

| Item | Estimate |
|------|----------|
| **Development (one-time)** | **₱50,000 – ₱80,000** (suggest ₱65,000) |
| **Hosting (she pays DigitalOcean directly)** | **~₱1,400/mo** lean start (droplet) |
| Comfort hosting (optional later) | ₱2,900 – ₱3,300 / month |
| Email notifications | ₱0 – ₱500 / month |
| Maintenance | Optional later (not required at launch) |

Full breakdown + how to explain it: [docs/budget-proposal.md](docs/budget-proposal.md)

---

## Timeline

**About 8–12 weeks** (discovery → build → training → go-live), paced as a first-client project.

---

## How to walk through this pack

1. Open **[wireframes/index.html](wireframes/index.html)** in a browser — click through the screens together.  
2. Read **[docs/system-specification.md](docs/system-specification.md)** for modules, roles, and what’s in/out of scope.  
3. Review **[docs/budget-proposal.md](docs/budget-proposal.md)** for build + Year-1 operating cost.

---

## Next step after approval

Build the real web app from this specification (separate project). This folder is the **proposal only**—no live system yet.
