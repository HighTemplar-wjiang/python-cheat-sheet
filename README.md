# python-cheat-sheet
Memo for python-related things that may not be used frequently or easy to forget

## Python Language
### Naming convention (Google Python Style Guide)
module_name, package_name, ClassName, method_name, ExceptionName, function_name, GLOBAL_CONSTANT_NAME, global_var_name, instance_var_name, function_parameter_name, local_var_name.

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

