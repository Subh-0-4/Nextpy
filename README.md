# Nextpy
Nextpy is a framework for building self-modifying software.
Key Features
🚧 Guardrails
Set clear boundaries: Users can precisely define what the AI system can and cannot do. This safeguard ensures that the AI system remains a dynamic, self-improving system without overstepping established limits.
🏗️ Greater control with structured outputs
More effective than chaining or prompting: The prompt engine unlocks the next level of prompt engineering, offering significantly greater control over LLMs compared to few-shot prompting or traditional chaining methods.

Superpowers to prompt engineers: It gives full power of prompt engineering, aligning with how LLMs actually process text. This understanding enables you to precisely control the output, defining the exact response structure and instructing LLMs on how to generate responses.

🏭 Powerful prompt engine
The philosophy is to handle more processing at compile time and maintain better sessions with LLMs.

Pre-compiling prompts: By handling basic prompt processing at compile time, unnecessary redundant LLM processing is eliminated.

Session state with LLMs: Maintaining state with LLMs and reusing KV caches can eliminate many redundant generations and significantly speed up the process for longer and more complex prompts. (only for open-source models)

Optimized tokens: The engine can transform many output tokens into prompt token batches, which are cheaper and faster. The structure of the template can dynamically guide the probabilities of subsequent tokens, ensuring alignment with the template and optimized tokenization. (only for open-source models)

Speculative sampling (WIP): You can enhance token generation speed in a large language model by using a smaller model as an assistant. The method relies on an algorithm that generates multiple tokens per transformer call using a faster draft model. This can lead to up to a 3x speedup in token generation.

🤖 Better AI Generations:
🧠 More Effective Than Chaining or Prompt Engineering - Next.py aligns with LLM processing patterns, enabling precise output control and optimal model utilization.

💡 Optimized for Code Generation - Regardless of the LLMs, prompts, or fine-tuning used, the underlying app framework significantly impacts the efficiency of code generation. Next.py's architecture is specifically engineered to maximize efficiency.

💾 Session State with LLM - Efficiently maintain state with LLMs, leveraging KV caches to convert multiple output tokens into prompt token batches. This approach reduces redundant generations, accelerating the handling of lengthy and intricate prompts. (only for open-source models)

🧪 Detect Syntax Errors: Test LLM-generated code, identifying and correcting LLM hallucinations, invalid Nextpy methods, and automatically generating prompts for seamless fixes.

🧱 Modularity
Multiplatform: The AI system does not have to run on a single location or machine. Different components can run across various platforms, including the cloud, personal computers, or mobile devices.

Extensible: If you know how to do something in Python or plain English, you can integrate it with Nextpy.

❤️ Developer-First: ❤️
📘 Transferable Knowledge - Learning Next.py teaches you framework-agnostic fundamentals and the best Python libraries, improving your python development expertise and enabling you to excel across any framework.
📦 Containerized & scalable
.🤖 files: The underlying agents can be effortlessly exported into a simple .agent or .🤖 file, allowing them to run in any environment.

Agentbox (optional): The AI system should be able to optimize computing resources inside a sandbox. You can use Agentbox locally or on a cloud with a simple API, with cloud Agentbox offering additional control and safety.
Performance
⚡ 4-10x faster than your Streamlit app: Our compiled software achieves a staggering 4-10x performance leap over Streamlit. See the difference for yourself at nextpy.org, boasting a PageSpeed score of 99/100.
image

🙏 Thanks
NextPy Framework is a cutting-edge software development framework optimized for AI-based code generation, built on the spirit of cooperation within the open-source community. It seamlessly integrates key components from landmark projects like Guidance, DSPy, Llama-Index, FastAPI-Mail, LangChain, ReactPy, Reflex, Chakra, Radix, NumPy, and Next.js, while also drawing insights from the React and Rust ecosystems.

One of the interesting modules is the generative UI module, which currently uses a forked version of Reflex, Reacton, and Solara.

We are deeply grateful to the open-source creators, contributors, and maintainers whose work has provided the foundation for NextPy. Your commitment to innovation and openness has been vital in shaping this framework. Your contributions have not only enhanced NextPy but are also advancing the new era of AI-powered software development. Thank you for being the catalysts and enablers of this transformational journey.

About
🤖Self-Modifying Framework from the Future 🔮 World's First AMS

dotagent.ai
Topics
python agent ai agi openai gpt webdev webdevelopment ai-agents fullstack-development mlops pydantic fastapi fastapi-template streamlit fastapi-framework sqlmodel llm llmops autogpt
Resources
 Readme
License
 Apache-2.0 license
 Activity
 Custom properties
Stars
 2.3k stars
Watchers
 32 watching
Forks
 179 forks
Report repository
Releases 1
Next.py 0.3.2
Latest
on Jan 16, 2024
Packages
No packages published
Contributors
16
@anubrag
@khushwantD
@shravya-34
@tardigrade-10
@soorykant
@AumJavalgikar
@Raj4646
@Abhi06027
@D21IT185BapodraRajSatish
@coderabbitai[bot]
@Pravin-Jalodiya
@pradeepsaini384
@niikkhilsharma
@SiddhantOjha17
+ 2 contributors
Languages
Python
94.1%
 
Jupyter Notebook
2.6%
 
JavaScript
1.9%
 
Vue
0.4%
 
Handlebars
0.4%
 
Jinja
0.3%
 
Other
0.3%
Footer
© 2025 GitHub, Inc.
Footer navigation
Terms
Privacy
Securi
