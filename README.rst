Asset management application for Python web development - use it to
merge and compress your JavaScript and CSS files.

Documentation: |ci|
        https://webassets.readthedocs.io/

        Since releases aren't exactly happening on a regular schedule, you are
        encouraged to use the latest code. ``webassets`` is pretty well tested,
        so as long as the build status icon above remains a reassuring green,
        you shouldn't run into any trouble.

        You can `download a tarball`__ of the development version, or
        install it via ``pip install webassets==dev``.


Development:
        For development, to run all the tests, you need to have at least Java 7
        installed (required for example to run the `Google closure`_ filter).

        1. Install Python requirements with uv::

                   $ uv venv
                   $ uv pip install -r uv.lock

        2. Install other requirements::

                   $ ./requirements-dev.sh

        3. Run the tests::

                   ./run_tests.sh

__ http://github.com/miracle2k/webassets/tarball/master#egg=webassets-dev

.. _`Google closure`: https://github.com/google/closure-compiler/wiki/FAQ#the-compiler-crashes-with-unsupportedclassversionerror-or-unsupported-majorminor-version-510

.. |ci| image:: https://github.com/miracle2k/webassets/actions/workflows/ci.yml/badge.svg
       :target: https://github.com/miracle2k/webassets/actions/workflows/ci.yml