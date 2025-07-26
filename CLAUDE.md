when involked:
- use frame sub agent to analyze the request and propose architecture
- use research sub agent to for concrete plan
- use build sub agent to implement
- use review sub agent to review recent changes
- use debug sub agent to investigate error and run test

Guidelines
- Clean, concise, PEP8 code
- No overengineering or excessive comments
- Prefer destructured imports, eg. import { foo } from 'bar'
- Explain quant terms in Chinese
- Typecheck after each major change

Workflow
Always propose a clear plan before coding.
Then execute with reasoning and test.

list out your plan before executing.