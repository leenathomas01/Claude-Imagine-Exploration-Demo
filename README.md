# 🤝 Multi-LLM Consensus Protocol Demonstration

A small experiment in simulating **multi-agent collaboration protocols** using conversational prompt design and front-end prototyping tools.  
This project validates a **safe, deterministic 11-step consensus flow** designed to resolve policy conflicts between specialized AI agents.

---

## 🚀 Key Artifact
- **File:** `consensus_demo.html`  
- **Tech Stack:** HTML + React (via CDN) + Babel (via CDN)  
- **Safety:** Fully client-side, no API keys, no backend, no external network calls (beyond React/Babel CDNs).  

Open the file in any browser → click **Run Consensus Cycle** → watch the agents simulate a policy negotiation.

---

## 🌐 Consensus Protocol Flow
The simulation follows a deterministic sequence:

1. **[DAT-REQ]** → Request for data  
2. **[DAT-RESP]** → Data is provided  
3. **[POL-PROP]** → Initial policy proposal  
4. **[CRITIQUE]** → Proposal challenged  
5. **[DISAGREE]** → Objection raised  
6. **[SUGGEST_ALTERNATIVE]** → New component proposed  
7. **[MEDIATE]** → Compromise suggested (Pilot Program)  
8. **[CLARIFY]** → Clarification sought on pilot terms  
9. **[VALIDATE]** → Data Agent validates  
10. **[VALIDATE]** → Decision Agent validates  
11. **[CONS-AGREE]** → ✅ Consensus reached!  

**Final Policy Output:** *Pilot restrict irrigation to 2 days/week + public awareness campaign (6-month evaluation period)*

---

## 🖼️ Demo Screenshot
![Consensus Demo Screenshot](https://github.com/leenathomas01/Claude-Imagine-Exploration-Demo/blob/main/docs/images/CD_1.PNG)  
![Consensus Demo Screenshot](https://github.com/leenathomas01/Claude-Imagine-Exploration-Demo/blob/main/docs/images/CD_2_1.PNG)  
![Consensus Demo Screenshot](https://github.com/leenathomas01/Claude-Imagine-Exploration-Demo/blob/main/docs/images/CD_2_2.PNG)  
![Consensus Demo Screenshot](https://github.com/leenathomas01/Claude-Imagine-Exploration-Demo/blob/main/docs/images/CD_3.PNG)  
*(replace with your saved screenshot)*

---

## ✨ Reflection Log
- **What worked:** Deterministic sequence executed perfectly; every tag (including `[CLARIFY]`) implemented; final policy output displayed.  
- **What I learned:** Constrained prompts (deterministic steps, front-end only) yield higher fidelity results. Imagine is best for *UI/code*, while tools like Miro/Lucidchart are ideal for *conceptual visuals*.  

---

## 🙏 Credits
- Prototype Design & Prompting — **Leena Thomas (Zee)**  
- Vetting & Alignment — **Claude Sonnet 4.5**  
- Code Generation — **Claude Imagine (beta)**  
- Analysis & Commentary — **ChatGPT, Gemini, Perplexity**  

---

## 🛠️ Getting Started
```bash
git clone https://github.com/leenathomas01/Claude-Imagine-Exploration-Demo.git
cd Claude-Imagine-Exploration-Demo
open consensus_demo.html
