# Unicode Slugify

This fork of `Unicode Slugify`_ uses `Text-Unidecode`_, that is under `Artistic License`_.
If you're OK with GLP better use original slugifier.


.. _Text-Unidecode: https://github.com/kmike/text-unidecode
.. _Artistic License: http://opensource.org/licenses/Artistic-Perl-1.0
.. _Unicode Slugify: https://github.com/mozilla/unicode-slugify

## Usage

    >>> import slugify

    >>> slugify.slugify(u'Bän...g (bang)')
    u'bäng-bang'

    >>> slugify.slugify(u'Bäuma means a tree', only_ascii=True)
    u'bauma-means-a-tree'

    >>> slugify(u'Bakıcı geldi', only_ascii=True)
    u'bakici-geldi'
