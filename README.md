# Personal Browsing Embeddings Extension

Welcome to the GitHub repository for the Personal Browsing Embeddings Extension! This browser extension allows users to selectively scrape and encode web page content or highlighted sections, and store the generated embeddings in a personal database. Additionally, the extension includes a chatbot interface for querying the local embeddings database, performing similarity searches, and leveraging language models for content interpretation. Enhance your browsing experience and retrieve valuable information with ease!

## Table of Contents

- [Objective](#objective)
- [Features](#features)
  - [Optional Features](#optional-features)
- [Development Steps](#development-steps)
- [User Experience](#user-experience)
- [Contribute](#contribute)

## Objective

Develop a browser extension that enables users to selectively scrape and encode web page content or selections, and store the generated embeddings in a personal database. Additionally, the extension will include a chatbot that can query the local embeddings database for similarity searches and pass the query, along with similar results, to a language model (e.g., GPT-4) for interpretation.

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

## Development Steps

- Browser Extension Development
  - Develop a browser extension compatible with popular web browsers (e.g., Chrome, Firefox).
  - Implement functionality for scraping entire web page content or user-selected content.
  - Provide a user interface for interacting with the extension, including an activation button.
- Embeddings Encoder
  - Choose an appropriate embedding model (e.g., Word2Vec, BERT) and decide whether to use pre-trained embeddings or train a custom model.
  - Implement the encoding process to convert scraped content into embeddings.
- Personal Browsing Embeddings Database
  - Design a database structure for efficient storage and retrieval of embeddings, metadata (e.g., link references), and any other relevant information.
  - Determine where the database will be stored (e.g., local storage, cloud storage) and ensure data security.
- Chatbot and Similarity Search
  - Develop a chatbot interface that allows users to interact with the extension and perform queries.
  - Implement similarity search functionality to find content similar to the user's query within the embeddings database.
  - Establish communication with an external language model (e.g., GPT-4) to provide comprehensive interpretations of queries and similar results.
- User Experience and Privacy
  - Design an intuitive user interface for installing the extension, managing the embeddings database, and interacting with the chatbot.
  - Address privacy concerns by providing clear information about data usage and collection, and obtaining user consent where necessary.
- Testing and Deployment
  - Conduct thorough testing of the browser extension to ensure proper functionality, performance, and usability.
  - Address any bugs or issues identified during testing.
  - Prepare the extension for deployment on browser extension marketplaces (e.g., Chrome Web Store, Firefox Add-ons).
- Documentation and Support
  - Create comprehensive documentation to guide users on how to install, use, and troubleshoot the extension.
  - Provide support channels (e.g., email, forum) for users to seek assistance or report issues.

## User Experience

As a user of the browser extension, you'll have a seamless and intuitive experience that enhances your browsing and information retrieval capabilities:

- **Installation and Setup:**
  - Easily install the extension from your browser's extension marketplace (e.g., Chrome Web Store, Firefox Add-ons).
  - Upon installation, an extension icon appears in your browser's toolbar, and you may be guided through a brief setup process to configure your preferences.

- **Web Content Encoding:**
  - While browsing the web, you can use the extension to capture and encode the content of web pages or specific sections you find interesting.
  - To capture content, simply highlight the desired text or navigate to the page you wish to encode, and click on the extension icon in your browser toolbar.
  - The extension will encode the selected content using embeddings and store it, along with associated metadata (e.g., link reference), in your personal browsing embeddings database.

- **Chatbot Interaction and Similarity Search:**
  - The extension features a chatbot that you can interact with to perform similarity searches within your embeddings database.
  - To initiate a search, simply type your query into the chatbot interface, and the chatbot will perform a similarity search to find content related to your query.
  - The chatbot will display results that closely match your query, including links to the original web pages for your reference.

- **Language Model Interpretation (Optional):**
  - If you choose to enable language model interpretation, the chatbot can enhance your search results by providing comprehensive interpretations and summaries.
  - After entering your query, the chatbot will pass the query and similar results to an external language model (e.g., GPT-4) for interpretation.
  - The chatbot will then present you with a rich response that incorporates the language model's insights and understanding of the content.

- **Managing Your Database:**
  - You have full control over your personal embeddings database, including the ability to view, organize, and delete stored content.
  - Through the extension's user interface, you can easily manage your database and ensure that it remains relevant and useful to your browsing experience.

## Contribute

We invite you to explore the repository, learn more about the extension, and contribute to its development. Thank you for your interest in the Personal Browsing Embeddings Extension!
