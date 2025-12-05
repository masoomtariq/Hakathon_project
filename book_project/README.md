# `book_project` Directory

This directory is the heart of the **Physical AI & Humanoid Robotics Textbook** project. It contains all the source code, documentation, and configuration for the interactive textbook.

## Subdirectory Breakdown

-   **`agents/`**: This directory contains the source code for the AI agents used in the project. For example, the `subagent_chapter_summarizer` is responsible for summarizing chapters of the textbook.

-   **`backend_rag_service/`**: This directory holds the FastAPI backend service. This service provides the API for the frontend, handling tasks like user authentication, content delivery, and interaction with the Qdrant vector database and Gemini LLM.

-   **`book_source/`**: This is the source code for the Docusaurus frontend. It includes all the React components, Markdown files for the textbook content, and styling for the website.

-   **`history/`**: This directory contains the history of prompts and interactions with the AI agents. This is useful for debugging and improving the agents over time.

-   **`specs/`**: This directory contains the specifications for the project, including the project plan, task lists, and other planning documents.

-   **`.claude/` and `.specify/`**: These directories contain configuration files and templates for the Claude and Specify development tools.
