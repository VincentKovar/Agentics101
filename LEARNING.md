
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
Ha — the raccoons have officially lost the contract to rabbits.

Let me pull up the logging skill.---

**Date:** April 18, 2026
**Topic:** Zapier Architecture — Forms, Zaps, Tables, Agents + Four Pillars of Prompting

**Core concept:** Zaps handle deterministic handoffs; Agents handle semantic interpretation — the handoff point is where predictable rules run out and judgment begins.

**Connection to main goal:** Directly maps to Post2myGithub pipeline architecture (Form → Zap → Table → Agent → GitHub/Slack) and transferable to playwriting opportunity aggregation.

**Next question or action:** Tomorrow — experiment with Zap → Agent data handoff; determine whether Gmail/multi-step limitations are tier walls or configuration gaps. Request LaunchCode student account.

**Sidequest flag:** None. Post2myGithub discussion was on-curriculum, not a detraction.

**Feynman gap:** Tested today — Zap vs. Agent architecture. Clean pass with strong analogy generation. No outstanding gaps.

**Mnemonic captured:** RCFT = Rabbits Can Fandango Tickets *(official as of today)* or Raccoons Can't Fake Talent.

---
Perfect notes. Let me refine the log with that tone correction:

---

**Date:** April 21, 2026

**Topic:** LaunchCode Exercise 2 — Agent vs. Zap decision-making; iterating agent instructions with Copilot

**Core concept:** An Agent is the right tool when a task requires judgment and interpretation (not just data routing), and the agent's value surfaces through *iteration* — each round of imprecise instructions reveals where your workflow thinking was muddy.

**Connection to main goal:** Direct. Post2myGithub needs an Agent for URL classification (matching "interested in" category, ranking multiple matches, flagging unreadable content). Today's exercise taught me: (1) how to scope agent work vs. Zap work, (2) that Copilot gives complete advice that may not fit your actual constraints, and (3) that "as if" language doesn't persist in agent configuration—only explicit rebuild does. Ensure changes have been recorded before testing. The error triggered  by forgetting to give the agent a URL confused the agent and it reverted to an earlier state. 

**Next question or action:** Before building the real Post2myGithub Agent, test whether Zapier's "Visit Site" tool can distinguish between free and paywalled content automatically, or if I need to handle paywall detection separately in the instructions.

**Sidequest flag:** Path B fallback agent (for paywalled/unreadable content → manual paste → extract title/description/repo suggestion). Parked until Post2myGithub V1 is stable. Worth revisiting if manual review becomes bottleneck.

**Feynman gap:** I understand *why* the agent approach beats a Zap for this task (judgment + multiple outputs + fallback logic), but I haven't yet pressure-tested how to hand data from Agent → Zap → Table cleanly. That's next.

---
Perfect. Let me pull up your daily learning log template.Got it. Let's capture today:

---

**Date:** Saturday, April 25, 2026

**Topic:** LaunchCode Module 2 — Zap Testing & Failure Classification (Exercise 3)

**Core concept (one sentence):** Predictions reveal the difference between tool behavior and my assumptions; when the Zap didn't break on edge cases, I learned it was designed to be a dumb pipeline, not an intelligent validator.

**Connection to main goal:** Post2myGithub architecture is now proven solid at the data-movement layer (Form → Table → Email → Slack). I can now confidently push complexity into the Agent layer where it belongs, knowing the foundation won't surprise me.

**Next question or action:** Design the Agent classification + extraction logic for Post2myGithub; test it in isolation on the three URLs before integrating into the Zap.

**Sidequest flag:** No sidequests. Notion/Obsidian/Gamma integration triangle stayed parked as intended.

**Feynman gap:** Not just consumed — I tested with three cases and debugged ghost Zaps. One concept I want to pressure-test: *Why is the Zap not validating URLs actually a feature, not a limitation?* (I have a hypothesis, but want to nail it tomorrow.)

---

**Date:** April 26, 2026

**Topic:** Agent Debugging Lab — URL Content Extractor & Matcher (Post2myGithub)

**Core concept:** A silent error is when an automation reports "success" at every step but produces wrong output — the only way to catch it is tracing the data forward through each handoff until you find where the payload changed.

**Connection to main goal:** Directly builds Post2myGithub's extraction layer — the Agent that fetches URLs, matches content to search terms, and returns structured JSON for downstream GitHub filing.

