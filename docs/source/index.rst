.. Minion documentation master file, created by
   sphinx-quickstart on Mon Aug  5 10:53:21 2013.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Minion
#################

Minion is a security testing framework, his goal is to enable developers and security testers
to bring web application security into a continuous testing cycle. To do this, both developers
and testers are given an easy to use dashboard that lists all the sites they need to scan,
detail scan summary page and detail issue page to explain vulnerability. Instead of learning a new scan tool,
users can write Minion plugins to call their favorite scan tools, and Minion will spawn
the tool as a new process, scan the target website, and return the results back to the user.

It is a based on Minion, a security testing framework build by Mozilla. For more information see https://wiki.mozilla.org/Security/Projects/Minion

This documentation is made to present Minion but also how to install it. It's based on
existing documentation of Minion (see http://minion-yeukhon.readthedocs.org/en/latest ), developed by Mozilla, but updated with added features.

Source code are on Github: see https://github.com/Wawki/minion

.. toctree::
   :maxdepth: 2
   :hidden:

   what_is_minion
   getting_started
   configure_minion
   install_plugins
   using_frontend
   install_guide_production
   inside_minion
   developing_plugins
   using_setup_sh

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

