# AskDoc

This bot understands your medical concerns and helps diagnose them. Here is what you can do:

1. Ask for your health-related questions.
2. Send a medical report and ask questions based on that

Components

1. **ChatGPT (Vision)**: This is given a prompt to act like a doctor and do diagnostics
2. **Tesseract**: To extract information from PDF and image reports
3. **Validation agent** (Coming soon): This validates input/output
4. **Memory** stored in NumPy array. This memory is queried for information when the user asks for a query
5. **Summarizer** that summarizes after 100 turns and stores that summary in the memory