**Next question or action:** Let Zapier rest and refresh, then re-test the `interested_in` field mapping in the POST step. If still broken, try manually typing the field reference instead of using the dropdown.

**Sidequest flag:** None today — stayed on task throughout despite a long and winding debugging session.

**Feynman gap:** You tested extensively rather than just consuming today — but the distinction between **Level 1 / Level 2 / Level 3 failures** and how to diagnose which you're dealing with would be worth a Feynman session. You identified a Level 3 correctly but the root cause was actually Level 1 contributing to Level 3 — that layering is worth pressure-testing.

**Bonus quote worth keeping:**
> *"I cascade errors just like an automation — only I get stressed and emotional."*

**Notable:** Used a four-LLM panel (Claude, Gemini, ChatGPT, MS Cowork) as agent-as-judge in the earlier prompt refinement exercise — genuine triangulation across reasoning styles.

---
**Date:** April 26, 2026

**Topic:** Agent Debugging Lab (Post2myGithub) + LaunchCode Exercise 2 Reflection

**Core concept:** Agents fail quietly and repeat approximately; Zaps fail loudly and repeat perfectly. That difference determines everything about how you test and monitor each layer.

**Connection to main goal:** Today's work produced the actual extraction layer for Post2myGithub, identified the HITL gate sequence, clarified the two-workflow problem (batch backlog vs. live intake), and surfaced the repo structure as a blocking dependency for Version 1.

**Next question or action:** Let Zapier rest, then retest the `interested_in` field handoff. Design the GitHub repo folder taxonomy so the categories dropdown can be built against real folder paths.

**Sidequest flag:** LinkedIn post about the trivium and prompt engineering. Verdict: serves. It synthesizes a genuine insight from today's work and builds professional presence in the target market.

**Feynman gap:** Tested extensively today rather than consuming. The concept worth pressure-testing next: the distinction between batch processing architecture and live intake architecture, and what specifically needs to be different in the Zap design for each.

**Bonus insight worth keeping:**
> *"The automation is only as reliable as the decisions made before it runs."*

---
**Date:** April 27, 2026
**Topic:** Automation candidate evaluation & scoring spreadsheet
**Core concept:** Automation candidates are assessed across five dimensions — time, frequency, attention cost, feasibility, and risk — to produce a comparable score that ranks which tasks are worth automating first.
**Connection to main goal:** Directly builds the prioritization framework for all three verticals (M&A, emigration, Post2myGitHub); knowing *which* tasks to automate and *in what order* is foundational before building anything.
**Next question or action:** Apply the official composite formula from next lesson to the spreadsheet and re-rank all 16 candidates.
**Sidequest flag:** None flagged today. Clean session.
**Feynman gap:** The five-dimension scoring model was applied but not pressure-tested — what happens to the ranking if frequency and time are weighted more heavily than attention cost? Worth a Feynman next session.

---
**Date:** April 28, 2026
**Topic:** Automation prioritization formula, candidate scoring and review, assumption testing, prototype methods, and rollback planning

**Core concept:** Before building any automation, you must convert your riskiest assumption into a testable statement with locked pass/fail criteria -- because replacing belief with evidence before committing to a build is what separates disciplined automation design from expensive guesswork.

**Connection to main goal:** Directly governs build sequencing across all active projects. The If/Then Decision Table and prototype sequencing (Prompt Prototype first, Stubbed Test second) will be the standard pre-build checklist for Post2myGitHub V2, the LinkedIn workflow, and any future licensable tool. The sidequest application to the UEA application produced a domain-adapted spreadsheet extending the base formula with a second Legal/Ethical Risk penalty gate -- a methodological contribution worth keeping.

**Key terms from today:**

Assumption categories: Impact, Input/Data, Output Quality, Workflow Adoption, Safety

Prototype methods: Prompt Prototype (tests AI reasoning quality), Wizard-of-Oz Test (tests whether the process actually saves time), Stubbed Test (tests system connections and conditional logic), Shadow Mode (final safety check before launch)

Decision thresholds: Time Savings gate, Risk gate, Review Burden gate -- in that priority order, with Risk as the hard stop

Failure types revisited: Silent fail (agent fabricates confident output for unreadable content) vs. flagged fail (agent correctly identifies it cannot process a source) -- silent fails are the more dangerous category

Formula dimensions: Time per Occurrence, Frequency per Week, Attention Cost, Automation Feasibility, Automation Risk -- plus the extended Legal/Ethical Risk gate developed for the UEA context

