# AI Curated Link List

## Contents
1. [AI Development Frameworks](#ai-development-frameworks)
2. [AI Benchmarks and Evaluation](#ai-benchmarks-and-evaluation)
3. [AI-Driven Tools for Software Development](#ai-driven-tools-for-software-development)

---

## AI Development Frameworks

- **[Composio SWE Kit Introduction](https://docs.composio.dev/swekit/introduction?s=09)**  
  The SWE Development Kit (SweKit) is a powerful framework within the Composio ecosystem, designed to facilitate the creation of Software Engineering agents. It features integration with GitHub, repo indexing, and Docker-based environments for secure agent execution. SweKit provides tools for agent scaffolding, customizable tools, and benchmarking to evaluate agent performance. It also supports frameworks like CrewAI and LlamaIndex, offering isolated workspaces for efficient agent operations.

## AI Benchmarks and Evaluation

- **[BigCode Bench](https://bigcode-bench.github.io/)**  
  BigCode Bench is a comprehensive evaluation platform that rigorously tests large language models (LLMs) on practical and complex programming tasks. It provides a challenging suite of benchmarks that simulate real-world coding scenarios, assessing the models' ability to understand, generate, and optimize code across various programming languages. BigCode Bench aims to push the boundaries of LLM capabilities, offering valuable insights into their performance in professional software development environments.

- **[LMSYS Chatbot Arena](https://lmarena.ai/)**  
  LMSYS Chatbot Arena is an open platform designed for the crowdsourced evaluation of large language models (LLMs). It enables users to compare different LLMs through pairwise interactions, contributing to a vast dataset of over 1,000,000 human evaluations. Using the Bradley-Terry model, LMSYS ranks these models on an Elo scale, providing a clear and quantitative assessment of their performance. This platform thrives on community participation, encouraging users to cast their votes and help refine the rankings. For a deeper understanding of the methodology, you can refer to the detailed analysis in their accompanying research paper.

- **[LiveBench](https://livebench.ai/?s=09)**  
  LiveBench is a cutting-edge benchmark platform designed to evaluate large language models (LLMs) with a focus on avoiding test set contamination and ensuring objective scoring. It features monthly releases of new questions derived from recently-released datasets, arXiv papers, news articles, and IMDb movie synopses, minimizing the risk of pre-exposure. Each question comes with verifiable, objective ground-truth answers, allowing for accurate, automated scoring without reliance on an LLM judge. LiveBench currently includes 18 diverse tasks across 6 categories, with plans to introduce even more challenging tasks over time.

- **[Artificial Analysis](https://artificialanalysis.ai/)**  
  Artificial Analysis provides benchmarking and related information to help people and organizations choose the right model for their specific use cases and decide which provider to use. The platform highlights the trade-offs between different models and providers, including factors such as model quality, price, output speed, latency, context window, and other key dimensions. By focusing on how users intend to utilize the model, Artificial Analysis assists in making informed decisions tailored to their needs.

- **[Salesforce CRM Benchmark](https://www.salesforceairesearch.com/crm-benchmark)**  
  Salesforce has developed the world's first LLM benchmark specifically for CRM, aimed at assessing the efficacy of generative AI models for business applications. This benchmark evaluates LLMs across sales and service use cases, focusing on accuracy, cost, speed, and trust & safety. What sets this benchmark apart is its reliance on real CRM data and human evaluations conducted by both Salesforce employees and external customers. The benchmark is grounded in real-world datasets from Salesforce and customer operations, providing a rigorous and practical assessment tool for businesses.

- **[Berkeley Function Calling Leaderboard V2](https://gorilla.cs.berkeley.edu/leaderboard)**  
  The Berkeley Function Calling Leaderboard (BFCL) V2 evaluates large language models (LLMs) on their ability to accurately call functions or tools. The leaderboard ranks models based on overall accuracy, latency, and cost. It includes detailed metrics such as Abstract Syntax Tree (AST) evaluation, execution of APIs, and irrelevance detection. The leaderboard also features interactive visualizations like a comparison chart and error type analysis, providing a comprehensive overview of LLM performance in function calling tasks.

## AI-Driven Tools for Software Development

- **[Agentless](https://github.com/OpenAutoCoder/Agentless)**  
  Agentless is a tool designed to solve software development problems using a two-phase process of fault localization and automated repair, without relying on an AI agent. It identifies code issues and generates patches through hierarchical localization and test filtering, making it an efficient solution for fixing bugs.

- **[Aider](https://aider.chat/)**  
  Aider is an AI-powered coding assistant that integrates with your development environment. It helps you write, refactor, and debug code more efficiently by understanding natural language instructions and providing relevant code suggestions. Aider supports multiple programming languages and can be used directly from the command line or integrated into your favorite code editor.

- **[AutoCodeRover](https://github.com/nus-apr/auto-code-rover)**  
  AutoCodeRover is a framework designed for automatically exploring and understanding software repositories. It facilitates tasks like code summarization, documentation generation, and repository visualization by utilizing static analysis and AI-based techniques. This tool aims to improve the efficiency of developers in navigating and comprehending large codebases.

- **[Genie](https://cosine.sh/genie)**  
  Genie is an advanced AI software engineer capable of autonomously solving bugs, building features, and refactoring code. Achieving a 30% evaluation score on the SWE-Bench, it functions like a collaborative colleague rather than just a copilot, offering full autonomy or paired interactions with users.

- **[Amazon Q Developer Guide](https://docs.aws.amazon.com/amazonq/latest/qdeveloper-ug/software-dev.html)**  
  Amazon Q Developer is designed to assist developers by generating code, providing implementation plans, and offering in-depth support for various coding tasks. It works within popular IDEs like Visual Studio Code and JetBrains, integrating directly into the development workflow. Developers can interact with Amazon Q using natural language commands to generate code, debug, refactor, and even optimize existing code. This tool is particularly useful for accelerating development processes, maintaining code quality, and integrating best practices seamlessly into the development cycle.

- **[Cursor](https://www.cursor.com/)**  
  Cursor.com is a platform that offers an AI-powered code editor designed to enhance productivity and collaboration for developers. It integrates artificial intelligence to assist in writing, refactoring, and debugging code, acting as a pair programmer that can significantly accelerate development processes. The platform aims to provide a seamless coding experience by integrating AI directly into the code editor, making it a valuable tool for teams and individual developers looking to optimize their coding workflows.

- **[Supermaven](https://supermaven.com/)**  
  Supermaven is an AI-powered code completion tool that aims to enhance developer productivity by providing fast, accurate code suggestions. It features a large context window, allowing it to understand and adapt to the unique structure of a codebase, leading to more relevant and precise code completions. Supermaven integrates seamlessly with popular IDEs like Visual Studio Code and JetBrains, and it's positioned as a powerful alternative to tools like GitHub Copilot, offering superior speed and context awareness.

- **[GitHub Copilot](https://github.com/features/copilot)**  
  GitHub Copilot is an AI-powered code completion tool developed by GitHub and OpenAI. It assists developers by suggesting entire lines or blocks of code based on the context of the current project. Integrated directly into popular IDEs like Visual Studio Code, Copilot enhances developer productivity by understanding the code context and providing intelligent code suggestions, making it an invaluable tool for both novice and experienced developers.

- **[Project IDX](https://idx.dev/)**  
  Project IDX is an AI-assisted workspace for full-stack, multiplatform app development in the cloud. With support for a broad range of frameworks, languages, and services, alongside integrations with your favorite Google products, IDX streamlines your development workflow so you can build and ship apps across platforms with speed, ease, and quality.

- **[Replit](https://replit.com/)**  
  Replit is an AI-powered software development and deployment platform that enables developers to build, share, and ship software quickly. Replit supports a collaborative environment, allowing users to code, test, and deploy directly from the platform, making it an ideal tool for rapid development.

- **[V0](https://v0.dev/chat)**  
  V0 is a generative user interface system by Vercel powered by AI. It generates copy-and-paste friendly React code based on shadcn/ui and Tailwind CSS that developers can use in their projects. This tool simplifies the process of building user interfaces by providing ready-to-use, customizable components, enabling faster and more efficient development.

---
