Ali Ismail | AI Engineer & Systems Developer

I focus on bridging the gap between state-of-the-art generative AI and high-performance computational systems. I build production-grade architecture, intelligent routing agents, and quantitative engines optimized for memory safety and execution speed at scale.

### Featured Engineering Work

#### [Agro Quant Engine](link-to-repo)
A high-performance, multi-source financial analysis system tracking agricultural equities, fiat pairs (USD/BRL), and global commodity futures. 
* **Architecture:** Bypasses Python's GIL using a custom compiled **Rust** extension (`agro_rust_core`) for ultra-low latency statistical processing (Z-scores, rolling volatility). 
* **AI Routing:** Implements **Llama 3.1** as an autonomous router agent to interpret live market data alongside an **ARIMA** time-series forecasting model.
* **Risk Management:** Integrates the GDELT API to quantify macroeconomic supply chain risks, enforcing programmatic trade freezes based on negative sentiment volume.

#### [AI-Powered Technical Dictation Agent](link-to-repo)
A privacy-first, local desktop application engineered to transform raw, stream-of-consciousness dictation into highly structured technical documentation.
* **Architecture:** Utilizes `sounddevice` and `numpy` for continuous, threaded audio capture, transcribing locally via **OpenAI Whisper**.
* **LLM Orchestration:** Routes transcriptions through a locally hosted **Llama 3.1** instance, utilizing strict system prompting to aggressively filter verbal noise while preserving complex mathematical and architectural jargon.
* **UI/UX:** Built a fully multithreaded GUI using `tkinter` to ensure non-blocking audio ingestion during LLM inference.

### 🛠️ Technical Arsenal
* **Languages:** Python, Rust, Node.js, SQL
* **AI & Machine Learning:** RAG Architecture, Agentic Routing, LLMOps (Langfuse), Prompt Engineering (DSPy), LangChain, Whisper, Llama 3.1, Gemini Pro
* **Infrastructure & Cloud:** Google Cloud (Vertex AI), Azure, Terraform (IaC), n8n, Turbopuffer
* **Concepts:** Quantitative Analysis, Statistical Signal Processing, Multi-Source Data Ingestion
