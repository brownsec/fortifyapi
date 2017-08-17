Fortify API
***********

Fortify API is an `SSC <https://saas.hpe.com/en-us/software/software-security-assurance-sdlc/>`_ SAST artifact and administration library interfacing with the RESTFul API.

Quick Start
~~~~~~~~~~~

Several quick start options are available:

- Build locally: ``python setup.py build``
- Install with pip (recommended): ``pip install fortifyapi``
- `Download the latest release <https://github.com/target/fortifyapi/releases/latest/>`__.

Example
~~~~~~~

::

    # import the package
    from fortifyapi import fortify

    # setup fortify ssc connection information
    host = 'https://localhost:8443/'

    # instantiate the fortify api wrapper
    ssc = fortify.FortifyApi(host)

    # Do something

Supporting information for each method available can be found in the `documentation <https://target.github.io/fortifyapi/>`__.

Bugs and Feature Requests
~~~~~~~~~~~~~~~~~~~~~~~~~

Found something that doesn't seem right or have a feature request? Please open a new issue.

Copyright and License
~~~~~~~~~~~~~~~~~~~~~

- Copyright 2017 Target Brands, Inc.
- `Licensed under MIT <https://github.com/target/fortifyapi/blob/master/LICENSE.txt/>`__.
