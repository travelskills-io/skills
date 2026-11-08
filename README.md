# TravelSkills

Open-source skills for travel pros, in the Agent Skills format that Claude and
ChatGPT read. Built from how the work is really done, not from generic web data.

A skill is a set of instructions and examples you add to an AI assistant once.
The assistant then uses it whenever your request matches.

Each skill targets one job and encodes how that job is actually done: the
choices an experienced pro makes, the phrasings they avoid, the practical
details they never forget. Every pattern draws on identified trade sources.

The skills follow the open [Agent Skills](https://agentskills.io) standard.

## Skills

| Skill | For | Status |
| --- | --- | --- |
| [`travel-planner`](travel-planner/) | Independent travel planners and travel advisors | Preview |

### travel-planner

Writes and reviews itineraries, trip proposals, day-by-day programs, hotel
descriptions, and emails to clients and suppliers. Writes for American clients
in English and for French clients in French, with each market's conventions.

You get a draft ready to review, and below it a "For the planner" list of what
to check before sending. In our tests, it never claimed a booking that wasn't
made or a trip you hadn't taken. Tested on Claude Sonnet, on cases for American
and French clients.

Page and download: [travelskills.io/skills/travel-planner](https://travelskills.io/skills/travel-planner)

## Install

No code, about 5 minutes. Step-by-step guides:
[English](INSTALL.md) · [Français](INSTALL.fr.md)

Tested on Claude. ChatGPT accepts the same skill format, but we haven't tested
it yet.

## Status

Built in public. `travel-planner` is the first skill, in preview.
`visitor-advisor` comes next.

## License

[MIT](LICENSE)

---

[travelskills.io](https://travelskills.io) · Nicolas François, Founder, TravelSkills
