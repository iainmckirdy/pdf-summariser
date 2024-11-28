# PDF Summariser

## Outline:
A simple CLI application for summarising PDFs with llms, that can also run locally with Ollama.

The program is particularly useful for providing brief summaries of large text documents such as research papers and academic articles.

This program runs using the LangChain framework.

## Details and Usage:
- **Running the Script**: Enter an OpenAI API key in the .env file then execute ``python main.py PDFpath`` or to run using a local llm execute ``python main.py local PDFpath``
- Running the program locally will require the device to have Ollama installed along with the llama3 model.
    - slower results can be expected when running the program locally

### Note on Language Models:
By default OpenAIs GPT-3.5-turbo is used for the sake of speed and cost, however this can be changed within main.py.

Similarly the default local model can be changed.
