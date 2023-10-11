SurvivalDatasets.py [![Unlicensed work](https://raw.githubusercontent.com/unlicense/unlicense.org/master/static/favicon.png)](https://unlicense.org/)
===============
~~[wheel](https://gitlab.com/KOLANICH/SurvivalDatasets/-/jobs/artifacts/master/raw/wheels/SurvivalDatasets-0.CI-py3-none-any.whl?job=build)~~
[![PyPi Status](https://img.shields.io/pypi/v/SurvivalDatasets.svg)](https://pypi.python.org/pypi/SurvivalDatasets)
~~![GitLab Build Status](https://gitlab.com/KOLANICH/SurvivalDatasets/badges/master/pipeline.svg)~~
~~![GitLab Coverage](https://gitlab.com/KOLANICH/SurvivalDatasets/badges/master/coverage.svg)~~
[![Libraries.io Status](https://img.shields.io/librariesio/github/KOLANICH/SurvivalDatasets.svg)](https://libraries.io/github/KOLANICH/SurvivalDatasets)
[![Code style: antiflash](https://img.shields.io/badge/code%20style-antiflash-FFF.svg)](https://codeberg.org/KOLANICH-tools/antiflash.py)

**We have moved to https://codeberg.org/KOLANICH-ML/SurvivalDatasets.py, grab new versions there.**

Under the disguise of "better security" Micro$oft-owned GitHub has [discriminated users of 1FA passwords](https://github.blog/2023-03-09-raising-the-bar-for-software-security-github-2fa-begins-march-13/) while having commercial interest in success and wide adoption of [FIDO 1FA specifications](https://fidoalliance.org/specifications/download/) and [Windows Hello implementation](https://support.microsoft.com/en-us/windows/passkeys-in-windows-301c8944-5ea2-452b-9886-97e4d2ef4422) which [it promotes as a replacement for passwords](https://github.blog/2023-07-12-introducing-passwordless-authentication-on-github-com/). It will result in dire consequencies and is competely inacceptable, [read why](https://codeberg.org/KOLANICH/Fuck-GuanTEEnomo).

If you don't want to participate in harming yourself, it is recommended to follow the lead and migrate somewhere away of GitHub and Micro$oft. Here is [the list of alternatives and rationales to do it](https://github.com/orgs/community/discussions/49869). If they delete the discussion, there are certain well-known places where you can get a copy of it. [Read why you should also leave GitHub](https://codeberg.org/KOLANICH/Fuck-GuanTEEnomo).

---

This is a module importing some survival datasets for measuring performance of survival models. Can be repurposed to import other kinds of datasets, but currently I have populated the DB only with survival ones.


Requirements
------------
* [`numpy`](https://github.com/numpy/numpy) ![Licence](https://img.shields.io/github/license/numpy/numpy.svg) [![PyPi Status](https://img.shields.io/pypi/v/numpy.svg)](https://pypi.python.org/pypi/numpy) [![TravisCI Build Status](https://travis-ci.org/numpy/numpy.svg?branch=master)](https://travis-ci.org/numpy/numpy) [![Libraries.io Status](https://img.shields.io/librariesio/github/numpy/numpy.svg)](https://libraries.io/github/numpy/numpy)
* [`pandas`](https://github.com/pandas-dev/pandas) ![Licence](https://img.shields.io/github/license/pandas-dev/pandas.svg) [![PyPi Status](https://img.shields.io/pypi/v/pandas.svg)](https://pypi.python.org/pypi/pandas) [![TravisCI Build Status](https://travis-ci.org/pandas-dev/pandas.svg?branch=master)](https://travis-ci.org/pandas-dev/pandas) [![CodeCov Coverage](https://codecov.io/github/pandas-dev/pandas/coverage.svg?branch=master)](https://codecov.io/github/pandas-dev/pandas/) [![Libraries.io Status](https://img.shields.io/librariesio/github/pandas-dev/pandas.svg)](https://libraries.io/github/pandas-dev/pandas) [![Gitter.im](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/pydata/pandas)
* [`requests`](https://github.com/requests/requests) [![PyPi Status](https://img.shields.io/pypi/v/requests.svg)](https://pypi.python.org/pypi/requests) [![Libraries.io Status](https://img.shields.io/librariesio/github/requests/requests.svg)](https://libraries.io/github/requests/requests)
* [`scikit-learn`](https://github.com/scikit-learn/scikit-learn) [![PyPi Status](https://img.shields.io/pypi/v/scikit-learn.svg)](https://pypi.python.org/pypi/scikit-learn) [![Libraries.io Status](https://img.shields.io/librariesio/github/scikit-learn/scikit-learn.svg)](https://libraries.io/github/scikit-learn/scikit-learn)
