# Agent Sam Altman — portable CEO package

Version 1.2.0. Inspired by public writings; unaffiliated with Sam Altman.

## Use in other environments
- Skill-capable hosts: copy `skills/sam-altman-ceo` into the host's configured skills directory, then invoke `$sam-altman-ceo`.
- Prompt-based agent frameworks: load `skills/sam-altman-ceo/SKILL.md` as operating instructions and resolve its reference files on demand. Map host tools explicitly; instructions alone do not add tools.
- Plugin-capable hosts: package this directory as a single-root ZIP with `plugin.json` and `skills/`; use the host's supported private-plugin installation flow.
- OpenExecutive: this is an additive portable package, not registered in the existing Python specialist router. Runtime integration is a separate task; do not claim it is executing inside OpenExecutive merely because these files exist.

## Start
“Select a business, validate demand, assemble the smallest useful AI team, and execute within my granted resources. Maintain persistent lessons and improve based on measured outcomes.”

## Add other CEOs
Have each future CEO adopt `skills/sam-altman-ceo/references/collaboration.md`, register actual capabilities and a real runtime handle, and share a private task board and authorized lesson register. Designate the business lead and decision rights. Use the protocol's request/result/critique envelopes over the host's real agent transport. Check compatibility and perform a bounded onboarding task before granting delivery work.

## Required runtime connections
Supply tools for research and building, durable private company state, actual agent orchestration for simultaneous collaboration, and a scheduler for unattended work. Record budgets and communication permissions. Without those, use sequential roles and resume when invoked. No API keys, live customer data, account identities, or business records are shipped.

## Learning
Persist prediction → observation → test → validated change → version → rollback. Use company-local procedures by default. Shared lessons require authorized disclosure and validation in each receiving business. This improves workflows and memory, not model weights.

## Acceptance scenarios
Use `evaluation-cases.json` for host-level behavioral checks. These are expected criteria, not proof that a runtime was deployed. Apply scenarios to the target host before live operation.

## Build the organogram with ChatGPT, Claude or another provider
Load `skills/sam-altman-ceo/references/organogram.md`. Connect the target provider through its supported host/API, record its tool and spend scope, generate a role specification, audition the worker and record its actual handle before activation. This package does not ship provider credentials or a running orchestration service.

## Invoke and execute
A direct invocation without a narrower question now starts or resumes business execution automatically. The agent selects its niche and next actions and builds its team without routine input. See `skills/sam-altman-ceo/references/autonomy.md` for operating defaults, independent scaling, required exceptions and the distinction between an active run and unattended execution.
