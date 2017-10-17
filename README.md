jupyter-scope-widget
===============================

A jupyter notebook widget for oscilloscope interaction

Installation
------------

To install use pip:

    $ pip install jupyter-scope-widget
    $ jupyter nbextension enable --py --sys-prefix jupyter-scope-widget


For a development installation (requires npm),

    $ git clone https://github.com/amcdawes/jupyter-scope-widget.git
    $ cd jupyter-scope-widget
    $ pip install -e .
    $ jupyter nbextension install --py --symlink --sys-prefix jupyter-scope-widget
    $ jupyter nbextension enable --py --sys-prefix jupyter-scope-widget
