Card List
=========

.. table:: Legend

  +--------------------+-----------+
  | <*card name*> (<*card count*>) |
  +====================+===========+
  | <*victory points*> | <*cost*>  |
  +--------------------+-----------+
  | [<*available action*> ...]     |
  +--------------------+-----------+
  | [<*flavor text*>]              |
  +--------------------+-----------+

.. table:: Iconography

  ============== ==========================================================
  Symbol         Meaning
  ============== ==========================================================
  R              Remnant resource
  G              Gaea resource
  B              Barren resource
  U              XenU resource
  x: y           *x* requires the player to have *y* in play
  x -> y         Consume *x* to produce a temporary resource of type *y*
  \|x\|          Count of *x* player has in play
  +x |eye|       Draw *x* additional cards during survey
  ^x             Publish findings about *x*
  x | y          *x* or *y*
  ============== ==========================================================

.. contents::

Gaea
----

.. this is terrible, fix the values

+-----------------------------------------------+
| Noble Savage, |female| (8)                    |
+==================+============================+
| 2 * \| |male| \| | (\| |female| \| + 1) * G   |
+------------------+----------------------------+

+-----------------------------------------------+
| Noble Savage, |male| (8)                      |
+==================+============================+
| \| |female| \|   | G                          |
+------------------+----------------------------+

+-----------------------------------------------+
| Ruminant |ruminant| (16)                      |
+==================+============================+
| \| |ruminant| \| | (\| |ruminant| \| + 1) * G |
+------------------+----------------------------+

+-----------------------------------------------+
| Carnivorous Plant |plant| (16)                |
+==================+============================+
| \| |plant| \|    | (\ |plant| \| + 1) * G     |
+------------------+----------------------------+

Remnant
-------

+-----------------------------------------------+
| Biomass Breeder (1)                           |
+==================+============================+
| 3                | RR                         |
+------------------+----------------------------+
| G: B -> GG                                    |
+------------------+----------------------------+

Barren
------

+-----------------------------------------------+
| Abandoned Asteroid Mine (1)                   |
+==================+============================+
|                  |                            |
+------------------+----------------------------+

+-----------------------------------------------+
| Expired Escape Pod (1)                        |
+==================+============================+
| 2                |                            |
+------------------+----------------------------+

XenU
----

+-----------------------------------------------+
| Matter Replicator (1)                         |
+==================+============================+
| 0                | U ^(G\|R)                  |
+------------------+----------------------------+
| R: B -> R *or* G: B -> G                      |
+------------------+----------------------------+

+-----------------------------------------------+
| Turbot-class Vanguard Ship (1)                |
+==================+============================+
| 0                | UU                         |
+------------------+----------------------------+
| \+1 |eye|                                     |
+------------------+----------------------------+

.. |male| unicode:: U+02642
.. |female| unicode:: U+02640
.. |ruminant| replace:: V
.. |plant| unicode:: U+2698
.. |eye| replace:: S
