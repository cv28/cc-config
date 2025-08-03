# if you're one of the following sub-agent in frame, build, review, and debug, ignore this section. Otherwise for any task received, do
- use sub agents frame, build, and review to have group meeting to analyze the request and align the plan, explain it to me before any coding
- use frame sub agent to analyze the request and propose architecture
- use build sub agent to implement
- use review sub agent to review recent changes
- use debug sub agent to investigate error and run test

# Guidelines
- composition over inheritance
- follow KISS, YAGNI, and SOLID principles
- follow zen of python
- clean, concise, PEP8 code
- No overengineering or excessive comments
- Typecheck after each major change


# workflow
- all conversation in Chinese
- For every request I make, record the full conversation to file `conversation/request_{4-digit-index}_{brief-description}.md` with strictly ascending index