# TNG Script Explorer Chatbot

## Overview

Star Trek: The Next Generation spans seven seasons filled with philosophical debates, technical challenges, and memorable dialogue. This project explores a simple idea:

**What if you could ask questions about TNG and get answers based on real episode scripts—while also checking facts and doing simple calculations when needed?**

The **TNG Script Explorer Chatbot** is an experimental assistant that combines script search, web lookup, and basic reasoning tools to give clearer, more reliable answers.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
  - [The Problem](#the-problem)
  - [What This Project Solves](#what-this-project-solves)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Who It’s For](#who-its-for)
- [Project Structure](#project-structure)
- [Data Sources](#data-sources)
- [Limitations & Future Vision](#limitations--future-vision)
- [Contributing](#contributing)
- [License](#license)

## Features

### The Problem

Fans and researchers often face several challenges when exploring Star Trek: The Next Generation:
* Scripts and transcripts are spread across many websites.
* Finding specific moments or quotes can be time-consuming.
* Regular chatbots may guess or invent answers.
* Some questions require extra context, like episode air dates, counts, or comparisons.

In short, no single tool provides grounded answers, background context, and basic reasoning together.

### What This Project Solves

**TNGRAGChatbot** combines multiple tools to provide reliable answers:

*   **Script Search (RAG)** – Finds relevant TNG scenes and dialogue to ground responses.
*   **Web Search** – Retrieves factual information from public sources when needed (e.g., episode air dates, production info).
*   **Math & Logic Helper** – Handles calculations, comparisons, and counts accurately.

Together, these capabilities let users ask anything from *“What did Picard say about the Prime Directive?”* to *“How many episodes feature Data learning about humor?”*, and get precise, grounded answers.

## Installation

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/MLProjects.git
    cd MLProjects
    ```

2.  **Create a virtual environment** (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the chatbot:

```bash
python main.py
```

*Note: Usage instructions will be updated as the project develops.*

## How It Works

The chatbot uses a combination of help tools working together:

### 1. Script Search (RAG)
When you ask a question about TNG, the chatbot first searches through the episode transcripts to find relevant scenes or dialogue. It then builds its response using those exact passages, instead of guessing.

### 2. Web Search
For questions that go beyond the scripts—such as episode air dates, production details, or historical context—the chatbot can briefly look up reliable public information to support the answer.

### 3. Math & Logic Helper
Some questions involve counting episodes, comparing seasons, or doing simple calculations. A built-in math helper ensures these answers are accurate instead of estimated.

**Together, these tools help the chatbot think before it speaks.**

## Who It’s For

*   **Star Trek fans** who want a conversational companion.
*   **Writers** studying dialogue or storytelling.
*   **People exploring ethics, leadership, and technology** in TNG.
*   **Anyone curious** about episode details, quotes, or numeric facts.

## Project Structure

```text
MLProjects/
├── README.md          # Project documentation
├── requirements.txt   # Python dependencies (coming soon)
├── src/               # Source code (coming soon)
│   ├── app.py         # Main application entry point
│   └── ...
└── data/              # Data files (transcripts, etc.)
```

## Data Sources

*   Fan-created transcripts of *Star Trek: The Next Generation*.
*   Publicly available web sources for factual context.

*All script content is used locally for personal and educational purposes.*

## Limitations & Future Vision

### Limitations
*   The chatbot only knows what it can find in the transcripts or public sources.
*   It does not replace official reference materials.
*   Other Star Trek series are not included yet.

### Future Vision
*   Adding more Star Trek series.
*   Creating character-specific personalities.
*   Improving conversational flow.
*   Making the chatbot feel more like the Enterprise computer.
*   Expanding research and reasoning abilities.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request
