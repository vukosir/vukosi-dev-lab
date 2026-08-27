# Python projects

Scripts, automation, scrapers, data analysis, small tools.

Each project gets its own folder with a `requirements.txt` so it can be set up
with:

```bash
python -m venv venv
source venv/bin/activate      # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

Virtual environments are ignored by the root `.gitignore`, so never commit
`venv/`. Commit the requirements file instead.
