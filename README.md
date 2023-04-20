# Personal Browsing Embeddings Extension

This browser extension enables users to capture and encode web content or selections, creating a personal embeddings database. The extension features a chatbot for searching the database, finding similar content, and using language models (e.g., GPT-4) for analysis. Use it to efficiently access and interpret past research.

## Table of Contents

- [Features](#features)
  - [Optional Features](#optional-features)
- [User Experience](#user-experience)
- [Example Use Case: Art History Student](#example-use-case-art-history-student)
- [Development Steps](#development-steps)
- [Contribute](#contribute)

## Features

- Scrape and encode web page content or highlighted sections
- Store embeddings in a personal database
- Query the embeddings database using a chatbot interface
- Perform similarity searches within the database
- Leverage language models for content interpretation

### Optional Features

- Always-On Encoding: Constantly record all content during normal browsing.
- History Encoder: Encode all content from browser history.
- URL Encoder: Scrape and encode content from a URL or list of URLs.
- Vector Database Options: Choose between local or hosted vector database service.
- Encoder Options: Use open source or API-based encoder.
- Retrieval Only vs. LLM Interpretation: Choose retrieval only or language model interpretation.
- Selective Deletion: Delete specific embeddings and associated metadata.

## User Experience

Use the extension to efficiently capture, encode, and retrieve web content:

- **Installation:**
  - Install the extension from your browser's extension marketplace (e.g., Chrome Web Store, Firefox Add-ons).
  - An extension icon appears in your browser's toolbar for easy access.

- **Content Encoding:**
  - Highlight text or navigate to a page, and click the extension icon to encode and store content.
  - The encoded content and metadata (e.g., link reference) are stored in your database.

- **Chatbot Search:**
  - Use the chatbot to search your database for content related to your query.
  - The chatbot displays matching results and links to original sources.

- **Language Model (Optional):**
  - Enable language model interpretation for comprehensive summaries and insights.
  - The chatbot passes your query to a language model (e.g., GPT-4) for interpretation.

- **Database Management:**
  - Control, organize, and delete content in your database through the extension's interface.

## Example Use Case: Art History Student

As an art history student researching Renaissance painters, use the extension to capture and retrieve information:

### Recording Research Content

- Use the extension to capture content from online sources about Renaissance painters.
- Store the content and metadata (e.g., link references) in your database.

### Remembering Details and Gaining Insights

- Query the chatbot for details about Leonardo da Vinci's painting techniques.
- Get matching results, original source links, and language model interpretations.

### Advancing Study Goals

- Make connections between painters, techniques, and movements with easy access to information.
- Use insights for class discussions, essays, and presentations on Renaissance art.

The extension supports your academic research and helps you gain valuable
insights.

## Development Steps

- **Browser Extension:**
  - Create an extension compatible with browsers (e.g., Chrome, Firefox).
  - Enable scraping of web page content or user-selected text.
  - Add a user interface with an activation button.

- **Embeddings Encoder:**
  - Select an embedding model (e.g., Word2Vec, BERT) and decide on pre-trained or custom embeddings.
  - Implement encoding to convert content into embeddings.

- **Database:**
  - Design a database for storing embeddings, metadata (e.g., link references), etc.
  - Decide on database location (e.g., local storage, cloud) and ensure security.

- **Chatbot and Search:**
  - Build a chatbot interface for user queries.
  - Implement similarity search to find related content in the database.
  - Integrate an external language model (e.g., GPT-4) for query interpretation.

- **User Experience and Privacy:**
  - Create a user-friendly interface for installation, database management, and chatbot interaction.
  - Address privacy concerns and obtain user consent for data usage.

- **Testing and Deployment:**
  - Test the extension for functionality, performance, and usability.
  - Fix bugs and issues found during testing.
  - Deploy on browser extension marketplaces (e.g., Chrome Web Store, Firefox Add-ons).

- **Documentation and Support:**
  - Provide documentation for installation, usage, and troubleshooting.
  - Offer support channels (e.g., email, forum) for user assistance and issue reporting.

## Contribute

Explore the repository, learn about the extension, and contribute to its development. Thank you for your interest in the Personal Browsing Embeddings Extension!