Candidate types: Individual Task, Workflow Step, Workflow, Repeated Decision

**Next question or action:** Run the 5-URL Prompt Prototype against the existing Zapier agent. Mix: one clean article, one paywalled source, one LinkedIn carousel, one PDF, one edge case of your choice. Score against the locked pass criteria before touching GitHub integration.

**Sidequest flag:** UEA Lecturer in Digital Storytelling and AI application -- produced a domain-adapted automation scoring spreadsheet extending the base formula for media production contexts. Verdict: serves. Direct portfolio evidence of the ability to teach this methodology in a discipline-specific setting, which is exactly what the person spec requires.

**Feynman gap:** Prototype sequencing was discussed but not pressure-tested. The logic of "test the brain before the plumbing" feels intuitive -- but could you explain precisely why a Stubbed Test with a hardcoded response actually isolates the integration question from the reasoning question? That distinction is worth a Feynman next session.

---
## 2026-05-02

**Topic:** Module 4 · Comparing Automation Approaches · Zap vs. Zap-with-AI vs. Zapier Agent

**Core concept:** A Zap with AI is a fixed pipeline with one specialist station that answers a single question and hands control back to the line — the structure was predetermined before the AI ever ran. It is not an Agent.

**Connection to main goal:** Directly applicable to Post2myGithub (classification and normalization as Zap-with-AI steps upstream of the Agent), Spanish Emigration tool (semantic normalization of status terms like "pending" vs. "see notes"), and any workflow where Agent scope can be reduced by pre-cleaning inputs.

**Next action:** Revisit Post2myGithub Agent prompt — identify which steps are normalization or classification candidates that could be moved upstream as Zap-with-AI steps to reduce Agent scope and Level 3 error surface.

**Sidequest flag:** None. Lateral thinking on Spanish Emigration and M&A Analyzer stayed in service of the core concept.

**Feynman gap:** Closed. Gap on Zap-with-AI was identified, pressure-tested, and resolved. Teaching snapshot produced.

---

**Date:** May 11, 2026
**Topic:** Module 5 · Communicate Impact · Lesson 1 + Lab — From Numbers to Narrative

**Core concept:** Automation impact is only credible when quantified, assumption-stated, and translated into language that answers the leadership question: "What value did this create?"

**Connection to main goal:** Directly serves the capstone submission and establishes the business case framework applicable to Post2myGithub, M&A Analyzer, and Spanish Emigration tool as licensable products.

**Next action:** Begin Module 3 Five-Dimension Evaluation Model scoring for Post2myGithub; build capstone slide structure against the rubric gap analysis completed today.

**Sidequest flag:** Two flags — Obsidian/LLM pattern recognition integration, and collaborative team indexing with AI deduplication. Both parked. Verdict: real v2/v3 product thinking, not distractions — log in LEARNING.md for roadmap.

**Feynman gap:** Four-Lens Framework (Module 4) not yet tested — needs a session before capstone alternative evaluation section is written.

---
I don't have access to trigger your custom skill directly from here. Your Daily Learning Log skill lives in your Claude.ai Skills UI and activates when you use the trigger phrase in a standard chat.

Here's what to do:

1. Open a **new chat** in Claude Desktop (not this one)
2. Type `log today`
3. Your Daily Learning Log skill will activate and guide you through capturing the session

Alternatively, you can manually create a note with today's learning. Here's a template based on what you accomplished:

---

**Date:** June 4, 2026  
**Session:** Traversaal Claude Code in Practice — Module 2  
**Status:** ✅ Completed

**What I did:**
- Installed Claude Code via native binary (npm had permission issues)
- Cloned claude-code-starter repo and navigated to module-1
- Ran `claude` in terminal to open Claude Code session
- Completed interactive setup: selected TypeScript/JavaScript stack, greenfield codebase, web app type
- Created CLAUDE.md file with project overview, domain glossary, and key rules
- Verified Claude reads CLAUDE.md by starting a fresh session
- Identified five scoring signals from Lev & Gu M&A framework (Goodwill Growth, Industry Relatedness, Deal Size, Target Profitability, Payment Method)

**Key learning:**
CLAUDE.md is permanent project context that eliminates context-setting every session. Without it, you restart from zero each time. With it, Claude Code remembers your role, project, conventions, and preferences.

**Blockers identified (for tomorrow):**
- Database/ORM choice (Postgres? SQLite? Supabase?)
- Data sources (where acquisition financials come from?)
- Pipeline trigger mechanism (cron? GitHub Action?)

