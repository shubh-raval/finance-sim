# finance-sim

Deployed build of the Household Finance Lab — a single-file app (`index.html`)
that runs a Python financial-projection engine in-browser via Pyodide.

Source, engine code, and tests live in the private `personal_finance` repo.
This repo exists only to serve the built artifact via GitHub Pages. The
default scenario shown here uses generic example numbers, not real data.

To update: rebuild `app.html` from the `personal_finance` repo's
`public-deploy-prep` branch (`python3 src/finance-lab/build.py`), copy it
here as `index.html`, commit, push.
