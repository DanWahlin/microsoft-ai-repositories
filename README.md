# Microsoft AI Repositories

This README aggregates Microsoft AI-related repositories, organized by AI use case to help users find relevant examples quickly. Each section contains a table with: Repository (linked to GitHub), Description (emphasizing AI aspects), Primary Language, and Technology (Microsoft products or Azure services used). Use the Searchable Index below to jump to sections based on your interests.

## Searchable Index

- **Python:** See [Generative AI](#generative-ai), [RAG (Retrieval-Augmented Generation)](#rag-retrieval-augmented-generation), [Chatbot Development](#chatbot-development), [AI Learning](#ai-learning), [Specialized AI Applications](#specialized-ai-applications).
- **C#:** See [RAG (Retrieval-Augmented Generation)](#rag-retrieval-augmented-generation), [Chatbot Development](#chatbot-development), [Power Platform Integration](#power-platform-integration), [AI Frameworks](#ai-frameworks).
- **JavaScript/TypeScript:** See [RAG (Retrieval-Augmented Generation)](#rag-retrieval-augmented-generation), [SharePoint & Teams Integration](#sharepoint--teams-integration), [GitHub Copilot](#github-copilot), [AI Frameworks](#ai-frameworks).
- **Azure OpenAI Service:** See [Generative AI](#generative-ai), [RAG (Retrieval-Augmented Generation)](#rag-retrieval-augmented-generation), [Chatbot Development](#chatbot-development), [AI Frameworks](#ai-frameworks).
- **Power Platform:** See [Power Platform Integration](#power-platform-integration).
- **SharePoint Framework:** See [SharePoint & Teams Integration](#sharepoint--teams-integration).
- **Specialized Technologies (e.g., PostgreSQL, KEDA):** See [Specialized AI Applications](#specialized-ai-applications).

## AI Use Cases

### Generative AI

Repositories focused on creating content using generative AI models.

| Repository                                            | Description                                              | Primary Language     | Technology                  |
|-------------------------------------------------------|----------------------------------------------------------|----------------------|-----------------------------|
| [Generative-AI-For-Beginners](https://github.com/Microsoft/Generative-AI-For-Beginners)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Tutorials covering generative AI concepts and implementation. | Python&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Azure OpenAI Service&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
| [openai-dotnet-samples](https://github.com/Azure-Samples/openai-dotnet-samples)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Samples for OpenAI in .NET, including specialized applications. | C#&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Azure OpenAI Service&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
| [phi-3cookbook](https://github.com/Microsoft/phi-3cookbook)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Demonstrates using the Phi-3 AI model for generative tasks. | Python&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | -&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |

### RAG (Retrieval-Augmented Generation)

Repositories demonstrating AI-driven search RAG capabilities, often with Azure AI Search.

| Repository                                            | Description                                              | Primary Language     | Technology                  |
|-------------------------------------------------------|----------------------------------------------------------|----------------------|-----------------------------|
| [aisearch-openai-rag-audio](https://github.com/Azure-Samples/aisearch-openai-rag-audio)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Demonstrates audio search using AI and RAG techniques.      | Python&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Azure Cognitive Services, Azure OpenAI Service |
| [azure-openai-rag-workshop](https://github.com/Azure-Samples/azure-openai-rag-workshop)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Workshop to build a RAG application using Azure OpenAI.     | Python&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Azure OpenAI Service&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
| [azure-search-openai-demo](https://github.com/Azure-Samples/azure-search-openai-demo)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Demonstrates semantic search with Azure Cognitive Search and Azure OpenAI. | Python&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Azure Cognitive Search, Azure OpenAI Service |
| [azure-search-openai-demo-csharp](https://github.com/azure-samples/azure-search-openai-demo-csharp)&nbsp;&nbsp;&nbsp;&nbsp; | Demonstrates semantic search with Azure Cognitive Search and Azure OpenAI in C#. | C#&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Azure Cognitive Search, Azure OpenAI Service |
| [azure-search-openai-demo-java](https://github.com/Azure-Samples/azure-search-openai-demo-java)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Demonstrates semantic search with Azure Cognitive Search and Azure OpenAI in Java. | Java&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Azure Cognitive Search, Azure OpenAI Service |
| [azure-search-openai-javascript](https://github.com/Azure-Samples/azure-search-openai-javascript)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Demonstrates semantic search with Azure Cognitive Search and OpenAI in JavaScript. | JavaScript&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Azure Cognitive Search, Azure OpenAI Service |

### Chatbot Development

Repositories for building AI-powered chatbots.

| Repository                                            | Description                                              | Primary Language     | Technology                  |
|-------------------------------------------------------|----------------------------------------------------------|----------------------|-----------------------------|
| [contoso-chat](https://github.com/Azure-Samples/contoso-chat)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Sample chatbot using AI technologies.                      | Python, C#&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Azure Cognitive Services&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
| [azure-openai-service-proxy](https://github.com/Microsoft/azure-openai-service-proxy)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Proxy to interact with Azure OpenAI Service for chatbot-like applications. | C#&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Azure OpenAI Service&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |

### AI Learning

Repositories providing educational content on AI and machine learning.

| Repository                                            | Description                                              | Primary Language     | Technology                  |
|-------------------------------------------------------|----------------------------------------------------------|----------------------|-----------------------------|
| [AI-For-Beginners](https://github.com/Microsoft/AI-For-Beginners)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Introductory tutorials on machine learning and AI.         | Python&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Azure Machine Learning&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
| [Data-Science-For-Beginners](https://github.com/Microsoft/Data-Science-For-Beginners)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Introductory data science tutorials with an AI focus.      | Python&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Azure Machine Learning&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
| [ML-For-Beginners](https://github.com/Microsoft/ML-For-Beginners)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Machine learning curriculum with practical lessons.        | Python&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Azure Machine Learning&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
| [Web-Dev-For-Beginners](https://github.com/Microsoft/Web-Dev-For-Beginners)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Web development tutorials, potentially with AI-powered apps. | JavaScript&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | -&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
| [Workshop-Interact-with-OpenAI-models](https://github.com/Microsoft/Workshop-Interact-with-OpenAI-models) | Workshop to interact with OpenAI models.                   | Python&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Azure OpenAI Service&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |

### Power Platform Integration

Repositories showcasing AI integration with Microsoft Power Platform.

| Repository                                            | Description                                              | Primary Language     | Technology                  |
|-------------------------------------------------------|----------------------------------------------------------|----------------------|-----------------------------|
| [powerplatform-samples](https://github.com/pnp/powerplatform-samples)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Samples demonstrating AI capabilities in Power Platform.   | C#, JavaScript&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Power Platform&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
| [powerplatform-snippets](https://github.com/pnp/powerplatform-snippets)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Code snippets for AI-related tasks in Power Platform.      | C#, JavaScript&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Power Platform&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |

### SharePoint & Teams Integration

Repositories integrating AI with SharePoint Framework or Microsoft Teams.

| Repository                                            | Description                                              | Primary Language     | Technology                  |
|-------------------------------------------------------|----------------------------------------------------------|----------------------|-----------------------------|
| [sp-dev-fx-aces](https://github.com/pnp/sp-dev-fx-aces)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | SharePoint Framework extensions with potential AI features. | JavaScript/TypeScript | SharePoint Framework&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
| [sp-dev-fx-extensions](https://github.com/pnp/sp-dev-fx-extensions)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | SharePoint Framework extensions, possibly AI-related.      | JavaScript/TypeScript | SharePoint Framework&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
| [sp-dev-fx-webparts](https://github.com/pnp/sp-dev-fx-webparts)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | SharePoint Framework web parts with possible AI functionalities. | JavaScript/TypeScript | SharePoint Framework&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
| [teams-dev-samples](https://github.com/pnp/teams-dev-samples)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Microsoft Teams development samples, which may include AI. | JavaScript/TypeScript | Microsoft Teams&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |

### GitHub Copilot

Repositories exploring GitHub Copilot, an AI pair programming tool.

| Repository                                            | Description                                              | Primary Language     | Technology                  |
|-------------------------------------------------------|----------------------------------------------------------|----------------------|-----------------------------|
| [CopilotAdventures](https://github.com/Microsoft/CopilotAdventures)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Interactive game to learn about GitHub Copilot.            | JavaScript&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | GitHub Copilot&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
| [Mastering-GitHub-Copilot-for-Paired-Programming](https://github.com/Microsoft/Mastering-GitHub-Copilot-for-Paired-Programming) | Tutorials for mastering GitHub Copilot for paired programming. | Documentation&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | GitHub Copilot&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |

### AI Frameworks

Repositories demonstrating AI frameworks like Semantic Kernel or LangChain.

| Repository                                            | Description                                              | Primary Language     | Technology                  |
|-------------------------------------------------------|----------------------------------------------------------|----------------------|-----------------------------|
| [ai-samples](https://github.com/dotnet/ai-samples)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Demonstrates AI and machine learning in .NET.              | C#&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Azure Cognitive Services&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
| [SemanticKernelCookBook](https://github.com/Microsoft/SemanticKernelCookBook)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Demonstrates Semantic Kernel for AI applications.          | C#&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Azure OpenAI Service&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
| [langchainjs-quickstart-demo](https://github.com/Azure-Samples/langchainjs-quickstart-demo)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Demonstrates using LangChain.js for AI applications.       | JavaScript/TypeScript | Azure OpenAI Service&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
| [serverless-ai-langchainjs](https://github.com/Azure-Samples/serverless-ai-langchainjs)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Demonstrates a serverless AI app with LangChain.js.        | JavaScript/TypeScript | Azure Functions, Azure OpenAI Service |

### Specialized AI Applications

Repositories for more specialized AI applications, such as audio search or database assistance.

| Repository                                            | Description                                              | Primary Language     | Technology                  |
|-------------------------------------------------------|----------------------------------------------------------|----------------------|-----------------------------|
| [azure-devops-release-notes](https://github.com/Azure-Samples/azure-devops-release-notes)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Generates release notes for Azure DevOps using AI.         | Python&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Azure OpenAI Service&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
| [agent-openai-python-prompty](https://github.com/Azure-Samples/agent-openai-python-prompty)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Demonstrates an AI agent using OpenAI and Prompty.         | Python&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Azure OpenAI Service&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
| [copilot-pg](https://github.com/Microsoft/copilot-pg)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | AI-powered extension for PostgreSQL to assist DBAs.        | C&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | PostgreSQL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
| [Fabric-Readiness](https://github.com/Microsoft/Fabric-Readiness)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Toolkit to assess readiness for Microsoft Fabric with AI capabilities. | PowerShell&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Microsoft Fabric&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
| [aks-store-demo](https://github.com/Azure-Samples/aks-store-demo)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Microservices app for AKS demos, potentially with AI components. | C#, Python&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Azure Kubernetes Service&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
| [carbon-aware-keda-operator](https://github.com/Azure/carbon-aware-keda-operator)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Operator for carbon-aware scaling with KEDA, potentially using AI. | Go&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | KEDA&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
| [cli-microsoft365](https://github.com/pnp/cli-microsoft365)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | CLI tool for Microsoft 365, potentially for AI-driven workflows. | JavaScript/TypeScript | Microsoft 365&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
