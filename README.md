# d2u
|     key | description
|     ---:|:---
|  script | d2u - convert msdos file to unix, removing any BOM mark
|    type | zsh
|  author | Wybo Dekker
|   email | wybodekker@me.com
| version | 1.00
| license | GNU General Public License

d2u converts ms-dos-like files in place to unix.
- replaces crlf sequences with lf's.
- if cr is the only line separator (like in hp-unix) it is replaced with lf.
- ^Z, ^Q and null characters are removed,
- any BOM mark is removed.
- character set is converted to utf-8.
