## String#cleanlines

Thre String#cleanlines method works essentially the same as String#lines,
returning an Array of line strings, but it also removes trailing whitespace
from each line.

    require 'facets/string/cleanlines'

    "a \n b \nc".cleanlines.to_a.assert == ["a","b","c"]

