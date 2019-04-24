sphinx-csharp [![Build Status](https://travis-ci.org/richardjhughes/sphinx-csharp.svg?branch=master)](https://travis-ci.org/richardjhughes/sphinx-csharp)
=============

C# domain for Sphinx.

Note: Work-in-progress. Only a subset of C# is currently supported.

Usage
-----

Install using pip:

```
pip install sphinx-csharp
```

To enable the extension, add the following to your conf.py:

```python
extensions = ['sphinx_csharp.csharp']
```

See [this example](https://raw.githubusercontent.com/richardjhughes/sphinx-csharp/master/test/index.rst) of how to document C# code.
