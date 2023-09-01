## Dependencies and Installation
----------------------------
To install the PDF Prompting App, please follow these steps:

1. Clone the repository to your local machine.

2. Install the required dependencies by running the following command (preferable to use a Python environment like Venv or Anaconda https://realpython.com/python-virtual-environments-a-primer/):
   ```
   pip install -r requirements.txt
   ```

3. Obtain an API key from OpenAI and add it to the `.env` file in the project directory.
```commandline
OPENAI_API_KEY=your_secrit_api_key
```

4. Run the `main.py` file using the Streamlit CLI. Execute the following command in the terminal:
   ```
   streamlit run app.py
   ```
5. Once the app is open, click on the "Browse Files" Button on the left hand side, find the 4 papers listed under "resources" in this repository, click the "Process" button.

6. Type your prompt into the chat bar and ask away! Feel free to include any other resources you would like to utilize to finetune the model.

## License
-------
This repository is released under the [MIT License](https://opensource.org/licenses/MIT).