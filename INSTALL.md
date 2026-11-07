# Install a TravelSkills skill

A skill is a set of instructions and examples that shows an AI assistant how a travel pro works. You install it once. The assistant then uses it whenever your request matches.

This guide uses `travel-planner` as the example. No code, about 5 minutes.

## Claude (claude.ai or the desktop app)

1. **Download the ZIP file** (a compressed folder) from [travelskills.io/skills/travel-planner](https://travelskills.io/skills/travel-planner). Keep it zipped: Claude reads the file as it is.
2. **Open Claude** in your browser or in the desktop app, and sign in.
3. **Go to Customize, then Skills.** Direct link: [claude.ai/customize/skills](https://claude.ai/customize/skills).
4. **Add a skill and choose to upload a file.** Select `travel-planner.zip`.
5. **Turn the skill on.** Check that `travel-planner` appears in your list of skills, with its switch on.
6. **If Claude asks for code execution,** open Settings, then Capabilities, and turn on code execution and file creation. The skill needs it to read its reference files.
7. **Try it.** Start a new chat and paste a real request, for example: "Rewrite this hotel description for my clients, a couple in their sixties who want quiet." Then paste the description.

What you get back: a draft for your client, and below it a "For the planner" list of what to check before sending. Review before you send, as you would with an assistant's work.

**Teams and organizations.** On Claude Team and Enterprise plans, the skill can be shared from Customize > Skills with the Share or Publish to org controls.

### If something goes wrong

- **Claude says it can't find SKILL.md.** The ZIP was unzipped and zipped again on your computer. Download the original file again and upload it as it is.
- **You don't see Skills.** Skills may not be available on your plan. Check Anthropic's help pages for your plan.
- **Claude doesn't seem to use the skill.** Check that its switch is on, then mention it in your request: "Use the travel-planner skill to…"

## ChatGPT

Tested on Claude. ChatGPT accepts the same skill format, but we haven't tested it yet. If you try it, tell us how it goes.
