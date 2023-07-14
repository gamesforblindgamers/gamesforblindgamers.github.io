# Games for Blind Gamers

Our [public website](https://gamesforblindgamers.github.io/)

# Developer Enviornment Setup

Install Python:

```bash
cd source
pip3 install -r requirements.txt
```

You may wish to install VSCode and the Markdown Extended Preview plugin to preview your changes.

## Making Changes

- Edit one or more content files in the `content` directory, e.g. `content/pages/about.md`
- Preview your changes with Markdown Extended Preview
- Generate the final HTML by running `python -m pelican` from the `source` directory
- Preview the full website by running `python -m http.server` from the `output` directory, and opening a browser to `localhost:8000`
- When you're satisfied with your changes, delete the `docs` directory, rename `output` to `docs`, and commit/push your changes
