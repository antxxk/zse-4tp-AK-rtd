Skladnia
================================

naglowki (poziomy 1-4)
----------------------

naglowek 1:
===========

naglowek 2:
-----------

naglowek 3:
~~~~~~~~~~~

naglowek 4:
^^^^^^^^^^^

akapit tekstowy
----------------


to jest zwykly akapit tekstu w rst

akapit informacyjny
--------------------

.. note::

  notatka

.. tip::

 porada

kod
---

kod liniowy: ``print("cos!")``

kod blokowy:

.. code-block:: python

   print("cos tam jakis kod")
   x = 5
   print(x)

odnośniki
---------

zewnętrzny link:  
`read the docs <https://readthedocs.org>`_

lokalny link:  
:doc:`autor`

listy
------

lista wypunktowana:

- element 1
- element 2
- element 3

lista numerowana:

1. pierwszy
2. drugi
3. trzeci

lista definicji:

termin 1
   opis terminu 1

termin 2
   opis terminu 2

obraz
-----

.. image:: obrazek.png
   :alt: opis alternatywny obrazka
   :align: center
   :figwidth: 300px
   :figcaption: podpis 
  
tabela
------

.. list-table::
   :header-rows: 1

   * - kolumna 1
     - kolumna 2
   * - wartosc 1
     - wartosc 2
   * - wartosc 3
... (Pozostałe wiersze: 2)
