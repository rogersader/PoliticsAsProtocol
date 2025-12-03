# Politics as Protocol – Canada Mapping

This document plugs **Canada’s real political system** into the 9-layer “politics as protocol” model.

Use it as:
- A **reference map** from real-world Canada → protocol layers  
- A starting point for deciding **what goes on-chain vs off-chain vs hybrid**

---

## 0. Canada – High-Level Snapshot

- **System type:** Constitutional monarchy + parliamentary democracy, modelled on the UK. :contentReference[oaicite:0]{index=0}  
- **Head of State:** King (represented in Canada by the Governor General). :contentReference[oaicite:1]{index=1}  
- **Head of Government:** Prime Minister. :contentReference[oaicite:2]{index=2}  
- **Three branches:** Legislative, Executive, Judicial (federal + provincial). :contentReference[oaicite:3]{index=3}  
- **Three levels:** Federal, Provincial/Territorial, Municipal. :contentReference[oaicite:4]{index=4}  
- **Core constitutional base:** Constitution Acts 1867–1982 + Canadian Charter of Rights and Freedoms. :contentReference[oaicite:5]{index=5}  

---

## 1️⃣ Governance Domain Model (Canada)

**Layer recap:** Define actors, rights, decision types, and resources before touching a chain.

### Actors (Canada)

**Federal level**

- **Parliament (Legislative branch)**  
  - **House of Commons** – 343 elected MPs representing electoral districts (“ridings”) as of the 2025 election. :contentReference[oaicite:6]{index=6}  
  - **Senate** – 105 appointed Senators representing regions. :contentReference[oaicite:7]{index=7}  

- **Executive branch**  
  - King (represented by the **Governor General**)  
  - **Prime Minister & Cabinet** (the Government) :contentReference[oaicite:8]{index=8}  

- **Judicial branch**  
  - **Supreme Court of Canada** (9 judges).  
  - Federal courts + provincial/territorial courts beneath it. :contentReference[oaicite:9]{index=9}  

**Sub-federal**

- **Provincial / Territorial governments**  
  - Legislatures (e.g., Ontario’s Legislative Assembly, Quebec’s National Assembly).  
- **Municipal governments**  
  - City councils, mayors – powers delegated by provinces. :contentReference[oaicite:10]{index=10}  

**Constituents**

- Citizens of Canada (core political rights). :contentReference[oaicite:11]{index=11}  
- Permanent residents and others (limited rights; still important for policy input).

---

### Rights & Roles (Canada)

- **Democratic rights (Charter ss. 3–5)**  
  - Right to vote and run for office in federal and provincial elections, max 5-year terms. :contentReference[oaicite:12]{index=12}  

- **Division of powers (Constitution Act, 1867, ss. 91–92)**  
  - **Federal powers**: trade and commerce, defence, criminal law, banking, immigration, etc. :contentReference[oaicite:13]{index=13}  
  - **Provincial powers**: property and civil rights, education, municipalities, natural resources, etc. :contentReference[oaicite:14]{index=14}  

- **Charter-protected rights & freedoms**  
  - Fundamental freedoms (expression, religion, association).  
  - Legal rights (life, liberty, security).  
  - Equality rights, mobility rights, etc. :contentReference[oaicite:15]{index=15}  

---

### Decision Types (Canada)

- **Constitutional amendments** – follow specific amending formulas in Constitution Act, 1982 (e.g. 7/50 rule). :contentReference[oaicite:16]{index=16}  
- **Federal legislation** – Acts of Parliament (House + Senate + Royal Assent). :contentReference[oaicite:17]{index=17}  
- **Provincial / territorial legislation** – Acts of provincial legislatures. :contentReference[oaicite:18]{index=18}  
- **Regulations & orders-in-council** – Made by cabinet under delegated authority. :contentReference[oaicite:19]{index=19}  
- **Budgets & appropriations** – Public spending authorizations at each level.  

---

### Resources (Canada)

- **Federal Consolidated Revenue Fund** – all public money at federal level.  
- **Provincial/municipal budgets** – health, education, local services, etc. :contentReference[oaicite:20]{index=20}  
- **Public assets & data** – lands, infrastructure, registries (health, tax, identity, land titles).

---

## 2️⃣ Identity & Access Layer (Canada)

**Layer recap:** Who you are and whether you can participate.

### Current Reality

- **No single nationwide digital e-ID yet** – identity is mostly physical docs (passports, driver’s licences, provincial health cards) plus some provincial digital ID pilots. :contentReference[oaicite:21]{index=21}  
- **Elections Canada** maintains the **National Register of Electors** (federal), based on tax, driver’s licence, and other data. :contentReference[oaicite:22]{index=22}  
- Provinces maintain their own voter lists for provincial/municipal elections.

### Protocol Hooks (Canada)

On-chain / hybrid candidates:

- **Digital Citizenship Credential**  
  - Bind a wallet or keypair to “federal citizen eligible to vote” via verifiable credentials, backed by Elections Canada & provinces.  
- **Eligibility Attestations**  
  - On-chain proofs: “over 18,” “resident of riding X,” “citizen vs PR,” without revealing identity (ZK-style).  
