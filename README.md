# Bekzhan Kimadiyev

Software engineer in Astana, Kazakhstan. I build backend systems and the tools around them: APIs, databases, integrations, and the occasional desktop add-in.

Currently a **Fullstack Software Engineer at [Smart Remont](https://smartremont.kz)** and a **Master's student at Nazarbayev University** (B.Sc. in Computer Science, NU, 2026).

---

### Work

**Smart Remont** — renovation company, internal business platform
- Backend services on Django REST Framework over PostgreSQL stored procedures: client requests, estimates, change orders.
- A Revit 2025 add-in (C#, .NET 8, WPF) that lets designers pull a client request into a Revit model and send room areas, measurements and work volumes straight to the backend.
- Payment and banking integrations on FastAPI, including installment plans and digital document signing.

### Selected projects

**[Future School](https://github.com/BekzhanK1/django-future-school-backend)** — LMS for International Future School Astana
- Multi-tenant platform with role-based access across five roles and full data isolation between schools.
- Automatic timetable generation; assessments with partial-credit grading.
- Serves 5,000+ users; heavy work runs in Celery workers.
- Django 5, Next.js 15, Celery, Redis, Microsoft Graph API · [backend](https://github.com/BekzhanK1/django-future-school-backend) · [frontend](https://github.com/BekzhanK1/future-school-frontend)

**[MoodLog](https://github.com/BekzhanK1/moodlog-backend)** — AI journaling app
- Async pipeline for voice transcription (Whisper) and sentiment analysis (GPT-4o).
- Entries encrypted at rest with AES-256 envelope encryption; JWT refresh-token rotation.
- Product analytics: DAU/MAU, retention, MRR; payments via Webkassa.kz.
- FastAPI, React · [backend](https://github.com/BekzhanK1/moodlog-backend) · [frontend](https://github.com/BekzhanK1/moodlog-frontend)

**[Monty](https://github.com/BekzhanK1/monty-finance)** — personal finance and meal planning
- Budgets, transactions and analytics with a Telegram integration; weekly meal plans built from a dish and ingredient catalog.
- FastAPI, SQLAlchemy, APScheduler, React 19, Mantine

**[Sauna](https://github.com/BekzhanK1/sauna-backend)** — B2B booking platform
- Dynamic pricing with time-based discounts; booking notifications through Telegram, WhatsApp and SMS.
- Django, DRF, Celery, Redis, React, Docker · [backend](https://github.com/BekzhanK1/sauna-backend) · [frontend](https://github.com/BekzhanK1/sauna-frontend)

### Stack

| | |
| :-- | :-- |
| **Languages** | Python, TypeScript, C#, SQL |
| **Backend** | Django, DRF, FastAPI, Celery, Redis, RabbitMQ, WebSockets |
| **Data** | PostgreSQL (stored procedures, query tuning), SQLAlchemy |
| **Frontend** | React, Next.js, Vue 3 / Quasar, Tailwind CSS |
| **AI** | OpenAI API, Whisper, Gemini, RAG |
| **Infra** | Docker, GitHub Actions, AWS S3, Linux |
| **Desktop** | .NET 8, WPF, Revit API |

### Contact

[LinkedIn](https://www.linkedin.com/in/bekzhan-kimadiyev-8b803b2b7/) · [Telegram](https://t.me/the_b_d) · [bkimadieff@gmail.com](mailto:bkimadieff@gmail.com)
