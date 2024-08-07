Regex used:

Date format

(\d{4})\.(\d{2})\.(\d{2})\.(\d{2})\.(\d{2})\.(\d{2})  -->  \1\\\2\\\3 \4\:\5\:\6

Space between cells names (NNG45Y00)

(\w{5})\s  -->  \1

Eliminate lines, separate with comas 

\n  -->  \,
