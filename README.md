# Documentation for Turris routers

This documentation is written in English. It will walk you through the
first setup of your router and give you insights into main features available
in Turris OS.

We are using Markdown to document everything and `mkdocs` to handle the
presentation.


## Requirements:

To render this documentation, you need [mkdocs](https://www.mkdocs.org/).

It can be installed easily using `pip` running the following command

```
pip install --user -r requirements.txt
```

If you are all set, you can clone this repository via `git`.

```
git clone --recurse-submodules https://gitlab.labs.nic.cz/turris/user-docs.git
```

### Run mkdocs

Once you have a cloned out directory with documentation, you can either render
it locally or run a local server that will serve it. To do the later, you just
need to run in the root directory of the documentation the following command

```
mkdocs serve
```

If everything works well, you should see the documentation on <http://127.0.0.1:8000>.
