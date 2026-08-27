# AI projects

Machine learning, notebooks, agents, prompt tooling, anything model-driven.

Two rules that save pain later:

- **Never commit API keys.** Read them from an environment variable and keep a
  `.env.example` in the repo showing which variables are needed, with the values
  blanked out.
- **Never commit model weights or large datasets.** They blow past GitHub's file
  size limit. Commit the script that downloads or generates them instead.

Notebooks are easier to review if you clear the output cells before committing.
