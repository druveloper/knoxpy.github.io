---
title: Packaging in Python
time: 6:30-8:30pm
address: Technology Cooperative, 13 Emory Place, Knoxville, TN
---

Packaging in Python is a complex topic. In this talk by Christopher Ostrouchov we will do an opinionated live demo of developing a pure Python package. We will most likely not be able to cover everything so Chris will defer to the audience for what they would like covered. We will also discuss the future of packaging as heard from the PyPI developers at PyCon.

A [git repository][1] is provided with all the steps along with [documentation][2].

Python packages used:

- twine (pypi package deployment)
- conda (anaconda package deployment)
- pytest, pytest-cov (testing and coverage)
- sphinx, sphinx_rtd_theme (for documentation)
- argparse (for cli)

Non-python tools used:

- gitlab (repository, continuous integration, continuous deployment, and job pipeline)
- readthedocs.org (for hosting documentation)
- docker hub (for hosting docker images)
- sheilds.io (for project badges)
- pypi.org (for pypi repository)
- anaconda.org (for python conda package repository)

[1]: https://gitlab.com/costrouc/python-package-template
[2]: https://costrouc-python-package-template.readthedocs.io/en/latest/
