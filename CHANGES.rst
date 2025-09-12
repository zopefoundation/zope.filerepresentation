=========
 Changes
=========

7.0 (2025-09-12)
================

- Replace ``pkg_resources`` namespace with PEP 420 native namespace.


6.1 (2025-02-14)
================

- Drop support for Python 3.7, 3.8.

- Add support for Python 3.12, 3.13.


6.0 (2023-01-14)
================

- Drop support for Python 2.7, 3.5, 3.6.

- Add support for Python 3.9, 3.10, 3.11.

5.0.0 (2020-03-31)
==================

- Drop support for Python 3.4.

- Add support for Python 3.7 and 3.8.

- Ensure all objects have a consistent interface resolution order.
  See `issue 7 <https://github.com/zopefoundation/zope.filerepresentation/issues/7>`_.


4.2.0 (2017-08-10)
==================

- Add support for Python 3.5 and 3.6.

- Drop support for Python 2.6 and 3.3.


4.1.0 (2014-12-27)
==================

- Add support for PyPy3.

- Add support for Python 3.4.


4.0.2 (2013-03-08)
==================

- Add Trove classifiers indicating CPython and PyPy support.


4.0.1 (2013-02-11)
==================

- Add tox.ini to release.


4.0.0 (2013-02-11)
==================

- Add support for Python 3.3 and PyPy.

- Drop support for Python 2.4 / 2.5.

3.6.1 (2011-11-29)
==================

- Add undeclared ``zope.schema`` dependency.
- Remove ``zope.testing`` test dependency and ``test`` extra.

3.6.0 (2009-10-08)
==================

- Add ``IRawReadFile`` and ``IRawWriteFile`` interfaces. These extend
  ``IReadFile`` and ``IWritefile``, respectively, to behave pretty much like a
  standard Python file object with a few embellishments. This in turn allows
  efficient, iterator- based implementations of file reading and writing.

- Remove dependency on ``zope.container``: ``IReadDirectory`` and
  ``IWriteDirectory`` inherit only from interfaces defined in ``zope.interface``
  and ``zope.interface.common.mapping``.

3.5.0 (2009-01-31)
==================

- Change use of ``zope.app.container`` to ``zope.container``.

3.4.0 (2007-10-02)
==================

- Initial Zope-independent release.
