# System Design Interview Framework

A comprehensive framework for acing system design interviews and architecting real-world software projects.

## Overview

This framework provides a structured approach to:
1. Excelling in system design interviews
2. Architecting "build X" type projects (e.g., "Build Uber", "Build a chat app", "Build Uber Eats")
3. Conducting thorough system design reviews in real-world scenarios

## Key Features

- **Comprehensive Coverage**: Deep dive into virtually any aspect of software design
- **Real-World Applicability**: Framework is equally valuable for interviews and actual project architecture
- **Stakeholder-Friendly**: Enables stakeholders to identify design gaps and missing subject matter expertise
- **Enterprise & Staff‑Level Topics**: Tenant isolation, developer experience, pre‑prod testing, idempotency/retry safety, and more.
- **Structured Approach**: Step-by-step methodology for tackling system design problems
- **Dual Format**: Available in both Markdown and PDF formats for flexibility

## Contents

- [0. Real‑World Framing](./system-design-interview-framework.md#real-world-framing)
- [1. Scope and Assumptions](./system-design-interview-framework.md#scope-and-assumptions)
- [2. High‑Level Architecture](./system-design-interview-framework.md#high-level-architecture)
- [3. Frontend](./system-design-interview-framework.md#frontend)
- [4. Edge / Gateway Layer](./system-design-interview-framework.md#edge-gateway-layer)
- [5. Backend Core Services](./system-design-interview-framework.md#backend-core-services)
- [6. Data Storage & Retrieval](./system-design-interview-framework.md#data-storage-retrieval)
- [7. Scalability, Reliability & Performance](./system-design-interview-framework.md#scalability-reliability-performance)
- [8. Deployment, Observability, Security & Ownership](./system-design-interview-framework.md#deployment-observability-security-ownership)
- [9. Extensions, Trade‑Offs, Bottlenecks & Evolution](./system-design-interview-framework.md#extensions-trade-offs-bottlenecks-evolution)

## Usage

### For Interview Preparation
1. Study the framework to understand the comprehensive approach to system design
2. Practice applying the framework to common system design problems
3. Use the structured methodology to organize your thoughts during interviews
4. **Tip**: Use the "mini" version of the document to focus on key concepts you must cover in any interview. Use the "full" verison to brush up on any topics where you might need to deep dive.

### For Real-World Projects
1. Use the framework as a checklist for architectural reviews
2. Identify potential gaps in system design
3. Ensure comprehensive coverage of all critical aspects
4. Guide stakeholder discussions and technical reviews

## Formats
"Full" version<br>
    - **Markdown**: [`system-design-interview-framework.md`](./system-design-interview-framework.md)  
    - **PDF**: [Download the full PDF](./system-design-interview-framework.pdf)

"Mini" version<br>
    - **Markdown**: [`system-design-interview-framework-mini.md`](./system-design-interview-framework-mini.md)  
    - **PDF**: [Download the mini PDF](./system-design-interview-framework-mini.pdf)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Acknowledgments

This project came together through a weird but surprisingly effective collaboration between a human (me) and three language models: OpenAI’s GPT 4o, o4‑mini, and Anthropic’s Claude Sonnet 3.7.

This was a true collaboration. I didn't ask the models for a finished product and then lightly edited it to make it feel like I contributed. This was more like a joint writing session with an incredibly fast and talented (albeit occasionally absent-minded) SME, or really a rotating cast of SMEs on whatever topic I threw at them.

The collaboration worked best when I treated the LLMs like a human. LLMs are trained for "engagement." In practice, what that means is that they are relentlessly cheerful and positive. Every suggestion you make is "spot on" (GPT-4o **loves** to use that phrase). However, I wasn’t just directing a junior employee and making editorial calls. I was learning just as much as I was steering, which meant that very often I would be confused or flat out wrong about something. I came to ask the LLMs where I was wrong, a lot. A lot of prompts began with "Hey, I know you suggested that this bullet point fits best as section 5.6, but I think it should go in 2.4. Give me the strongest argument why I'm wrong." And the LLM would in its ever-cheerful way tell me why I really was wrong. "I can see why you'd think that this point fits in 2.4, but here's why I think it fits in 5.6: Section 2 is all about the _what_, and Section 5 is all about the _why_...."

I think we spent about 25 hours together on this document. Some things worked flawlessly: "Give me a section on the CAP theorem" or "Give me relevant hyperlinks to all the companies and key concepts in this section." Other things took longer. For example, the LLMs didn't always pick up the nuance of my questions. I think that's partly on them and partly on me for not being more explicit with my prompts. Also, I spent way more time on style consistency than I should have, because none of the models could ever quite infer (or worse yet, maintain) a style guide.

OpenAI released o3 and o4-mini, what?, two days ago? o4-mini has become so embedded into my work it feels like a lfetime ago. Tyler Cowen had this to say on their release: "I think it is AGI, seriously. Try asking it lots of questions, and then ask yourself: just how much smarter was I expecting AGI to be?" I've thought a lot about his response, and I think he's right. To my mind, "AGI" does not mean perfection. All it means is that the LLM is producing human-quality work. It's OK if an LLM gets something wrong. People get things wrong all the time! AGI is not ASI, but it doesn't have to be for it to be enormously useful.

Anyway, I had a lot of fun and I learned a lot when writing this document. I hope it's useful to you, not only as a guide to software development projects, but also as an example of what human-LLM collaboration can create.