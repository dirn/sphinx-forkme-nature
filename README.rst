======================================================
Fork Me Nature: Sphinx Nature Theme with GitHub Ribbon
======================================================

This repository contains a modified version of the Sphinx nature theme. In
addition to the standard appearance of the nature theme, this theme will
include an optional `GitHub Ribbon`_ at the top of the page.

.. _GitHub Ribbon: https://github.com/blog/273-github-ribbons

To use this theme for your Sphinx documenation, do the following:

1. Place the ``forkme_nature`` folder inside the ``_themes`` folder in your docs
   folder. Alternatively you can use this repository's root folder as your
   _themes folder.
2. Add the following to your ``conf.py`` file::


    sys.path.append(os.path.abspath('_themes'))

    html_theme_path = ['_themes']
    html_theme = 'forkme_nature'

3. The following options can be set in ``theme.conf`` inside the
   ``forkme_nature`` folder::


    # Name of the GitHub repository
    github_repo = dirn/sphinx-forkme-nature

    # Ribbon position, default is fixed, change to any other value for absolute
    ribbon_fixed = yes
