BDO-community ( *Black Desert Online Community* ) 
=================================================

.. image:: https://img.shields.io/github/issues/RealImperialGames/BDO-community.svg
  :alt: Issues on Github
  :target: https://github.com/RealImperialGames/BDO-community/issues

.. image:: https://img.shields.io/github/issues-pr/RealImperialGames/BDO-community.svg
  :alt: Pull Request opened on Github
  :target: https://github.com/RealImperialGames/BDO-community/issues

.. image:: https://img.shields.io/github/release/RealImperialGames/BDO-community.svg
  :alt: Release version on Github
  :target: https://github.com/RealImperialGames/BDO-community/releases/latest

.. image:: https://img.shields.io/github/release-date/RealImperialGames/BDO-community.svg
  :alt: Release date on Github
  :target: https://github.com/RealImperialGames/BDO-community/releases/latest

+--------------+--------------------------+---------------------------+---------------------------+--------------------------+--------------------------+
| Branch name  | BDOC-utils               | BDOC-core                 | BDOC-db                   | BDOC-client              | BDOC-server              |
+==============+==========================+===========================+===========================+==========================+==========================+
| master       | |bdoc-utils_lin|         | |bdoc-core_lin|           | |bdoc-db_lin|             | |bdoc-client_lin|        | |bdoc-server_lin|        |
|              | |bdoc-utils_win|         | |bdoc-core_win|           | |bdoc-db_win|             | |bdoc-client_win|        | |bdoc-server_win|        |
+--------------+--------------------------+---------------------------+---------------------------+--------------------------+--------------------------+

How to install ?
----------------

``TODO: make sense``


How to exec tests ?
-------------------

``TODO: make sense``


How to download from Github ? ( *development, documentation, testing, design* )
-------------------------------------------------------------------------------

*We are using Git-submodule functionality to handle all projects as independent packages*

+ 1. *Clone this repo* : ``git clone https://github.com/RealImperialGames/BDO-community.git``
+ 2. *Enter on repo directory* : ``cd BDO-community``
+ 3. *Clone submodules* : ``git submodule update --init --recursive``
+ 4. *Attach branches HEAD* : ``git submodule foreach git checkout master``


Contributing
~~~~~~~~~~~~

We welcome contributions to BDO-community! These are the many ways you can help:

* Submit patches and features
* Make BDOC-core ( *new updates to improve main library* )
* Make BDOC-db ( *new updates for database configuration or queries* )
* Make BDOC-client ( *new updates for community client* )
* Make BDOC-server ( *new updates for community server* )
* Improve the BDOC-utils bdoc-utils_
* Improve the BDOC-core bdoc-core_
* Improve the BDOC-db bdoc-db_
* Improve the BDOC-client bdoc-client_
* Improve the BDOC-server bdoc-server_
* Report bugs 
* And Donate bdoc-donate_ !

Please read our documentation to get started. Also note that this project
is released with a `code of conduct<bdoc-conduct_>`, please make sure to review and follow it.



.. |bdoc-utils_lin| image:: https://travis-ci.org/RealImperialGames/BDOC-utils.svg?branch=master
.. |bdoc-utils_win| image:: https://ci.appveyor.com/api/projects/status/-/branch/master?svg=true
.. |bdoc-core_lin| image:: https://travis-ci.org/RealImperialGames/BDOC-core.svg?branch=master
.. |bdoc-core_win| image:: https://ci.appveyor.com/api/projects/status/-/branch/master?svg=true
.. |bdoc-db_lin| image:: https://travis-ci.org/RealImperialGames/BDOC-db.svg?branch=master
.. |bdoc-db_win| image:: https://ci.appveyor.com/api/projects/status/-/branch/master?svg=true
.. |bdoc-client_lin| image:: https://travis-ci.org/RealImperialGames/BDOC-client.svg?branch=master
.. |bdoc-client_win| image:: https://ci.appveyor.com/api/projects/status/-/branch/master?svg=true
.. |bdoc-server_lin| image:: https://travis-ci.org/RealImperialGames/BDOC-server.svg?branch=master
.. |bdoc-server_win| image:: https://ci.appveyor.com/api/projects/status/-/branch/master?svg=true
.. _bdo-community: https://realimperialgames.github.io/BDO-community
.. _bdoc-utils: https://realimperialgames.github.io/BDOC-utils
.. _bdoc-core: https://realimperialgames.github.io/BDOC-core
.. _bdoc-db: https://realimperialgames.github.io/BDOC-db
.. _bdoc-client: https://realimperialgames.github.io/BDOC-client
.. _bdoc-server: https://realimperialgames.github.io/BDOC-server
.. _bdoc-donate: https://opencollective.com/BDO-community
.. _bdoc-conduct: https://github.com/RealImperialGames/BDO-community/CODE_OF_CONDUCT.md
