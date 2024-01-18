# qgridtrusted-notebooks

Commands to start the demo:

    python3.11 -m venv --upgrade-deps .venv \
    && .venv/bin/python -m pip install --requirement requirements.txt

Command to run the demo notebook:

    .venv/bin/python -m nbclassic index.ipynb

Commands to update `requirements.txt`:

    rm requirements.txt \
    && pipx run --spec=pip-tools pip-compile
