# theWorkdayDestroyer
Workday and similar ATS platforms degrade applicant experience, misrepresent qualified candidates through faulty parsing, and create massive inefficiencies in hiring workflows, all while locking companies into expensive, hard-to-replace systems. This system stops now. 
Death to HR.

Grievances:
Candidates hate filling out the same info repeatedly.
Automated resume parsing is unreliable and often ignored.
Applicants get ghosted → no quality feedback loop for the company.
HR buys features they never use; bad UX persists because the user ≠ buyer.
Filtering based on keywords + biases in parsing → systemic exclusion.

Intended Resolution:
No forced data entry, no locked-in templates.
AI modules are optional, swappable, and sandboxed.
Candidates can view, edit, or redact the system's interpretation of their experience.
Structured output is generated post-consent, making intelligent filtering possible without compromising the human story.
We invite developers and companies to contribute filters, UI modules, and enrichment layers that fit their culture and ethics.
No silent parsing.
No shadow filtering.
No mandatory AI processing.
Every decision made by the system must be inspectable by the applicant.

Features:
Format-Agnostic Upload - Accept resumes in multiple formats without rigid forms.
Modular Parsing Layer	Pluggable Agents - Extract structured data.
Consent-Driven AI Interpretation - Resume is interpreted and previewed before any processing or sharing.
Candidate Narrative Editor - Applicants can refine or rewrite how they’re represented.
Recruiter Dashboard (MVP) - Simple search and filter UI over semantically tagged applicant profiles.
Privacy-First Architecture - No tracking, no unauthorized scraping, full data control by applicants.

System Components:
Frontend: Next.js + Tailwind
Backend: Supabase (Postgres) or modular backend with API-first structure
AI Layer: Optional plugin interface for OpenAI, Claude, open-source LLMs, or even custom rule-based logic
Resume Parser: Custom pipeline for PDF, DOCX, plaintext → semantic graph
Search/Match Layer: Typesense or Weaviate for hybrid semantic + keyword search
Auth: Magic Link / OAuth2
Deployment: Vercel, Railway, Fly.io — dev-friendly out of the box

Who’s This For?
Applicants tired of filling out the same forms across platforms.
Recruiters who want meaningful insights, not just keyword matches.
Developers interested in open, ethical hiring infrastructure.
Startups who need an ATS that doesn’t suck time or money.

Roadmap:
Phase 1: Resume Ingestion + Preview
Upload any format → semantic breakdown.
review/approve before save.

Phase 2: Recruiter UI
Minimalist search, filtering, tagging.
Feedback loop for interview outcomes.

Phase 3: AI Plugin Support
OpenAI agent example.
Plug-in interface for custom agents.

Phase 4: Applicant Dashboard
Track submissions.
Tailor resume narratives.
Insights on visibility & filtering.

