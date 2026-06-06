# cyr2latin

transliterate cyrillic to latin

## Properties

|key|value|
|-:|:-|
|  script:|cyr2latin|
|   short:|transliterate cyrillic to latin|
|    type:|ruby|
|  author:|Wybo Dekker|
|   email:|[wybodekker@me.com](mailto:wybodekker@me.com)|
| version:|1.01|
| license:|GNU General Public License|
|   intro:|cyr2latin transliterates cyrillic characters to|
|         |latin. Currently only Russian cyrillic is understood,|
|         |and the output is for phonetic Dutch. Accent marks in the|
|         |input are removed, unless the **--keep** option is used.|

## Options

|option|description|
|:-|:-|
|-h		|print this help and exit|
|-H, --help	|print full documentation and exit|
|-V, --version	|print version and exit|
|-k, --keep	|keep accent marks; they are removed by default|
|-t, --test	|report error when input contains latin characters|
