<h1 align="center">turkeypy</h1>
<p align="center">
A Python re-implementation of the <a href="https://esolangs.org/wiki/Chicken">chicken</a> esoteric programming language by Torbjörn Söderstedt.
</p>

<p align="center">
<img width="25%" src="assets/logo.png">
</p>

<p align="center">
A Thanksgiving derivative of [chickenpy](https://github.com/kosayoda/chickenpy/)
</p>


## What's turkey?
A turkey program only contains the tokens `"turkey"`, `" "` and `"\n"`. The number of turkeys per line represent an opcode, which is loaded onto the same stack as the program and executed directly.

For more details, view the [original implementation and spec here](https://web.archive.org/web/20180816190122/http://torso.me/chicken), or view the [Esolang page for chicken](https://esolangs.org/wiki/Chicken).

## Installation
```
$ pip install turkeypy
$ turkeypy --help
```

## Manual Installation
### Requirements
- Python 3.8+
- [Poetry](https://github.com/python-poetry/poetry)

### Steps
1. Click the **Clone or download** button in the top right corner.
2. Either clone the repository or download the ZIP file and extract.
3. Change directory and install dependencies.
```
$ cd turkeypy
$ poetry install --no-dev
```
Run the program by launching a subshell:
```
$ poetry shell
$ turkeypy --help
```
Or by running it directly using `poetry`:
```
$ poetry run turkeypy --help
```

### Dependencies
- [Click](https://github.com/pallets/click)

## Examples
Examples can be found in the `examples/` directory:
```
$ turkeypy -f examples/hello_world.tky
```

## License
This project is licensed under MIT. For more information see the [LICENSE](https://github.com/kosayoda/chickenpy/blob/master/LICENSE) file.
