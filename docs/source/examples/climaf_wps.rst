.. _climaf_wps:

Example: CliMAF WPS
===================

In this example we are creating a Web Processing Service for CliMAF_.

Create WPS using Cookiecutter
-----------------------------

We create an initial WPS with Cookiecutter_ and the `bird-house/cookiecutter-birdhouse`_ WPS template.

Install Cookiecutter using Conda_::

  $ conda install -c conda-forge cookiecutter

Run Cookiecutter with the WPS template::

  $ cookiecutter https://github.com/bird-house/cookiecutter-birdhouse.git

Cookiecutter will ask you a few questions, here the answers for the CliMAF WPS::

  full_name [Full Name]: Mary Stuart
  email [your@email]: mary@stuart
  github_username [bird-house]: cp4cds
  project_name [Babybird]: CliMAF WPS Demo
  project_slug [climaf_wps_demo]: climafwps
  project_repo_name [climafwps]: climaf_wps_demo
  project_short_description [A Web Processing Service for Climate Data Analysis.]: A Web Processing Service for CliMAF.
  version [0.1.0]: 1.1.0
  Select open_source_license:
  1 - Apache Software License 2.0
  2 - MIT license
  3 - BSD license
  4 - ISC license
  5 - GNU General Public License v3
  Choose from 1, 2, 3, 4, 5 [1]: 1
  http_port [5000]: 5000

A project folder `climaf_wps_demo` is created with a fully functional WPS and example processes.

Push this project now to `GitHub <https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/>`_.

You can find the result in our `CP4CDS <https://github.com/cp4cds/climaf-wps-demo>`_ GitHub project.




.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`bird-house/cookiecutter-birdhouse`: https://github.com/bird-house/cookiecutter-birdhouse
.. _CliMAF: http://climaf.readthedocs.io/en/latest
.. _Conda: https://conda.io/docs/index.html
