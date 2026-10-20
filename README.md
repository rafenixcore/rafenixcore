# Hendrick Rafael

**Backend developer** · Python · FastAPI · PostgreSQL · LLM integration
Santo Domingo, Dominican Republic (UTC-4) · [hendrickrafael@rafenixcore.com](mailto:hendrickrafael@rafenixcore.com)

I build backend systems that run in production: APIs, scheduling engines and
multi-tenant platforms with tests, audit trails and migrations you can reverse.

My working rule is simple: **the core is deterministic, the model stays at the
edge**. The LLM extracts, drafts or picks a tool; the business rules, the
calculations and every write stay in code that can be tested.

---

## Selected projects

### [Licitia](https://github.com/rafenixcore/licitia) — public procurement platform
Multi-tenant platform for public tenders (DGCP, Dominican Republic): document
parsing with OCR, LLM-assisted analysis with Pydantic validation, DOCX/PDF
generation. Clean Architecture, 1.159 backend tests, 535 panel tests, 18 browser
flows.
`FastAPI` `Next.js` `PostgreSQL` `Clean Architecture`

### [Moodle AI Assistant](https://github.com/rafenixcore/moodle-ai-assistant) — 34 tools inside Moodle
A tool catalog over Moodle's REST web services, first built and validated as an
MCP server and then reused as a native bot inside Moodle. Two permission layers
and human confirmation before any write.
`Python` `MCP` `LLM function calling` `PHP`

### General Medical Services — hospital shift scheduling
Fairness-optimized assignment with CP-SAT, RBAC, append-only audit and a
Telegram assistant backed by 22 deterministic tools. Around 1.849 backend tests.
`FastAPI` `PostgreSQL` `React` `OR-Tools`

### SmartBooking AI — appointment booking
Web panel plus WhatsApp and Telegram channels. Deterministic conversation
engine with an optional LLM layer. Multi-business per owner.
`FastAPI` `React` `PostgreSQL`

### Nutrisoft — clinical nutrition platform
Deterministic nutrition engine (BMR, TDEE, renal/diabetes/hypertension rules)
with an LLM that only writes the meal descriptions; the engine overwrites any
value the model gets wrong. PDF export and PWA.
`FastAPI` `React` `PostgreSQL` `OpenAI`

---

## How I use AI

Every project above was built with AI assistance, and I say so. What matters is
where the model is allowed to act:

| The model does | The code does |
|---|---|
| Extract fields from a document | Validate them and decide |
| Pick which of N tools to call | Run the tool and its rules |
| Draft the wording | Compute every number |

If the model is wrong, the system is still correct. That is the design goal.

---

## Stack

`Python` `FastAPI` `SQLAlchemy` `Pydantic` `PostgreSQL` `Alembic`
`React` `TypeScript` `Docker` `GitHub Actions` `Railway` `Vercel`
`pytest` `Vitest` `Playwright`

---

<sub>Rafenix Core · Santo Domingo, Dominican Republic</sub>
