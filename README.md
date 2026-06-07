# Priyavrat Uniyal

I build backend systems and local-first tools around AI, memory, privacy, and developer workflow.

I like software that makes messy work easier to reason about: fewer repeated explanations, clearer failures, and more context kept close to the people using it.

## experiments

### [Tuskbase](https://github.com/priyavratuniyal/tuskbase)

Local-first memory for AI coding agents.

Agents can write code now. The fragile part is continuity: decisions, repo context, and the reason something exists disappear too easily between sessions.

### [EchoTrace](https://github.com/priyavratuniyal/echotrace)

Local-first observability for voice AI.

Voice systems fail in layers: audio, transcription, prompts, model behavior, scoring, and glue code. EchoTrace is about making those failures inspectable.

### [Koshika](https://github.com/priyavratuniyal/koshika)

Offline-first health report parsing with on-device AI.

Health PDFs are useful, private, and annoying to reason through. Koshika explores making them searchable without casually uploading them somewhere.

## recurring thoughts

- local-first is underrated
- memory is different from state
- reliability beats clever prompts
- privacy should be a default shape
- good tools reduce repeated context-setting
- boring infrastructure helps weird ideas survive
- write down the decision before the system forgets why

## default approach

Boring pieces first: backend systems, local storage, simple protocols, small CLIs, and tools that can be inspected without ceremony.

The stack matters less than whether the system stays understandable.
