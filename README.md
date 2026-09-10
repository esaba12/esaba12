# Ethan Saba

CS @ University of Michigan. I build tools that turn messy information into something a
person can actually act on — and I ship them, so real people use them.

Mostly TypeScript/React and Python, on Postgres. Lately a lot of LLM plumbing: the
interesting part isn't the prompt, it's everything around it — auth, rate limits, bad
input, and what happens when the model is wrong.

## Projects

**[Recruiting OS](https://github.com/esaba12/recruiting-tool)** · [live](https://recruiting-os-phi.vercel.app)
A recruiting CRM, application tracker, and job-board aggregator for a student job search.
Multi-tenant with bring-your-own-key AI — your data stays in your own account and you're
never billed for anyone else's usage. React + Supabase, with Gmail and Notion pipelines
that turn email and call notes into structured records.

**[OpenRestore](https://github.com/esaba12/openrestore)**
A bedside sunrise alarm and sound machine built from a smart bulb and a speaker you
already own. Self-hosted, LAN-only, no cloud and no subscription — replaces a $170 Hatch
Restore plus $60/year of content for about $65 in parts. Python, `pytest` / `ruff` /
`mypy --strict`, with mock drivers so the whole thing runs without hardware.

**[kitCreator](https://github.com/esaba12/kitCreator)**
Turns any song into a playable multi-octave sampler kit — hand it an audio file, get back
an SFZ + DecentSampler preset that loads in any sampler. Drums, bass, guitar, piano, and
synth all work end to end. Built for a Roland MC-101, generalized to any DAW.

**[Course Signal](https://github.com/esaba12/course-signal)** · [live](https://uiuc-course-demand-tool.vercel.app)
An advisor-facing planning tool that reads course history to make the next scheduling
conversation clearer. Institution-neutral by design; UIUC is the demo adapter. Built for
OpenAI build week — and deliberately scoped as a *signal*, not a capacity forecast.

**[Shishi](https://github.com/esaba12/Shishi)** · [live](https://shishi-app.vercel.app/)
A three-sided platform for funding and organizing Shabbat dinners in Tel Aviv, connecting
sponsors who underwrite dinners, hosts who open their homes, and attendees looking for a
seat at the table.

**[Real Estate Market Update Bot](https://github.com/esaba12/real-estate-news)**
A weekly pipeline that turns commercial real-estate news into a short market update with
voiceover. Built while working in commercial real estate, for the people I worked with.

**[Keep In Touch](https://github.com/esaba12/keepintouch)**
An SMS check-in system that decides *who* to reconnect with and *when* — cadence-decay
prioritization with calendar-aware send timing.

**[Portfolio](https://github.com/esaba12/EthanSabaPortfolio)** · [ethansaba.com](https://ethansaba.com)
Personal site. Next.js + TypeScript.

## Private work

Two larger projects aren't public, but are the ones I'd most want to talk through:

- **Outpost** — a fashion shopping app that unifies one feed across retailers and surfaces
  the real price, with sale and price-drop alerts. React Native + Expo on a 31-table
  Postgres schema with row-level security throughout, CI, and a test harness.
- **Community Directory** — an access-controlled member directory with an Obsidian-style
  graph view: Louvain community detection and degree centrality computed at import,
  rendered as a force-directed graph over a roster held under strict RLS.

Additional work lives in separate GitHub environments tied to my school, Axonius, and
Alias Intelligence, and stays private there.

## What I like building

- Interfaces that make complicated information legible
- Small tools that save people real time
- Systems that connect data, people, and decisions
- Creative software — especially anything involving sound

## Links

[Portfolio](https://ethansaba.com) · [Recruiting OS](https://recruiting-os-phi.vercel.app) · [Course Signal](https://uiuc-course-demand-tool.vercel.app) · [Shishi](https://shishi-app.vercel.app/)
