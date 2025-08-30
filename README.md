Browser-Based LLM Agent – Proof of Concept

This project is a prototype that illustrates how a large language model can be combined with external utilities directly in the browser. Instead of being limited to plain text replies, the agent can interact with search engines, connect with API pipelines, and even execute JavaScript in real time. The goal is to show how a lightweight UI and a simple JavaScript agent core can demonstrate the next generation of interactive AI systems.

🔹 Core Capabilities

🌐 Flexible Model Selection

Switch easily between providers such as AI Pipe Proxy API (default), OpenAI GPT, Claude, Gemini, and more.

Built-in dropdown menu for real-time provider and model selection.

🤖 Iterative Reasoning Engine

Processes user queries by repeatedly engaging with the LLM until the task is resolved.

Employs structured function-calling (similar to OpenAI’s tool call design).

🛠 Integrated Tools

Google Search → Pulls quick web snippets for context.

AI Pipe Proxy API → Connects to customizable workflows.

JavaScript Sandbox → Runs code securely inside the browser itself.

🎨 User Interface & Experience

Simple, Bootstrap-powered layout.

Chat window with live-streaming responses and file upload support.

Error handling via alerts for smooth interaction.

Built-in logging and performance metrics for debugging.
