.. TechWriter documentation master file, created by
   sphinx-quickstart on Sun Oct 20 18:55:50 2024.


Welcome to Harrie's Showcase
=============================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   pages/portfolio
   pages/blockchain


Rationale
---------

This site acts as a showcase for my technical writing.


Static Site Skills
******************

This site is written in Python's reStructured Text (rST), which is rendered as HTML.

The :doc:`portfolio <pages/portfolio>` includes links to a Slate site, which uses Markdown to render HTML on GitHub pages. This achieves several objectives:
1) It demonstrates that I can handle static site builders solo (no team here!).
2) The site consumes API data and displays that in a user-friendly manner (more user friendly than current Read the Docs offerings!).
3) It protects past clients' sensitive information.
4) Having to update this site retains my rST know-how.

Most documentation projects prefer tools that consume files in Markdown and, for APIs, YAML/Markdown blends. I tend to simply use my favorite notepad tool, Sublime to work the docs.

I work like a dev: I push and pull to GitHub *et al*. I collaborate on reviews on PRs.

I like to hack documentation management by applying metadata/front matter to files. This way, the file manages its own details while tickets can manage the high-level needs.
