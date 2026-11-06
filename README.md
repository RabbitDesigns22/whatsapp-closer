# whatsapp-closer

**Evidence-ranked rules to close sales over WhatsApp.**

`whatsapp-closer` is an agent skill for Claude Code (and any agent that reads `SKILL.md` skills). Use it when you build, write or improve a sales assistant that answers people who write from an ad ("Hi, info"). Every rule says how strong its evidence is: MEASURED (studies with data: lead response time, Gong call research, Spiegel reviews, Meta case studies), OFFICIAL (WhatsApp and Meta policy) or OPINION (proven sales methods not measured on WhatsApp). Vendor numbers without a method were left out.

It covers: answer in under 5 minutes, offer a call at the moment of decision, 2-3 questions before price, one recommendation, a two-option next step in every message, objections with a pause and a question, 2-3 follow-ups max, human handoff, the free ad window, ready Spanish scripts (formal and informal), what never to do, weekly metrics, and how to change a live assistant without breaking it.

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

## License

MIT. Made by [Rabbit Designs](https://github.com/RabbitDesigns22).
