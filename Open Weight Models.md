## 🧠 Open-Weight LLMs & Embedding Model Families

Explore leading open-weight language models, reasoning models, coding models, small language models, and embedding systems for building powerful AI agents and RAG applications.

| **Model Family** | **Category** | **What It Is** | **Best Use Case** | **License** | **Adoption** | **Hugging Face Models** |
|:---|:---|:---|:---|:---|:---:|:---|
| **Llama Family** | General | Meta's open-weight model family and a major reference point for fine-tuning tutorials and tooling support. | Broad ecosystem support and fine-tuning workflows. | Custom Llama License | Very High | [Hugging Face ↗](https://huggingface.co/meta-llama) |
| **Qwen3** | General | Alibaba's model family spanning 0.6B to large Mixture-of-Experts models, with strong multilingual capabilities and agentic tool use. | General-purpose AI agents and multilingual applications. | Apache-2.0 | Very High | [Hugging Face ↗](https://huggingface.co/Qwen) |
| **Qwen3-Coder** | Coding | Coding-focused variants optimized for repository-scale editing and agentic coding workflows. | Self-hosted AI coding agents. | Apache-2.0 | Very High | [Hugging Face ↗](https://huggingface.co/Qwen) |
| **DeepSeek** | Reasoning | Mixture-of-Experts models with open reasoning traces that helped make test-time compute more accessible. | Cost-effective reasoning and knowledge distillation. | MIT | Very High | [Hugging Face ↗](https://huggingface.co/deepseek-ai) |
| **gpt-oss** | General | Open-weight models from OpenAI designed to run on a single 80GB GPU or a 16GB laptop. | Exploring OpenAI-style model capabilities without relying on hosted API inference. | Apache-2.0 | Very High | [Hugging Face ↗](https://huggingface.co/openai) |
| **Mistral & Magistral** | General | European model families known for parameter efficiency and permissive licensing options for smaller models. | Cost-sensitive production workloads, particularly in the EU. | Apache-2.0 & Custom | High | [Hugging Face ↗](https://huggingface.co/mistralai) |
| **Devstral** | Coding | Mistral coding models specifically developed for agentic software engineering tasks. | Local software engineering agents and SWE-bench-style workflows. | Apache-2.0 | High | [Hugging Face ↗](https://huggingface.co/mistralai) |
| **Gemma** | Small Models | Google's compact models with strong instruction-following capabilities and a large fine-tuning community. | Edge deployment, lightweight classifiers, and routing models. | Gemma Terms | Very High | [Hugging Face ↗](https://huggingface.co/google) |
| **Phi** | Small Models | Microsoft's small language models trained on curated and synthetic datasets, offering strong reasoning per byte. | Running reasoning models on CPUs or GPUs with around 4GB memory. | MIT | High | [Hugging Face ↗](https://huggingface.co/microsoft) |
| **Kimi K2** | Agentic | Moonshot's trillion-parameter-class MoE model family designed for long-horizon tool use. | Agent benchmarks and complex multi-step tool workflows. | Modified MIT | High | [Hugging Face ↗](https://huggingface.co/moonshotai) |
| **GLM** | General | Zhipu's model family with strong coding and agentic capabilities and frequent open releases. | General-purpose applications as an alternative to Qwen. | MIT | High | [Hugging Face ↗](https://huggingface.co/zai-org) |
| **MiniMax** | Long Context | Hybrid-attention models designed for extremely long context windows with lower serving costs. | Million-token context experiments. | Apache-2.0 | Medium | [Hugging Face ↗](https://huggingface.co/MiniMaxAI) |
| **Nemotron** | Enterprise | NVIDIA post-trained models with open datasets and inference-optimized variants. | Enterprise AI deployments on NVIDIA hardware. | NVIDIA Open License | High | [Hugging Face ↗](https://huggingface.co/nvidia) |
| **OLMo** | Fully Open | Allen Institute models with publicly available training data, code, checkpoints, and logs. | Research, education, and reproducible AI experiments. | Apache-2.0 | Medium | [Hugging Face ↗](https://huggingface.co/allenai) |
| **SmolLM** | Tiny Models | Hugging Face's sub-2B parameter models with fully open training data. | On-device and browser-based AI agents. | Apache-2.0 | Medium | [Hugging Face ↗](https://huggingface.co/HuggingFaceTB) |
| **Granite** | Enterprise | IBM models featuring indemnification, guardian variants, and strong document-handling capabilities. | Regulated enterprise AI pilots. | Apache-2.0 | Medium | [Hugging Face ↗](https://huggingface.co/ibm-granite) |
| **Command** | RAG-Tuned | Cohere models optimized for retrieval-augmented generation and citation-grounded answers. | Enterprise RAG applications with inline citations. | CC-BY-NC for Weights | Medium | [Hugging Face ↗](https://huggingface.co/CohereLabs) |
| **Falcon** | General | TII's UAE-developed models featuring permissive licensing and multilingual coverage. | Applications requiring permissive commercial-use options. | Apache-2.0 | Medium | [Hugging Face ↗](https://huggingface.co/tiiuae) |
| **Sarvam AI** | India | Indic-language-focused models designed for Indian languages, voice, and large-scale government deployment. | Products serving Hindi and regional-language users. | Custom & Apache | Medium | [Hugging Face ↗](https://huggingface.co/sarvamai) |
| **AI4Bharat IndicTrans** | India | Open Indic translation and speech models developed by IIT Madras. | Adding support for 22 Indian languages to AI agents. | MIT | Medium | [Hugging Face ↗](https://huggingface.co/ai4bharat) |
| **Krutrim** | India | Ola-developed Indic-focused foundation models with open weights. | India-first consumer AI products. | Custom | Emerging | [Hugging Face ↗](https://huggingface.co/krutrim-ai-labs) |
| **BGE & BGE-M3** | Embeddings | BAAI embedding models supporting dense, sparse, and multi-vector retrieval. | Budget-friendly multilingual search and retrieval. | MIT | Very High | [Hugging Face ↗](https://huggingface.co/BAAI) |
| **Nomic Embed** | Embeddings | Open embedding models with published training data and long-context support. | Replacing paid embedding APIs with self-hosted alternatives. | Apache-2.0 | High | [Hugging Face ↗](https://huggingface.co/nomic-ai) |
| **Jina Embeddings** | Embeddings | Multilingual and multimodal embedding models with late-chunking support. | Long-document retrieval and semantic search. | Apache-2.0 | High | [Hugging Face ↗](https://huggingface.co/jinaai) |
| **Qwen3 Embedding & Reranker** | Embeddings | Open embedding and reranking model families released alongside Qwen3. | High-quality open retrieval and reranking without relying on paid APIs. | Apache-2.0 | High | [Hugging Face ↗](https://huggingface.co/Qwen) |

---

**📌 Important Note:** Open-weight does not always mean unrestricted commercial use. Model licenses, usage policies, training-data availability, and redistribution rights can differ. Always verify the specific model's license and terms before deployment.
