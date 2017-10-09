---
title: Pytest setup
currentMenu: classes
---

Pytest is a testing framework for python.

## References

* [The pytest website](https://docs.pytest.org/en/latest/)

* ["Python Testing with pytest" book](https://pragprog.com/book/bopytest/python-testing-with-pytest)


# Install process
You can (and should) add pytest to your project's conda virtual environment. However, to get started, here's a review of how to create a new conda virtual environment with everything you need to play around.

Step 1 - create a conda virtual environment with latest stable versions of pytest:

```conda create -n use-pytest pytest```

Step 2 - Enable your new pytest environment

```source activate use-pytest```

Here's an example transcript for your reference:


    [14:37][zim@kali:~/Desktop/LaunchCode/unit4/testing]
    $ conda create -n use-pytest pytest
    Fetching package metadata .........
    Solving package specifications: .

    Package plan for installation in environment /Users/zim/miniconda3/envs/use-pytest:

    The following NEW packages will be INSTALLED:

        certifi:    2016.2.28-py36_0
        openssl:    1.0.2l-0
        pip:        9.0.1-py36_1
        py:         1.4.34-py36_0
        pytest:     3.2.1-py36_0
        python:     3.6.2-0
        readline:   6.2-2
        setuptools: 36.4.0-py36_1
        sqlite:     3.13.0-0
        tk:         8.5.18-0
        wheel:      0.29.0-py36_0
        xz:         5.2.3-0
        zlib:       1.2.11-0

    Proceed ([y]/n)? y

    xz-5.2.3-0.tar 100% |######################################################################################################| Time: 0:00:00   1.98 MB/s
    zlib-1.2.11-0. 100% |######################################################################################################| Time: 0:00:00  11.01 MB/s
    python-3.6.2-0 100% |######################################################################################################| Time: 0:00:01   9.08 MB/s
    certifi-2016.2 100% |######################################################################################################| Time: 0:00:00  17.98 MB/s
    py-1.4.34-py36 100% |######################################################################################################| Time: 0:00:00  25.72 MB/s
    setuptools-36. 100% |######################################################################################################| Time: 0:00:00  16.29 MB/s
    pytest-3.2.1-p 100% |######################################################################################################| Time: 0:00:00   8.21 MB/s
    #
    # To activate this environment, use:
    # > source activate use-pytest
    #
    # To deactivate this environment, use:
    # > source deactivate use-pytest
    #


    [14:37][zim@kali:~/Desktop/LaunchCode/unit4/testing]
    $ source activate use-pytest
    (use-pytest)
    [14:38][zim@kali:~/Desktop/LaunchCode/unit4/testing]
    $ pytest --version
    This is pytest version 3.2.1, imported from /Users/zim/miniconda3/envs/use-pytest/lib/python3.6/site-packages/pytest.py
    (use-pytest)
    [14:38][zim@kali:~/Desktop/LaunchCode/unit4/testing]



Once your virtual environment is tunning, verify proper operation and review the command line options:

```pytest --help```


## For more information

See [Installation and Getting Started](https://docs.pytest.org/en/latest/getting-started.html)



# Running tests

At the appropriate level in your project, simply invoke ```pytest``` to find and run all the tests.

```pytest```

Without arguments, pytest looks in your current working directory and recursively looks in all subdirectories and runs any test files  (files whose names starting with "test_" or ending with "_test") that it finds.

To make your test code discoverable by ```pytest```, use the following naming conventions::

* Test files should be named test_*something*.py or *something*_test.py.

* Test methods and functions should be named test_*something*().

* Test classes should be named Test*Something*.

To run a specific test in a specific file, use a double colon

```pytest filepath::testname```

## Using tests in an IDE

If you are using an IDE like PyCharm, running tests is both easier (because the IDE is designed to do so) and harder (because the user interface is more complicated and ideosyncratic.) Correctly configured, your IDE can run tests continuously in the background and make your life wonderfully easy.
