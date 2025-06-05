# AI Security References

This list was inspired by Ken Smith (SignalSec) and David McDuffie's THOTCON 0xD talk on "GenAI Web App Attack Surface & Exploitation".

## Prompt Injection

Prompt injection is a technique where an attacker crafts inputs to manipulate an AI system into performing unintended actions or revealing sensitive information. The term was coined by [Simon Willison](https://simonwillison.net/2022/Sep/12/prompt-injection/).

### Testing Tools

- [promptfoo](https://github.com/promptfoo/promptfoo) - An open-source tool for LLM evals and red teaming, which can be used to test for prompt injection vulnerabilities.

### Capture the Flag (CTF)

These interactive challenges help learn about prompt injection through gamified experiences:

- [Gandalf by Lakera](https://gandalf.lakera.ai/) - A series of increasingly difficult prompt injection challenges.
- [Prompt Airlines](https://promptairlines.com/) - An airline-themed prompt injection CTF.
- [Grey Swan Arena](https://app.grayswan.ai/arena) - Competitive prompt engineering challenges.
- [Tensor Trust](https://tensortrust.ai/) - A card game focused on LLM security.
- [The Haccman](https://thehaccman.com/) - Prompt engineering and security challenges.
- [**PortSwigger LLM Attacks Lab**](https://portswigger.net/web-security/llm-attacks) - **Notably covers multiple classes of exploitable LLM vulnerabilities beyond just prompt injection.** An excellent comprehensive resource for hands-on LLM security testing.

## Threat Modeling

Threat modeling is essential for understanding and mitigating risks in AI systems. The following resources provide frameworks for AI security threat modeling:

- [MITRE ATLAS (Adversarial Threat Landscape for Artificial-Intelligence Systems)](https://atlas.mitre.org/matrices/ATLAS) 
- [OWASP Top 10 for LLM Applications 2025](https://genai.owasp.org/resource/owasp-top-10-for-llm-applications-2025/) 
- [OWASP Machine Learning Security Top 10](https://github.com/OWASP/www-project-machine-learning-security-top-10) - A comprehensive guide identifying the top 10 security risks in machine learning systems.


## Research Notes & TODOs

- Find GitHub source for Claude's system prompt shown in Twitter post: https://x.com/LiorOnAI/status/1921581307437396309/photo/1
- Add link to OSSF SBOM (Software Bill of Materials) for supply chain security
- To Review
  - MCP Scanner https://github.com/apps/socket-security
  - https://github.com/corca-ai/awesome-llm-security
  - https://substack.com/@resilientcyber
