## Gustavo Aguiar

**Product Engineer at [Prolog](https://github.com/prologapp)**: full stack with React/TypeScript and Java.

I like owning a problem end to end: understanding what the operator actually needs, shaping the solution with product and design, and shipping it across the frontend, the API and the database. These days a big part of that is making AI agents genuinely useful in a real production codebase.

Live projects and case studies: **[Portfolio](https://72-60-148-65.sslip.io)**

---

### Product

**Fleet analytics platform.** I led Prolog's fleet dashboards from a blank page to production. Instead of building one-off screens, I designed a config-driven engine (component registry, KPI engine, shared data context, chart library) so that each new dashboard is mostly configuration. The Fleet, CPK, Safety and Maintenance dashboards all run on it.

**Micro-frontend platform.** I work in a Module Federation architecture on top of our in-house design system, which means balancing feature speed against keeping shared contracts stable for other teams.

**Backend when it's needed.** I write Spring Boot, MyBatis and PostgreSQL code, so the features I own don't stop at the API boundary.

### Agent engineering

I build the harness around coding agents: the context, guardrails and feedback loops that turn them from autocomplete into teammates.

- **[fantasmas](https://github.com/gus-aguiar/fantasmas)** is a Go TUI that lets me run a fleet of agents from one terminal. It tracks missions and tasks, surfaces the questions that need a human, and follows each PR through CI.
- **Scheduled sentinel agents** audit repos overnight and report back with evidence.
- **E2E test agents** discover real selectors and routes before writing Playwright specs, so the tests match the app as it is, not as an agent imagines it.
- **Team skills and review loops** encode how we ship (merge gates, verification before "done", database safety), so agents follow the same rules engineers do.

### Toolbox

`TypeScript` `React` `Next.js` `Module Federation` · `Java` `Spring Boot` `MyBatis` `PostgreSQL` · `Go` `Node.js` `Python` · `Playwright` `Jest` · `Docker` · `Claude Code`

---

[Portfolio](https://72-60-148-65.sslip.io) · [LinkedIn](https://linkedin.com/in/gustavo-p-m-aguiar) · gustavopma90@gmail.com
