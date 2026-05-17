EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

AIM:

To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

SCENARIO:

You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

1.Accuracy

2.Coherence

3.Simplicity

4.Speed

5.User experience

OUTPUT:

**PARAGRAPH BEFORE APPLYING PROMPTING TECHNIQUES:**

Blockchain technology, often associated with cryptocurrencies like Bitcoin, represents a paradigm shift in how digital transactions and data are stored, verified, and shared. Fundamentally, blockchain is a decentralized ledger system where data is grouped into "blocks," each linked to the previous block through a cryptographic hash, forming a chronological "chain." This architecture ensures that once a block is added, its information cannot be altered retroactively without changing subsequent blocks, which would require majority consensus across the network. This immutability provides a foundational layer of security and trust without necessitating centralized authorities such as banks or governmental institutions. At its core, blockchain relies on distributed computing, which means that every participant or "node" in the network holds a copy of the complete blockchain. This distribution makes the system resistant to attacks, fraud, or single points of failure, creating redundancy and heightened resilience. Transaction validation within blockchain networks typically employs consensus mechanisms, such as Proof of Work (PoW) or Proof of Stake (PoS). Proof of Work, popularized by Bitcoin, requires participants (miners) to solve complex computational puzzles to validate transactions, incentivized by cryptocurrency rewards. Proof of Stake, on the other hand, selects validators based on the quantity of cryptocurrency they "stake" or lock in the network, reducing energy consumption and promoting scalability. These mechanisms ensure that all nodes agree on the current state of the ledger, maintaining consistency and preventing double-spending or fraudulent activities. Beyond finance, blockchain applications extend to supply chain management, healthcare, voting systems, identity verification, and smart contracts. For example, in supply chain contexts, blockchain can provide an immutable record of goods from origin to consumer, enhancing transparency and reducing counterfeit risks. Smart contracts, self-executing agreements coded on the blockchain, automate transaction enforcement based on predefined conditions, eliminating intermediaries and increasing efficiency. Despite its advantages, blockchain also presents challenges. Scalability remains a concern, as public blockchains often face limitations in transaction throughput compared to centralized databases. Additionally, the energy demands of certain consensus algorithms, particularly Proof of Work, have drawn criticism regarding environmental sustainability. Data privacy is another notable issue; while transactions are pseudonymous, public ledger structures inherently reveal transaction histories, necessitating sophisticated privacy-preserving solutions when handling sensitive information. Furthermore, regulatory ambiguity and the evolving legal landscape create uncertainties for enterprises considering blockchain deployment. Despite these hurdles, blockchain offers compelling benefits through decentralization, transparency, integrity, and trustless interactions. Emerging innovations, such as Layer-2 protocols, sharding, and zero-knowledge proofs, aim to address throughput and privacy limitations, driving broader adoption. As research and development continue, the technology has the potential to transform industries by enabling secure, verifiable, and distributed systems that operate beyond traditional intermediaries. By understanding blockchain’s fundamental principles—its decentralization, cryptographic linkage, consensus-driven validation, and application versatility—organizations and individuals can better assess its suitability for specific use cases and contribute to its ongoing evolution. Overall, blockchain represents a convergence of computer science, cryptography, and distributed systems engineering that promises to reshape how digital trust is established, assets are managed, and collaborative processes are coordinated across various domains, offering a foundation for more transparent, secure, and automated digital ecosystems.

**USING CHATGPT**

**1. Zero-Shot Summary**

Blockchain is a decentralized system that securely records transactions using cryptography and consensus methods. It provides transparency, security, and trust without central control and is applied in cryptocurrencies, healthcare, supply chains, voting, and smart contracts. Despite challenges like scalability and energy consumption, blockchain continues to evolve as an important digital innovation.

**2. Few-Shot Summary**

**Example 1**

Input: Artificial Intelligence helps machines learn and make decisions like humans.
Summary: AI enables machines to perform tasks intelligently through learning and decision-making.

**Example 2**

Input: Cloud computing provides online storage and computing resources over the internet.
Summary: Cloud computing delivers storage and computing services remotely through the internet.

**Given Paragraph Summary**

Blockchain is a decentralized digital ledger that uses cryptography and consensus mechanisms to securely verify transactions. It improves transparency, security, and trust across industries such as finance, healthcare, voting, and supply chains, though challenges like scalability and regulation still exist.

**3. Chain-of-Thought Summary**

1. Identify the main topic: Blockchain technology.

