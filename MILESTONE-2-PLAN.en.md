# 💡 IDEA-TON

![logo](./images/logo.png)


## **Project Overview**
ObraClara is a digital platform designed to modernize the management of Service Orders (OS) and Request Notes (NP) in public construction projects. 

Today, these processes rely on WhatsApp messages, scattered PDFs, and physical logbooks, leading to loss of traceability, legal risks, delays, and low operational transparency.

The platform centralizes the registration, tracking, and validation of critical project documents. 

### It incorporates:
- Automated digitalization of OS/NP through uploads of photos, PDFs, text, or voice.
- Immutable blockchain traceability, storing document hashes to guarantee authenticity and prevent tampering.
- Automated alerts for deadlines and critical response windows.
- AI-powered search, enabling users to find historical records, justify delays, audit processes, or generate reports in seconds.
- A unified dashboard for site managers and construction company owners.

ObraClara reduces operational time, eliminates document loss, strengthens transparency, and provides reliable legal evidence for audits and public oversight. It is a scalable solution for construction companies and municipalities, aligned with modern standards of public and private sector management.

## Table of contents

- [Summary](#summary)
- [Features](#features)
- [Endpoints](#endpoints)
- [Operations](#operations)
- [Retriable errors](#retriable-errors)
- [Reference](#reference)
- [Changelog](#changelog)
- 
---
- [ ]  2-3 minute pitch video (uploaded and link provided)
    - Walkthrough of what you built + your pitch
    - Include: problem, solution, demo, market context, Milestone 2 overview
    - Upload to any platform (e.g., YouTube, Loom) and share the link
- [ ]  Pitch deck (URL)
    - Problem & solution
    - Market research & competitive analysis
    - Technical approach
    - Milestone 2 plan summary
- [ ]  Public GitHub repository
    - Open source license
    - `MILESTONE-2-PLAN.md` using [Milestone 2 Plan Template](https://www.notion.so/Milestone-2-Plan-Template-28b3e52aeb15802d919ffdfe5d4ca5b4?pvs=21)
    - `README.md`: including setup instructions, link to demo URL (if applicable), link to pitch video, team member names + roles, link to pitch deck

### Bonus Material (to be Included in `README.md`)

- [ ]  Demo video showing prototype/concept (separate from pitch video)
- [ ]  User feedback or validation evidence (e.g. surveys, results from mini marketing campaign)
- [ ]  Marketing material or plan (e.g. social media links, online engagement with product)

### 💡 IDEA-TON TECH REQUIREMENTS

- Technical architecture document (detailed plan)
- Wireframes/mockups showing user flow
- See: [IDEA-T-ON TECHNICAL PLAN CHECKLIST](https://www.notion.so/IDEA-T-ON-TECHNICAL-PLAN-CHECKLIST-2a43e52aeb1580558beddf44eed73e73?pvs=21)


----
# IDEA-T-ON TECHNICAL PLAN CHECKLIST

## 🏗️ Technical Architecture

### System Diagram

*[Include ONE clear diagram showing how your components connect. Use Mermaid, Excalidraw, or draw on paper and photo it]*

E.g. mermaid :

`graph LR
    A[Component 1] --> B[Component 2]
    B --> C[Component 3]`

### Tech Stack

**Frontend:**

- Framework: [e.g., Next.js, React]
- Web3: [e.g., Polkadot.js, PAPI]
- UI: [e.g., Tailwind, shadcn]

**Backend/Contracts:**

- Type: [e.g., ink! contract, FRAME pallet, API service]
- Language: [e.g., Rust, TypeScript]
- Storage: [e.g., On-chain, IPFS, Arkiv]

**Blockchain:**

- Chain: [e.g., Asset Hub, Custom parachain]
- Tools: [e.g., SubQuery, Chopsticks]

### How Data Flows

*[Simple step-by-step of a user action through your system]*

1. User does X →
2. Frontend calls Y →
3. Blockchain processes Z →
4. User sees result

---

## 🎨 Design & User Flow

### Mockups

**Figma/Design Tool or simple wireframes**

- Link: [Figma or Balsamiq share link or if hand drawn share photo]
- Key screens: [List 3-5 main screens]
- Files: [Attach images or links]

### Main User Flow

*[Describe the core action step-by-step with 3-5 steps]*

**Example: Minting an NFT**

1. Connect wallet
2. Upload image + metadata
3. Set price
4. Sign transaction
5. View your listing

*[Include screenshots or sketches for each step]*

---

## ⚙️ Implementation Plan

### Hackathon Weekend (Nov 14-16)

*[What you'll build in 72 hours - be realistic]*

- [ ]  [Task 1 - e.g., Deploy smart contract to testnet]
- [ ]  [Task 2 - e.g., Build basic UI with wallet connection]
- [ ]  [Task 3 - e.g., Connect frontend to contract]
- [ ]  [Task 4 - e.g., Record demo video]

**Weekend deliverable:** [e.g., Working prototype on Paseo testnet]

### Milestone 2 - 6 Weeks (Nov 18 - Dec 24)

*[Required for Main Track prize consideration - outline your post-hackathon plan]*

**Weeks 1-2:** [e.g., Add feature X, optimize contract]

**Weeks 3-4:** [e.g., Integrate partner bounty tech, user testing]

**Weeks 5-6:** [e.g., Mainnet deployment prep, documentation]

**M2 Deliverable:** [e.g., Mainnet-ready product with 10 test users]

---

## 🔍 Technical Feasibility

**Why this will work:**

- ✅ [e.g., We have Rust/FRAME experience]
- ✅ [e.g., Libraries exist for core features]
- ✅ [e.g., Similar projects prove it's possible]

**Biggest challenges:**

1. **[Challenge]** → *Solution: [How you'll handle it]*
2. **[Challenge]** → *Solution: [How you'll handle it]*

**Key dependencies:**

- [e.g., Asset Hub pallet availability]
- [e.g., Testnet RPC access]