# d2u

convert msdos file to unix, removing any BOM mark

## Properties

|key|value|
|-:|:-|
|  script:|d2u|
|   short:|convert msdos file to unix, removing any BOM mark|
|    type:|zsh|
|  author:|Wybo Dekker|
|   email:|[wybodekker@me.com](mailto:wybodekker@me.com)|
| version:|1.00|
| license:|GNU General Public License|
|   intro:|d2u converts ms-dos-like files in place to unix.|
|         |- replaces **crlf** or just **cr** sequences with **lf**'s.|
|         |- **^Z**, **^Q** and **null** characters are removed,|
|         |- any BOM mark is removed.|
|         |- character set is converted to utf-8.|

## Options

|option|description|
|:-|:-|
|-h,--help	|print short help and exit|
|-H,--Help	|print full documentation and exit|
|-V,--version	|print version and exit|
|-v,--verbose	|report each file being handled|
