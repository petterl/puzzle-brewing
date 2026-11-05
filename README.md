# puzzle-brewing

Tools and recipe database for Puzzle Brewing.

Recipes and batch logs live in `docs/` as plain Markdown and are published with
MkDocs Material at <https://petterl.github.io/puzzle-brewing/>.

- `docs/recipes/` – one file per recipe
- `docs/batches/` – one file per batch, named `<YYYY-MM-DD>-<recipe-slug>.md`
- `docs/brewday/` – Brew Day planner app (syncs via `data/brewday.json`)
- `templates/` – copy these when starting a new recipe or batch

## Preview locally

```sh
python -m venv .venv
.venv\Scripts\activate        # on macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

Then open <http://127.0.0.1:8000>.
