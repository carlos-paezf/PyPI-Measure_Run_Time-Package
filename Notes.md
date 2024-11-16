# Notas de publicación del repositorio

Este es mi primer paquete de Python publicado en la plataforma de PyPI, por ello quiero recordar los comandos que use:

```bash
pip install setuptools wheel
```

```bash
py .\setup.py sdist bdist_wheel
```

```bash
py -m pip install --upgrade twine
```

```bash
py -m twine upload dist/*
```

```bash
pip install measure-run-time
```
