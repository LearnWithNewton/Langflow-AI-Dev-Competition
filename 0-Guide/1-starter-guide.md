### Learning Reference

> https://www.youtube.com/watch?v=ou-BDb_3zLc

> https://www.youtube.com/watch?v=rz40ukZ3krQ

> https://www.youtube.com/watch?v=2TJxpyO3ei4

### Starter Guide to get started with Langflow

1. Open a terminal or command prompt.
2. Navigate to your project directory (or where you want the environment). 
    - `cd /path/to/your/project`
3. Create the environment : 
    - `python -m venv your_environment_name` e.g., `python -m venv langflow`
4.  Activate the environment.
    - On Windows: `myenv\Scripts\activate` e.g., `langflow\Scripts\activate`
    - On macOS/Linux: `source myenv/bin/activate`

5. you should see your environment activated as 
    - `(your_environment_name) /path/to/your/project` e.g., `(langflow) F:\Codes\Langflow>`
6. Install [Microsoft visual C++  14.0]( https://visualstudio.microsoft.com/visual-cpp-build-tools/) before installing `langflow` package

7. Run below command to install langflow
    - `pip install langflow`
8. To run Langflow, enter the following command (locally)
    - `python -m langflow run`

9. Running AstraDB
    - Refer this [video](https://www.youtube.com/watch?v=ou-BDb_3zLc) to how to get AstraDB account created on DataStax plateform
    - use the AstraDB token and endpoint url in your langflow AstraDB component

9. Installing & Running ChromaDB
    - `pip install chromadb`
    - running chroma db `chroma run --host localhost --port 8090 --path ./chroma_data`

10. [Download](https://ollama.com/library/llama3.1) and Install Ollama3.1 8b model 
    - Run Ollama model : `ollama run llama3.1`

