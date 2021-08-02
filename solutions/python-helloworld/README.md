##Basic Python Helloworld flask application

#Testing code is set to true just for running it.

Once we have completed writing the test, we can construct a GitHub Action that will execute the tests using pytest tool. For this purpose, a new #workflow is defined in the pytest.yml file within the .github/workflows directory.

To trigger the workflow a new commit is necessary (e.g. editing the README.md fie). On the successful execution of the GitHub Action, we should see an output mentioning that all the test passed successfully (as expected)
