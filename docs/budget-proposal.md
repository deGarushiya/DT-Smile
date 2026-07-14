# Budget Proposal  
## DT Smile Dental Clinic — Patient Management System

**Prepared for:** DT Smile Dental Clinic — Doc Shelay (dentist-owner) + receptionist  
**Prepared by:** Independent developer (first company/freelance client)  
**Currency:** Philippine Peso (₱)  
**FX note:** Conversions use **₱58 = $1 USD**. Actual DigitalOcean bills are in USD and will vary with exchange rate.

---

## 1. Why this quote is different

This is not an agency / enterprise quote. It reflects that:

| Factor | How it affects the price |
|--------|--------------------------|
| Doc Shelay is family (cousin) | Development fee is set as a **family / starter rate**, not full market |
| First client out of the company | Project also builds a **portfolio case study** and real clinic references |
| Small single-clinic setup | Scope stays practical (1 dentist + reception, email reminders only) |
| She owns hosting | Clinic pays DigitalOcean (and email) **directly** — not marked up |

**Quoted development fee: ₱50,000 – ₱80,000** (one-time)

For context only: a full market “Complete” build for the same feature list is often closer to ₱300,000+. That gap is intentional goodwill for a first family client—not because the work is small.

---

## 2. Recommended path (what to present to Doc Shelay)

| Recommendation | Detail |
|----------------|--------|
| **Development (one-time)** | **₱50,000 – ₱80,000** |
| **Suggested midpoint** | **₱65,000** |
| **Hosting** | Paid **directly by the clinic** on DigitalOcean |
| **Lean hosting (start)** | Droplet ~**₱1,400/mo** ($24) — good starter |
| **Comfort hosting (optional)** | Droplet + managed DB + Spaces + backups ≈ **₱2,900–3,300/mo** |
| **Maintenance** | **Optional later** — not required at launch |
| **Timeline** | About **8–12 weeks** (part-time friendly / first-client pace) |
| **Notifications** | Email only (no SMS) |

---

## 3. What’s included in ₱50,000–₱80,000

Same product scope as the proposal pack (Sheets replacement for a small clinic):

- Appointment scheduling (day/week, statuses, conflict check)  
- Electronic patient records (profile, visits, simple dental chart, file uploads)  
- Billing & payment monitoring (Cash / GCash / bank / card recording)  
- Prescriptions (create / print / history) — Doc Shelay only  
- Email appointment reminders  
- Basic reports dashboard  
- Multi-user: Dentist (Doc Shelay) + Reception  
- Deploy on DigitalOcean under **her** account  
- Short training + **30-day bug-fix warranty** after go-live  

### Suggested payment schedule (development only)

| Milestone | % | Example at ₱65,000 |
|-----------|---|---------------------|
| Kickoff / scope locked | 40% | ₱26,000 |
| Working demo (patients + appointments + billing) | 40% | ₱26,000 |
| Go-live + training | 20% | ₱13,000 |

---

## 4. Hosting — she pays DigitalOcean directly

You set it up; **her card / her DigitalOcean account** so she owns the server and data.

### Option A — Lean start (~₱1,400/mo) — **recommended for day one**

| Item | Spec | ≈ PHP / mo |
|------|------|------------|
| Basic Droplet | 2 vCPU, 4 GB RAM, 80 GB SSD ($24) | **₱1,392** |
| Domain (amortized) | Optional | ₱50–100 |
| Email | Free tier or low paid | ₱0–500 |
| **Typical start** | | **≈ ₱1,400 – ₱2,000** |

App + database can run on one droplet at the beginning. Add managed database / Spaces later if needed.

### Option B — Comfort stack (~₱2,900–3,300/mo)

| Item | ≈ PHP / mo |
|------|------------|
| Droplet $24 | ₱1,392 |
| Weekly backups ~$5 | ₱290 |
| Managed PostgreSQL $15 | ₱870 |
| Spaces $5 | ₱290 |
| **Subtotal** | **₱2,840 – ₱3,190** |

No SMS costs. Email reminders only.

---

## 5. Optional maintenance (later — only if she wants)

Not billed automatically. After the 30-day warranty:

| Plan | Includes | PHP / mo |
|------|----------|----------|
| **As-needed** | Fixes / small changes billed per request | Agree per task |
| **Light retainer** | Priority help, small tweaks (~2–4 hrs) | ₱2,000 – ₱3,500 |
| **Standard retainer** | More hours + monthly check-in | ₱5,000 – ₱8,000 |

For a cousin / first client, **as-needed** after warranty is often enough.

---

## 6. Year-1 cost example (family rate)

Assuming **₱65,000** build + lean hosting **₱1,500/mo** + no retainer:

| Cost | Amount |
|------|--------|
| Development | ₱65,000 |
| Hosting + email (12 × ₱1,500) | ₱18,000 |
| Domain / misc | ₱2,000 |
| **Year-1 total (approx.)** | **≈ ₱85,000** |

With optional light retainer (₱2,500 × 12): **≈ ₱115,000** Year-1.

---

## 7. Fair expectations at this rate

So this stays healthy for both of you:

- Scope stays as in the **system specification** — new big features after launch are extra or Phase 2  
- Timeline can flex around a first-client / portfolio build (agree dates in writing)  
- She pays hosting directly; you don’t absorb server bills  
- Portfolio credit agreed (e.g. “Built for DT Smile Dental Clinic”) if she’s comfortable  
- SMS, PhilHealth/HMO APIs, native apps, DICOM imaging remain **out of scope**  

---

## 8. Not included

- SMS / text reminders  
- PhilHealth / HMO claims integrations  
- DICOM imaging systems  
- Native mobile apps  
- Large Google Sheets cleanup beyond basic patient CSV import  
- Formal legal/compliance certification  
- Hardware (PCs, printers, tablets)  
- Ongoing maintenance unless she opts in later  

---

## 9. Recommendation summary

| Decision | Choice |
|----------|--------|
| Development | **₱50,000 – ₱80,000** (suggest **₱65,000**) |
| Why lower than market | Cousin + first client + portfolio |
| Hosting | **She pays DigitalOcean** (~₱1,400/mo lean start) |
| Maintenance | **Optional later** |
| Notifications | Email only |
| Next step | Agree fee + dates → build |

---

## 10. How to say it to her (short)

> Market rate for a full clinic system like this is usually much higher. Because you’re family and this is my first official client, I’m offering development at **₱50,000–₱80,000**. You pay hosting yourself on DigitalOcean — about **₱1,400/month** to start. After launch I’ll fix bugs for 30 days; ongoing maintenance is optional if you want it later.
