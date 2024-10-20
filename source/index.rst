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

Showcasing is challenging. Writing is always a collaborative endeavour and many clients apply access management; controlling access to documentation.

Some clients can't admit to the freelancer's contribution. I learnt this early in my consulting career when I undertook a large report triage project in which I engaged in, and collaborated with, an analyst to re-conduct the statistics and a researcher to verify the quoted data. I personally:

- critiqued the existing analysis
- agreed the compromises required to rework all the statistical analyses and finish
- hired and managed the statistician
- compiled and edited the report
- wrote entire sections, including the recommendations
- managed a VA and the researcher

and my acknowledged role: editor!

Sometimes it is simply too politically delicate to admit why you needed your freelancer.

Thankfully, not all clients are complicated and there are examples in the "wild" that are publicly available.


Static Site Skills
******************

This site is written in reStructured Text (rST) which is rendered as HTML.

The :doc:`portfolio <pages/portfolio>` includes links to a Slate site, which uses markdown to render HTML on GitHub pages. This achieves several objectives:
1) It demonstrates my markdown capabilities.
2) It demonstrates that I can handle static site builders solo (no team here!).
3) The site consumes API data and displays that in a user-friendly manner (more user friendly than current read the docs offerings!).
4) It protects my client's sensitive information.

Most customers I work with in documentation projects prefer tools that consume files in Markdown and, for APIs, YAML/Markdown blends. I tend to simply use my favorite notepad tool, Sublime to work the docs.

I work like a dev: I push and pull to GitHub *et al*. I collaborate on reviews on PRs.

I like to hack documentation management by applying metadata/front matter to files. (Although, I recently got stung by GitBook and Stoplight with my quick-n-dirty hacks. GitBook killed my front matter with a recent release and my HTML wip comments containing ":" killed Stoplight's  -- thankfully support at both were ... supportive!).