- **Voter Registry Smart Contract**  
  - Mirrors the federal + provincial registers in a privacy-preserving way for protocol-level eligibility checks.

---

## 3️⃣ Representation & Delegation Layer (Canada)

**Layer recap:** How individual voice becomes political power.

### Current Canada

- **House of Commons elections**  
  - Canada is divided into **338–343 electoral districts (“ridings”)**; each elects one MP. :contentReference[oaicite:23]{index=23}  
  - Voting system: **First-past-the-post (FPTP)** – candidate with most votes wins the seat. :contentReference[oaicite:24]{index=24}  

- **Government formation**  
  - Party with **confidence of the House** (usually most seats) forms the Government. Majority vs minority governments depend on seat counts. :contentReference[oaicite:25]{index=25}  

- **Senate**  
  - Senators appointed by the Governor General on advice of the PM; represent regions and review legislation. :contentReference[oaicite:26]{index=26}  

- **Provinces and municipalities**  
  - Each has its own elected legislature or council using similar FPTP-style systems. :contentReference[oaicite:27]{index=27}  

### Protocol Hooks (Canada)

- **On-chain representation graph**  
  - Represent **MPs, MLAs, municipal councillors**, parties and caucuses as on-chain entities with terms, ridings, and roles.  
- **Liquid democracy overlay (non-binding at first)**  
  - Citizens delegate to issue-based or regional representatives on-chain, creating a **parallel legitimacy signal** to compare against FPTP outcomes.  
- **Recall / mandate dashboards**  
  - Track confidence/approval signals on-chain even if legal recall rules stay off-chain initially.

---

## 4️⃣ Proposal & Deliberation Lifecycle (Canada)

**Layer recap:** Idea → law/budget → execution.

### Current Canada

- **Federal legislative flow** (simplified):  
  1. Policy idea developed by cabinet / MP / committee.  
  2. **Bill introduced** in House or Senate; multiple readings, committee study, amendments. :contentReference[oaicite:28]{index=28}  
  3. Passed by **both Houses**, then **Royal Assent** by Governor General. :contentReference[oaicite:29]{index=29}  
  4. Comes into force via commencement provisions or orders-in-council.

- **Public input**  
  - Committee hearings, consultations, white papers, online feedback – mostly off-chain, scattered across sites and PDFs.

- **Budget cycle**  
  - Annual federal & provincial budgets tabled by finance ministers; supply and appropriation bills must pass to authorize spending. :contentReference[oaicite:30]{index=30}  

### Protocol Hooks (Canada)

- **On-chain bill metadata**  
  - Every bill / motion / regulation gets a **content hash and metadata record** (sponsor, stage, committee, links).  
- **Deliberation links**  
  - Public submissions, committee transcripts, and expert reports anchored via hashes; results remain in web2 / IPFS.  
- **Formal on-chain “governance actions”**  
  - Mirror Cardano-style governance actions: proposal types for laws, budgets, appointments that track progress through the real process.  
- **Participatory overlays**  
  - Non-binding civic referenda or preference signals attached to each bill or budget item.

---

## 5️⃣ Voting Protocol Layer (Canada)

**Layer recap:** Collect & count votes securely.

### Current Canada

- **Federal/provincial elections**  
  - FPTP, one vote per elector per riding. :contentReference[oaicite:31]{index=31}  
  - **Paper ballots, hand-counted**, overseen by Elections Canada (federal) or provincial agencies. :contentReference[oaicite:32]{index=32}  

- **Referenda / plebiscites**  
  - Rare; ad-hoc enabling legislation (e.g., past referenda on constitutional changes or provincial matters).

- **Security model today**  
  - Physical chain of custody, scrutineers, recounts; not cryptographically verifiable by individual voters, but well-tested administratively.

### Protocol Hooks (Canada)

- **Parallel cryptographic referenda**  
  - Start with **consultative on-chain votes** (no legal force) to test ZK voting, end-to-end verifiability, and anti-coercion, while paper remains official.  
- **Per-riding governance channels**  
  - On-chain voting instances scoped to each riding to mirror Elections Canada’s district model. :contentReference[oaicite:33]{index=33}  
- **Public verification layer**  
  - Publish commitment hashes for results, recounts, and tallies on-chain, even if ballots remain paper.

---

## 6️⃣ Policy Encoding & Enforcement Layer (Canada)

**Layer recap:** Once a decision is made, how does it bite?

### Current Canada

- **Laws & regulations**  
  - Published in the **Canada Gazette**, Justice Laws website, and provincial equivalents. :contentReference[oaicite:34]{index=34}  
- **Enforcement**  
  - Carried out by departments, agencies, regulators, police, and courts.  
- **Budgets**  
  - Appropriations authorize departments to spend from the Consolidated Revenue Fund (federal) or provincial funds.

### Protocol Hooks (Canada)

- **On-chain legal registry (hash-based)**  
  - Hash every Act, regulation, and amendment; maintain an **immutable timeline** of Canada’s legal state.  
- **Treasury shadowing**  
  - Represent budget lines and transfers as **on-chain commitments**, even if fiat flows remain off-chain initially.  
