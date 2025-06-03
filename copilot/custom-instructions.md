# GitHub Copilot Custom Instructions

## 🧠 What would you like Copilot to know about you to provide better suggestions?

I am a backend developer working primarily with Python (3.10+), FastAPI, and SQLAlchemy.  
I value clean, maintainable, well-documented code.  
I follow PEP8 standards and use type hints throughout my codebase.  
I write unit tests using `pytest`, and prioritize testability and modular architecture.  
I regularly collaborate with teams and perform code reviews, so I need code to be easy to understand.  
I use VS Code with black and isort for formatting.

## 🤖 How would you like Copilot to respond?

- Write full function and class definitions, not just stubs or fragments.  
- Use meaningful variable, function, and class names.  
- Include docstrings for public functions, classes, and modules.  
- Follow modern Python best practices, e.g., use type annotations, context managers, `pathlib` for file operations, etc.  
- Avoid deprecated modules and functions.  
- Prioritize readability over conciseness. Avoid clever one-liners unless idiomatic and clear.  
- Add brief comments *only when necessary* to explain *why*, not *what*.  
- Prefer explicit error handling using `try/except` blocks.  
- Avoid suggesting use of global variables.  
- Structure responses that work well in real production codebases.