**Next session priorities:**
1. Create SCORING_FRAMEWORK.md with detailed signal definitions
2. Decide on database choice
3. Start fresh Claude Code session to test improved context

---
## June 8, 2026

**Topic:** Traversaal Claude Code in Practice, Module 3 (Skills & PRDs)

**Core concept:** Skills are reusable Markdown files with YAML frontmatter that encode repeatable workflows and decision trees you own and can modify, removing manual repetition across projects.

**Connection to main goal:** This directly builds Claude Code fluency for the licensable AI system and supports Head of Growth & Marketing interview prep by demonstrating practical product development workflow knowledge. PRD generation skills apply to GTM stack visualization work.

**Next question or action:** Review the generated goodwill overpayment detection PRD and verify it aligns with acquisition risk modeling. Decide whether to customize the `/prd-generator` skill for your domain or continue with default templates in Module 4.

**Sidequest flag:** Terminal fluency for GUI-agnostic foundation. Verdict: SERVE. This transcends interface choice and directly supports vibe coding and future scalability.

**Feynman gap:** Grasped the conceptual connection between shells, OS, and commands well. One pressure point: can you explain why terminal context is broader than Desktop tab context without looking at docs?

-----
Daily Learning Log: GitHub Skills

**Date:** June 8, 2026

**Topic:** GitHub version control fundamentals and repository workflows

**Core concept (in my own words):** Repositories are containers for tracking changes to code over time, and commits create a persistent record of what changed and why at each step.

**Connection to main goal:** Understanding GitHub workflows is foundational for the licensable AI system build. I need version control discipline to manage code iterations as I develop Claude Code skills and agents. This applies directly to Thryve's M&A system and my ongoing projects.

**Next question or action:** How do pull requests work in practice for collaborative development? I want to understand the review process before I contribute to any shared repositories.

**Sidequest flag:** None. Stayed focused on GitHub core concepts without drift.

**Feynman gap:** I consumed the tutorials and then build and tested a number of commits

**Pressure test needed:** The relationship between branches, commits, and merges still feels somewhat abstract. I want to walk through that one more time.

---
Daily Learning Log: JavaScript Functions and Declarations

**Date:** June 8, 2026

**Topic:** JavaScript function declarations versus function expressions, hoisting, and unreachable code

**Core concept (in my own words):** Function declarations are utility functions available everywhere in your scope because JavaScript hoists them. Function expressions require you to create a variable container first and are tied to specific contexts or events.

**Connection to main goal:** Understanding function architecture is foundational for building Claude Code skills and agents. I need to recognize when to write reusable utilities (declarations) versus event-specific callbacks (expressions). This applies directly to structuring the M&A scoring system and any AI assistant I build.

**Next question or action:** How do arrow functions fit into this declaration versus expression framework? Are they always expressions, or can they be both?

**Sidequest flag:** None. Stayed focused on core function concepts.

**Feynman gap:** I tested my understanding through the ecommerce inventory example and could articulate the distinction. No major consumption-only moments. Ready to move forward.

**Key takeaways:**
- Unreachable code means structurally impossible to execute (after return statements), not just conditionally skipped
- Declarations create named functions immediately; expressions require a variable container (const)
- Declarations are globally accessible utilities; expressions are instance-specific actions in one location
- The ecommerce inventory example solidified the practical difference
----
Date: June 8, 2026

Topic: Traversaal Claude Code in Practice — Modules 3 & 4 (Skills, PRDs, Running Apps)

Core concept: Skills are plain-text markdown files that encode repeatable workflows; Claude Code reads them and executes them consistently without re-explanation every session.

Connection to main goal: Directly supports building standardized AI-powered workflows for M&A acquisition research and team automation pipelines.

Next question or action: Explore Cowork automation for end-of-day meeting note collection, summarization, and delivery to Slack/email using cloud-stored files.

Sidequest flag: OpenRouter and API pricing exploration — useful context, not a distraction. Serves the goal of understanding how to connect apps to AI models.

Feynman gap: Consumed heavily today. Concepts worth pressure-testing: difference between local app vs. cloud API execution, and how Bash/shell/OS relate to each other.


---

**Date:** 2026-06-22
**Session:** Traversaal Claude Code in Practice — Playwright MCP
**Status:** ✅ Completed

