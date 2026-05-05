# Sumble Sales Brain — AE Knowledge & Playbook

This is Eric Fitz's personal AI context + sales playbook for selling at Sumble. Eric is an Account Executive at Sumble (eric@sumble.com), having recently moved from Zendesk. The goal of this file is to give Claude the context it needs to help with account research, territory planning, demo + value mapping, competitive positioning, and Command-of-the-Message-style discovery.

This is a knowledge file, not an automation system. There is no daily send loop, no Mail.app integration, no enrichment cron. Eric runs outbound through Salesforce + Gmail + standard sequences.

---

## Who Eric Is

- **Role:** Account Executive at Sumble (full-cycle / closing)
- **Email:** eric@sumble.com
- **CRM:** Salesforce
- **Email/Calendar:** Gmail / Google Workspace
- **Methodology:** Command of the Message / Force Management (value-based, pain-led, "before / after / proof / metric")
- **Prior role:** AE at Zendesk (selling CX/CS software). Useful priors: discovery rhythm, multi-threading at enterprise, MEDDPICC instincts, AppleScript/Mail.app outbound experience.
- **Focus areas at Sumble:**
  1. **Account research + territory planning** — interpreting Sumble signals to prioritize the right accounts and the right contacts within them.
  2. **Demo + value mapping** — translating Sumble's knowledge graph capabilities into specific buyer pains by persona (RevOps, CRO, CMO, ABM lead).

---

## What Sumble Is

Sumble is an AI-powered sales intelligence platform built around a **knowledge graph + LLM infrastructure** that turns unstructured public signals into coherent narratives about target accounts.

- **Founders:** Anthony Goldbloom and Ben Hamner (founders of Kaggle).
- **Funded:** $38.5M total — $8.5M seed (Coatue) + $30M Series A (Canaan Partners). Emerged from stealth October 2025.
- **Launched:** April 2024.
- **Coverage:** ~2.6M companies globally.
- **Reference customers:** Snowflake, Figma, Wiz, Vercel, Elastic (19+ enterprise customers as of late 2025).
- **Form factor:** Web app + API.

### What Sumble actually does

Sumble crawls social media, job boards, company sites, and regulatory filings, then connects the signals through a knowledge graph designed for LLM consumption. The output is a live view of a target account that includes:

- **Technographics by department** — not just "company X uses Salesforce," but which team uses what.
- **Org charts and team structure** — who reports to whom, who owns which initiative.
- **Key projects and initiatives** — what's actually being built or migrated.
- **Hiring trends** — surge hiring on a function = budget + buying intent.
- **Change events** — leadership shifts, reorgs, budget cycle moves, M&A.
- **Recommended contacts** — who to reach for a given motion.

### Core value prop (the thing that wins deals)

> "Pipeline and details that ZoomInfo and others miss."

ZoomInfo, Apollo, and Clay tell you **who** exists at a company. Sumble tells you **what's actually happening inside** — projects, team-by-team tooling, who owns what — so reps know not just who to email but **why now and what to say**. The wedge is *contextual depth at the team level*, not contact volume.

---

## Sumble's ICP (who we sell to)

Primary buyers, in priority order:

1. **Sales leaders** — CRO, VP Sales, VP RevOps, RevOps Director. They own pipeline efficiency and rep productivity. Pain: reps wasting time on bad accounts; ZoomInfo data is stale or shallow.
2. **Marketing leaders** — CMO, VP Demand Gen, ABM lead. They own targeting and segmentation. Pain: ABM lists built from firmographics + revenue alone don't reflect what's actually happening inside accounts.
3. **Enterprise revenue teams** — mid-market and enterprise sales orgs with established stacks (already have ZoomInfo / Apollo / Clay / Salesforce). They want a *layer of context* on top, not a rip-and-replace of their existing data tools.

### Where Sumble lands easiest

- Companies whose sales motion depends on **technographic signal** (devtools, infra, security, MarTech, MLOps, AI tooling — anyone whose ICP is defined by "uses X").
- Teams already running **multi-source enrichment** (Clay users especially) — Sumble is a unique signal, not a substitute.
- Enterprise GTM orgs with dedicated **RevOps + research** functions to operationalize the data.

