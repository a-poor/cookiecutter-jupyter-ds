# cookiecutter-jupyter-ds

_created by Austin Poor_

A cookiecutter template for a simple Docker / Jupyter / Data-Science project.

__Requirements__:
* Python
* Cookiecutter
* Docker / Docker-compose

Once cookiecutter is installed, this template can be cloned with the command:
```bash
$ cookiecutter gh:a-poor/cookiecutter-jupyter-ds
```

Then, the jupyter container can be started with
```bash
$ docker-compose up
```

Docker will expose port `8888` for Jupyter.
