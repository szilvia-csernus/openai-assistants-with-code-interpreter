# OpenAI Assistants API with Code Interpreter

> Notebooks for Maths Tutor and Mortgage Calculator

With the help of the Code Interpreter tool, the assistant can give accurate answers to questions which would be inaccurate by using the Chat Completion GPT on its own.
---

## How to run this project?

0. Prerequisites:

   - Make sure Python3 is installed.
   - If you don't have an account with OpenAI, create one here: https://openai.com/ then create a project API key under Dashboard / API keys.

1. Clone the project.

2. Create a virtual environment inside the project folder:

   `python -m venv venv`

3. Activate the virtual environment:

   Mac: `source venv/bin/activate`

   Windows: `venv\Scripts\activate`

4. Select interpreter in VSCode:

   (on Mac) - Cmd + Shift + P  ---> Select Interpreter ---> Select the created `venv` environment

   (on Windows) - 

5. Install the python dependencies:

   `pip install -r requirements.txt`


6. Create an `.env` file in the root folder and add your project's API key:

   ```
   OPENAI_API_KEY=your-unique-opanai-project-key
   ```

7. Run Jupyter Notebook:

   `jupyter notebook`

8. In the notebook, run the code snippets in the given/desired order.


## Credits


- OpenAI: https://openai.com
