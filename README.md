<div align="center">

<img src="https://avatars.githubusercontent.com/u/238680727?v=4" width="120" style="border-radius: 50%;" />

# Nuno Ferreira

**QA Analyst · Java Developer · Psychology Graduate**

Porto, Portugal · Open to remote, hybrid and on-site roles

[LinkedIn](https://www.linkedin.com/in/nuno-ferreira-a02552203/) ·
[Email](mailto:nunopferreira01@gmail.com)

*Building software as if a real person depends on it. Because someone always does.*

</div>

---

## Hi, I'm Nuno 👋

I studied psychology. Then life took me behind a bar, into a dangerous-goods logistics warehouse and to a hardware repair bench, before I wrote my first line of code.

I used to think that path was a detour. Today I think it is the reason I do this work. In every one of those jobs I saw the same thing: when a system fails, a real person feels it, usually on their worst day.

So that is what I build for. I test software before it reaches people, and when I write it, I write the tests and quality gates that stop a release before a bug gets out.

### Right now

- 🧪 **QA Tester at SPT Logistic**, testing a new logistics app against the warehouse workflows I used to run myself
- 🏗️ **Building ObraPro** at Enso Digital, a multi-tenant construction management SaaS in Java 21 and Spring Boot 3
- 💚 **Drawn to** health tech, mental health products and AI features that need to be safe, not just clever

---

## How I work

**Start from the person, not the feature.** Who is using this, in what state of mind, and what happens to them if it breaks?

**Prove it with tests.** A safety rule belongs in a test suite that fails the build, not in a comment or a code review.

**Reproduce, isolate, fix, verify.** The same loop I used at the repair bench, applied to software.

**Write it down.** Clear bug reports, documented decisions (ADRs) and known issues anyone on the team can pick up.

---

## Featured projects

### 🌱 [Lumen](https://github.com/Nokz22/Lumen): a wellbeing platform where safety is tested, not assumed

`Java 17` `Spring Boot 3` `React` `TypeScript` `PostgreSQL` `RabbitMQ`

Daily mood, energy and sleep check-ins, PHQ-9 and GAD-7 questionnaires, simulated wearable data and an AI companion. It is the project where my two backgrounds meet.

- If someone answers the PHQ-9 risk question positively, scoring stops and the crisis flow opens. A test fails the build if that ever breaks.
- Every message to the AI companion is risk-checked **before** it reaches the language model. The crisis flow is never rate-limited.
- CI on GitHub Actions: **87.9% line coverage** with an 80% JaCoCo gate, plus Testcontainers integration tests and ArchUnit architecture tests.
- **30 frontend tests** cover the screens where a bug is not cosmetic. An automated WCAG 2.1 AA check caught a button at 3.94:1 contrast before any user saw it.

### More projects

| Project | What it does | Why it matters |
| --- | --- | --- |
| **[Segue o Ritmo](https://github.com/Nokz22/segue-o-ritmo)** <br> `Java 17` `Swing` | A memory game for elderly users and people with cognitive difficulties | Accessibility first: large touch targets, full-screen kiosk mode and a Portuguese interface |
| **[AETHER](https://github.com/Nokz22/Aether)** <br> `Java 21` `Spring Modulith` `Next.js` | A personal "AI operating system" for projects, calendar, habits, finances and notes | Module boundaries enforced by tooling; the AI layer only uses each module's public API |
| **[GLaDINATOR](https://github.com/Nokz22/GLaDINATOR)** <br> `Spring MVC` `REST` `OpenAI API` | An AI guessing game that narrows down the answer through yes/no questions | Built by a team of four to a fixed deadline with a shared Git workflow |
| **[Sueca](https://github.com/Nokz22/SuecaGame)** <br> `Java` `MVC` `Sockets` | The traditional Portuguese card game, playable over LAN | Game rules fully decoupled from the UI through MVC |

🔒 **Private:** ObraPro, the construction SaaS I'm building at Enso Digital, and a crypto analytics and backtesting platform. I'm happy to walk through their architecture, code and tests in a conversation.

---

## Toolbox

| Area | Tools |
| --- | --- |
| **Testing & quality** | JUnit 5 · Mockito · Testcontainers · ArchUnit · Vitest · React Testing Library · JaCoCo · Checkstyle |
| **QA practice** | Manual and exploratory testing · Test scenario design · UAT · Regression · Accessibility (WCAG 2.1 AA) · Bug reporting |
| **Backend** | Java 17/21 · Spring Boot 3 · Spring Modulith · Spring Security / JWT · JPA / Hibernate · Flyway · REST APIs · RabbitMQ |
| **Data** | PostgreSQL · MySQL · SQL |
| **Frontend** | React · Next.js · TypeScript · JavaScript · Tailwind |
| **Tooling** | GitHub Actions · Docker · Maven · Gradle · Git · Jira |
| **AI** | Claude · Claude Code · LLM integration with safety guardrails |
| **Architecture** | Clean Architecture · Modular monolith · Multi-tenancy · ADRs · C4 · SOLID |

---

## The longer story

Before software, I spent over two years in logistics operations, handling ADR (dangerous) goods and international clients, where data accuracy and compliance deadlines were legal requirements. Before that, I ran a bar: stock, a team of people I hired myself, and systems going down in the middle of a busy night.

Under all of it sits a psychology degree. Mostly it taught me that the people using a system are more interesting, and less predictable, than the system itself.

None of that shows up in a tech stack. It shows up in the questions I ask before I test anything, and in how I stay calm when things break.

I'm still early in this path, and I know how much there is to learn. I just know why I'm here.

---

<div align="center">

**Portuguese** (native) · **English** (C1) · **Spanish** (advanced)

📍 Porto, Portugal · Open to **remote**, **hybrid** and **on-site** roles

**If my story speaks to you, I'd love to hear yours.** [Let's talk](mailto:nunopferreira01@gmail.com)

</div>
