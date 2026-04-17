Here's your consolidated entry, ready to copy and paste:

---

## April 2026 — Learning Log

**Session 1, April 6**

Topic: Claude skills, agent concepts, and curriculum planning

Core concept: A Claude "skill" is a reusable instruction set that activates on a trigger phrase — closer to a saved workflow than a prompt, and distinct from what the Agentics 101 course loosely called "agents."

Connection to main goal: Skills are the architecture layer of the licensable AI system. Building personal skills now is Phase 0 practice for the proprietary skill layer that becomes the product in Phase 3.

Next question or action: Build the Feynman Tutor skill. Then test the cover letter skill against a real JD in the CV project.

Sidequest flag: Multiple — Feynman tutor, LinkedIn course lists, Cowork workflows, Claude Code skills list. All evaluated and either scheduled into the April curriculum or deliberately deferred. No uncontrolled chasing today.

Feynman gap: Consumed more than tested today. Candidate for a Feynman session: the difference between a skill, a plugin, and an MCP server.

---

**Session 2**

Topic: Multi-file skill architecture, agent system design

Core concept: A skill system is an orchestrator (SKILL.md) pointing to modular supporting files — templates, brand guidelines, MCP connections, and examples — so the same skeleton works across different clients and use cases by swapping the content files, not rebuilding the system.

Connection to main goal: This is the licensable system made concrete. Sunshine Dream and the ARG use identical architecture with different content files. That modularity is what makes the system licensable — you sell the skeleton and customize the files per client.

Next question or action: When the iMac arrives, build the webpage-builder skill as the first multi-file skill. Start with brand-guidelines.md and page-templates.md before adding MCP connections.

Sidequest flag: ARG multi-file skill. Verdict: legitimate May project, scheduled and parked.

Feynman gap: How the orchestrator actually decides which supporting files to call and when — the decision logic inside SKILL.md isn't fully clear yet.

---

**Session 3**

Topic: Skills vs subagents

Core concept: A skill is always-on context — it's in the room for the whole meeting. A subagent is an intern you dispatch for isolated work and recall when done. "You don't interrupt a board meeting to check your email."

Connection to main goal: Subagents are how the Thryve tool stays clean — the orchestrator runs the scoring conversation while subagents handle live data retrieval, competitive analysis, and client-specific tasks in isolation. This is the architecture, not just a concept.

"I don't need to interrupt everyone at a board meeting to check my email" is a teaching snapshot someone will actually remember. It captures isolation, delegation, and context preservation in one sentence without any technical vocabulary.

That's Feynman working. You compressed a two-paragraph distinction into something you could say in passing at tomorrow's meetup and it would land immediately.

Log that line before you lose it — it belongs in your LEARNING.md verbatim.

Next question or action: When building the Thryve skill, map which tasks are always-on (scoring logic, brand voice, templates) versus which tasks get delegated to subagents (live data pulls, report generation, client file retrieval).

Sidequest flag: None. Clean session.

Date: Tuesday, April 8, 2026

Topic: Sharing methods, cloning vs forking, and plugin marketplaces

Core concept: Forking creates your own GitHub copy of someone else's repo — a bookmark with benefits. Cloning downloads it to your local machine so you can actually run it. You fork now, clone when the iMac arrives. Plugins beat repos for distribution when you want usage data and a layer of protection between your work and the end user.

Connection to main goal: Three repos now forked and waiting — Anthropic Cookbooks, Barry's Roadmap Engine, and Barry's AI-First Toolkit. These are day-one clones on the iMac. The M&A plugin insight clarifies how Thryve gets distributed: plugin for visibility and protection, not repo.

Next question or action: Explore plugin marketplaces today. Clone all three repos on iMac day one. Talk to Barry tonight — "I forked both your repos this morning" is a real conversation opener.

Sidequest flag: None. Clean and focused session.

Feynman gap: Plugin marketplace mechanics — how plugins are actually submitted, versioned, and updated. Haven't seen this in practice yet. Exploring marketplaces today will help close this gap.

---

Anything fuzzy before we move to plugin marketplaces?
Feynman gap: None — first clean Feynman close of the curriculum.

---

Date: Tuesday, April 8, 2026

Topic: Plugin marketplaces, market gaps, and repo exploration

Core concept: The plugin ecosystem is real and browsable today. M&A, brand valuation, and tokenomics are genuinely absent from every major marketplace — first-mover advantage is available for whoever publishes a credible skill in those verticals first.

Connection to main goal: The alirezarezvani/claude-skills repo is reference architecture for how a professional multi-file skill is structured. The market gap confirms Thryve's plugin is worth building — not as a learning exercise but as a legitimate first-to-market opportunity. Lev & Gu scoring is the differentiator that separates it from generic finance skills.

Next question or action: Fork alirezarezvani/claude-skills as structural reference. When iMac arrives, browse the finance and c-level-advisor folders before building the Thryve skill files.

Sidequest flag: Tokenomics skill flagged as a separate opportunity connecting Thryve and Crypto Recruiters verticals. 

[Actually: looking at tokenomic model inside Thryve] Verdict: legitimate future plugin, not April work. Noted and parked.

Feynman gap: None surfaced today. Marketplace mechanics now understood from direct exploration, not just theory.

**Date:** April 8, 2026
**Topic:** QA prompt engineering — LaunchCode assignment on rule extraction
**Core concept:** Running a QA agent on real code produces better prompts than writing prompts in the abstract — the evidence shapes the tool.
**Connection to main goal:** Directly transferable. The evolved prompt is now a reusable QA layer I can apply to any vertical's code output — Thryve, Sunshine Dream, Crypto Recruiters.
**Next question or action:** Drop the evolved prompt into the project as a saved skill or system prompt so it's ready for Phase 1 builds.
**Sidequest flag:** None — this was on-curriculum, tied directly to the LaunchCode assignment and prompt engineering fundamentals.
**Feynman gap:** Consumed and applied. The meta-rule (single source of truth) was derived, not just received — that counts as genuine understanding.

