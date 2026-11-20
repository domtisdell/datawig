# datawig

Fork of awslabs/datawig (imputation of missing table values with MXNet). The owner changed only `requirements/requirements.txt` (pins `pandas==1.2.5` and `mxnet==1.7.0.post2`). Otherwise unmodified and kept for reference.

- Do not change it without being asked. Pull requests go to `domtisdell/datawig`, never the parent. Pass `-R domtisdell/datawig` to every `gh pr` command, and do not add or push to an `upstream` remote.
- Package: `datawig/`. Tests: `test/`. Docs: `docs/` (`make html` in `docs/`).
- `README.md` documents this setup: `python3 -m venv venv`, `./venv/bin/pip install -e .`, `./venv/bin/pip install -r requirements/requirements.dev.txt`, `./venv/bin/python -m pytest`.
- `.travis.yml` holds upstream's encrypted PyPI deploy value. Do not copy it or try to use it. Do not publish to PyPI.
- `datawig-js/` and `experiments/` are upstream's side projects. Do not edit them.