### Where Sumble is harder

- Pure SMB outbound shops optimizing for cost-per-contact (Apollo wins on price).
- Teams that don't have someone to interpret signals — Sumble rewards thoughtful use, doesn't replace a rep's judgment.

---

## Competitive Landscape

The right framing: Sumble is **not** trying to be the contact database. It's the context layer **on top of** whatever DB the buyer already has. Lead with that — don't get sucked into a contact-count comparison with ZoomInfo or Apollo.

| Competitor | What they do | Where they win | Where Sumble wins |
|---|---|---|---|
| **ZoomInfo** | Deep B2B contact + intent DB, 100M+ profiles, ~$15K–40K/yr. Email accuracy 90–93%. | Contact volume, direct dials, scale. Enterprise default. | Department-level technographics, project-level signal, org context. ZoomInfo's intent is keyword-based; Sumble's is structured + behavioral. |
| **Apollo.io** | 275M contacts / 73M companies, generous free tier, built-in sequences + dialer. Cost-per-contact ~$0.002. | Cheap outbound execution. SMB / fast-moving teams. | Sumble doesn't compete on price-per-record. Wins when "we already have Apollo, why would we pay more?" → answer: *Apollo gives you contacts; Sumble tells you why those contacts matter this quarter.* |
| **Clay** | Data orchestration / waterfall enrichment across 150+ sources via spreadsheet UI. | Custom enrichment workflows, RevOps power-user love. | Sumble is **complementary**, not competitive — pitch it *as a Clay column*. Teams running Clay should be a fast yes when shown unique Sumble signal. |
| **HG Insights / Enlyft** | Tech stack / install-base specialists. | Mature technographic data, large enterprise contracts. | Department-level granularity (HG/Enlyft are company-level), plus org/project/hiring signal HG doesn't model. Plus modern UX. |
| **Common Room** | Community / PLG / dev advocate signals. | PLG companies tracking developer engagement. | Different problem — Common Room watches your community; Sumble watches the *outside world*. They co-exist; not a real competitive overlap, but RevOps teams sometimes lump them together. |

### Talk tracks by competitor

- **vs ZoomInfo:** "ZoomInfo tells you *who works there*. Sumble tells you *what they're working on*. Most enterprise teams keep both."
- **vs Apollo:** "Apollo is great execution rails. Sumble is the targeting brain that decides which accounts deserve those rails."
- **vs Clay:** "Clay is the kitchen. Sumble is one of the best ingredients. Teams running Clay add Sumble as a column."
- **vs HG Insights:** "HG sees the building. Sumble sees the rooms inside it." (Department-level granularity.)

---

## Sumble's Plays / Value Narratives

The six plays — they're not mutually exclusive, most accounts fit 2+. Plays #1 and #2 are the **headline pair** for almost every customer conversation: MQL enrichment is the moment-of-truth motion, CRM enrichment is the always-on layer that makes it scalable.

### 1. ⭐ MQL enrichment — turn marketing-sourced contacts into sales-ready opps (HEADLINE PLAY)
The single highest-leverage motion for Sumble. Marketing already generates the contact (web form, gated content, event scan, ad click). Sumble enriches that contact with the **context** that decides whether it converts: *what's actually happening at their company, what initiatives they own, what signals say "this is real budget, not tire-kicking."*

