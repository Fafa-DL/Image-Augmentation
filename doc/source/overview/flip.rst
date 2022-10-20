***************
augmenters.flip
***************

HorizontalFlip
--------------

Alias for ``Fliplr``.

API link: :class:`~imgaug.augmenters.flip.HorizontalFlip`


VericalFlip
--------------

Alias for ``Flipud``.

API link: :class:`~imgaug.augmenters.flip.VerticalFlip`


Fliplr
------

Flip/mirror input images horizontally.

.. note::

    The default value for the probability is ``1.0``, i.e. all images
    will be flipped.

API link: :class:`~imgaug.augmenters.flip.Fliplr`

**Example.**
Flip 50% of all images horizontally::

    import imgaug.augmenters as iaa
    aug = iaa.Fliplr(0.5)

.. figure:: ../../images/overview_of_augmenters/flip/fliplr.jpg
    :alt: Horizontal flip


Flipud
------

Flip/mirror input images vertically.

.. note::

    The default value for the probability is ``1.0``, i.e. all images
    will be flipped.

API link: :class:`~imgaug.augmenters.flip.Flipud`

**Example.**
Flip 50% of all images vertically::

    aug = iaa.Flipud(0.5)

.. figure:: ../../images/overview_of_augmenters/flip/flipud.jpg
    :alt: Vertical flip

