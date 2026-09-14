## CMD+C will stop running e.g. streamlit home.py and bring the terminal back to normal.

1. Create README.md file for taking notes

## Saving Code
1. On Left-hand side of screen, go to "source control"
2. client to add files to the commit (i.e., stage changes)
3. Enter a commit message
4. Click commit
5. Click sync
6. Check the Github repository to confirm it has synced


## Setting up Environment
1. Create virtual enironment (in terminal)
> python -m venv .venv
2. Activate virtual environment (in T)
> source .venv/bin/activate
3. to install libraries/dependencies, create a requirements.txt file
4. add openai, streamlit, python-dotenv to requirements.txt file
5. install dependencies by referring to requirements.txt file
 >pip install -r requirements.txt
6. Create a .env file
>make sure .env is grayed out or gitignored (type .env in the gitignore file)
7. Add secrets to .env
> OPENAI_API_KEY="key"
8. Now commit/resync
