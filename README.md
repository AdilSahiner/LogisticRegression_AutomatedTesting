# Automated Testing for LogisticRegression

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/AdilSahiner/LogisticRegression_AutomatedTesting/master)

Click on the mybinder badage to launch the project in your mybinder environment.

# Usage

First, you need to install the dependencies listed in requirements.txt. You can run `!pip install -r requirements.txt` in your first cell in jupyter-notebook 
and all dependencies will be loaded using pip.

As stated in the exercise, two test cases for the predict and fit functions must be written. These can be found in `tests.ipynb`

If you run `tests.ipynb` in mybinder, you should be able to see test results at the end of the notebook. 

# Results

the first test case for the fit function checks whether the function duration exceeds the duration of the test 120%, which should not be the case. Therefore, the test will fail otherwise. You can run the tests to see the results at the end.

the predict test case tests if the obtained accuracy matched the model accuracy used in the training and evaluation process. This should match since a seed is used
to provide the same results for the model..
