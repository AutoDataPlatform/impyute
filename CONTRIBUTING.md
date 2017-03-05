# Contributing to impy
Before anything else, thank you for deciding to contribute! +1
The following is a set of guidelines for contributing to the imputations library, impy, which is hosted [here](https://github.com/eltonlaw/impy) 

### Code of Conduct
This project adheres to the Contributor Covenant [code of conduct](CODE_OF_CONDUCT.md).
By participating, you are expected to uphold this code.

### Style
All Python must adhere to [PEP8](https://www.python.org/dev/peps/pep-0008/)

### Bugs

#### Reporting
* **Ensure the bug was not already reported** by searching on GitHub under [Issues](https://github.com/eltonlaw/impy/issues).
* * If you're unable to find an open issue addressing the problem, [open a new one](https://github.com/rails/rails/issues/new). Be sure to include a **title and clear description**, as much relevant information as possible, and a **code sample** or an **executable test case** demonstrating the expected behavior that is not occurring.

#### Patching
* Open a new GitHub pull request with the patch.
* Ensure the PR description clearly describes the problem and solution. Include the relevant issue number if applicable.

### Suggesting Enhancements
This project was created to from having data with missing values to having data without missing values. Any enhancement that brings value in that direction is good. If there's something interesting or that you're unsure about, open an issue and we can discuss it.
Enhancement suggestions are tracked as [GitHub issues](https://guides.github.com/features/issues/). Create an issue and try to provide most or all of the following information:
* **Use a clear and descriptive title** for the issue to identify the suggestion.
* **Provide a description of the suggested enhancement** in as many details as possible.
* **Provide specific examples to demonstrate the steps**. Include copy/pasteable snippets which you use in those examples, as [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the current behavior** and **explain which behavior you expected to see instead** and why.
* **Anything else you think would be helpful**

### Current To-Do's
* Restructure project structure so algorithms are sorted into types of imputations(single/multiple imputation, regression, likelihood) or types of dataset(time series, independent) 
* impy/datasets: Add complete case datasets, Add datasets with natural MCAR/MAR/MNAR, Add MAR/MNAR mutators  
* Add Expectation Maximization imputer
* Add Kalman Filter
* Add EM with Kalman Filter imputer
* impy/diagnostics: Find attributes of raw dataset(% missingness etc.), Visualize missing values, provide info about imputed values 

### Running Tests

``` shell
$ nosetests
```
