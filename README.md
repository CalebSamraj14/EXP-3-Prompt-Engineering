# EXP-3-PROMPT-ENGINEERING-

## Aim: 
The rapid evolution of large language models (LLMs) has introduced a new paradigm for technical work, where AI systems serve as powerful assistants for research, problem-solving, and information synthesis. The effectiveness of these tools, however, is not uniform and heavily depends on the user's ability to craft precise and effective prompts—a discipline known as prompt engineering.

This experiment, designated "EXP-3-PROMPT-ENGINEERING," aims to systematically evaluate and compare the prompting capabilities of five prominent AI platforms in 2024:

ChatGPT (by OpenAI)

Claude (by Anthropic)

Google's Gemini (formerly Bard)

Cohere Command

Meta's Llama 3 (via a public-facing experiment)

The specific use case for this evaluation is Answering Technical Questions, a critical task for engineers, developers, and researchers. The report documents the methodology, presents a comparative analysis of the results, and provides actionable insights for optimizing prompt-driven workflows.

## Algorithm:
Prompt: A specific, multi-part technical question was presented to each model. The prompts were carefully designed to require a combination of factual recall, logical reasoning, and structured output.

Output: The generated response from the AI model was captured and saved for analysis.

Result: Each output was quantitatively and qualitatively scored against a predefined set of criteria, including:

Accuracy: Factual correctness and absence of hallucinations.

Completeness: The degree to which the response addressed all parts of the prompt.

Clarity & Coherence: The readability and logical flow of the answer.

Code Quality: (Where applicable) The correctness and efficiency of generated code snippets.

Timeliness: The speed of response generation.

Citations/Sources: The model's ability to provide verifiable sources.

A uniform prompt was used across all platforms to ensure a fair comparison.

## Prompt
The following prompts were used in the evaluation:

Finite Element Analysis (FEA): "Explain the key differences between linear and non-linear finite element analysis. Provide a simple Python code snippet using a hypothetical library to demonstrate a basic non-linear static analysis, including the load-displacement plot. What are three common sources of non-linearity in a mechanical system?"

Quantum Computing: "Describe the concept of quantum entanglement and its potential application in secure communication (e.g., Quantum Key Distribution). What is a qubit, and how does it differ from a classical bit? Provide a markdown table comparing the two, including their state representation, and list one potential security vulnerability in a basic QKD protocol."

Database Design: "Design a database schema for a real-time multiplayer game. The schema must include tables for Users, Games, and GameSessions. For the GameSessions table, use JSON data types to store in-game events and state changes. Explain the relationships between these tables and provide a SQL query to retrieve all game sessions for a specific user, ordered by their start time."

4.0 Platform Overviews
4.1 ChatGPT
ChatGPT, powered by OpenAI's GPT-4o model, is a general-purpose conversational AI. It is widely recognized for its robust reasoning capabilities, creative writing, and proficiency in various programming languages. Its latest updates have focused on multimodal interactions and enhanced reasoning through the use of an "omni" model.

Figure 1: A typical conversation flow within the ChatGPT user interface, showing the input box and a generated response.

## 4.2 Claude
Claude, developed by Anthropic, is known for its constitutional AI approach, which prioritizes helpful, harmless, and honest outputs. The Claude 3 family of models (Haiku, Sonnet, and Opus) offers a spectrum of performance. Opus, the flagship model, is highly regarded for its large context window, enabling it to process and reason over massive documents.

Figure 2: The clean and minimalist user interface of Claude, highlighting its focus on straightforward text interaction.

## 4.3 Google Gemini
Google's Gemini (formerly Bard) is a powerful conversational AI deeply integrated with Google's ecosystem. Its key feature is its ability to access and synthesize real-time information from the web. This is particularly advantageous for questions that require up-to-the-minute data or information from recent research papers.

Figure 3: The Google Gemini interface showcasing its ability to provide a response with integrated search results and a "Google it" button for verification.

## 4.4 Cohere Command
Cohere's Command family of models, including Command R and Command R+, are engineered for enterprise-grade applications. They are highly optimized for Retrieval Augmented Generation (RAG) and tool-use workflows, making them ideal for tasks that require grounding in a specific knowledge base and multi-step actions.



## 4.5 Meta Llama 3
Meta's Llama 3 is a series of open-source models available for free for both research and commercial use. This open-source nature allows for unprecedented flexibility in fine-tuning and deployment. It has demonstrated strong performance on various benchmarks, particularly in code generation and logical reasoning, and provides a powerful alternative to closed-source models.



## 5.0 Results & Analysis
This section presents the results of the evaluation based on the three technical prompts, following the Prompt → Output → Result algorithm for each platform.

## 5.1 Prompt 1: Finite Element Analysis (FEA)
Prompt: "Explain the key differences between linear and non-linear finite element analysis. Provide a simple Python code snippet using a hypothetical library to demonstrate a basic non-linear static analysis, including the load-displacement plot. What are three common sources of non-linearity in a mechanical system?"

## ChatGPT Output & Result:

Output: A detailed, well-structured explanation with correct theoretical distinctions. The Python code snippet was well-commented, syntactically correct, and included a clear conceptual plotting function. The list of non-linearity sources (material, geometric, boundary conditions) was accurate.

