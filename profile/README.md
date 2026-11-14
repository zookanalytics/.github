# Zook Analytics

I'm John Zook. Zook Analytics is the umbrella for the software I build and the consulting I do.

## How I build

AI is changing how software gets made, and I've built with it since 2023. For the past year I haven't written code by hand. I run a standing team of ten or more AI agents, with Claude building and Codex reviewing, and my time goes to steering, judging architecture, and turning each correction into process so the next round needs less of it.

How those agents work comes from [gc-toolkit](https://github.com/zookanalytics/gc-toolkit), the opinionated, open-source pack I build on Gas City, a multi-agent runtime. Its [written foundation](https://github.com/zookanalytics/gc-toolkit/blob/main/docs/foundation.md) starts from one asymmetry: AI changed the cost of work. Agent iteration is cheap, and human attention is the budget. It's [the same question I bring to an engineering organization](https://www.zookanalytics.com/#approach): where judgment has to sit, and what the system should handle before it asks a person.

## What's here

- [gc-toolkit](https://github.com/zookanalytics/gc-toolkit): the pack above. Start with its [foundation document](https://github.com/zookanalytics/gc-toolkit/blob/main/docs/foundation.md), the charter the rest of the pack follows.
- [sprintshow](https://github.com/zookanalytics/sprintshow): lets an AI agent show what it just built. Turns a markdown demo script into a short captioned video, with each step checked against the live app.
- [bmad-orchestrator](https://github.com/zookanalytics/bmad-orchestrator): home of agent-env, a CLI that gives each AI agent its own isolated, ready-to-work development environment. Ships on npm as agent-env; the BMAD workflow dashboard lives alongside it.

## The consulting

I advise CEOs, CTOs, and executive teams on the engineering organization behind the product: how it's built, how it decides, and how it delivers. AI is changing all three. More at [zookanalytics.com](https://www.zookanalytics.com).

## Reach me

Email [hello@zookanalytics.com](mailto:hello@zookanalytics.com). I'm also on [LinkedIn](https://www.linkedin.com/in/johnzook), and my personal GitHub is [johnzook](https://github.com/johnzook).
