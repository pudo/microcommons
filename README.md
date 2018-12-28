# banal

Commons of Python micro-functions. This basically an out-sourced, shared
utils module.

Rules:

* Must work in Python 2 and Python 3
* Cannot depend on anything but six and the standard library

## Functions

* ``is_listish``: check if something is list-ish
* ``is_mapping``: check if an object is dict-ish
* ``ensure_list``: make sure an argument is a list, or make it into a single-element list
* ``clean_dict``: remove null values from a dict, recursively
* ``decode_path``: decode a path name to be unicode
* ``hash_data``: generate a SHA1 from a dict of reasonable objects