2. Extract key concepts: decentralization, cryptography, consensus mechanisms, transparency, immutability.

3. Note applications: cryptocurrencies, healthcare, voting, supply chains, smart contracts.

4. Identify advantages: security, efficiency, trust.

5. Identify limitations: scalability, energy usage, privacy, regulations.

6. Form concise summary:

Blockchain is a decentralized and secure digital ledger system that uses cryptography and consensus mechanisms to verify transactions transparently without central authorities. It has applications beyond cryptocurrencies, including healthcare, voting, supply chains, and smart contracts. While blockchain offers improved security and efficiency, issues such as scalability, energy consumption, and regulatory uncertainty continue to be challenges.

**4. Role-Based System Summary**

**Role:** Teacher

Blockchain is a secure decentralized technology that stores transaction records across many computers. It improves transparency and trust and is used in finance, healthcare, voting, and smart contracts, though it still faces technical and regulatory challenges.

**Role:** Business Analyst

Blockchain technology enables transparent and tamper-resistant transaction management without intermediaries. Its applications in finance, logistics, healthcare, and digital contracts can improve efficiency and trust, but scalability and compliance issues remain concerns.

**Role:** Technical Expert

Blockchain is a distributed ledger system using cryptographic hashing and consensus algorithms such as Proof of Work and Proof of Stake to maintain secure and immutable records. Despite its advantages in decentralization and security, optimization is needed for scalability, privacy, and energy efficiency.

**USING GEMINI**

**1. Zero-Shot Summary**

Blockchain is a decentralized, secure digital ledger that uses cryptography and consensus mechanisms to record transactions transparently and immutably without a central authority. While widely applicable in areas like supply chains, healthcare, and smart contracts, it faces hurdles including scalability, high energy consumption, and regulatory uncertainty that emerging technologies are working to solve.

**2. Few-Shot Summary**

**Example 1 (Input):** Cloud computing allows users to access servers, storage, and databases over the internet. It eliminates the need for physical hardware, offering scalability and cost savings, though it introduces data security risks.
**Example 1 (Output):** Cloud computing delivers internet-based IT resources, saving costs and increasing scalability despite security risks.

**Example 2 (Input):** Artificial Intelligence mimics human intelligence to perform tasks like problem-solving and pattern recognition. It automates industries and improves efficiency, but raises ethical concerns regarding job displacement and bias.
**Example 2 (Output):** AI replicates human intellect to automate tasks and boost efficiency, but faces ethical and bias challenges.

**Target Text (Output):**

Blockchain is a decentralized ledger offering secure, transparent transactions across various industries, though it struggles with scalability, energy use, and regulation.

**3. Chain of Thought (CoT) Summary**

**Step 1:** Identify the core technology and definition.

Drafting: Blockchain is a decentralized, secure digital ledger using cryptography and consensus (PoW/PoS) for trust without central authorities.

**Step 2:** Identify the applications.

Drafting: It goes beyond crypto into supply chains, healthcare, voting, and smart contracts.

**Step 3:** Identify the challenges and future outlook.

Drafting: It faces scalability, energy, privacy, and regulatory hurdles, which new tech aims to fix.

**Step 4:** Synthesize into a cohesive, concise summary.

**Final CoT Summary:**

Blockchain is a secure, decentralized digital ledger that eliminates central authorities using cryptography and consensus mechanisms. It is utilized across diverse sectors like healthcare and supply chains, but its widespread adoption depends on overcoming current limitations in scalability, energy consumption, and regulation.

**4. Role-Based Systems**

**Role A:** The Tech Enthusiast / Startup Founder

"Look at blockchain as the ultimate trust machine. It’s a decentralized ledger that completely bypasses middlemen using cryptographic consensus like PoW and PoS. We aren't just talking crypto here—it’s revolutionizing smart contracts, supply chains, and voting by making data completely immutable. Sure, we have to grind through some current bottlenecks like tech scalability and regulatory gray areas, but the next wave of tech is fixing that. This is the future of transparent digital infrastructure."

**Role B:** The Corporate Executive / Risk CIO
Executive Brief briefing: Blockchain Technology

1. Core Value: A decentralized, tamper-proof digital ledger ensuring data transparency and immutability without third-party dependencies.

2. Operational Scope: Viable applications identified in supply chain logistics, healthcare records, and automated smart contracts.

3. Risk Factors: Implementation carries notable exposure regarding system scalability, high energy overheads, data privacy compliance, and fluid regulatory frameworks.

