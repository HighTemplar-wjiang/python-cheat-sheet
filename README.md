# python-cheat-sheet
Memo for python-related things that may not be used frequently or easy to forget

## Python Language
### Personal Naming convention (for any language)
- **Package and module**: short, all-lowercase
- **Class**: CapitalizedWords
- **Method**: lower_case_with_underscores
- **Variable**: mixedCase
- **Constant**: UPPERCASE
- **Non-public**: \_single_leading (method), \_singleLeading (variable)

## Libraries
### Regular experssion
- **Greedy vs non-greey match**: .* vs. .*?

## Python Documentation
### sphinx: best documentation tool for Python
- **Website**: <http://www.sphinx-doc.org>
- **Installation**: pip install sphinx
- **General usage**

  *sphinx-apidoc [source] [target]*
  
  *make html*
- **Highlights**
  * Autodoc is **not** enabled by default
  * Use [napoleon](https://pypi.python.org/pypi/sphinxcontrib-napoleon) for parsing Numpy and [Google style](http://www.sphinx-doc.org/en/stable/ext/example_google.html#example-google) docstrings