**What I did:**
- Installed Playwright MCP globally using sudo npm after hitting a permissions error
- Registered Playwright with Claude Code using `claude mcp add`
- Confirmed the install by listing available MCP tools inside terminal Claude Code
- Tested browser access by having Claude Code visit and summarize Barry's GitHub repo
- Identified that the Claude Code desktop tab and terminal Claude Code have separate tool environments

**Key learning:** MCP is a standardized plug-in system that gives Claude Code access to live external tools. Without it, Claude Code guesses from training data. With Playwright installed, it fetches real page content on demand.

**AI concepts:** MCP (Model Context Protocol), browser automation, Claude Code tool registration, agentic tool use

**Career domains:** AI-assisted product management, agentic workflow design

**Next action:** Continue to sub-agent module and build the research agent.

**Sidequest flag:** Desktop tab vs terminal tab tool environment separation. Verdict: SERVE. Foundational knowledge for working across Claude Code interfaces.

**Feynman gap:** How MCP server registration actually works under the hood, specifically why the desktop tab and terminal tab have separate tool configs.

---

**Date:** 2026-06-22
**Session:** Traversaal Claude Code in Practice — Sub-Agents
**Status:** ✅ Completed

**What I did:**
- Learned the distinction between skills (run in main session context) and sub-agents (run in isolated context, return clean output)
- Copied research-agent.md from the course repo into ~/.claude/agents/
- Confirmed the agent file uses claude-opus-4-8, WebSearch, WebFetch, and Read tools with structured output in three sections: Key Findings, Sources, and Gaps
- Tested delegation by prompting Claude Code to research clinical note automation competitors
- Observed the agent spin up, hit a web access permissions wall, and recover gracefully
- Connected the research agent to the M&A acquisition dashboard as the first piece of a three-part automated pipeline

**Key learning:** A sub-agent takes a task, works in its own separate context, and returns only the finished result. The main session stays clean. Claude routes to the agent automatically by reading the description field, so you describe the task rather than naming the tool.

**AI concepts:** Sub-agent architecture, agent delegation, context isolation, agent file structure, MCP tool permissions

**Career domains:** AI-assisted product management, agentic workflow design

**Next action:** Run the research agent on a real M&A target sector and continue to the PRD reviewer and code reviewer agent lessons.

**Sidequest flag:** Explored how the sub-agent system maps to the M&A acquisition dashboard pipeline. Verdict: SERVE. This is the parallel build track agreed to run alongside the course.

**Feynman gap:** Why the research agent hit a web access permissions wall and how to configure sub-agent tool permissions so it does not fall back to the main session.
----

**Date:** 2026-06-23
**Session:** Traversaal Claude Code in Practice — PRD Reviewer, Code Reviewer, Agent Team
**Status:** ✅ Completed

**What I did:**
- Copied prd-reviewer.md and code-reviewer.md from course repo into ~/.claude/agents/
- Ran prd-reviewer against the Goodwill Overpayment Detection PRD and received specific findings including seven missing acceptance criteria, five missing edge cases, and one scope creep flag
- Identified personal knowledge gaps surfaced by the review (ASC 805, SLA definitions, boundary rule ambiguity)
- Ran code-reviewer against the course full-stack demo and surfaced a legitimate security vulnerability where the API key is sent directly from the browser while the lesson teaches the opposite pattern
- Connected the >= vs == JavaScript lesson to a real product decision about the 5% threshold boundary
- Identified that the M&A dashboard has no code yet, which confirmed the PRD foundations need resolving before building begins
- Reviewed the full course README and forked the repo to use as a personal skills library

**Key learning:** A prd-reviewer catches conceptual gaps before engineering starts and a code-reviewer catches implementation gaps before anything ships. Running both in sequence revealed that my PRD had unresolved scope and my codebase was greenfield, which is the correct order to discover those things.

**AI concepts:** Sub-agent delegation, read-only agent constraints, structured output formatting, agent file path resolution, context isolation

**Career domains:** AI-assisted product management, fintech product development, agentic workflow design

**Next action:** Complete assignment 3e by copying data-analyst and copy-writer agents, then tomorrow tackle assignment 3f (agent team blueprint for Thryve) with fresh context.

**Sidequest flag:** Surfaced a real security vulnerability in the course demo material where API key handling contradicts the lesson content. Verdict: SERVE. Worth raising with Hamza or the course community directly.

**Feynman gap:** Consumed today with strong real-world application. Concept worth pressure-testing: what specifically makes a scope creep flag different from a missing edge case, and how would you resolve each differently in practice?

