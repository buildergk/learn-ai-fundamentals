## Setup Project

### Setup Project Folder
- Create a folder name that you would like. Example: `learn-ai-fundamentals`.
- Open the directory in the IDE of your choice. Cursor or VS Code preferred.

### Setup Environment File
- Create a `.env` file at the root of the directory. This file holds the secrets and variables related to the project environment.
- Add `OPENAI_API_KEY` variable in the environment file like below.
  ```
  OPENAI_API_KEY=sk-proj-XXXXXXXXXXXXXXXXXXXXXXXXXXXX
  ```
  Note: Replace _sk-proj-XXXXXXXXXXXXXXXXXXXXXXXXXXXX_ with your own key copied from [Setup OpenAI](./06-Setup-OpenAI.md)

### Setup Gitignore
- Create a `.gitignore` file at the root of the directory. This file holds the patterns of file and folders which needs to be ignored in Git.
- Add the environment file in the `.gitignore` file. The contents of the file should look like below.
  ```
  .env
  ```

