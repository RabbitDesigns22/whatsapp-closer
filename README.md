# whatsapp-closer

**Evidence-ranked rules to close sales over WhatsApp.**

`whatsapp-closer` is an agent skill for Claude Code (and any agent that reads `SKILL.md` skills). Use it when you build, write or improve a sales assistant that answers people who write from an ad ("Hi, info"). Every rule says how strong its evidence is: MEASURED (studies with data: lead response time, Gong call research, Spiegel reviews, Meta case studies), OFFICIAL (WhatsApp and Meta policy) or OPINION (proven sales methods not measured on WhatsApp). Vendor numbers without a method were left out.

It covers: answer in under 5 minutes, offer a call at the moment of decision, 2-3 questions before price, one recommendation, a two-option next step in every message, objections with a pause and a question, 2-3 follow-ups max, human handoff, the free ad window, ready Spanish scripts (formal and informal), what never to do, weekly metrics, and how to change a live assistant without breaking it.

## See the difference

> **You:** Hi, info

**Without the skill:** a long wall of prices and features, then silence. Two days later: "Did you see my message???"

**With the skill:** a quick friendly reply, two or three questions, one recommendation, and a next step with two options ("Tuesday or Thursday?"). Each rule is tagged with how strong its evidence is.

**Skip it if** you sell through a checkout page with no chat in between.

**Status:** in daily use in the author's own setup. Plain instructions, no scripts, no network calls. MIT. Issues and suggestions welcome.

## Install

```bash
npx skills add RabbitDesigns22/whatsapp-closer
```

Or manually: copy `skills/whatsapp-closer/` into `~/.claude/skills/`.

## Works well with

- [`small-budget-ads`](https://github.com/RabbitDesigns22/small-budget-ads): the ads that bring the conversations.
- [`easy-for-them`](https://github.com/RabbitDesigns22/easy-for-them): messages people actually follow.

## Español

**Reglas comprobadas para cerrar ventas por WhatsApp.** Para armar o mejorar una asistente que contesta a quien escribe desde un anuncio. Cada regla dice si está medida, si es regla oficial de Meta o si es un método de ventas reconocido: contestar en menos de 5 minutos, ofrecer llamada en el momento de decidir, 2-3 preguntas antes del precio, una sola recomendación, cada mensaje termina con dos opciones de día, objeciones con pausa y pregunta, máximo 2-3 seguimientos, siempre una persona disponible. Trae guiones en español (de usted y de tú), lo que nunca hay que hacer y cómo medir si cierra.

Instalar: `npx skills add RabbitDesigns22/whatsapp-closer`

## More skills from the same setup

These come from one real workflow: a small agency run with 15+ Claude Code sessions in parallel. Each skill fixes one problem that kept happening there.

| Skill | What it fixes |
|---|---|
| [one-pass](https://github.com/RabbitDesigns22/one-pass) | get it right the first time; stop paying tokens for rework |
| [hora-exacta](https://github.com/RabbitDesigns22/hora-exacta) | real date and time in every message, so nothing lands on the wrong day |
| [hands-on](https://github.com/RabbitDesigns22/hands-on) | the agent does what it can and only asks you for codes, keys and payments |
| [easy-for-them](https://github.com/RabbitDesigns22/easy-for-them) | steps people actually follow: direct link, one action per line |
| [one-answer](https://github.com/RabbitDesigns22/one-answer) | one thought-through answer instead of plan, fix, new plan |
| [never-twice](https://github.com/RabbitDesigns22/never-twice) | a shared error log so no session repeats a known mistake |
| [report-now](https://github.com/RabbitDesigns22/report-now) | status checked live this minute, stamped with the time |
| [sort-me-out](https://github.com/RabbitDesigns22/sort-me-out) | one ordered list of what is urgent, waiting and forgotten |
| [in-the-loop](https://github.com/RabbitDesigns22/in-the-loop) | a live board so parallel sessions know what the others changed |
| [study-first](https://github.com/RabbitDesigns22/study-first) | reads everything in full and answers point by point, no invented details |
| [session-watchdog](https://github.com/RabbitDesigns22/session-watchdog) | wakes the sessions that got stuck mid-task, leaves the rest alone |
| [skill-harvest](https://github.com/RabbitDesigns22/skill-harvest) | reads your sessions and finds the skills you are missing |
| [small-budget-ads](https://github.com/RabbitDesigns22/small-budget-ads) | Meta Ads rules for 1-5 USD a day ad sets |
| [whatsapp-number-onboarding](https://github.com/RabbitDesigns22/whatsapp-number-onboarding) | connect a number to the WhatsApp Cloud API in the safe order |
| [proposal-pdf](https://github.com/RabbitDesigns22/proposal-pdf) | short PDF proposals with every price checked against its source |
| [published-vs-planned](https://github.com/RabbitDesigns22/published-vs-planned) | says "published" only for what it saw live on the public page, Facebook and Instagram checked apart |
| [source-every-fact](https://github.com/RabbitDesigns22/source-every-fact) | every price, phone and name on a post traced to its source, nothing added |
| [only-what-was-asked](https://github.com/RabbitDesigns22/only-what-was-asked) | "pause only Google Ads" pauses only Google Ads, and proves the rest did not move |
| [model-per-chat](https://github.com/RabbitDesigns22/model-per-chat) | the right model for each chat: top model where mistakes cost money, cheap or none where it only runs often |
| [music-by-niche](https://github.com/RabbitDesigns22/music-by-niche) | music that matches the client's business, never repeated for a client or across clients in 3 weeks |
| [full-power](https://github.com/RabbitDesigns22/full-power) | the best the model can do on high-stakes work: strongest model only for the hard step, best-of-N with a judge, fresh-eyes verifier |

If one of them saved you a redo, a star helps other people find it.

## License

MIT. Made by [Rabbit Designs](https://github.com/RabbitDesigns22).
