===============================
{{ cookiecutter.project_name }}
===============================

{{ cookiecutter.project_short_description}}

* GPL v2

Features
--------

* TODO

Usage
-----

Launching the app
~~~~~~~~~~~~~~~~~

Kivy is compatible with Python2 as well as Python3::

    cd {{ cookiecutter.repo_name }} 
    python main.py

Running the testsuite
~~~~~~~~~~~~~~~~~~~~~

Run its testsuite either with Python3::

    cd {{ cookiecutter.repo_name }} 
    python -m unittest discover

Or with nose::

    cd {{ cookiecutter.repo_name }} 
    nosetests

Deploying to Android
~~~~~~~~~~~~~~~~~~~~

You can easily run the app on Android by using the kivy launcher. See:

http://kivy.org/docs/guide/packaging-android.html#packaging-your-application-for-the-kivy-launcher

Issues
------

Report bugs at https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.repo_name }}/issues.
