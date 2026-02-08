Zstd
====
.. automodule:: numcodecs.zstd

.. autoclass:: Zstd

    .. autoattribute:: codec_id
    .. automethod:: encode
    .. automethod:: decode
    .. automethod:: get_config
    .. automethod:: from_config

.. note::

    If the compressed data does not contain the decompressed size, streaming
    decompression will be used.

Helper functions
----------------

.. autofunction:: compress
.. autofunction:: decompress