- **Reg-tech integration**  
  - Build domain-specific smart contracts where compliance can be checked automatically (e.g., open data obligations, algorithmic disclosure, etc.), while human enforcement remains off-chain.

---

## 7️⃣ Constitutional & Oversight Layer (Canada)

**Layer recap:** Rights, checks, and amendments.

### Current Canada

- **Core documents**  
  - **Constitution Acts 1867 & 1982** define state structure + amending procedures. :contentReference[oaicite:35]{index=35}  
  - **Canadian Charter of Rights and Freedoms** protects fundamental, democratic, legal, equality, and other rights. :contentReference[oaicite:36]{index=36}  

- **Judicial oversight**  
  - **Courts (especially Supreme Court)** can strike down or interpret laws inconsistent with the Constitution/Charter. :contentReference[oaicite:37]{index=37}  

- **Notwithstanding clause (s.33)**  
  - Allows Parliament or provincial legislatures to temporarily override certain Charter rights (ss. 2, 7–15) for up to 5 years, renewable. :contentReference[oaicite:38]{index=38}  
  - High-profile use around Quebec’s secularism laws (Bill 21, Bill 9, etc.). :contentReference[oaicite:39]{index=39}  

- **Auditors & watchdogs**  
  - Auditor General, parliamentary budget officer, ethics commissioner, provincial equivalents.

### Protocol Hooks (Canada)

- **Machine-readable “Charter layer”**  
  - Tag on-chain proposals with which Charter sections they potentially touch; require a **rights impact analysis** hash before ratification.  
- **On-chain record of constitutional litigation**  
  - Track which laws are under Charter challenge, which sections invoked, and outcomes; create a live “constitutional health” dashboard.  
- **Constitutional committee analogue**  
  - Inspired by Cardano’s Constitutional Committee: a multi-stakeholder body (judges/academics/Indigenous reps, etc.) whose **non-binding protocol veto** flags proposals likely unconstitutional.

---

## 8️⃣ Infrastructure Layer (Canada)

**Layer recap:** Tech stack.

### Current Canada

- **Elections infrastructure** – web portals, paper ballots, counting systems, party databases. :contentReference[oaicite:40]{index=40}  
- **Parliamentary systems** – LEGISinfo, Hansard, committee systems, broadcasting. :contentReference[oaicite:41]{index=41}  
- **Court / legal publishing** – CanLII, Justice Laws, provincial e-filing. :contentReference[oaicite:42]{index=42}  

### Protocol Hooks (Canada)

- **Governance chain / rollup**  
  - A dedicated **governance ledger for Canada** (could be a Cardano-based sidechain or rollup) hosting:  
    - Identities/VC anchors  
    - Proposal records  
    - Governance actions  
    - Treasury/budget commitments  

- **Bridges to institutional systems**  
  - APIs from the chain into:  
    - Parliamentary tracking systems  
    - Elections Canada dashboards  
    - Government open data portals  

- **Citizen & rep clients**  
  - Citizen app: identity, voting, delegation, explainers.  
  - MP / MLA dashboard: link on-chain signals to real votes, committees, and constituency work.

---

## 9️⃣ Security, Resilience & Inclusivity Layer (Canada)

**Layer recap:** Make it usable and robust for real people.

### Current Canada

- **Accessibility & inclusion**  
  - Voting accommodations (advance polls, mail-in ballots, assistive tools). :contentReference[oaicite:43]{index=43}  
- **Resilience**  
  - Paper ballots as a physical audit trail; independent elections agencies; multi-party scrutineers. :contentReference[oaicite:44]{index=44}  

### Protocol Hooks (Canada)

- **Mobile-first governance UX**  
  - Build **simple, bilingual (EN/FR)** interfaces with offline-friendly modes and transparent explanations of each vote.  
- **Key recovery and shared custody**  
  - Integrate with government-backed recovery (e.g., in-person verification at Service Canada / provincial offices) + social recovery options.  
- **Threat modelling at state scale**  
  - Design for:  
    - State-level cyberattacks  
    - Platform capture / censorship  
    - Disinformation surges around referenda and elections  

- **Civic transparency dashboards**  
  - Public “governance explorers” tracking:  
    - Bills, budgets, Charter challenges  
    - Participation rates per riding  
    - How well on-chain civic signals align with real votes

---

## 🔍 Putting It Together – Canada as a Protocol Host

**Today:**  
Canada already has a **clear separation of powers**, **three levels of government**, and a **rights-anchored constitution**. :contentReference[oaicite:45]{index=45}  

**Protocol blueprint (minimal viable path):**

1. Start with **Layer 8/4**: on-chain registry of bills, votes, and legal hashes + participatory overlays (consultative referenda).  
2. Add **Layer 2/3 hooks**: digital credentials & delegation graph; keep paper elections as source of truth.  
3. Migrate **budgets & small funds** (innovation, participatory budgeting) into on-chain treasury flows.  
4. Finally, introduce **constitutional / Charter-aware tooling** to make rights analysis and challenges legible and auditable in real time.

This way, **Canada-as-it-exists** becomes the “off-chain anchor,” and the protocol grows around it as a **governance co-processor**, not a replacement.

---