- **Buyer:** Sales leadership (CRO, VP Sales) + Marketing leadership (CMO, VP Demand Gen). The pitch lands cleanest when both are in the room because it's the one play that makes both sides look better.
- **The problem we solve:** MQLs hit Salesforce as a name + email + company. Sales reps work them blind, or burn cycles on hand-research, or — most common — let 60–80% rot because they "don't know enough yet." Marketing gets blamed for "bad leads"; sales gets blamed for "not working leads." Both are right. Both lose.
- **Sumble unlock:** every MQL gets auto-enriched at the moment it lands with:
  - **Active initiatives at the account** (what they're hiring for, projects in flight, recent leadership moves) → *why now.*
  - **Pipeline drivers specific to that company** (what their stack reveals about budget cycle, team size, recent investment) → *what's the deal worth.*
  - **Differentiating angles** (the one signal that separates this account from the 50 others that look identical on firmographics) → *what to say in the first reply.*
  - **The right second contact** to multi-thread to, surfaced from the org graph, before the rep has to ask "who else should I be talking to?"
- **Outcome reps feel:** every MQL arrives with a 30-second briefing instead of a Google search. SDRs and AEs reply faster, more specifically, and to the right person.
- **Outcome marketing feels:** MQL → SQL conversion goes up; the "lead quality" debate ends because every lead carries its own context.
- **How to demo it:** take a real recent MQL from the prospect's CRM (or a peer's logo), show the unenriched record, then pull Sumble open and walk through the four bullets above live. The *contrast* is the demo.
- **Discovery questions:**
  - "Walk me through what happens when an MQL hits a rep's queue — what do they actually know about the account?"
  - "What's your MQL → SQL conversion rate? What does marketing think it should be?"
  - "How much time does a rep spend researching a single MQL before reaching out — and how much of that is Google + LinkedIn stitched together?"
  - "When a deal closes from an inbound lead, can you point to *what the rep said* in the first reply that made it work?"
- **Metric to anchor on:** MQL → SQL conversion rate (and time-to-first-meaningful-touch). If they don't measure either, that *is* the conversation.

### 2. ⭐ CRM enrichment — make sure AEs and reps target the right accounts with the right messaging (HEADLINE PLAY)
The always-on operational counterpart to Play #1. Where MQL enrichment fires at the *moment* a marketing-sourced lead lands, CRM enrichment is the **persistent layer** that lives across every account in Salesforce, so reps are working the right accounts with the right buying group and the right message — every day, not just at MQL touchpoints.

- **Buyer:** CRO + VP Sales (the rep productivity story) + RevOps (the data quality + integration story). Most champion: RevOps. Most decision power: CRO.
- **The problem we solve:** Salesforce account records are graveyards. Stale technographics, outdated org charts, no project signal, no play match, no messaging guidance. AEs do their best research on Tier-1 accounts, then run the rest of the territory blind. The 33%-attainment SMB / Mid-Market segments aren't a talent problem — they're a **signal-per-account problem.** Strategic AEs work ~4 deals a year on accounts they know cold (54% attainment); SMB AEs work 22-36 deals a year on accounts they barely know (33% attainment). The difference is signal density.
- **Sumble unlock:** every account in the territory gets enriched on a recurring basis with:
  - **Right account:** prioritized by current signal pattern (initiatives + hiring + tooling + change events), refreshed continuously — not a one-time score.
  - **Right buying group:** the 3–5 people inside the account who actually own the decision, surfaced from the org graph. Most aren't the contact already in Salesforce.
  - **Right play:** the specific play whose signal pattern fits this account *right now* (e.g., "Conversational AI hiring surge + IPO timing → AI Transformation play with [peer customer] proof").
  - **Right message:** the specific 2–3 signals an AE should lead with, plus the matched peer customer / proof point. Eliminates the "what do I say?" stall.
- **Where it lives:** Salesforce account fields + Outreach sequence personalization tokens. Reps don't open another tool — Sumble enrichment shows up where they already work.
- **Outcome reps feel:** every account in the territory is "warmed up" — the AE no longer chooses between 4 well-researched accounts and 30 dark ones. The reply rate gap between strategic and SMB outreach narrows because the *signal density* gap narrows.
- **Outcome leadership feels:** SMB / Mid-Market attainment moves toward strategic-AE numbers without changing headcount. Same reps, same quota, more pipeline.
- **Discovery questions:**
  - "Walk me through what's on a typical Salesforce account record when an AE opens it cold — what do they actually know?"
  - "What's the attainment gap between your strategic and SMB segments? What do you attribute it to?"
  - "When a rep needs to multi-thread, how do they figure out the buying group today — and how often is the contact already in Salesforce wrong or stale?"
  - "How specific is the average outbound email a rep sends? When did you last spot-check?"
  - "If every account in the territory had the same depth of context as your top 20, what would change?"