Result: ChatGPT performed exceptionally well on this prompt. Its response was accurate, complete, and the code was functional from a conceptual standpoint. The tone was professional and educational.

Claude Output & Result:

Output: The theoretical explanation was highly nuanced and well-written. The Python code was also correct and included a more detailed explanation of the steps involved in an iterative non-linear solver. The list of non-linear sources was also correct.

Result: Claude's response was also highly accurate and complete. Its prose was arguably more fluid and detailed, making it slightly more pedagogical. It did not, however, have the same level of conciseness as ChatGPT.

Google Gemini Output & Result:

Output: Provided a solid, accurate explanation. The code was similar to ChatGPT's but its primary strength was the inclusion of citations to recent university lectures and research papers on FEA, grounding the response in verifiable sources.

Result: Gemini's response was accurate and complete. Its real-time grounding in web sources gave it an edge in trustworthiness, a critical factor for technical validation.

Cohere Command Output & Result:

Output: The response was accurate and focused heavily on a structured breakdown of the concepts. While it lacked the conversational fluidity of others, it provided a clear, bulleted list of differences and non-linearity sources. The code was also correct but less descriptive.

Result: Cohere’s output was highly structured and accurate, ideal for quick data extraction but less suited for a comprehensive, educational explanation. The focus on RAG made it more reliable for factual retrieval.

Meta Llama 3 Output & Result:

Output: A very strong, accurate response. The code snippet was arguably the most elegant and Pythonic of all, demonstrating a deep understanding of programming best practices. The theoretical explanation was concise and correct.

Result: Llama 3 demonstrated a high degree of technical competence, particularly in the code generation aspect. The open-source nature of the model is a significant advantage for users who require customizability.

## 5.2 Prompt 2: Quantum Computing
Prompt: "Describe the concept of quantum entanglement and its potential application in secure communication (e.g., Quantum Key Distribution). What is a qubit, and how does it differ from a classical bit? Provide a markdown table comparing the two, including their state representation, and list one potential security vulnerability in a basic QKD protocol."

### ChatGPT Output & Result:

Output: A clear, concise explanation of entanglement and qubits. The markdown table was formatted perfectly. It correctly identified the "eavesdropper problem" as a vulnerability and explained it well.

Result: Excellent performance. The response was accurate, complete, and perfectly formatted.

### Claude Output & Result:

Output: Provided a highly detailed and accessible explanation, using analogies to simplify complex concepts. The table was well-formatted, and the vulnerability explanation was robust and provided more context.

Result: Claude's strength in text generation shone here. The explanation was arguably the best for a non-expert, making it a powerful tool for educational purposes.

### Google Gemini Output & Result:

Output: Generated a good response with correct technical details and a clear table. It cited sources from reputable physics journals and institutions, adding significant credibility to the claims.

Result: Gemini's real-time knowledge and sourcing capability were a major benefit for this prompt, as quantum computing is a rapidly evolving field.

## 5.3 Prompt 3: Database Design
Prompt: "Design a database schema for a real-time multiplayer game. The schema must include tables for Users, Games, and GameSessions. For the GameSessions table, use JSON data types to store in-game events and state changes. Explain the relationships between these tables and provide a SQL query to retrieve all game sessions for a specific user, ordered by their start time."

### ChatGPT Output & Result:

Output: Generated a logical, well-normalized schema with correct foreign key relationships. The SQL query was syntactically correct and efficient. The use of a JSON column was implemented correctly in the conceptual schema.

Result: ChatGPT delivered a solid, standard-compliant solution that would be immediately useful to a database developer.

### Claude Output & Result:

Output: Provided a similar schema but with a more detailed explanation of why specific design choices were made (e.g., using a separate table for GameSessions to avoid bloating the Games table). The SQL query was also correct.

Result: Claude's output was excellent for its depth of explanation, making it a good "whiteboard" partner for brainstorming design decisions.

Meta Llama 3 Output & Result:

Output: The generated schema and SQL query were flawless. Llama 3 showed exceptional proficiency in handling structured data and code-based tasks, reflecting its strong performance on coding benchmarks.

Result: Llama 3 proved to be a formidable tool for practical, code-focused tasks, offering a high-quality, open-source alternative.
## Output
<img width="1024" height="608" alt="Screenshot 2025-09-09 092412" src="https://github.com/user-attachments/assets/48b68fb7-f1ee-4b37-b5ed-7f00af6c01e3" />


## Result
The landscape of prompting tools in 2024 is diverse and highly competitive. While all evaluated platforms demonstrated strong core capabilities in answering technical questions, their unique architectures and design philosophies lead to distinct strengths.

For most general technical tasks, a user can rely on ChatGPT or Llama 3. When dealing with extensive documents or nuanced discussions, Claude is the clear winner. For tasks requiring real-time data or source validation, Google Gemini is an indispensable tool. Finally, for enterprise-level applications and integration with private knowledge bases, Cohere Command offers a specialized, robust solution.

The ongoing evolution of these models underscores the importance of prompt engineering as a core skill. By understanding the specific strengths of each platform, engineers can select the right tool for the job, significantly enhancing productivity and the quality of their work.
<img width="2048" height="2048" alt="Gemini_Generated_Image_4aldh04aldh04ald" src="https://github.com/user-attachments/assets/f1bcab12-2cb4-42fd-a674-1e715a1606bc" />

