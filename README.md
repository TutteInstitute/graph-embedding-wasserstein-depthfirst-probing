# Graph embedding by Wasserstein distance between clouds of depth-first probes

See the [notebook](embedding.ipynb) is for details.

## Setup

The following works on UNIXish platforms, including Linux and MacOS workstations.
This should also work on Windows, but the environment activation command may be
different.

```sh
python -m venv .env
. .env/bin/activate
pip install -r requirements.txt
```

Then either start Jupyter Lab (classic notebook should also work):

```sh
jupyter lab
```

If you instead want to work out of an already running Jupyter instance (e.g. Jupyterhub),
install a kernel associated to this environment:

```sh
python -m ipykernel install --user --name 'graph-embedding' --display-name "Graph embedding by depth-first probes"
```

Remark that for best results, especially for visualization widgets embedded into the notebook,
this Jupyter instance should have compatible installs of `ipywidgets` and `jupyter_bokeh` (exact same versions). This question is moot if one runs their own Jupyter Lab out of this environment.