4. Strategic Outlook: Monitoring emerging optimizations is recommended before full-scale enterprise integration.

**USING COPILOT**

**1. Zero-shot Summary**

Without prior examples, the system condenses the text directly:

Blockchain is a decentralized ledger that enables secure, transparent, and immutable transactions, with applications beyond cryptocurrency in areas like supply chains, healthcare, and voting, though challenges like scalability and regulation remain.

**2. Few-shot Summary**

Using learned patterns from prior examples (imagining the system has seen summaries before):

Blockchain ensures trust through cryptography and consensus, powering not only cryptocurrencies but also smart contracts, healthcare, and supply chains. While it offers transparency and efficiency, issues like energy use, privacy, and regulation still need solutions.

**3. Chain-of-Thought Summary**

1. Blockchain is a decentralized ledger.

2. It secures transactions via cryptography and consensus (Proof of Work, Proof of Stake).

3. Benefits: transparency, immutability, trust, efficiency.

4. Applications: cryptocurrencies, supply chains, healthcare, voting, smart contracts.

5. Challenges: scalability, energy consumption, privacy, regulation.

6. Emerging technologies aim to address these limitations.

**Final summary:**

Blockchain is a transformative system offering secure, transparent digital interactions, though it faces hurdles in scalability, energy, privacy, and regulation.

**4. Role-Based Summaries**

1. Technologist: Blockchain is a breakthrough in distributed computing, enabling secure peer-to-peer transactions without central control.

2. Economist: Blockchain reduces transaction costs and builds trust in markets, but regulatory uncertainty and energy inefficiency hinder adoption.

3. Policy Maker: Blockchain could modernize voting and healthcare systems, but privacy and compliance frameworks must evolve.

4. Business Leader: Blockchain offers efficiency and transparency in supply chains and contracts, though scalability and regulation remain barriers to mass adoption.

**USING CLAUDE AI**

**1. Zero-shot summary**

Direct, no examples given

Blockchain is a decentralized, tamper-proof digital ledger that records transactions using cryptography and consensus mechanisms. It enables trust without central authorities and powers applications from cryptocurrency to supply chains, healthcare, and smart contracts — though scalability, energy use, and regulatory gaps remain ongoing challenges.

**2. Few-shot summary**

Guided by prior examples

Example pattern: "X is a Y that does Z, used in A and B, but faces C."

Blockchain is a cryptographic ledger system that records transactions without central oversight, used in finance, logistics, healthcare, and governance — but limited by slow throughput, high energy costs, and unclear regulation. Emerging solutions continue to close these gaps.

**3. Chain-of-thought summary**

Step-by-step reasoning first

1. What is it? A decentralized ledger secured by cryptography and consensus (PoW/PoS).

2. What does it do? Records transactions transparently and immutably — no central authority needed.

3. Where is it used? Crypto, supply chains, healthcare, voting, smart contracts.

4. What are the limits? Scalability, energy use, privacy concerns, regulatory uncertainty.

**Conclusion:**

Blockchain offers transparent, secure, trustless record-keeping with broad real-world use — but must overcome technical and regulatory hurdles to reach its transformative potential

**4. Role-based summary**

Tailored by audience role

**Developer-** Blockchain is a distributed ledger using cryptographic hashing and consensus protocols (PoW/PoS). Build with it for smart contracts, trustless systems, and immutable audit trails.

**Business-** Blockchain cuts out middlemen, reduces fraud, and automates contracts — driving efficiency in supply chains, finance, and healthcare. Regulatory clarity is still evolving.

**Beginner-** Think of blockchain as a shared notebook no one can erase or fake. Everyone on the network keeps a copy, so there's no need to trust a single bank or authority.

**Policy-** Blockchain enables transparent, tamper-proof record systems for voting, identity, and healthcare — but energy consumption and regulatory gaps demand urgent policy frameworks.| Prompting Technique        | Accuracy  | Coherence | Simplicity  | Speed     | User Experience | Overall                |
| -------------------------- | --------- | --------- | ----------- | --------- | --------------- | ---------------------- |
| Zero-Shot Prompting        | Medium    | Good      | Very Simple | Very Fast | Easy            | Good                   |
| Few-Shot Prompting         | High      | High      | Simple      | Medium    | Very Good       | Better                 |
| Chain-of-Thought Prompting | Very High | Very High | Moderate    | Slower    | Detailed        | Best for complex tasks |
| Role-Based Prompting       | High      | High      | Simple      | Medium    | Engaging        | Very Good              |




RESULT:
