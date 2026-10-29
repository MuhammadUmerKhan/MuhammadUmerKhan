### Hi, I'm Umer 👋

AI Engineer at Revera Innovations. I build agentic systems — LangGraph agents, hybrid
retrieval, real-time voice agents — and I spend most of my time on the part after the demo:
whether it holds up, and what it does when it doesn't.

**[AskUmer](https://github.com/MuhammadUmerKhan/AskUmer-Hybrid-RAG-Conversational-Assistant)** —
a ReAct agent over hybrid retrieval: Qdrant dense search fused with BM25 by rank fusion, then
cross-encoder reranking, across 898 chunks. Guardrails screen input before any model call, and a
DeepEval judge suite runs
[in CI](https://github.com/MuhammadUmerKhan/AskUmer-Hybrid-RAG-Conversational-Assistant/blob/main/.github/workflows/ci.yml)
and fails the build on a faithfulness or answer-relevancy regression. A lighter build of it
answers questions on [buildwithumer.site](https://buildwithumer.site/).

**[DineMate](https://github.com/MuhammadUmerKhan/DineMate-Agentic-AI-for-Automated-Food-Ordering)** —
four LangGraph agents covering ordering, kitchen dispatch and admin, with voice through Whisper.
I red-teamed it against the OWASP LLM Top 10 and MITRE ATLAS across eight attack categories,
found a price-manipulation flaw, fixed it with server-side recomputation, and
[published the report](https://github.com/MuhammadUmerKhan/DineMate-Agentic-AI-for-Automated-Food-Ordering/blob/main/SECURITY.md)
rather than keeping it internal.

**[SupportGenie](https://github.com/MuhammadUmerKhan/SupportGenie-Dual-Fine-Tuned-LLM-Customer-Support-Chatbot)** —
Mistral-7B and LLaMA-3-8B fine-tuned with LoRA in 4-bit on a single free-tier T4, to final loss
1.78 and 1.49.

I build the products these run inside too — Postgres schemas, REST APIs, React admin panels,
Expo mobile apps — including two multi-tenant platforms: one live, where I'm the main developer
in a two-person team, and one I'm building now.

[Portfolio](https://buildwithumer.site/) ·
[LinkedIn](https://www.linkedin.com/in/muhammadumerkhan-ai/) ·
[Email](mailto:muhammadumerk546@gmail.com)

Open to AI engineering roles, remote or hybrid.
