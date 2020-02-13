# Cambridge Dictionary

## Installation

```sh
cd cambridge
mkdir -p ~/.local/bin
install ./cambridge ~/.local/bin/
```

> Note: install cambridge <DESIRED LOCATION SHOULD BE IN THE PATH>

## Usage of `./cambridge`

```sh
cambridge <phrase>
```

> Note: < required > [ optional ]

## Usage of `./autocomplete`

```sh
./autocomplete <part_of_a_phrase>
```

## Examples

### Basic Usage of `cambridge`

```sh
$ cambridge hello
A1 hello /heˈləʊ/ exclamation, noun
used when meeting or greeting someone
```

### Basic Usage `autocomplete`

```sh
$ autocomplete hel
held
helical
helices
helicobacter pylori
helicoid
helicopter
helicopter pad
helicopter parent
helicopter view
```

### Multiple Words 

```sh
$ cambridge "come on"
C1 come, on /kʌm/ phrasal verb with come verb
to start to happen or work
```