- **Metrics to anchor on:** segment-level attainment (SMB / Mid-Market vs. Strategic), pipeline-per-rep, MQL→SQL conversion (Play #1 lives downstream of CRM enrichment quality), reply rate on cold outbound.

### 3. Tech-stack-driven prospecting (displacement / attach)
Find buyers using competitor X (or complement Y) and reach the team using it.
- **Buyer:** AE-led RevOps; sales reps for displacement.
- **Sumble unlock:** *who* on the team uses the tool, not just whether the company uses it.
- **Common pattern:** "Show me every account using [Competitor] in their CS team but not in their Sales team — those are split-stack consolidation plays."

### 4. Hiring intent / job-posting signals
Surge hiring on a function = budget allocated = buying window opening.
- **Buyer:** SDR/AE, demand gen.
- **Sumble unlock:** structured hiring trends (Sumble normalizes job postings into roles + technologies + team growth deltas), not just "they're hiring."
- **Common pattern:** "Companies that hired 5+ Data Engineers in the last 90 days" → outbound trigger for data tooling.

### 5. Account prioritization for AEs
Score the territory so reps work the right accounts first. (Subset of CRM enrichment, but worth calling out as a standalone for buyers focused on territory design.)
- **Buyer:** CRO / VP Sales / RevOps.
- **Sumble unlock:** signals → score → ranked territory list. Replace gut-feel + ZoomInfo employee count with multi-signal model.
- **Common pattern:** Build a custom scoring rubric per persona/play; deliver as Salesforce-ranked list.

### 6. ABM list-building for marketing
Build target lists from firmographic + tech + signal filters.
- **Buyer:** CMO / VP Demand Gen / ABM lead.
- **Sumble unlock:** filters that other ABM tools don't have (e.g., "uses Snowflake AND hiring ML eng AND has VP-level Data role").
- **Common pattern:** Marketing builds the list in Sumble → exports to ad platforms / CRM / sequencer.

### The unifying narrative

> *"ZoomInfo and Apollo gave you contacts. Sumble gives you the **context** that decides which contacts matter this quarter — and what to say to them."*

Lead with that. Then drop into whichever play fits the buyer in front of you.

---

## Reference Pitch: The Zendesk Strategic Brief (worked example)

This is the canonical pitch arc for Plays #1 + #2 combined. It's a real internal-discussion deck (`Sumble_Zendesk_MQL_3.html`) built for Zendesk and it's the template Eric should adapt for any prospect with a similar shape: high inbound MQL volume, large AE org, AI/AR pressure from leadership, segmented attainment gap.

### The arc (18 slides, summarized)

1. **The strategic context.** Anchor in their CEO's number. For Zendesk: "$500M AI ARR target. $200M today. The path runs through a $700M pipeline gap." (Tom Eggemeier, AWS re:Invent 2025.) Net new ARR needed × 4× pipeline coverage = $1.2B in net-new pipeline. ~1,000 AEs × $500K each = $500M sourced. **Gap: $700M.**
2. **The problem in one number.** Today's MQL → SQL conversion: ~1%. Industry-typical for B2B inbound. Marketing hits volume targets, SDRs work the queue, **99% never becomes pipeline.**
3. **The reframe.** *"You don't have a lead problem. You have a context problem."* Adding more leads, more sequences, more nurture won't fix it. The bottleneck is the moment an SDR opens a fresh MQL and sees a name, a title, an asset — and almost nothing else.
4. **A real lead.** Pick one specific, non-obvious example. In the Zendesk deck: a senior banker at Morgan Stanley visits the Zendesk help center. No form fill. One page view. Identified by visitor-tracking.
5. **Before — the SDR's view.** Show the actual MQL record in their tool. A name, a title, a firm, a help-center page view. A "Research with AI" button — *the system itself admitting it doesn't have enough context.*
6. **The SDR's three options, none of which convert.**
   - Spend 20 minutes researching → triages one lead, ignores the queue.
   - Send a generic nudge → 2% reply rate, opportunity dies politely.
   - Skip it entirely → opportunity dies quietly.
7. **Sumble detects the trigger.** *Why* was the banker on the help center? In the Zendesk deck: he was researching for **Acko's $2–2.5B IPO mandate.** This is the inference no other tool makes.
8. **The transitive opportunity.** *"The MQL was Oscar. The opportunity is Acko."* Reverse-IP tools surface visitors. Intent platforms surface topics. Neither traces a senior banker's visit back to the deal he was mandated on. **Sumble didn't enrich the lead — Sumble re-routed the deal.**
9. **The signal pattern at the real account.** Concrete bullets:
   - 9 Conversational AI + 7 LLM engineer reqs tied to customer-facing automation
   - 30+ active claims & customer service ops roles across five Indian metros
   - 5% workforce reduction (April 2026) publicly tied to "AI integration"
   - DRHP filing window opens H2 2026 — operational tooling decisions get locked in *now*
10. **The buying group, surfaced.** Four people. Three at Acko. *None filled out a form.* Multi-thread sequence ready, already enriched, already linkable.
11. **Match to their plays.** Show how the account's signal pattern triggers their internal plays — and name the specific peer customer whose case study lands. (For Zendesk: AI Transformation play, Lush + Siemens proofs.)
12. **Same hour, two emails.** This is the killer slide. Show the generic email a rep sends today next to the specific email Sumble enables.
    - Generic: *"Hi Oscar — I noticed you visited our help center recently. Just wanted to reach out and see if there's anything specific we can help you find..."*
    - Specific: *"Animesh — I'll be specific about why I'm reaching out, because I know the next 12 months at Acko are going to be ferocious. Morgan Stanley, ICICI, and Kotak just got named on the IPO. Your team is up to 9 Conversational AI reqs and 7 LLM engineer roles, and the April workforce restructuring around AI integration was a clear public signal. Meanwhile you're serving 75M users with ~1,300 employees across five metros — the math doesn't support staying on email-and-tickets through the DRHP window. This is the exact pattern we ran with Lush (369% ROI) and Siemens (23% productivity lift). Worth a 25-minute conversation? I'd loop in Rohan from your AI side."*
13. **The aggregate impact.** *"Same 1,000 MQLs. 7× more SQLs."* Reply rate jumps from 4% to 22-28%.
14. **The attainment gap visualized.** Strategic AEs hit 54% attainment ($110-130K avg deal, ~4 deals/yr). SMB AEs hit 33% ($16.5K avg deal, ~22-36 deals/yr). *"The difference isn't talent. It's signal-per-account."* (Source: RepVue, 1,343 verified Zendesk seller ratings.)
15. **The under-worked majority.** The biggest gains aren't from the leads reps already work — they're from the cold-bucket leads getting skipped today. Generic-to-specific lift on engaged leads: 4% → 18-22%. Cold-bucket lift: pure incremental SQL because the alternative is zero outreach.
16. **The category claim.** *"Other tools tell you who they are. Sumble tells you what they're being mandated to do."* Connecting deal mandate + hiring graph + buying group + the right play in time for the SDR's first email requires four structured datasets that exist together in exactly one place.
17. **The land.** *"Your funnel doesn't need more leads. It needs the layer between record and action."* Three-step rollout:
    1. Run 90 days on a cohort — one segment, one SDR pod, measure conversion lift.
    2. Pipe into Salesforce + Outreach — enrichment as account fields and play matches.
    3. Roll out to the full team — *same MQL volume, materially more pipeline. Marketing's number stays the same; sales' number changes.*

### How to adapt this arc to a new prospect

Replace four anchor variables and the rest follows:

| Variable | What to find | Where to find it |
|---|---|---|
| **The CEO number** | Their public ARR / pipeline / growth target | Earnings calls, investor day decks, conference keynotes |
| **The real MQL example** | One non-obvious help-center / docs / pricing-page visitor whose backstory is interesting | Their own analytics + Sumble enrichment of recent visitors / form fills |
| **The signal pattern** | 4 bullets that tell the buying story (hiring + restructuring + timing trigger + scale) | Sumble account profile |
| **The peer proof points** | 2 customer logos with hard numbers (ROI %, productivity lift, conversion) | Their own marketing site / case studies |

The structure (problem → reframe → real example → before/after → aggregate impact → category claim → land) doesn't change. The variables do.

### When to use this arc

- Account has high inbound volume + a stretched ARR target + a known attainment gap (segmented sales org).
- Champion is RevOps; economic buyer is CRO or CMO.
- They've already tried "more leads" and it didn't move the number.
- You can find a real, specific, non-obvious MQL example for them. Without that, the "before / after" emails fall flat.

### When NOT to use this arc

- Early-stage GTM with no segmentation in their AE org (no attainment gap to exploit).
- Pure SMB outbound shop — the math is different and the deck's strategic-vs-SMB framing doesn't land.
- Buyer hasn't confirmed they care about MQL→SQL conversion. Run discovery first; don't pitch this deck cold.

---

## Discovery — Command of the Message Cuts

Run discovery on **before-state pain → required capabilities → metrics → proof**. The four required capabilities Sumble delivers, with discovery questions for each:

### Capability 1 — Account-level context (not just contacts)
- "Walk me through how a rep decides which 50 of their 500 accounts to work this week."
- "When a rep opens an account in [ZoomInfo / Apollo], what do they actually learn about what's happening inside?"
- "How often do reps email someone who's already churned out of the role they're targeting?"

### Capability 2 — Department-level technographics
- "When you say a company 'uses Snowflake' — do you know whether it's the Data team, the Analytics team, or just one engineer's POC?"
- "How do you target plays where the buyer is a specific *team* inside a company, not the company as a whole?"

### Capability 3 — Hiring + project signals as buying triggers
- "What's the trigger today that tells your team an account is *in market*?"
- "When a company hires 10 ML engineers, how does your team find out, and how fast?"
- "How do you separate noise hiring from a real org build-out?"

### Capability 4 — Org + project context for messaging
- "When a rep writes a cold email, what do they personalize on?"
- "How often do reps have to ask 'who runs [function] there?' and just guess from LinkedIn?"

### Metrics to anchor on (Force Management style)
- Pipeline conversion: outbound → meeting → qualified opp → close.
- Rep productivity: hours/week on research, accounts worked per rep, meeting set rate.
- Marketing efficiency: CAC by ABM list source, MQL → SQL conversion.
- Data spend ROI: dollars on stack (ZI + Apollo + Clay + ours) vs. opps sourced.

---

## Demo Flow (default narrative, adjust for buyer)

The arc: **broken status quo → Sumble's unique signal → tactical use → org-level outcome.**

1. **Open with the buyer's account** — pull their company in Sumble live, show what we know. Wins attention every time.
2. **Find a peer/prospect they care about** — show department-level tech stack + one project signal + a hiring trend.
3. **Walk one play end-to-end** — pick the play that matches their pain (usually #1 or #3 above).
4. **API + integration moment** — show Salesforce attach / Clay column / direct list export. Map to *their* stack.
5. **ROI math** — the metric they cared about in discovery, mapped to Sumble's unlock.

Per-persona shading:
- **CRO:** lean on rep productivity + pipeline conversion. Avoid feature soup.
- **RevOps:** lean on data quality + integration. They'll demo it themselves; don't over-narrate.
- **CMO/ABM:** lean on list-building filters + ABM-platform handoff.
- **SDR/AE direct user:** lean on the personalization moment ("write the cold email with this open in front of you").

---

## Common Things Eric Will Ask Claude

| Eric says | What Claude should do |
|---|---|
| "Research [company] for me" | Pull what's publicly known: tech stack hints, recent news, leadership changes, hiring trends, likely Sumble plays for that account, suggested contacts to target. Cross-reference Sumble MCP if available. |
| "Help me prep for [persona] at [company]" | Persona pain → discovery questions → likely objections → competitive context (what they probably already use) → suggested Sumble play. |
| "Draft a cold email to [contact] at [company]" | Command-of-the-Message style: lead with their team's specific signal (not Sumble), one observation, one tight value statement, low-friction CTA. Plain text, under 100 words, subject under 40 chars. (Same email rules Eric uses from Zendesk days.) |
| "What's the play for [account]?" | Match account profile → ICP fit → which of the four plays applies → talk track. |
| "Build me an ABM list for [criteria]" | Translate criteria into Sumble-style filters (firmographic + tech + signal + person filters), suggest the export path, flag credit cost considerations. |
| "Compare us to [competitor]" | Use the competitive matrix above. Lead with the framing (context layer, not DB), don't get pulled into contact-count debates. |
| "What's a good discovery question for [pain]?" | Use the Command-of-the-Message capability buckets above; tie the question to a metric. |

---

## Email + Outreach Rules (carried over from Zendesk hub)

These are Eric's personal preferences, not Sumble policy. Worth keeping consistent because they work.

- **Plain text only.** No HTML, no bold, no italics, no link brackets.
- **Subject line under 40 characters** — won't truncate on mobile lock screens.
- **2–3 short paragraphs**, blank line between each.
- **No sentence over 20 words.** No bullets, no numbered lists, no em-dashes.
- **Under 100 words total.**
- **Lead with an observation about THEM** — a specific signal from Sumble, a hiring trend, a project, a leadership move. Not about Sumble.
- **One specific data point.** "You hired 12 data engineers in Q3" beats "I noticed you're growing."
- **Low-friction CTA:** "10 min, no pitch" style.
- **Vary openers across a batch.** Never repeat the same first line.
- **Sign off:**
  ```
  Eric
  Account Executive | Sumble
  ```
- **Sequencing:** all sends go through Salesforce + Gmail with native tooling. No autonomous send. No Mail.app loop. No 200/day cap (that was a Zendesk-era system).

---

## What NOT to Do

- **Do not** position Sumble as a ZoomInfo/Apollo replacement in early conversations. It's a context layer on top of whatever they already use. The replacement framing only comes up if the buyer brings it up first.
- **Do not** lead with features. Lead with their account's signal pulled live from Sumble.
- **Do not** quote contact-count comparisons against Apollo. We will lose that comparison; it's the wrong frame.
- **Do not** over-promise on coverage outside the ~2.6M companies Sumble crawls — confirm coverage before committing on enterprise targets in long-tail geographies.
- **Do not** carry over Zendesk-specific automation patterns (Mail.app sender, 200/day cap, prospects.json state machine). This brain is for knowledge + AI assist, not autonomous outreach.
- **Do not** assume any account is already a Sumble customer unless verified. Reference list as of late 2025: Snowflake, Figma, Wiz, Vercel, Elastic, plus ~14 others. Verify before pitching.

---

## MCP / Tooling Available to Claude

- **Sumble MCP** (`claude.ai Sumble`) — Eric's primary research tool. Available functions include `FindOrganizations`, `FindPeople`, `FindJobs`, `EnrichOrganization`, `EnrichPerson`, `SearchTechnologies`, `MatchOrganizations`, `RunSqlQuery`, `GetMyCompanyProfile`, `GetAccountInformation`, plus list management. Always call `GetMyCompanyProfile` once per session (free) to ground context. Watch credit balance — 402 = out of credits.
- **Gmail MCP** — read-only inbox scanning for replies/bounces. Drafting via Salesforce sequences, not Gmail directly.
- **Google Calendar MCP** — meeting scheduling and prep.

---

## Key References

- **Sumble docs:** https://docs.sumble.com/
- **Sumble homepage:** https://sumble.com/
- **TechCrunch stealth-exit announcement:** https://techcrunch.com/2025/10/22/sumble-emerges-from-stealth-with-38-5m-to-bring-ai-powered-context-to-sales-intelligence/
- **Command of the Message reference:** Force Management methodology — before/after/required-capabilities/metrics/proof.

---

*Last updated: 2026-05-05. Update this file when: ICP shifts, new plays emerge, competitive landscape changes, or Eric's territory/role changes.*
