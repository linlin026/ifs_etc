Backgrounds
===========

Description
-----------

Two sources of sky background are considered:

* **Zodiacal light**: Zodiacal light varies as a function of angular distance of the target from the Sun and from the ecliptic. We adopt data in Leinert et al. (1998).
* **Earth shine**: Earth-shine varies strongly as a function of angle between the target and the Earth lime. We adopt data from Figure 9.1 in HST/WFC3 instrument handbook.

Background levels
-----------------

.. code-block:: console

    config['background']['zodiacal'] = <zodiacal_level>

``<zodiacal_level>`` can be "high", "med", or "low".


Background package
------------------







