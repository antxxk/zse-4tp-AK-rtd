
Nagłówek 4:
^^^^^^^^^^^

Akapit tekstowy
----------------

To jest zwykły akapit tekstu w reStructuredText (rst).

Akapit informacyjny
--------------------

.. note::

   notatka

.. tip::

   porada

Kod
---

Kod w linii: ``print("elo!")``

Kod blokowy:

.. code-block:: python

   print("przykładowy kod")
   x = 67
   print(x)

Odnośniki
---------

Zewnętrzny link:  
`Read the Docs <https://readthedocs.org>`_

Lokalny link:  
:doc:`autor`

Listy
------

Lista wypunktowana:

- element pierwszy
- element drugi
- element trzeci

Lista numerowana:

1. pierwszy punkt
2. drugi punkt
3. trzeci punkt

Lista definicji:

termin 1
   opis dla terminu 1

termin 2
   opis dla terminu 2

Obraz
-----

.. image:: obrazek.png
   :alt: alternatywny opis obrazka
   :align: center
   :figwidth: 300px
   :figcaption: podpis obrazka

Tabela
------

.. list-table::
   :header-rows: 1

   * - Kolumna 1
     - Kolumna 2
   * - Wartość 1
     - Wartość 2
   * - Wartość 3
     - Wartość 4
... (pozostałe wiersze: 2)

---

Jeśli chcesz, papi, mogę też zrobić **bardziej “estetyczną” wersję** z lekkimi zmianami w układzie i stylu nagłówków, żeby wyglądało nowocześniej. Chcesz, żebym tak zrobił?
