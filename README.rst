dls_bluesky_commissioning
===========================

|code_ci| |docs_ci| |coverage| |pypi_version| |license|

Contains some plans for commissioning beamlines, written using jupyter notebooks.

============== ==============================================================
PyPI           ``pip install dls_bluesky_commissioning``
Source code    https://github.com/dls-controls/dls_bluesky_commissioning
Documentation  https://dls-controls.github.io/dls_bluesky_commissioning
Releases       https://github.com/dls-controls/dls_bluesky_commissioning/releases
============== ==============================================================

To install run:
.. code-block:: bash
    module load python/3.10
    module unload controls_dev
    pipenv install

Then to start run ``pipenv run jupyter-lab``

.. |code_ci| image:: https://github.com/dls-controls/dls_bluesky_commissioning/workflows/Code%20CI/badge.svg?branch=master
    :target: https://github.com/dls-controls/dls_bluesky_commissioning/actions?query=workflow%3A%22Code+CI%22
    :alt: Code CI

.. |docs_ci| image:: https://github.com/dls-controls/dls_bluesky_commissioning/workflows/Docs%20CI/badge.svg?branch=master
    :target: https://github.com/dls-controls/dls_bluesky_commissioning/actions?query=workflow%3A%22Docs+CI%22
    :alt: Docs CI

.. |coverage| image:: https://codecov.io/gh/dls-controls/dls_bluesky_commissioning/branch/master/graph/badge.svg
    :target: https://codecov.io/gh/dls-controls/dls_bluesky_commissioning
    :alt: Test Coverage

.. |pypi_version| image:: https://img.shields.io/pypi/v/dls_bluesky_commissioning.svg
    :target: https://pypi.org/project/dls_bluesky_commissioning
    :alt: Latest PyPI version

.. |license| image:: https://img.shields.io/badge/License-Apache%202.0-blue.svg
    :target: https://opensource.org/licenses/Apache-2.0
    :alt: Apache License

..
    Anything below this line is used when viewing README.rst and will be replaced
    when included in index.rst

See https://dls-controls.github.io/dls_bluesky_commissioning for more detailed documentation.
