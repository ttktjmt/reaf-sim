:orphan:

mjswan embed test: iPad
=======================

Preview only. The same simulation five times, each framed a little differently, to find what stops it on iPad.
Tap Play in each and note which ones start.

A. As the RL pages embed it
---------------------------

``allow="xr-spatial-tracking; fullscreen"``, ``loading="lazy"``

.. raw:: html

   <iframe src="https://embed.mjswan.com/L3eRFxI" title="A (mjswan)"
     allow="xr-spatial-tracking; fullscreen" loading="lazy"
     style="width: 100%; aspect-ratio: 16 / 9; border: 0;"></iframe>

B. The share menu's snippet
---------------------------

``allow="xr-spatial-tracking"``, ``allowfullscreen``, ``loading="lazy"``

.. raw:: html

   <iframe src="https://embed.mjswan.com/L3eRFxI" title="B (mjswan)"
     allow="xr-spatial-tracking" allowfullscreen loading="lazy"
     style="width: 100%; aspect-ratio: 16 / 9; border: 0;"></iframe>

C. A without lazy loading
-------------------------

``allow="xr-spatial-tracking; fullscreen"``

.. raw:: html

   <iframe src="https://embed.mjswan.com/L3eRFxI" title="C (mjswan)"
     allow="xr-spatial-tracking; fullscreen"
     style="width: 100%; aspect-ratio: 16 / 9; border: 0;"></iframe>

D. No attributes
----------------

.. raw:: html

   <iframe src="https://embed.mjswan.com/L3eRFxI" title="D (mjswan)"
     style="width: 100%; aspect-ratio: 16 / 9; border: 0;"></iframe>

E. A, starting without the cover
--------------------------------

``?autoplay=1``: no Play to tap, the simulation loads at once.

.. raw:: html

   <iframe src="https://embed.mjswan.com/L3eRFxI?autoplay=1" title="E (mjswan)"
     allow="xr-spatial-tracking; fullscreen" loading="lazy"
     style="width: 100%; aspect-ratio: 16 / 9; border: 0;"></iframe>
