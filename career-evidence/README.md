# Build a reusable career evidence knowledgebase

A CV or resume is necessarily selective. Over time, useful projects, decisions, responsibilities and examples can be forgotten, taken for granted or reduced to a few old bullet points.

These instructions ask an AI agent to interview you systematically about your career and maintain a detailed evidence knowledgebase in a local Markdown file. The agent works through your career one focused question at a time, uses neutral prompts to help memories surface, records uncertainty and corrections, and notes how each substantial example might support a future CV, application or interview.

The result is reusable source material, not a finished CV. You can later use it to create a base CV or tailor an application without relying on whatever you happen to remember in that conversation.

## What you need

1. An AI agent that can read, create and edit files in a local working folder. A chat interface without file tools is not suitable for this workflow.
2. A capable model with enough usage allowance for a detailed interview that may continue across several sessions.
3. Any existing CVs or resumes, role histories, application drafts, feedback, achievement notes or relevant career documents you want the agent to consider. These are useful but optional.
4. Time to answer conversationally. You do not need to prepare a list of achievements or know which experiences will prove useful.

## Privacy

Career documents can contain personal contact details, confidential employer information and accounts of difficult situations. Check how your chosen AI service handles supplied files and conversation data. Use copies of documents and remove information you do not want to share.

Tell the agent when evidence is private, sensitive or unsuitable for public use. The prompt asks it to preserve those restrictions in the knowledgebase, but you remain responsible for what you provide and later publish.

## Getting started

1. Create a working folder for the interview.
2. Put copies of any existing career documents you want considered into that folder.
3. Copy the [full agent instructions](prompt.md) into a new agent session and give it access to the folder. Allow it to create and update the local Markdown knowledgebase.
4. Answer one question at a time. Approximate memories and “I don't know” are valid answers. Correct the agent when an interpretation, attribution, figure or suggested wording is wrong.
5. Pause when you need to. The knowledgebase includes an **Interview control** section so the agent can recover the purpose, coverage and next step after an interruption or conversation compaction.

The default output is `cv-evidence-kb.md`. It should contain the detailed career evidence, its sources and qualifications, potential CV/application uses, framing decisions, coverage gaps and a clear resumption point. The prompt recognises both “CV” and “resume” and asks the agent to follow your preferred terminology.

The interview is complete when the agreed career areas have useful coverage, the saved material has been checked against the supplied documents, and further questions no longer serve a specific material gap. More memories can always be added later.
