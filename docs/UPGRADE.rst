If you used this buildout before and run into any issues then check the
following notes:

* We depend on zc.buildout >= 1.4.1, but can't express this in the
  configuration. Remove bin/buildout and the eggs directory and bootstrap
  again (see INSTALL.rst).

* If you ran this on Snow Leopard before 2009-09-05, then you got a 32-bit
  version. You need to recreate all modules with C extensions, so basically
  all eggs with C parts like PIL and all Zope installations.
