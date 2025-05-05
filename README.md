🧠 AI-Powered Multilingual QA and MCQ Generator
Tech Stack: Python, Hugging Face Transformers, Mistral 7B, LLaMA, Streamlit, FastAPI, LangChain, Jinja2, PyPDF2, ReportLab

An intelligent system that generates context-based question answers and multiple-choice questions from multilingual or code-mixed input using LLaMA and Mistral 7B models.

🔹 Generates both QA pairs and MCQs with high contextual relevance
🔹 Handles multilingual input, including code-mixed languages (e.g., English-Hindi)
🔹 Preserves named entities and important keywords in outputs
🔹 Built with a modular architecture:
 • Streamlit UI for user interaction
 • FastAPI backend for efficient model inference
🔹 Incorporates an end-to-end ML pipeline from preprocessing to output generation
🔹 LangChain used for chaining prompts and logical flow
🔹 PDF export functionality using PyPDF2 and ReportLab
🔹 Uses Jinja2 templates placed in the templates/ folder to render HTML output
🔹 All generated files (e.g., final PDFs or HTML pages) are saved in the static/ folder for easy access
