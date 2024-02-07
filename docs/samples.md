---
label: "Samples"
icon: list-unordered
order: 20
---

# AskTheCode Samples

Welcome to the Samples page of AskTheCode! Here, you'll find various examples showcasing the interaction of the ChatGPT plugin with different GitHub repositories. These samples will help you understand how AskTheCode can assist you in answering questions related to your repositories.

!!!info Note
As we continue to enhance AskTheCode, more samples will be added to this page.
!!!

---

### Refit Library's HTTP Proxy Client Generation

In this sample, we dive into understanding how the [Refit](https://github.com/reactiveui/refit/) library generates the HTTP proxy client internally. 

[View Sample](https://chat.openai.com/share/9cb9ff0a-078f-4011-9c15-d4d21f6e5c0e)

---

### Langchain and ChatGPT Plugins Integration

Lets assume we are targeting to find out about integrating ChatGPT plugin into the Langchain pipeline. For that we can provide the link to the [docs directory in the Langchain Github repository](https://github.com/langchain-ai/langchain/tree/master/docs) and ask ChatGPT to look for the details of integration. Since the repository of the Langchain is quite huge, the prompt should be pretty specific, something like:

```Prompt
https://github.com/langchain-ai/langchain/tree/master/docs

Langchain is capable of integrating ChatGPT Plugins into the pipeline. For this it uses the specific tool.
Please give me an example of using this tool
```

This will give us a sample of how to integrate Langchain with the GPT plugin:

![](/resources/usage/search/langchain-sample-no-search.png)

---

### Documentation Generation

This conversation demonstrates the use of AskTheCode's file creation and update features within a GitHub repository. It showcases a step-by-step process for analyzing a repository's structure, creating new directories and files, and updating existing files with specific annotations and documentation content. The interaction shows how users can efficiently manage GitHub files, including writing and applying documentation updates directly through conversational commands.

[View Sample](https://chat.openai.com/share/8f02d663-4d3d-4ac4-8319-2316974e1e1b)