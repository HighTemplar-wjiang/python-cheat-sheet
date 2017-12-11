# python-cheat-sheet
Memo for python-related things that may not be used frequently

## Python Language
### Personal Naming convention
- **Package and module**: short, all-lowercase
- **Class**: CapitalizedWords
- **Method**: lower_case_with_underscores
- **Variable**: mixedCase
- **Constant**: UPPERCASE
- **Non public**: \_single_leading (method), \_singleLeading (variable)

## Python Documentation
### sphinx: best documentation tool for Python
- **Website**: <http://www.sphinx-doc.org>
- **Installation**: pip install sphinx
- **General usage**

  *sphinx-apidoc [source] [target]*
  
  *make html*
- **Highlights**
  * Autodoc is **not** enabled by default
  * Use [napoleon](https://pypi.python.org/pypi/sphinxcontrib-napoleon) for parsing Numpy and Google style docstrings
