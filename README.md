# 🦜🔗 LangChain Experiments

A collection of hands-on experiments and demos exploring LangChain's core capabilities including OpenAI function calling, structured output parsing, LCEL (LangChain Expression Language) chaining, and real-world information extraction.

---

## 📁 Project Structure

### `1_OpenAiFunctionCalling_LangChain.ipynb`
> **Basic OpenAI Function Calling Example**
- Demonstrates how to use OpenAI’s `function_call` feature with a simple weather-fetching function.
- Shows how to parse the response and conditionally call a backend function.
- Great starting point for understanding LLM-tool interaction.

---

### `2_LCEL_LangChain.ipynb`
> **LangChain Expression Language (LCEL) Workflow**
- Introduces LCEL syntax for building declarative pipelines using LangChain.
- Combines prompts, models, and parsers using `|` operator.
- Ideal for chaining modular components together for clarity and maintainability.

---

### `3_OpenAiFunctionCalling_in_LangChain.ipynb`
> **Function Calling in LangChain Style**
- Deep dive into using `ChatOpenAI` with function specs.
- Uses LangChain’s interface to register tools/functions with Pydantic models.
- Parses LLM outputs into structured objects automatically.

---

### `4_tagging_and_extraction_langchain.py`
> **Structured Tagging & Information Extraction**
- Uses LangChain’s `convert_pydantic_to_openai_function` for structured tagging (e.g., sentiment, language).
- Extracts nested information (e.g., people, papers) from raw text or web pages.
- Demonstrates document loading, text splitting, and chain composition for scalable info extraction.
- Also includes real-world web scraping (e.g., from Lilian Weng's agent blog post).

---

## 🛠️ Setup

```bash
pip install openai langchain python-dotenv
