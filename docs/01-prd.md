# PRD — Living Portfolio

- **Owner:** Karan Rathod
- **Status:** Draft v0.1
- **Last updated:** 2026-11-05

> ✍️ Karan: rewrite anything marked `TODO(karan)` in your own words. Interviewers will ask about this doc.

## 1. Problem
Static portfolios (templates, animations) look the same and are easy to fake with AI. Recruiters in 2026 screen for **proof of shipping, judgment over AI output, and specialization**. My real strengths — rolling out ERPNext in a manufacturing company, integrating third-party systems (OnTime, Lystloc, WhatsApp Business), and multi-tenant SaaS exposure at Billeasy — are invisible in a normal portfolio.

TODO(karan): one paragraph — why *you* need this, in your words.

## 2. Goals
1. Show **live proof of work** (GitHub activity, DSA practice) without manual effort.
2. Show **how I make decisions** through case studies and ADRs.
3. Rank on Google for **niche ERPNext / manufacturing-tech** topics.
4. Let visitors **get answers instantly** (AI assistant, Recruiter Fit, instant contact).
5. Be **maintainable by one person** — no code changes to update content.
6. Be a **learning vehicle**: TanStack Start, Cloudflare, pgvector, Git team workflow.

## 3. Non-goals (v1)
- No fancy 3D/heavy animation.
- No training or hosting our own LLM.
- No public user accounts / comments.
- No showing confidential company code or data.

## 4. Personas
| Persona | Wants | Success looks like |
|---|---|---|
| **Recruiter** (60 sec skim) | Is he a fit? Resume. | Downloads resume / uses Fit check / contacts |
| **Hiring manager / tech lead** | Depth, judgment, code quality | Reads a case study + opens the repo |
| **MSME owner / client** | Can he digitize my factory (ERP, attendance, CRM)? | Contacts via WhatsApp/form |
| **Fellow developer** | ERPNext how-tos | Reads blog via Google, follows |
| **Karan (admin)** | Update in seconds, ideally from phone | Telegram quick-add / admin edit, no deploy |

## 5. User stories (v1)
**Visitor**
- As a recruiter, I can view and download the resume in one click.
- As a recruiter, I can paste a job description and see how Karan's real experience maps to it, with sources.
- As a visitor, I can see what Karan worked on today/this week (GitHub, DSA).
- As a visitor, I can read case studies: problem → constraints → decision → outcome.
- As a visitor, I can contact Karan instantly (form or WhatsApp) and he is notified immediately.
- As a reader, I find blog posts through Google and the pages load fast on mobile.
- As a visitor, I can ask the assistant questions and get answers with citations.

**Admin**
- As Karan, I can add/edit experience, projects, posts, skills and resume without code.
- As Karan, I can log a DSA problem / note from Telegram in one message.
- As Karan, I see resume views/downloads, contact leads and chat usage on a dashboard.
- As Karan, only I can access admin.

## 6. Success metrics
| Metric | Target (first 3 months after launch) |
|---|---|
| Resume downloads | TODO(karan) |
| Contact leads (recruiter + client) | TODO(karan) |
| Organic search clicks/month | TODO(karan) |
| Lighthouse (perf/SEO/a11y) | ≥ 95 |
| Monthly running cost | ≈ ₹0 + domain |
| Time to update content | < 1 minute |

## 7. Constraints
- **Cost:** free tiers only (Cloudflare, Neon, Gemini free). Domain is the only spend.
- **Team:** solo developer, evenings/weekends.
- **Security:** no private company data to external LLMs; admin behind Cloudflare Access; secrets never in git.
- **Reliability:** LeetCode has no official API — features must fail gracefully.

## 8. Release plan
| Release | Scope |
|---|---|
| v0.1 | Docs, flows, wireframes, architecture, repo + CI |
| v1.0 | Core site + admin + resume tracking + contact + blog + SEO + domain |
| v1.1 | GitHub + DSA live activity, Telegram bot |
| v1.2 | AI assistant, Recruiter Fit, skills AI section |
| v2 | Open-source contributions showcased |

## 9. Open questions
- TODO(karan): Which company projects can be shown publicly, and which need redaction? Check with your manager.
- TODO(karan): Domain name?