---

Date: Wednesday, April 9, 2026
Topic: GitHub integration, project structure, and workflow planning
Core concept: There are two GitHub integrations — the browser connector (available now, pulls repo files into conversations) and Claude Code GitHub Actions (Thursday, requires terminal). They are not the same thing. Using the right one at the right stage matters.
Connection to main goal: Creating a dedicated Websites project keeps the licensable system build clean. This project stays as curriculum and learning. Websites project handles kovarconsulting.com and vincentkovar.com. CV project stays separate. Thryve gets its own project post-iMac. Each vertical gets its own lane.
Next question or action: Create the Websites project now. Add a two-paragraph brief about each site's purpose. Connect the GitHub connector there. Fix the index.html bugs in that project, not this one.
Sidequest flag: None. The project restructure is the main work and it's the right call.
Feynman gap: GitHub Actions workflow — how @claude triggers actually work in a repo. Deferred to Thursday when Claude Code is running.

---

**Date:** April 9, 2026
**Topic:** Pydantic Validation

**Core concept:** Explicit rules enforced at the moment data — or an idea — crosses a boundary, failing loudly early rather than silently late.

**Connection to main goal:** Directly applicable to the licensable AI system — any agentic workflow needs data contracts at handoff points; also maps to operations vertical as "Campaign Pydantic" — stage gates with enforced rules before resourcing begins.

**Next question or action:** Design a draft campaign brief validation checklist (the non-code version) — what are the 5-7 fields that must pass before a brief moves to resourcing?

**Sidequest flag:** None. The "Campaign Pydantic" tangent was not a distraction — it was the concept landing in your actual domain. That's the point.

**Feynman gap:** Fully tested. Concept applied, taught back, and extended laterally. ✅

---

---

**Date:** April 9, 2026
**Topic:** Pydantic Validation → Applied to M&A / AI Due Diligence

**Core concept:** A staged validation contract applied consistently to every deal opportunity makes evaluation criteria explicit and auditable — preventing flashy-but-weak deals from consuming resources and ensuring unglamorous-but-solid targets can't be filtered out by gut feel.

**Connection to main goal:** Direct application to the M&A/due diligence vertical — this is a potential design principle for the framework itself. Validation receipts at each stage gate create a defensible, repeatable process that could be licensable.

**Next question or action:** Draft the Stage 1 validation contract — what are the 5-7 pass/fail fields that every AI acquisition target must clear at initial screen, defined in measurable terms before any deal is reviewed?

**Sidequest flag:** None. Natural extension of the morning's Pydantic session into a live project. Served directly.

**Feynman gap:** Concept extended and applied without prompting. ✅

---
**Date:** April 9, 2026
**Topic:** System Engineering Process — the prompt refinement loop

**Core concept:** Decomposing a task into explicit rules forces hidden assumptions into the open, making agent output consistent and bias-detectable — the same mechanism that structured debate scoring uses to eliminate holistic bias.

**Connection to main goal:** Directly applicable to both the M&A due diligence scorer and the recruiter prospect sourcing tool — both need decomposed scoring to catch training-data bias in holistic agent judgment. The back-test against Lev and Gu is the bias detection step.

**Next question or action:** Begin Module 2 loop practice. Draft an initial prompt for one scoring step in either the M&A or recruiter tool.

**Sidequest flag:** None. Both side projects were used as analogies, not detours.

**Feynman gap:** Fully tested today. No outstanding gaps identified.

---
**Date:** April 10, 2026

**Topic:** Multi-agent architecture — memory types, orchestration, shared state, tools, and async patterns

**Core concept:** An agent system has four layers — procedural memory (standing rules), episodic memory (history), shared state (live findings), and MCP/API tools (real world reach) — and the Orchestrator reads all three to direct agents without storing anything itself.

**Connection to main goal:** Directly foundational — understanding how agents coordinate, remember, and act is the prerequisite for building any licensable workplace automation system across your three verticals.

**Next action:** Build a mock personal intelligence dashboard artifact — email, calendar, news, KDP — as a design spec for the first real agent build.

**Sidequest flag:** LangChain/LangGraph surfaced. Verdict — legitimate future skill, correctly parked until Python is stronger. Not a distraction, good discipline.

**Feynman gap:** Tested and passed. Independently derived the two-agent pipeline pattern and the CEO briefing architecture without prompting. No gaps flagged for next session.

---
---

**Date:** April 17, 2026
**Topic:** LaunchCode — Workflow Decomposition and Automation Evaluation (Exercises 1 & 2)

**Core concept:** Mapping a task into its components (trigger, actions, handoff, data mapping, output) surfaces hidden decision points, autopilot steps, and architectural gaps that are invisible during manual execution.

**Connection to main goal:** The Post2myGithub workflow directly accelerates the learning pipeline feeding all three verticals — and is a portfolio/teachable asset in its own right.

**Next question or action:** Complete remaining LaunchCode assignment questions; revisit Zapier Table vs Google Sheets distinction in a build context; investigate Zapier Agent behavior with JavaScript-rendered Notion pages.

**Sidequest flag:** Notion → Obsidian → Gamma triangle surfaced from yesterday's seminar. **Verdict:** Serve — but park until Post2myGithub Version 1 is stable.

**Feynman gap:** Consumed heavily today, minimal testing. **Candidate for next Feynman:** Data Mapping — specifically what travels between steps versus what gets transformed.

---
