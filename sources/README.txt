================
jptomo.github.io
================

`jptomo.github.io`_ の元ページ

.. code-block:: console

   $ git clone git@github.com:jptomo/github-pages.git
   $ git clone git@github.com:jptomo/jptomo.github.io.git
   $ ln -s jptomo.github.io github-pages/_build
   $ cd github-pages
   $ pyvenv-3.4 --clear venv34
   $ source ./venv34/bin/activate
   $ pip install -r requirements.txt
   $ make html
