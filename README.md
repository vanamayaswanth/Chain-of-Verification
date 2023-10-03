

# Chain of Verification (CoVe)

CoVe is a Python project that leverages OpenAI's GPT-3.5 and other language models to create a chain of verification for answering questions, fact-checking statements, and generating verified responses. This project is designed to assist in providing well-researched and factually accurate answers to questions.

## Table of Contents

- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Custom Memory](#custom-memory)
- [Contributing](#contributing)


## Getting Started

CoVe allows you to follow a structured process to answer questions and verify information. The process consists of several steps, including drafting an initial response, planning verification questions, answering those questions, and generating a final verified response.

## Prerequisites

Before using CoVe, ensure you have the following prerequisites installed:

- Python 3.8.2 < 3.9 or later 
- Pip for package management

## Installation

To install CoVe and its dependencies, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/vanamayaswanth/Chain-of-Verification.git
   cd CoVe
   ```

2. Create a virtual environment (recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use: venv\Scripts\activate
   ```

3. Install the required Python packages:

   ```bash
   pip install -r req.txt
   ```

## Usage

To use CoVe, follow these steps:

1. Input your OpenAI API key when prompted.

2. Run the CoVe application:

   ```bash
   python CoVe.py
   ```

3. Enter your question or statement when prompted.

4. CoVe will guide you through the verification process and provide a final verified response.

## Custom Memory

CoVe supports custom memory implementations for storing and retrieving information during verification. You can customize the memory functionality by implementing a custom memory class, as shown in the provided example.

## Contributing

Contributions are welcome! If you have ideas for improvements or encounter issues, please open an issue or submit a pull request.


## Note


purely reflecting the langchain docs fix bug and improvement




