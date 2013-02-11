=======
CHANGES
=======

4.0.1 (2013-02-11)
------------------

- Add tox.ini to release.


4.0.0 (2013-02-11)
------------------

- Added support for Python 3.2, 3.3 and PyPy.
- Dropped support for Python 2.4 / 2.5.

3.6.1 (2011-11-29)
------------------

- Add undeclared ``zope.schema`` dependency.
- Remove ``zope.testing`` test dependency and ``test`` extra.

3.6.0 (2009-10-08)
------------------

- Added `IRawReadFile` and `IRawWriteFile` interfaces. These extend
  `IReadFile` and `IWritefile`, respectively, to behave pretty much like a
  standard Python file object with a few embellishments. This in turn allows
  efficient, iterator- based implementations of file reading and writing.

- Removed dependency on ``zope.container``: `IReadDirectory` and
  `IWriteDirectory` inherit only from interfaces defined in ``zope.interface``
  and ``zope.interface.common.mapping``.

3.5.0 (2009-01-31)
------------------

- Changed use of ``zope.app.container`` to ``zope.container``.

3.4.0 (2007-10-02)
------------------

- Initial Zope-independent release.
