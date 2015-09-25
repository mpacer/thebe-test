# thebe-test

This allows you to check out interactive code at http://michaelpacer.github.io/thebe-test/. 

You need to have jupyter installed(`pip install -U jupyter`) and run a notebook server from a place that does not modify the origin call from your browser (e.g., virtualenvs can mess this up):

    jupyter notebook --NotebookApp.allow_origin=* --no-browser 

In the simplest of cases, this should work for you.
