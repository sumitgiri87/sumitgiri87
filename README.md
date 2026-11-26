### Sumit Giri, PhD

Mathematician turned AI security engineer, based in Toronto.
I break LLM and agent systems, then build the guardrails and audit trails that make them safer to ship.
My PhD is in number theory and cryptography, so I also care about the crypto underneath, especially the move to post-quantum.

**What I work on**

- Guardrails and red-teaming for LLM and agent systems (prompt injection, tool-scope abuse, data exfiltration)
- Tamper-evident audit logging for AI agents
- Post-quantum cryptography migration

**Selected work**

- [secure-enterprise-knowledge-hub](https://github.com/sumitgiri87/secure-enterprise-knowledge-hub): FastAPI and LiteLLM gateway where every tool call goes through one guardrail chokepoint. On the repo's own offline red-team set (7 scripted attack calls across injection, tool-scope and exfiltration, plus 2 benign calls) it stops 7 of 7 attacks with 0 benign calls blocked. Run it with `python tests/redteam/run_redteam.py`.
- [llm-audit-logger](https://github.com/sumitgiri87/llm-audit-logger): zero-dependency, hash-chained JSONL audit trail for LangChain and LangGraph agents. Editing a past record breaks the chain, and `verify_log` reports it (covered by a unit test).
- [agentic-rag-security-lab](https://github.com/sumitgiri87/agentic-rag-security-lab): vulnerable-by-design RAG pipeline for practicing indirect prompt injection. Runs offline with the Python standard library.
- [agentic-ai-security-audit-framework](https://github.com/sumitgiri87/agentic-ai-security-audit-framework): a methodology and control-mapping sheet for auditing agentic AI systems.
- [defenders-deck](https://github.com/sumitgiri87/defenders-deck): offline threat-modeling exercise on the OWASP Top 10 for agentic AI. I ran it at Threat Modeling Connect Toronto in October 2026.

**Community**

Co-founder of the Toronto chapter of the [AI Security Engineers Community](https://www.aiseceng.io/) and organizer of the Threat Modeling Connect Toronto chapter.

**Elsewhere**

[LinkedIn](https://www.linkedin.com/in/sumit-giri-0111) · [Medium](https://medium.com/@sumit.giri199)

CompTIA CySA+, Security+
